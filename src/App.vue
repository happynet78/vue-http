<template>
	<!-- <CreatePost />
	<PostList /> -->

	<!-- Lifecycle Hooks -->
	<!-- <Parent /> -->

	<!-- <TemplateRef /> -->

	<!-- Mixin -->
	<ClickCount />
	<HoverCount />
</template>

<script>
// import PostList from './components/PostList.vue'
// import CreatePost from './components/CreatePost.vue'
// import Parent from './components/Parent.vue'
// import TemplateRef from './components/TemplateRef.vue'
import ClickCount from './components/ClickCounter.vue'
import HoverCount from './components/HoverCounter.vue'

export default {
	name: 'App',
	components: {
		// PostList,
		// CreatePost,
		// Parent,
		// TemplateRef,
		ClickCount,
		HoverCount,
	}
}
</script>

<style>
#app {
	font-family: Avenir, Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: #2c3e50;
	margin-top: 60px;
}
</style>
