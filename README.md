# group-17-roll-no-49-to-51

--------------

Syntax for the project on webpage of a website.

--------------

@import url('https://fonts.googleapis.com/css?family=Roboto:700&display=swap');
*{
	padding: 0;
	margin: 0;
}
.wrapper{
	background: url(bg1.jpg) no-repeat;
	background-size: cover;
	height: 100vh;
}
.navbar{
	position: fixed;
	height: 80px;
	width: 100%;
	top: 0;
	left: 0;
	background: rgba(0,0,0,0.4);
}
.navbar .logo{
	width: 150px;
	height: auto;
	padding: 20px 100px;
}
.navbar ul{
	float: right;
	margin-right: 20px;
}
.navbar ul li{
	list-style: none;
	margin: 0 8px;
	display: inline-block;
	line-height: 80px;
}
.navbar ul li a{
	font-size: 20px;
	font-family: 'Roboto', sans-serif;
	color: white;
	padding: 6px 13px;
	text-decoration: none;
	transition: .4s;
}
.navbar ul li a.active,
.navbar ul li a:hover{
	background: red;
	border-radius: 2px;
}
.wrapper .center{
	position: absolute;
	left: 50%;
	top: 55%;
	transform: translate(-50%, -50%);
	font-family: sans-serif;
	user-select: none;
}
.center h1{
	color: white;
	font-size: 70px;
	width: 900px;
	font-weight: bold;
	text-align: center;
}
.center h2{
	color: white;
	font-size: 70px;
	font-weight: bold;
	margin-top: 10px;
	width: 885px;
	text-align: center;
}
.center .buttons{
	margin: 35px 280px;
}
.buttons button{
	height: 50px;
	width: 150px;
	font-size: 18px;
	font-weight: 600;
	color: #ffb3b3;
	background: red;
	outline: none;
	cursor: pointer;
	border: 1px solid #cc0000;
	border-radius: 25px;
	transition: .4s;
}
.buttons .btn2{
	margin-left: 25px;
}
.buttons button:hover{
	background: #cc0000;
}
