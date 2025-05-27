<script lang="ts">
	import data from '$lib/assets/header_logo.json';
</script>

<div class="logo">
	<a class="link" href="/">
		<img class="image" src={data.src} alt="" />
		<span class="text">{data.text}</span>
	</a>
</div>

<style lang="scss">
	.logo {
		.link {
			display: flex;
			align-items: center;
			gap: 0.5rem;

			.image {
				width: 2.5rem;
				border-radius: 50%;
			}

			.text {
				font-size: 1.5rem;
			}
		}
	}
</style>
