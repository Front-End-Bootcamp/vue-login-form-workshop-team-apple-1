<script setup>
const props = defineProps(['name', 'variant', 'classes']);
</script>
	
<template>
	<button :class="[props.classes, 'btn btn-'+props.variant]">{{props.name}}</button>
</template>