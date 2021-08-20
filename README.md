<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- displays site properly based on user's device -->

  <link rel="icon" type="image/png" sizes="32x32" href="./https://user-images.githubusercontent.com/89213929/130268280-da62c079-9ba8-4fb3-880a-c2ff42968b38.p">






  <title>Frontend Mentor | Order summary card</title>

  <!-- Feel free to remove these styles or customise in your own stylesheet 👍 -->
  <style>


	body {text-align:center;
	background: url(https://user-images.githubusercontent.com/89213929/130268703-1992624b-f5d9-4f37-8223-9b3fa81a09f0.jpg);
	font-weight: 500, 700, 900;
	font-family: sans-serif;

	}

	section{background-color:white;
	width:450px;
	margin: auto;
	margin-top:70px;
	border-radius: 25px;
	margin-bottom: 50px;
	height: 650px;
	}
	table {background-color: hsl(225, 100%, 98%);
			width:380px;
			margin:auto;
			margin-top:20px;
			border-radius: 25px;
			margin-bottom:25px;
			}
	h1 {margin-top:40px;}
	h4 {margin-bottom:0;
		margin-left:0;
		padding-bottom:5px;}
	p {margin-top:0;
		margin-left:0;
		color: hsl(224, 23%, 55%);
		font-size: 16px;
		line-height: 25px;}
.music {width: 70px;
height: 70px;}
	.hero {border-top-left-radius: 25px;
			border-top-right-radius: 25px;
      width: 450px;
height: 200px;;
			}
	.plan {
		text-align: left;
	}
	.change {color: hsl(245, 75%, 52%);}
	.change:hover {color: #7B68EE;
	text-decoration: none;}

	input {border-radius: 10px;
			width:380px;
			background-color: hsl(245, 75%, 52%);
			height:40px;
			color: white;
			text-align:center;
			margin-bottom: 25px;
			font-weight: bolder;
			border: none;
			}
	input:hover {background-color: #7B68EE;}

	.cancel {color: grey;
			text-decoration: none;
			margin-bottom: 100px;
			font-size: 12px;
			font-weight: bolder;}
	.cancel:hover {color: black;
	}

  .attribution { font-size: 11px; text-align: center; }
  .attribution a { color: hsl(228, 45%, 44%); }
  </style>
</head>
<body>

  <section>
  <img class="hero" src="https://user-images.githubusercontent.com/89213929/130268678-617950e3-b30f-4659-89f5-76e627915e18.jpg" alt="hero">
  <h1>Order Summary</h1>
  <p>
  You can now listen to millions of songs,<br>
  audiobooks, and podcasts on any
  device <br> anywhere you like!
  </p>
  <table>

  <tr>
  <td><img class="music" src="https://user-images.githubusercontent.com/89213929/130268680-d7a4e19e-f02e-47ec-aee4-47e71a02423c.jpg" alt="music"></td>
  <td class="plan">
  <h4>Annual Plan</h4>
  <div><p>$59.99/year</p><div>
  </td>
  <td> <a href="#" class="change"><b>Change<b></a></td>
  </tr>

  </table>




  <input type="button" value="Proceed to Payment">
  <br>

  <a href="#" class="cancel"> Cancel Order </a>


  </section>

  <div class="attribution">
    Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>.
    Coded by <a href="#">Martina Bobulová</a>.
  </div>
</body>
</html>
