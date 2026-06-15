<script>
	import { page } from '$app/state';
</script>

<h1>{page.status === 404 ? 'Page not found' : 'Something went wrong'}</h1>
<p>
	{#if page.status === 404}
		The page you are looking for does not exist.
	{:else}
		{page.error?.message}
	{/if}
</p>
<a href="/">Go back home</a>