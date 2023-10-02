# Restaurants-website---front-page-of-a-restaurant
![image](https://github.com/poojamaurya3477/Restaurants-website---front-page-of-a-restaurant/assets/119335176/41d8ab3b-21f3-424e-8456-f920038bb8f4)

A great restaurant website can attract new customers and raise the overall profile of your restaurant. Here’s how to create your own restaurant website
here's the html code provided .......
<html>

<head>
	<title> Restraurant </title>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href='./css/main.css' />
    <link rel="shortcut icon" href="C:\Users\pooja\Downloads\front image.jpg"/>
    <!---<script src="./js/anime.min.js"></script>    
    <script src="js/intro.js"></script>-->
    <link rel="stylesheet" href="root.css">
    
</head>
<body>

    <!--  animated nav bar -->
     <div class="navBar" id="nv">
        <nav>
            <i class="bi bi-justify" onclick="alert('heelo')" id="hamMenu"></i>
            <ul>
                <!-- main nav section -->
                <li><a href='?page=home'>HOME </a></li>
                <li><a href='?page=menu'>MENU </a></li>
                <li><a href='?page=ourstory'>OUR STORY  </a></li>
                <li><a href='?page=contactus'>CONTACT US </a></li>
                  
               <!--- <li class="socialIcon"><a href="call:111-111-111"><i class="bi bi-telephone-forward"></i></a></li>
                <li class="socialIcon"><a href="instgram.com/example"><i class="bi bi-instagram"></i></a></li>
                <li class="socialIcon"><a href="mailto:example@example.com"><i class="bi bi-envelope-fill"></i></a></li>
               -->
            </ul>
        </nav>
    </div>  
    
    <div class="header">

       
         
    <!-- main logo !-->
	<div class="IntroMsg">
    <img  alt="Restro where food meets passion" 
    class="logo" src="C:\Users\pooja\Downloads\Restro.jpg" id="introLogo" width="200" height="200" />
    </div>
    
	<div class='IntroMsg'>
        <h1> Stunning food, Amazing Quaility  </h1>
    </br>
        <span>
           Let us host your next special occassion
        </span>
        <h2>
       <a href="call:111-111-111" style="text-decoration: none; color: white;"> <i class="bi bi-telephone-forward-fill"> <span> Contact US today </span></i></a>
       
        </h2>
	</div>
        
     <div class="menu">   
        <div class="menuIntro">     
            
            <img src="C:\Users\pooja\Downloads\coke.jpg" />
            <img src="C:\Users\pooja\Downloads\chai.jpg" />
        </div>
            
    <!-- menu layout-->
        <section id="home-menu">
            <h2>DRINK MENU</h2>
			<h3> Cold drink, tea, and water</h3>
	<ul>
		<li>
			<span class="dish">Sprite 200ml </span>
			<span class="Price">20</span>
			<span class="Description">With ice  or soda.</span>
		</li>
		<li>
			<span class="dish"> Thumps up 200ml</span>
			<span class="Price">20</span>
			<span class="Description">With ice  or soda.</span>
		</li>
		<li>
			<span class="dish">Coco cola 200ml </span>
			<span class="Price">20</span>
			<span class="Description">With ice or soda.</span>
		</li>
		<li>
			<span class="dish">Maaza 200ml</span>
			<span class="Price">25</span>
			<span class="Description"></span>
		</li>
		<li>
			<span class="dish">  Tea </span>
			<span class="Price">20</span>
			<span class="Description">With Ginger or Elaichi </span>
		</li>
		<li>
			<span class="dish">Coffee</span>
			<span class="Price">30</span>
			<span class="Description"> Brugold or Nescafe</span>
		</li>
		<li>
			<span class="dish">Cold coffee.</span>
			<span class="Price">40</span>
			<span class="Description">With ice  or soda</span>
		</li>
		<li>
			<span class="dish">Sparkling Water</span>
			<span class="Price">20</span>
			<span class="Description">With ice  or soda</span>
		</li>
	</ul>
    </section>
    <!-- end of menu layout -->
    </div>

    <div class="menu">   
        <div class="menuIntro">    
            <img  id="caption_img"src="C:\Users\pooja\Downloads\paratha.webp"  />  
            <img id="caption_img" src="C:\Users\pooja\Downloads\maggie.jpg" />
        </div>
 
     <section id="home-menu">
            <h2>FOOD MENU</h2>
			<h3> Entrees, mains, and handhelds</h3>
	<ul>
		<li>
			<span class="dish">Paratha</span>
			<span class="Price">40-120</span>
			<span class="Description">Aalo, Pyaaz, Gobhi ,Paneer  
			</span>
		</li>
		<li>
			<span class="dish">Maggie</span>
			<span class="Price">45-90</span>
			<span class="Description">Veg, Paneer, Paneer butter,masala </span>
		</li>
		<li>
			<span class="dish">Noodles</span>
			<span class="Price"> 90</span>
			<span class="Description">
				Veg , Paneer 
			</span>
		</li>
		<li>
			<span class="dish">Samosa</span>
			<span class="Price">15</span>
			<span class="Description">
				Aalo, Paneer
			</span>
		</li>
		<li>
			<span class="dish">Gujiya</span>
			<span class="Price">25</span>
			<span class="Description">Normal, Dipped with Sugar syrup</span>
		</li>
		<li>
			<span class="dish">Chaat</span>
			<span class="Price">40</span>
			<span class="Description">Normal, Basket </span>
		</li>
		
	</ul></section></div>


    <div class="menu">   
        <div class="menuIntro">    
             <img src="C:\Users\pooja\Downloads\jamun.jpg" />
             <img src="C:\Users\pooja\Downloads\icecream.jpg" />
        </div>
     <section id="home-menu">
            <h2>DESERT MENU</h2>
			<h3> Deserts and sweets</h3>
	<ul>
		<li>
			<span class="dish">Chocolate cake .</span>
			<span class="Price">400</span>
			<span class="Description">Loaded Chocolate cake with fudge topping.</span>
		</li>
		<li>
			<span class="dish">Cheesecake.</span>
			<span class="Price">200</span>
			<span class="Description">cheesecake toped with strawberry topping.</span>
		</li>
		<li>
			
		</li>
		<li>
			<span class="dish">Gulab jamun</span>
			<span class="Price">20</span>
			<span class="Description"></span>
		</li>
		<li>
			<span class="dish">Ice cream</span>
			<span class="Price">45</span>
			<span class="Description">Chocolate, vanilla , Streawberry, Butterscotch</span>
		</li>
		<li>
			<span class="dish">Ras Malai</span>
			<span class="Price">30</span>
			<span class="Description">
				</span>
		</li>
		<li>
			
		</li>
	</ul></section></div></div>


   

