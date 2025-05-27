<script lang="ts">
	import Header from '$lib/components/Header.svelte';
	import Footer from '$lib/components/Footer.svelte';
	import '$css/global.scss';
</script>

<div class="wrap">
	<Header />
	<main>
		<div class="base">
			<div class="container">
				<slot />
			</div>
		</div>
	</main>

	<Footer />
</div>

<style lang="scss">
	.wrap {
		display: grid;
		grid-template-rows: auto 1fr auto;
		grid-template-columns: 100%;
		min-height: 100vh;
	}

	.base {
		padding: 0 4rem;
	}

	.container {
		width: 100%;
		max-width: 1200px;
		margin: 0 auto;
	}
</style>
