<template>
    <n-grid :cols="4" x-gap="16" y-gap="16" class="mainGrid">
        <n-gi span="4">
            <n-h1>State of Vue Exercises</n-h1>
        </n-gi>
        <n-gi span="4">
            <n-alert title="Naive UI" type="info">
                <n-p
                    >Check out the library, docs, and components
                    <n-a
                        href="https://www.naiveui.com/en-US/os-theme"
                        target="_blank"
                        >here</n-a
                    >.</n-p
                >
            </n-alert>
        </n-gi>
        <n-gi>
            <Exercise1 />
        </n-gi>
        <n-gi>
            <Exercise2 />
        </n-gi>
        <n-gi>
            <Exercise3 />
        </n-gi>
        <n-gi>
            <Exercise4 />
        </n-gi>
        <n-gi span="4">
            <ExerciseFreeform />
        </n-gi>
    </n-grid>
</template>

<script setup lang="ts">
import { NAlert, NGrid, NGi, NP, NA, NH1 } from 'naive-ui'
import Exercise1 from './components/Exercise1.vue'
import Exercise2 from './components/Exercise2.vue'
import Exercise3 from './components/Exercise3.vue'
import Exercise4 from './components/Exercise4.vue'
import ExerciseFreeform from './components/ExerciseFreeform.vue'
</script>

<style>
.mainGrid {
    padding: 1rem;
    width: auto !important;
}

.exercise-card {
    height: 100%;
    border-radius: 10px;
    border: none;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.25);
}
</style>
