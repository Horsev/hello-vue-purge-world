<template lang="pug">
.hello
	h1 {{ msg }}
	p
		| For a guide and recipes on how to configure / customize this project,
		br
		| check out the&#32;
		a(href='https://cli.vuejs.org' target='_blank' rel='noopener') vue-cli documentation
		| .
	h3 Installed CLI Plugins
	ul
		li
			a(href='https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel' target='_blank' rel='noopener') babel
		li
			a(href='https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint' target='_blank' rel='noopener') eslint

</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>
