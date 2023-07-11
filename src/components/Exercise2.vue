<template>
    <n-card title="Ex 2: Methods" class="exercise-card">
        <p>Value 1: {{ val1 }}</p>
        <p>Value 2: {{ val2 }}</p>
        <p>Add buttons (or similar) and create methods to:</p>
        <n-list>
            <n-li>Modify value 1</n-li>
            <n-li>Modify value 2</n-li>
            <n-li>Modify both at the same time</n-li>
        </n-list>
    </n-card>
</template>

<script setup lang="ts">
import { NCard, NList, NLi } from 'naive-ui'
import { ref } from 'vue'

const val1 = ref(0)
const val2 = ref(0)
</script>
