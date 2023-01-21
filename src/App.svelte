<script>
	let count = 1

	const increment = () => {
		count++
	}

	const decrement = () => {
		count--
	}
</script>

<main>
    <p>
        {count}
    </p>
    <button id="inc" on:click={increment}>+</button>
    <button id="dec" on:click={decrement}>-</button>
</main>

<style>
	main {
		color: white;
		text-align: center;
		align-items: center;
		justify-content: center;
		width: 100%;
		height: 100%;
		max-width: 500px;
		max-height: 300px;
		margin: 0 auto;
		font-size: 200%;
		background-color: blue;
		padding: 35px
	}

	button {
		height: 70px;
		width: 70px;
		color: white;
		align-items: center;
		justify-content: center;
		text-align: center;
	}

	#inc {
		background-color: green;
	}

	#dec {
		background-color: red;
	}
</style>