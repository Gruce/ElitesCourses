<template>
    <div class="w-min border-2 border-[#262626] rounded flex" :class="{ 'flex-col w-96' : col }">
        <slot />
    </div>
</template>

<script setup>
const props = defineProps({
    col: {
        type: Boolean,
        default: false,
    }
})
</script>
