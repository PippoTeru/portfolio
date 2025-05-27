<script lang="ts">
	import data from '$lib/assets/global_nav.json';
</script>

<nav class="g-nav">
	<ul class="list">
		{#each data as item}
			<li class="item">
				<a href={item.href}>{item.text}</a>
			</li>
		{/each}
	</ul>
</nav>

<style lang="scss">
	.g-nav {
		.list {
			display: flex;
			gap: 1rem;
		}
	}
</style>
