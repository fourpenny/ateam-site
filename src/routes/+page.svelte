<script>
    import league from '$lib/league_photo.jpg';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<meta name="description" content="The A-Team Website" />
</svelte:head>

<div class="w-full">
	<div>
		<h1 class="text-center my-2 text-2xl">The A-Team</h1>
		<h2 class="text-center text-xl">RoboCup SSL</h2>
	</div>
	<div class="flex justify-center">
		<img src={league} alt="RoboCup SSL League 2023" class="size-3/5 flex-none my-8 rounded-md border-4 border-yellow-500"/>
	</div>
</div>
