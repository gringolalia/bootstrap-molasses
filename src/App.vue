<template lang="pug">
#app
	.bmd-layout-container.bmd-drawer-f-l.bmd-drawer-overlay(style="position: absolute")
		header.bmd-layout-header
			.navbar.navbar-light.bg-faded
				button.navbar-toggler(type='button', data-toggle='drawer', data-target='#dw-s2')
					span.sr-only Toggle drawer

					i.material-icons menu

				ul.nav.navbar-nav
					li.nav-item.dignity.mr-5(style="font-size: 20px")
						i.fa.fa-gears.fa-2x.mr-3
						| Engenho Novo LLC

		#dw-s2.bmd-layout-drawer.bg-faded
			header.p-3.mb-2.text-white.bg-dark.text-left
				a.navbar-brand.dignity
					i.material-icons.mr-3 restaurant
					| O Cardápio

			ul.list-group.dignity
				a.list-group-item
					i.material-icons local_dining
					| Enchiladas

				a.list-group-item
					i.material-icons room_service
					| Tacos

				a.list-group-item.active.text-white
					i.material-icons restaurant_menu
					| Tamales

				a.list-group-item
					i.material-icons fastfood
					| Quesadillas

				a.list-group-item
					i.material-icons local_bar
					| Margaritas

				a.list-group-item
					i.material-icons beach_access
					| Cochinita

				a.list-group-item
					i.fa.fa-street-view.fa-2x
					| Chilaquiles

				a.list-group-item
					i.material-icons free_breakfast
					| Guacamole

				a.list-group-item
					i.fa.fa-bus.fa-lg
					| Mole Poblano

				a.list-group-item
					i.material-icons waves
					| Cabrito


		main.bmd-layout-content
			.container
				router-view
</template>

<script>
export default {
	name: 'App'
}
</script>

<style>
#app {
	font-family: 'Avenir', Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: #2c3e50;

}

.list-group-item.active {
	background-color: #607D8B;
	color: white;
}

</style>
