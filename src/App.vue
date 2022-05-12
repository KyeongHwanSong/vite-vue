<template lang="">
	<div @click="increase">{{ count }}</div>
	<p><img src="./assets/images/logo.png" alt="" /></p>
</template>
<script>
export default {
	data() {
		return {
			count: 0,
		};
	},
	methods: {
		increase() {
			this.count++;
		},
	},
};
</script>
<style lang=""></style>
