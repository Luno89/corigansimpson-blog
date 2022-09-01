<script lang="ts">
	import { page } from '$app/stores';
</script>

<header>
	<nav class="bg-white shadow-lg">
		<div class="max-w-6xl mx-auto px-4">
			<div class="flex justify-between">
				<div class="flex space-x-7">
					<div>
						<a href="#" class="flex items-center py-4 px-2">
							<img src="logo.png" alt="Logo" class="h-8 w-8 mr-2" />
							<span class="font-semibold text-gray-500 text-lg">Towards Better .Dev</span>
						</a>
					</div>
				</div>
				<div class="hidden md:flex items-center space-x-3 ">
					<a
						href=""
						class="py-2 px-2 font-medium text-gray-500 rounded hover:bg-gray-500 hover:text-white transition duration-300"
						>Log In</a
					>
					<a
						href=""
						class="py-2 px-2 font-medium text-white bg-gray-500 rounded hover:bg-gray-400 transition duration-300"
						>Sign Up</a
					>
				</div>
				<div class="md:hidden flex items-center">
					<button class="outline-none mobile-menu-button">
						<svg
							class=" w-6 h-6 text-gray-500 hover:text-green-500 "
							x-show="!showMenu"
							fill="none"
							stroke-linecap="round"
							stroke-linejoin="round"
							stroke-width="2"
							viewBox="0 0 24 24"
							stroke="currentColor"
						>
							<path d="M4 6h16M4 12h16M4 18h16" />
						</svg>
					</button>
				</div>
			</div>
		</div>
		<!-- <div class="hidden mobile-menu">
			<ul class="">
				<li class="active"><a href="index.html" class="block text-sm px-2 py-4 text-white bg-green-500 font-semibold">Home</a></li>
				<li><a href="#services" class="block text-sm px-2 py-4 hover:bg-green-500 transition duration-300">Services</a></li>
				<li><a href="#about" class="block text-sm px-2 py-4 hover:bg-green-500 transition duration-300">About</a></li>
				<li><a href="#contact" class="block text-sm px-2 py-4 hover:bg-green-500 transition duration-300">Contact Us</a></li>
			</ul>
		</div>
		<script>
			const btn = document.querySelector("button.mobile-menu-button");
			const menu = document.querySelector(".mobile-menu");

			btn.addEventListener("click", () => {
				menu.classList.toggle("hidden");
			});
		</script> -->
	</nav>
	<!-- <nav data-sveltekit-prefetch>
		<ul>
			<li class:active={$page.url.pathname === '/'}>
				<a href="/">Home</a>
			</li>
			<li class:active={$page.url.pathname === '/about'}>
				<a href="/about">About</a>
			</li>
			<li class:active={$page.url.pathname === '/todos'}>
				<a href="/todos">Todos</a>
			</li>
		</ul>
		<svg viewBox="0 0 2 3" aria-hidden="true">
			<path d="M0,0 L0,3 C0.5,3 0.5,3 1,2 L2,0 Z" />
		</svg>
	</nav> -->
</header>
