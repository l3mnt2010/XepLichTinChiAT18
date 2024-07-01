<template>
    <footer class="text-center text-sm">
        <span class="font-bold mx-2">Nguồn: ngosangns</span>
        <span class="font-bold mr-2">Clone ké by l3mnt2010 :v</span> <span><button class="p-2 font-bold bg-green-600 rounded-md" onclick="window.print()">Lưu về PDF</button></span>
    </footer>
</template>

<style>
	footer {
		display: flex;
		justify-content: center;
		align-items: center;
		padding: 12px;
		width: 100%;
		min-width: 60rem;
	}

	@media (min-width: 480px) {
		footer {
			padding: 12px 0;
		}
	}
</style>
