<template lang="pug">
#app.p-5.d-flex.flex-column
	img.align-self-center(alt='Vue logo' src='./assets/logo.png' width="200" height="200")
	hello-world(msg='Vue.js App + Bootstrap + postcss/purgecss')
	.d-flex
		button.btn.btn-danger(type="button") Danger
		.p-1
		button.btn.btn-custom(type="button") Custom
	.p-2
	a.text-custom(href="#") Custom link
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style lang="sass" scoped>
img
  animation: 0.25s appear ease-in

@keyframes appear
  0%
    opacity: 0
</style>
