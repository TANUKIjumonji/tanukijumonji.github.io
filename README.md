# tanukijumonji.github.io
<h1><center>5秒後にリダイレクトします</center><h1>
<script>
function update(timestamp) {

	if (timestamp > 5000) {
		window.location = 'https://1-notes.com/category/css/css-shape-design/';
	} else {
		// 5000秒以内は繰り返す
		window.requestAnimationFrame(update);
	}

}

window.requestAnimationFrame(update);
</script>
