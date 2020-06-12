<script>
	import Footer from '../components/Footer.svelte';
	import Menu from '../components/Menu.svelte';
	import Nav from '../components/Nav.svelte';
	import SettingsPage from '../components/SettingsPage.svelte';
	import Sidebar from '../components/Sidebar.svelte';
	import TitlePage from '../components/TitlePage.svelte';
</script>
<style></style>
<body>
	<div class="app-container app-theme-white body-tabs-shadow fixed-sidebar fixed-header">
		<Menu/>
		<SettingsPage/>  
		<div class="app-main">
			<Sidebar/>
			<div class="app-main__outer">
				<div class="app-main__inner">
				
					<main>
						<slot></slot>
					</main>
				</div>
				<!--<Footer/>-->
			</div>
		</div>
	</div>
	<script type="text/javascript" src="assets/scripts/main.js" async></script>
</body>