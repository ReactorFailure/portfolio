<script>
	let { children } = $props();
</script>

<div class = "wrapper">
	
	<aside class="sidebar shadow-xl">
		<div class="mb-4 text-center border-b-2">
			<a href="/">
				<img src="/logo_cubeSpin.gif" alt="Logo as a spinning cube" width="210" height="210" class="max-w-fill h-auto pointer-events-none">
				<p class="text-left font-bold">@ReactorFailure</p>
			</a>
		</div>
		<nav>
			<ul class="sidebar-nav space-y-1 list-none font-bold">
				<li><a href="/">Home</a></li>
				<li><a href="/blog">Blog</a></li>
				<li><a href="/projects">My Projects</a></li>
				<li><a href="/tools">Tools</a></li>
			</ul>
		</nav>
	</aside>
	
	<div class="main">
		<main class="main-content shadow-xl">
			{@render children()}
		</main>
		
		<footer class="footer shadow-xl">
			<div class="mb-5">
				<div class="flex justify-center mb-1">
					<a href="https://github.com/ReactorFailure" target="_blank" class="flex items-center gap-1">
						<img src="/logo.png" alt="small logo" width="20" height="20"/>
						@ReactorFailure
					</a>
				</div>
				
				<div class="flex items-center justify-center gap-2">
					<a href="/#section-contact">Contact</a>
					<span class="footer-divider"></span>
					<a href="https://github.com/ReactorFailure/portfolio/blob/master/LICENSE">Site Repo</a>
					<span class="footer-divider"></span>
					<a href="https://boiledsoup.atabook.org" target="_blank"> AtaBook Guestbook</a>
				</div>
			</div>
			<p>Made with <a href="https://svelte.dev/" target="_blank">SvelteKit</a>, <a href="https://tailwindcss.com/" target="_blank">TailwindCSS</a>, <a href="https://www.3dgifmaker.com/" target="_blank"> 3D Gif Maker</a>, <a href="https://www.getpaint.net/" target="_blank">Paint.NET</a>, Duct Tape, WD-40, and Hopes and Dreams</p>
			<p><a href="https://github.com/ReactorFailure/portfolio" target="_blank">© 2026 - Licensed under Apache 2.0 License</a></p>
		</footer>
	</div>
</div>