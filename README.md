# minicurso-web-responsivo

<!--
assim que comenta as coisa em html
-->

<html>
<head>
<title>Segundo Site</title>
<meta name="viewport" content= "width = device-width, initial-scale=1.0">
<style>


*{
	margin:0;
}
.container{
width:1140px;
background:gray;
}
.col-1{
width:8.33333333333333%;
float: left;
border: 1px solid grey;	
box-sizing: border-box;
}
.linhas{
margin-bottom: 20px;
}
.col-2{
width:16.66666666666667%;
float: left;
border: 1px solid grey;	
}
.col-3{
width:25%;
float: left;
border: 1px solid grey;
}

@media(max-width:480px){
	.col-1{
		width:50%
	}
	.col-2,
	.col-3
	{
	width:100%;
	}
	.container{
		width:100%
	}
}
</style>
</head>
<body>
	<div class="container">
		<div class = "linha">
			<div class = "col-1">col-1</div>
			<div class = "col-1">col-1</div>
			<div class = "col-1">col-1</div>
			<div class = "col-1">col-1</div>
			<div class = "col-1">col-1</div>
			<div class = "col-1">col-1</div>
			<div class = "col-1">col-1</div>
			<div class = "col-1">col-1</div>
			<div class = "col-1">col-1</div>
			<div class = "col-1">col-1</div>
			<div class = "col-1">col-1</div>
			<div class = "col-1">col-1</div>
		</div>
		<div class = "linha">
			<div class = "col-2">col-2</div>
			<div class = "col-2">col-2</div>
			<div class = "col-2">col-2</div>
			<div class = "col-2">col-2</div>
			<div class = "col-2">col-2</div>
			<div class = "col-2">col-2</div>			
		</div>
		<div class="linha">
			<div class = "col-3">col-3</div>
			<div class = "col-3">col-3</div>
			<div class = "col-3">col-3</div>
			<div class = "col-3">col-3</div>
		</div>
		
	</div>
</body>

</html>
