<template lang="pug">
.container
	img(src="../assets/hammer-sickle.svg" width="150px")
	h1 {{ msg }}
	h2 Ai Conflito
	h4 O Velho Cabrito de São Benedito

	button.btn.btn-secondary.btn-lg.active.mt-5.mr-3.dignity
		i.fa.fa-street-view.fa-2x.mr-2
		| Impress Me
	button.btn.btn-primary.btn-lg.active.mt-5.dignity
		i.fa.fa-street-view.fa-2x.mr-2
		| Imprint Me
</template>

<script>
export default {
	name: 'HelloWorld',
	data () {
		return {
			msg: 'Adeus, Mundo Imundo'
		}
	}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
	font-weight: normal;
}
ul {
	list-style-type: none;
	padding: 0;
}
li {
	display: inline-block;
	margin: 0 10px;
}
a {
	color: #42b983;
}
</style>
