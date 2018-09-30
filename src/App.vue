<template>
	<div id="app">
  		<Presence />
	</div>
</template>

<script>
    import Presence from './components/Presence.vue'

    export default {
        name: 'app',
        components: {
            Presence
        }
    }
</script>

<style>
	#app {
		font-family: 'Avenir', Helvetica, Arial, sans-serif;
		-webkit-font-smoothing: antialiased;
		-moz-osx-font-smoothing: grayscale;
		text-align: center;
	}
</style>
