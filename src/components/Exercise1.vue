<template>
    <n-card title="Ex 1: Data" class="exercise-card">
        <p>
            Display the component data in this card. Feel free to use naive-ui
            or custom components.
        </p>
    </n-card>
</template>

<script setup lang="ts">
import { NCard } from 'naive-ui'

const text = 'This is an awesome string'
const num = 46
const colours = ['black', 'blue', 'red', 'cyan', 'magenta']
const team = { sport: 'football', players: 11, ball: true, bat: false }
</script>
