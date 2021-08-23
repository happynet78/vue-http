<template>
	<div>
		<button @click="incrementCount">Clicked {{ count }} times </button>
	</div>
</template>

<script>
import CounterMixin from '../mixins/counter'

	export default {
		name: 'ClickCount',
		mixins: [CounterMixin],
		// data() {
		// 	return {
		// 		count: 0,
		// 	}
		// },
	}
</script>

<style scoped>

</style>