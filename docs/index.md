<! DOCTYPE html>
<html>
<head>
<title>The Box Model</title>
<style>
* {
	box-sizing: border-box;
	margin: 0;
	padding: 0;
}
body{
	background-color: gray;
	margin: 0;
	padding: 0;
}
#box {
	 background-color:blueviolet;
	 padding: 10px;
	 border: 5px solid black;
	 margin: 40px;
	 width: 400px;
	 margin-top: 50px;
	 overflow: auto;
}
#content {
	background-color:#90EE90 ;
}
h1{
	margin-bottom: 30px;
}
</style>
</head>
<body>
<h1> BOX MODEL </h1>
<div id="box">
<div id="content">The CSS Box Model is essentially a box that wraps around every HTML element. It consists of: borders,padding,margins, and the actual contents.</div>
</div>
</body>
</html>
