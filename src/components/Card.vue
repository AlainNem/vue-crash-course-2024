<script setup>
import { defineProps } from 'vue';

defineProps({
   bg: {
       type: String,
       default: 'bg-grey-100'
   }
})
</script>

<template>
    <div :class="`${bg} p-6 rounded-lg shadow-md`">
        <slot></slot>
    </div>
</template>