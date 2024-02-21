<script>
	function yes() {
		alert('tebrikler')
	}

	function no() {
		alert('Allah Kahretsin seni')
	}
</script>

<div class="flex flex-col items-center justify-center h-screen bg-slate-500 text-6xl">
	<h1 class="bg-yellow-500">Benimle çıkar mısın?</h1>
	<button on:click={yes} class="bg-green-500 hover:scale-150 duration-200">evet</button>
	<button on:click={no} class="bg-red-950 hover:scale-50 hover:rotate-90">hayır</button>
</div>
