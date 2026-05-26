<svelte:head>
	<title>ReactorFailure | Home</title>
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
			<p class="-mt-5">I have a DEC in Computer Science & Math and I am currently majoring in Accounting</p>
		</div>
	</div>
</section>

<section>
	<div class="flex item-center justify-center gap-2.5">
		<div class="border-3 border-indigo-500 bg-indigo-50 rounded-md p-2 w-1/3 overflow-hidden">
			<h1>Announcements</h1>
			<div>
				<p>No announcements</p>
			</div>
		</div>
		<div class="border-3 border-violet-500 bg-violet-50 rounded-md p-2 flex-1 overflow-hidden">
			<h1>Blog Posts</h1>
			<div>
				<p>No blog posts</p>
			</div>
		</div>
	</div>
</section>

<section id="section-contact" class="text-center mt-5 p-2 bg-[#e0e0e0] rounded-md font-semibold">
	<h1 class="contact">Contact</h1>
	<div class="flex items-center justify-center -mt-0.5 mb-3">
		<div class="h-2 bg-blue-500 w-24"></div>
	</div>
	<p>I rarely check these communication channels, I'll do my best to check my inbox</p>
	
	<div class="flex items-center justify-center gap-3 mt-3">
		<a href="https://github.com/ReactorFailure" target="_blank" class="circle-btn bg-[#24292e]">
			<span class="circle-btn-icon">
				<img src="/github-icon.png" alt="Github Logo" width="35" height="35" />
			</span>
			<span class="circle-btn-label text-lg">Github</span>
		</a>
		
		<a href="mailto: soup2soup@proton.me" target="_blank" class="circle-btn bg-[#0369a1]">
			<span class="circle-btn-icon">
				<img src="/email-icon.png" alt="Email Icon" width="35" height="35" />
			</span>
			<span class="circle-btn-label text-lg">Email</span>
		</a>
	</div>
</section>