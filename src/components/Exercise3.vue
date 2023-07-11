<template>
    <n-card title="Ex 3: Computed" class="exercise-card">
        <p>Create an input of any sort to modify the `animal` data.</p>
        <p>
            Display the animal data using HTML elements, components, or library
            components.
        </p>
        <p>
            Finally, create a couple of elements to display the animal data, but
            make sure to "add something to it". For example, display add the
            string "My favourite pet is..."
        </p>
    </n-card>
</template>

<script setup lang="ts">
import { NCard } from 'naive-ui'
import { ref } from 'vue'

const animal = ref('sheep')
</script>
