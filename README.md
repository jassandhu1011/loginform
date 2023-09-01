# loginform
<!------A basic functional login form made with html------>
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta http-equi="X-UA-Compatible" content="IE=edge">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Login Form</title>
</head>
<body>
<div class="container">
	<div class="box">
		<!--------------Login Box------------------------>
		<div class="box-login" id="login">
		<div class="top-header">
		<h3>Login form</h3>
		<h4>Happy to have you back.</h4>
	</div>
		<div class="input-group">
		<input type="text" class="input-box" id="logEmail" required>
		<label for="logEmail">Email address</label>
	</div>
<div class="input-group">
		<input type="password" class="input-box" id="logPassword" required>
		<label for="logPassword">Password</label>
		<div class="eye-area">
		<div class="eye-box" onclick="myLogPassword">
		<i class="fa-regular fa-eye" id="eye"></i>
		<i class="fa-regular fa-eye-slash" id="eye-slash"></i>
	</div>
		<div class="remember">
		<input type="checkbox" id="formcheck" class="check">
		<label for="formcheck">Remember me</label>
	</div>
	<input type="submit" value="Sign-in" name="submit" id="submit">
		<div class="forget"
		<a href="#">Forgot password?</a>
		</div>
	<div class="register-link">
	<p>Don't have an account?
	<a href="registerform.html">Register</a></p>
</div>
	<style>
	@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500&display=swap');
*
{
	margin: 0;
	padding: 0;
	box-sizing: border-box;
	font-family: 'Poppins',sans-serif;
}
body
{
	background-color: rgba(254,194,12);
	background-size: cover;
	background-position: center;
	background-repeat: no-repeat;
	background-attachment: fixed;
}
.container
{
	display: flex;
	justify-content: center;
	align-items: center;
	min-height: 100vh;
}
.box
{
	display: flex;
	flex-direction: row;
	position: relative;
	padding: 60px 20px 30px;
	height: 620px;
	width: 350px;
	background-color: rgb(255,220,220,0.4);	
	border-radius: 30px;
	-webkit-backdrop-filter: blur(15px);
	backdrop-filter: blur(15px);
	border: 3px solid rgba(255,255,255,0.2);
	overflow:hidden;	
}
.box-login
{
	postion: absolute;
	width: 85%;
	left: 27px;
	transition: .5s ease-in-out;
}
.top-header h3
{
	font-size: 22px;
	font-weight: 600;
	margin-bottom: 8px;
	font-style: gigi
}
.top-header h4
{
	font-size: 14px;
	font-weight:300;
	margin-botton: 8px
}
.input-group
{
	width: 100%;
}
.input-box
{
	width: 100%;
	height: 50px;
	font-size: 15px;
	color: #040404;
	border: none;
	border-radius: 10px;
	padding: 7px 45px 0 20px;
	background: rgba(224,223,223,0.6);
	background-filter: blur(2px);
	outline: none;
}
.input-field label
{
	position: absolute;
	left: 20px;
	top: 15px;
	font-size: 15px;
	transition: .3s ease-in-out;
}
.input-box:focus ~ label,.input-box:valid ~ label
{
	top: 2px;
	font-size: 10px;
	color: #c12828;
}
.remember
{ 	
	display: flex;
	font-size: 13px;
	margin: 12px 0 30px 0;
	color: #000;
}
.check
{
	margin-right: 8px;
	width: 14px;
}
input#submit
{
	weight:100%;
	height: 50%;
	font-size: 20px;
	font-weigth: 500;
	margin-left: 100px;
	border: block yellow;
	border-radius: 10px;
	background: rgba(254,194,12);
	color: #fff;
	box-shadow: 0px 4px 20px rgba(62,9,9,0.145);
	cursor: pointer;
}
</style>
</html>
