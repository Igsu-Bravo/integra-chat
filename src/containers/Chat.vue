<template>
	<section id="main-wrapper">
		<p>Title</p>
		<p>Info</p>
		<p>contentsz</p>
	</section>
</template>
<script>
export default {
  name: 'Chat',
  props: {
		conf: [],
 }
}
</script>
<style scoped>
#main-wrapper {
  font-family: 'Courier New', Courier, monospace;
	max-width: 300px;
	display: flex;
	flex-direction: column;
	border: 1px solid green;
	border-radius: 10px;
}
</style>