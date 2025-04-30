<script>
	import '../app.css';

	let { children } = $props();
</script>


<nav class="fixed top-0 left-0 right-0 bg-gray-800 text-white p-4 flex justify-center space-x-8 z-10">
	<a href="/" class="hover:text-gray-400">Einführung</a>
	<a href="/typography" class="hover:text-gray-400">Typography</a>
	<a href="/colorundcontrast" class="hover:text-gray-400">Color and Contrast</a>
	<a href="/animationundmotion" class="hover:text-gray-400">Animation and Motion</a>
  </nav>

{@render children()}
