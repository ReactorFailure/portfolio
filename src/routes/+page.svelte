<script>
	import { onMount } from "svelte";

	onMount(() => {
		const script = document.createElement('script');
		script.src = 'https://iframe.chat/scripts/main.min.js';
		script.onload = () => {
			chattable.initialize({
				stylesheet: '/css/chattable.css'
			});
		};
		document.head.appendChild(script);
	});
</script>

<svelte:head>
	<title>Home - ReactorFailure</title>
</svelte:head>

<section class="rounded-md shadow-md text-center p-5 mb-5 font-semibold bg-linear-to-b from-violet-700 to-indigo-950 to-95% text-white relative overflow-hidden">
	<img src="/logo_fidgetSpinner.gif" alt="Logo spinning like a fidget spinner" class="absolute left-0 top-0 h-full object-cover opacity-20 pointer-events-none"/>
	
	<div class="relative z-10">
		<div>
			<h1>Hello!</h1>
			<h2 class="-mt-1">Welcome to my site</h2>
			<div class="my-4"></div>
			<div class="flex items-center justify-center">
				<div class="h-2 bg-blue-500 w-24"></div>
			</div>
		</div>
		<div class="pt-5">
			<p class="mt-1 p-1">I'm ReactorFailure. I like to program sometimes as a hobby and try to learn new things.</p>
			<p class="-mt-5">I have a degree in Computer Science & Math and I am currently majoring in Accounting</p>
		</div>
	</div>
</section>

<section>
	<div class="flex item-center justify-center gap-2.5">
		<div class="border-3 border-indigo-500 bg-indigo-50 rounded-md p-2 w-1/3 overflow-hidden">
			<h2>Announcements</h2>
			<div>
				<p>No announcements</p>
			</div>
		</div>
		<div class="border-3 border-violet-500 bg-violet-50 rounded-md p-2 flex-1 overflow-hidden">
			<h2>Blog Posts</h2>
			<div>
				<p>No blog posts</p>
			</div>
		</div>
	</div>
</section>

<section id="section-contact" class="text-center mt-5 mb-5 p-2 bg-[#e0e0e0] rounded-md font-semibold">
	<h1 class="contact">Contact</h1>
	<div class="flex items-center justify-center -mt-0.5 mb-3">
		<div class="h-2 bg-blue-500 w-24"></div>
	</div>
	<div class="pt-1">
		<p class= "mt-1 p-1">I rarely check these communication channels but I'll do my best to check my inbox.</p>
		<p class= "-mt-5">Alternatively, you might have a chance to talk to me on the chat room below.</p>
	</div>
	
	<div class="flex items-center justify-center gap-3 mt-3">
		<a href="https://github.com/ReactorFailure" target="_blank" class="circle-btn bg-[#24292e]">
			<span class="circle-btn-icon">
				<img src="/icons/logo/github-icon.webp" alt="Github Logo" width="35" height="35" />
			</span>
			<span class="circle-btn-label text-lg">Github</span>
		</a>
		
		<a href="https://codeberg.org/ReactorFailure" target="_blank" class="circle-btn bg-[#01579b]">
			<span class="circle-btn-icon">
				<img src="/icons/logo/codeberg-icon.webp" alt="Codeberg Logo" width="35" height="35" />
			</span>
			<span class="circle-btn-label">Codeberg</span>
		</a>
		
		<a href="mailto: soup2soup@proton.me" target="_blank" class="circle-btn bg-[#00857f]">
			<span class="circle-btn-icon">
				<img src="/icons/logo/email-icon.webp" alt="Email Icon" width="35" height="35" />
			</span>
			<span class="circle-btn-label text-lg">Email</span>
		</a>
	</div>
</section>

<section class="flex flex-col items-center bg-[#e0e0e0] border-double border-10 border-amber-900 p-2">
	<div class="bg-indigo-500 p-2 rounded-t-md text-cyan-300">
		<h2>Useless Chatroom</h2>
	</div>
	<!-- svelte-ignore a11y_missing_attribute -->
	<iframe
		id="chattable"
		class="w-full max-w-2xl h-[500px] border-indigo-500 border-5 rounded-b-md"
		src="https://iframe.chat/embed?chat=test020202"
	></iframe>
	
	<div>
		<div>
			
		</div>
		
		<div>
			
		</div>
	</div>
</section>