# myFirstSpringTask

</!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>First Project With CSS</title>
	<style type="text/css">
		header {
			background-color: rgb(132, 0, 15);

		}

		p{
			color:white;
		}

		.headList {
			color: white;
			display: flex;
			list-style-type: none;
			justify-content: right ;
			
		}
		.headList > li{
			margin-left: 10px;
			margin-right: 10px;
		}

		.headList>li>a {
			color: gray;
			font-size: 13px;
			text-decoration: none;
		}


		.headList{
			position: absolute;
			top: 0;
			right: 0;
			display: flex;
			margin: 2;
			padding: 6;
			z-index: 1;

		}

		.body1{
			background-color: rgb(180, 215, 218);
			display: flex;

		}

		.body1 p{
			display: flex;
			color: black;
			
		}

		.body1 img{
			width:500px;
			margin: auto; 
			padding: 20px 20px 20px 20px;
		}

		.latestNews {
			text-align: center;
		}

		.body3 {
			display: flex;
			margin-left: auto;
			margin-right: auto;

		}

		.body3 button{
			color: white;
			background-color: rgb(132, 0, 15);
			border: none;
		}

		.body3 img{
			width:300px;
		}

		.body3 p{
			color: black;
			
		}

		.body3 div{
			border:2px #d9dbdb solid; 
			width:300px;
			margin:auto;
             		}

	/*	.firstBlock{
			border:2px #d9dbdb solid; 
			width:150px;
		}
*/
		



	</style>
</head>
<body>
<header>
<p class="headertitle"><b>BITLAB</b> NEWS</p> 
<ul class="headList">
	<li><a href="">Home</a></li>
	<li><a href="">Sport</a></li>
	<li><a href="">Science</a></li>
	<li><a href="">Politics</a></li>
	<li><a href="">Finance</a></li>
</ul>
</header>
</div>

<div class="body1">
	<img src="https://metaratings.ru/upload/iblock/c09/c099ea2e4e75d074ba7ec267f572fffe.jpg" ></img>

	<div class="body11">


	<h2>Khabib to Conor: "It's the same thing"</h2>

	<p>They said "Khabib is too hittable, he walks straight into shots with his chin in the air, Michael Johnson is going to catch him". Khabib then spent 15 min chatting with Dana White while giving Johnson the worst beating of his life.
	<br>They then said "Khabib is too hittable, he walks straight into shots with his chin in the air, Edson Barboza is going to catch him". Barboza got outstruck on the feet and lost 10 years of life expectancy on the ground.
</p>
</div>
</div>

<div class="latestNews">
	<h3>Latest news</h3>
</div>

<div class="body3">

	<div class="firstBlock">
		<img src="https://sportishka.com/uploads/posts/2021-11/1637353943_1-sportishka-com-p-eden-azar-komandnii-sport-foto-2.jpg"></img>

		<h5>Eden Hazard injury update</h5>
		<p>Real Madrid striker Eden Hazard injured again on last match with Sevilla FC.</p>

		<button>Read More</button>
	</div>

	<div class="secondBlock">
		<img src="https://sportishka.com/uploads/posts/2021-11/1637353943_1-sportishka-com-p-eden-azar-komandnii-sport-foto-2.jpg"></img>

		<h5>Eden Hazard injury update</h5>
		<p>Real Madrid striker Eden Hazard injured again on last match with Sevilla FC.</p>

		<button>Read More</button>
	</div>

	<div class="thirdBlock">
		<img src="https://sportishka.com/uploads/posts/2021-11/1637353943_1-sportishka-com-p-eden-azar-komandnii-sport-foto-2.jpg"></img>

		<h5>Eden Hazard injury update</h5>
		<p>Real Madrid striker Eden Hazard injured again on last match with Sevilla FC.</p>

		<button>Read More</button>
	</div>

	<div class="secondBlock">
		<img src="https://sportishka.com/uploads/posts/2021-11/1637353943_1-sportishka-com-p-eden-azar-komandnii-sport-foto-2.jpg"></img>

		<h5>Eden Hazard injury update</h5>
		<p>Real Madrid striker Eden Hazard injured again on last match with Sevilla FC.</p>

		<button>Read More</button>
	</div>

</div>

</body>
</html>
