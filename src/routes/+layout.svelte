<script>
	import { Canvas } from '@threlte/core';
	import Scene from './Scene.svelte';
</script>

<slot />

<Canvas>
	<Scene />
</Canvas>
