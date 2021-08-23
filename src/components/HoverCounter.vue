<template>
	<div>
		<h2 @mouseover="incrementCount">Clicked {{ count }} times </h2>
	</div>
</template>

<script>
import CounterMixin from '../mixins/counter'

	export default {
		name: 'HoverCount',
		mixins: [CounterMixin]
		// data() {
		// 	return {
		// 		count: 100,
		// 	}
		// },
		// methods: {
		// 	incrementCount() {
		// 		this.incrementCount += 1
		// 	}
		// }
	}
</script>

<style scoped>

</style>