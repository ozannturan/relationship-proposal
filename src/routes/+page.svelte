<script>
	function yes() {
		alert('Congrulations!')
	}

	function no() {
		alert('U Lost Me')
	}
</script>

<div class="flex flex-col items-center justify-center h-screen bg-slate-500 text-6xl">
	<h1 class="bg-yellow-500">Will you go on a date with me?</h1>
	<button on:click={yes} class="bg-green-500 hover:scale-150 duration-200">Yes</button>
	<button on:click={no} class="bg-red-950 hover:scale-50 hover:rotate-90">No</button>
</div>
