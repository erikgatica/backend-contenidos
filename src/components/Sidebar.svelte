<script>
	let current = 'home';
</script>

<div class="app-sidebar sidebar-shadow">
	<div class="app-header__logo">
		<div class="logo-src"></div>
		<div class="header__pane ml-auto">
			<div>
				<button type="button" class="hamburger close-sidebar-btn hamburger--elastic" data-class="closed-sidebar">
				<span class="hamburger-box">
				<span class="hamburger-inner"></span>
				</span>
				</button>
			</div>
		</div>
	</div>
	<div class="app-header__mobile-menu">
		<div>
			<button type="button" class="hamburger hamburger--elastic mobile-toggle-nav">
			<span class="hamburger-box">
			<span class="hamburger-inner"></span>
			</span>
			</button>
		</div>
	</div>
	<div class="app-header__menu">
		<span>
		<button type="button" class="btn-icon btn-icon-only btn btn-primary btn-sm mobile-toggle-header-nav">
		<span class="btn-icon-wrapper">
		<i class="fa fa-ellipsis-v fa-w-6"></i>
		</span>
		</button>
		</span>
	</div>
	<div class="scrollbar-sidebar">
		<div class="app-sidebar__inner">
			<ul class="vertical-nav-menu">
				<li class="app-sidebar__heading">Dashboards</li>
				<li>
					<a href="/" class:mm-active="{current === 'home'}"
							on:click="{() => current = 'home'}">
					<i class="metismenu-icon pe-7s-rocket"></i>
					Home
					</a>
				</li>
				<li class="app-sidebar__heading">Planes</li>
				<li>
					<a href="/planes/entelcl" class:mm-active="{current === 'plan-entelcl'}"
							on:click="{() => current = 'plan-entelcl'}">
					<i class="metismenu-icon pe-7s-diamond"></i>
					EntelCL
					</a>
				</li>
				<li>
					<a href="/planes/entelpe" class:mm-active="{current === 'plan-entelpe'}"
							on:click="{() => current = 'plan-entelpe'}">
					<i class="metismenu-icon pe-7s-car"></i>
					EntelPE
					</a>
				</li>
                <li>
					<a href="/planes/clarocl" class:mm-active="{current === 'plan-clarocl'}"
							on:click="{() => current = 'plan-clarocl'}">
					<i class="metismenu-icon pe-7s-car"></i>
					ClaroCl
					</a>
				</li>
                <li>
					<a href="/planes/womcl" class:mm-active="{current === 'plan-womcl'}"
							on:click="{() => current = 'plan-womcl'}">
					<i class="metismenu-icon pe-7s-car"></i>
					WomCL
					</a>
				</li>
				<li class="app-sidebar__heading">Estadisticas</li>
				<li>
					<a href="/">
					<i class="metismenu-icon pe-7s-diamond"></i>
					EntelCL
					<i class="metismenu-state-icon pe-7s-angle-down caret-left"></i>
					</a>
					<ul>
						<li>
							<a href="/estadisticas">
							<i class="metismenu-icon"></i>
							Planeta Modelos
							</a>
						</li>
						<li>
							<a href="elements-dropdowns.html">
							<i class="metismenu-icon">
							</i>Platinum
							</a>
						</li>
						<li>
							<a href="elements-icons.html">
							<i class="metismenu-icon">
							</i>LadoB
							</a>
						</li>
						<li>
							<a href="elements-badges-labels.html">
							<i class="metismenu-icon">
							</i>MasQueFutbol
							</a>
						</li>
						<li>
							<a href="elements-cards.html">
							<i class="metismenu-icon">
							</i>PornoTube
							</a>
						</li>
						<li>
							<a href="elements-list-group.html">
							<i class="metismenu-icon">
							</i>Ijuegos
							</a>
						</li>
						<li>
							<a href="elements-navigation.html">
							<i class="metismenu-icon">
							</i>ClubCiencias
							</a>
						</li>
						<li>
							<a href="elements-utilities.html">
							<i class="metismenu-icon">
							</i>GoMusic
							</a>
						</li>
					</ul>
				</li>
				<li>
					<a href="/">
					<i class="metismenu-icon pe-7s-car"></i>
					EntelPE
					<i class="metismenu-state-icon pe-7s-angle-down caret-left"></i>
					</a>
					<ul
						>
						<li>
							<a href="components-tabs.html">
							<i class="metismenu-icon">
							</i>Planeta Modelos Pre
							</a>
						</li>
						<li>
							<a href="components-accordions.html">
							<i class="metismenu-icon">
							</i>Planeta Modelos Post
							</a>
						</li>
						<li>
							<a href="components-notifications.html">
							<i class="metismenu-icon">
							</i>LatinStrip Pre
							</a>
						</li>
						<li>
							<a href="components-modals.html">
							<i class="metismenu-icon">
							</i>LatinStrip Post
							</a>
						</li>
						<li>
							<a href="components-progress-bar.html">
							<i class="metismenu-icon">
							</i>LadoB Pre
							</a>
						</li>
						<li>
							<a href="components-tooltips-popovers.html">
							<i class="metismenu-icon">
							</i>LadoB Post
							</a>
						</li>
						<li>
							<a href="components-carousel.html">
							<i class="metismenu-icon">
							</i>HotZone Pre
							</a>
						</li>
						<li>
							<a href="components-calendar.html">
							<i class="metismenu-icon">
							</i>HotZone Post
							</a>
						</li>
						<li>
							<a href="components-pagination.html">
							<i class="metismenu-icon">
							</i>HotTube Pre
							</a>
						</li>
						<li>
							<a href="components-scrollable-elements.html">
							<i class="metismenu-icon">
							</i>HotTube Post
							</a>
						</li>
						<li>
							<a href="components-maps.html">
							<i class="metismenu-icon">
							</i>SexyTube Pre
							</a>
						</li>
                        <li>
							<a href="components-maps.html">
							<i class="metismenu-icon">
							</i>SexyTube Post
							</a>
						</li>
                        <li>
							<a href="components-maps.html">
							<i class="metismenu-icon">
							</i>Ijuegos Pre
							</a>
						</li>
                        <li>
							<a href="components-maps.html">
							<i class="metismenu-icon">
							</i>Ijuegos Post
							</a>
						</li>
                        <li>
							<a href="components-maps.html">
							<i class="metismenu-icon">
							</i>Entel Gana
							</a>
						</li>
					</ul>
				</li>
                <li>
					<a href="/">
					<i class="metismenu-icon pe-7s-car"></i>
					ClaroCl
					<i class="metismenu-state-icon pe-7s-angle-down caret-left"></i>
					</a>
					<ul>
						<li>
							<a href="components-tabs.html">
							<i class="metismenu-icon">
							</i>Platinum
							</a>
						</li>
						<li>
							<a href="components-accordions.html">
							<i class="metismenu-icon">
							</i>HotZone
							</a>
						</li>
						<li>
							<a href="components-notifications.html">
							<i class="metismenu-icon">
							</i>La Roja
							</a>
						</li>
					</ul>
				</li>
                <li>
					<a href="/">
					<i class="metismenu-icon pe-7s-car"></i>
					WomCL
					<i class="metismenu-state-icon pe-7s-angle-down caret-left"></i>
					</a>
					<ul>
						<li>
							<a href="components-tabs.html">
							<i class="metismenu-icon">
							</i>Juegos
							</a>
						</li>
					</ul>
				</li>
				<li class="app-sidebar__heading">Forms</li>
				<li>
					<a href="forms-controls.html">
					<i class="metismenu-icon pe-7s-mouse">
					</i>Forms Controls
					</a>
				</li>
				<li>
					<a href="forms-layouts.html">
					<i class="metismenu-icon pe-7s-eyedropper">
					</i>Forms Layouts
					</a>
				</li>
				<li>
					<a href="forms-validation.html">
					<i class="metismenu-icon pe-7s-pendrive">
					</i>Forms Validation
					</a>
				</li>
				<li class="app-sidebar__heading">Charts</li>
				<li>
					<a href="charts-chartjs.html">
					<i class="metismenu-icon pe-7s-graph2">
					</i>ChartJS
					</a>
				</li>
				<li class="app-sidebar__heading">PRO Version</li>
				<li>
					<a href="https://dashboardpack.com/theme-details/architectui-dashboard-html-pro/" target="_blank">
					<i class="metismenu-icon pe-7s-graph2">
					</i>
					Upgrade to PRO
					</a>
				</li>
			</ul>
		</div>
	</div>
</div>