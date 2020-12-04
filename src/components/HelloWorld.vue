<template>
	<h1>{{ msg }}</h1>
	<button @click="count++">count is: {{ count }}</button>
	<p class="bg-black font-bold">
		Edit x <code>components/HelloWorld.vue</code> to test hot module
		replacement.
	</p>
</template>

<script>
	export default {
		name: "HelloWorld",
		props: {
			msg: String,
		},
		data() {
			return {
				count: 0,
			};
		},
	};
</script>
