# PasswordBox
блок с запросом пароля
<!DOCTYPE html>
<html>
<head>
	<title>Пароль</title>
	<style>
		body{
			background-color: lightblue;
			padding: 30px;
		}
	</style>
	<script>
		function checkPassword() {
			var password = document.getElementById("passwordBox");
			var passwordText = password.value;
			if (passwordText == "ernest300") {
				return true;
			}
			alert("Доступ запрещен!");
			return false;
		}
	</script>
</head>
<body>
	<p style="font-size: 30pt;">Найден алмаз МОНАХ</p>
	<p>Для входа на сайт введите пароль!</p>
	<p>Пароль:<input id="passwordBox" type="password"></p>
	<a href="monkdiamonddiscovery.html" onclick="return checkPassword();">
	Нажать для проверки пароля и перехода на сайт.</a>
</body>
</html>
