<script setup lang="ts">
import { defineComponent } from 'vue';

interface ComponentProps{
    title: string;
}

const props = defineProps<ComponentProps>()
</script>
<script lang="ts">
export default defineComponent({
    data() {
        return { }
    },
    methods: {},
})
</script>

<template>
    <div v-show="false" >
        {{ props.title }}
    </div>
</template>

<style scoped>
</style>