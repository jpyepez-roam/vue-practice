<template>
    <n-card title="Ex 4: Watch" class="exercise-card">
        <p>
            Create a button, switch, or input to toggle the "status". Use the
            status variable to show/hide the alert below (or perhaps to change
            its content).
        </p>
        <n-alert title="Success!" type="success"> Status alert </n-alert>
    </n-card>
</template>

<script setup lang="ts">
import { NCard } from 'naive-ui'
import { NAlert } from 'naive-ui'
import { ref } from 'vue'

const status = ref(false)
</script>
