# Progetto-di-Informatica
Forza4
<!DOCTYPE html>
<html>
<body>
	<table id = "Forza4">
	</table>
</body>
<script>
	const R = 6
	const C = 7
	const table = document.getElementById("Forza4")
	table.border = 1
	for (let i = 0; i < R; i++) {
		const row = document.createElement("tr")
		for (let j = 0; j < C; j++) {
			const cell = document.createElement("Td")
			cell.onclick = () => seleziona(j, i)
			row.appendChild(cell)
		}
		table.appendChild(row)
	}
</script>
</html>