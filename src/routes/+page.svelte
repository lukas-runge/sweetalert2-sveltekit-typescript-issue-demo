<script lang="ts">
	import '../app.css';
	import { onMount } from 'svelte';

	import Swal from 'sweetalert2';

	onMount(() => {
		Swal.fire('This thing works!');
	});
</script>
