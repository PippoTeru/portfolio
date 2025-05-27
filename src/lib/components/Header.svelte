<script lang="ts">
	import HeaderLogo from './HeaderLogo.svelte';
	import GlobalNav from './GlobalNav.svelte';
</script>

<header>
	<div class="base">
		<div class="container">
			<HeaderLogo />
			<GlobalNav />
		</div>
	</div>
</header>

<style lang="scss">
	.base {
		background-color: #fff;
		box-shadow: 0 4px 4px #ddd;
	}

	.container {
		display: flex;
		justify-content: space-between;
		align-items: center;
		width: 100%;
		max-width: 1200px;
		height: 4.5rem;
		margin: 0 auto;
	}
</style>
