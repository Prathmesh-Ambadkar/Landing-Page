# Landing Page
 Using html and Css

<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Food Website</title>
	<link href="https://fonts.googleapis.com/css2?family=EB+Garamond&family=Poppins:wght@200&display=swap" rel="stylesheet">
	<link rel="stylesheet" type="text/css" href="C:\Users\ASUS\Desktop\HTML\Projects\Normalize.css">
	<link rel="stylesheet" type="text/css" href="C:\Users\ASUS\Desktop\HTML\Projects\Style5.css">
</head>
<body>
	<section class="food_image">
		<div class="image_wrpper">
			<h1>HERE IS FOOD ALL YOU LOVE</h1>
			<p> ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
			tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
			quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commod.<p>
			<form class="form_style">
				<input class="search_style" type="text" placeholder="Search here">
				<button type="submit">Search food</button>
			</form>
		</div>
	</section>

	<section class="product">

		<div class="Product_list_items">
			<img class="img_responsive" src="C:\Users\ASUS\Desktop\HTML\Projects\Food1.jpg">
			<h2 class="product1_Heading">Food1</h2>
			<p> ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
			tempor incididunt ut labore et dolore magna.</p>
		</div>

		<div class="Product_list_items">
			<img  class="img_responsive" src="C:\Users\ASUS\Desktop\HTML\Projects\Food2.jpg">
			<h2 class="product2_Heading">Food2</h2>
			<p> ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
			tempor incididunt ut labore et dolore magna.</p>
		</div>

		<div class="Product_list_items">
			<img class="img_responsive" src="C:\Users\ASUS\Desktop\HTML\Projects\Food3.jpg">
			<h2 class="product3_Heading">Food3</h2>
			<p> ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
			tempor incididunt ut labore et dolore magna.</p>
		</div>
		
	</section>

</body>
</html>

<Html Ends Here>
 
 <CSS>
  
  body
{
	font-family: 'EB Garamond', serif;
}
/*Uitility classes*/
.img_responsive
{
	max-width: 100%;
}
.food_image
{
	background: url(spaghetti-g250fdc039_1920.jpg) no-repeat;
	background-size: cover;
	height: 100vh;
	position: relative;
}
.image_wrpper
{
	color: white;
	position: absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%,-50%);
}
.image_wrpper,h1
{
	text-align: center;
}
.form_style .search_style
{
  display: block;
  width: 80%;
  margin-left: auto;
  margin-right: auto;
  border-radius: 2rem;
  padding: .6rem;
  outline: none;
  border: none;
  text-align: center;
}
.form_style button
{
	margin-right: auto;
	margin-left: auto;
	width: 40%;
	background-color: #ff6600;
	border-radius: 2rem;
	border: none;
	padding: .3rem;
	margin-top: 1rem;
}

/*product section*/

.product
{
	width: 80%;
	margin-left: auto;
	margin-right: auto;
}
.Product_list_items
{
	float: left;
	
	width: 50%;
}
 
