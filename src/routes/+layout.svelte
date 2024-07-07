<script>
    import logo from '$lib/ateam-ball-no-background.png';
    import "../app.css";
</script>

<nav class="h-24 flex w-full justify-between">
	<a href="/robots" class="flex-auto my-8 basis-1/5 text-center hover:text-yellow-500">Robots</a>
	<a href="/open-source" class="flex-auto my-8 basis-1/5 text-center hover:text-yellow-500">Open Source</a>
    <a href="/" class="flex-auto my-2 basis-1/5 flex justify-center hover:text-yellow-500">
        <img src={logo} alt="The A-Team Logo" class="h-20 mx-0">
    </a>
	<a href="/blog" class="flex-auto my-8 basis-1/5 text-center hover:text-yellow-500">Blog</a>
	<a href="/events" class="flex-auto my-8 basis-1/5 text-center hover:text-yellow-500">Events</a>
</nav>

<slot></slot>