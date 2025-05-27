<script lang="ts">
	const date = new Date();
</script>

<footer>
	<div class="base">
		<div class="container">
			<p>&copy; {date.getFullYear()} Pippo</p>
		</div>
	</div>
</footer>

<style lang="scss">
	.base {
		background-color: #ddd;
	}

	.container {
		height: 3rem;
	}

	p {
		text-align: center;
		line-height: 3rem;
	}
</style>
