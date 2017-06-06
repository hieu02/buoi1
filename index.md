<html>
<head>
<meta name="description" content="Baivenha" />
<meta name="keywords" content="HTML,CSS,XML,JavaScript" />
<meta name="author" content="duchieu" />
<meta http-equiv="content-type" content="text/html;charset=UTF-8" />
</head>
<body>
  <form action="/action_page.php">
  <input type="text" name="Họ" placeholder="Họ">
  <input type="text" name="Tên" placeholder="Tên">
</form>
<p>Ấn vào nút đăng kí để hoàn thành:</p>
<button onclick="myFunction()">Đăng kí</button>
<p id="demo">Chúc mừng đã đăng kí thành công</p>
<script>
if ( document.getElementById("demo").value)
{ greeting= "Chúc mừng bạn đã đăng kí thành công";}
</script>
</body>
</html>
