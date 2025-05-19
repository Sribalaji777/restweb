# Ex.07 Restaurant Website
## Date:

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
home.html
<html>
  <head>
    <title>Restaurnt Poster</title>
    <body bgcolor="grey">
      <center>
      <div class="con">
        
        <img src="logo.png" alt="Image" width="300" height="250">
        <h1>Raffles biriyani</h1>
    

    </center>
      <style>
        h1{
          color: brown;
          font-size: 50px;
          font-family:cursive;
          
        }
        .con{
          display: flex;
          align-items: center;
          margin-left: 450px;
        }
        nav{
          background-color: black;
          color: beige;
          padding: 15px;
          border-radius: 20px;
        }
        
        .cd{
          width: 1500px;
          
        }
        li,ul{
          display: inline;
          font-size:xx-large; 
        }
        ul{
          margin-right: 100px;
        }
        li{
          margin: 90px;
          cursor: pointer;
        }
        li:hover{
          color:skyblue;
        }
        .box{
          background-color:rgba(250, 235, 215, 0.553);
          display:inline-block;
          border-color:beige;
          border-radius: 20px;
          border-width: 1px;
          border-style: solid;
          width: 400px;
          border-left: 500px;
          margin: 15px;
          line-height: 25px;
          
        }
        .container{
          text-align: center;
        }
        hr{
          height: 5px;
          background-color:black;
          margin-left: 800px;
          margin-right: 100px;
          border-style:groove;
          border-radius: 5px;
        }
        .content{
          background-image: url("food images008.png");
          background-size: 1300px; 
          background-position: center;  
          padding: 20px;  
          border: 10px;
          position: relative;
          
        }
        .content img{
            border-radius: 35px;
            width: 1300px;
            height: 300px
        }
        .text{
            color: white;
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            font-size: 24px;
            font-weight: bold;
            
        }
        .content h1{
            color:white;
            
        }
        h3{
          color: red;
        }
        .highlight {
          color: red;
          font-weight: bold;
      }
      a:hover{
        text-decoration: none;
      }
      a{
        text-decoration: none;
      }
      </style>
    <center>
      <div class="cd">
        <nav>
         <ul>
          <a href="home.html" style="color:white"><li>home  |</li></a>
          <a href="menu.html" style="color: white;"><li>menu  |</li></a>
          <a href="administration.html" style="color:white"><li>administartion  |</li></a>
          <a href="contact us.html" style="color: white;"><li>contact us    |</li></a>
         </ul>
       </nav>
      </div>
    </center>
    <br>
    <br>
    <br>
    <center>
  <div class="content">
    <img src="briyani.jpg">
    <div class="text ">
        <h1>30% off this week</h1>
        <p>Join us for our grand opening! Experience mouth-watering cuisine, a cozy atmosphere, and exceptional service. Reserve your table now for an unforgettable dining experience. Call or book online. We can't wait to welcome you!</p>
    </div>
</div>
  </center>
  <br>
  <br>
  <div class="container">
          <div class="box">
            <h2>Our New Menu</h2>
            <img src="MENU IAMGE.jpg" height="300x" width="350x" alt="img">
            <p>Welcome to our exquisite new food menu! Delight your taste buds with our freshly prepared dishes, crafted with the finest ingredients. From savory starters like crispy calamari to delectable main courses such as our signature grilled salmon. Don't miss our mouth-watering desserts, including rich chocolate lava cake and refreshing lemon sorbet. Quench your thirst with our extensive drink selection, featuring hand-crafted cocktails and premium wines. Join us for an unforgettable dining experience where every bite is a celebration of flavor and quality. Bon appetit!</p>
            <a href="new menu.html">Our New Menu</a>
          </div>
          <div class="box">
            <h2>Book A Table</h2>
            <img src="table.jpg" height="300x" width="350x" alt="img">
            <p>Book your table now at our exquisite restaurant and savor an unforgettable dining experience! Enjoy a wide array of delectable dishes, crafted with the finest ingredients to tantalize your taste buds. Whether you're planning a romantic dinner, a family gathering, or a special celebration, our welcoming ambiance and exceptional service await you. Don’t miss out on our exclusive menu options and hand-crafted beverages. Reserve your spot today and make your next meal truly special! Call or book online. Your Food, Your Story, Your Table</p>
            <a href="book table.html">Book Table Now</a>
          </div>
          <div class="box">
            <h2>Opening Hours</h2>
            <img src="open.jpg" height="300x" width="350x" alt="imf">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Neque sint voluptate molestiae praesentium facilis dolores ex molestias at, exercitationem inventore similique. Eaque, maxime recusandae reprehenderit debitis odit quasi quidem ex cum soluta perferendis qui perspiciatis quaerat veritatis minus nobis, est voluptatum quis explicabo officiis voluptatem sunt. Molestiae ab obcaecati nesciunt autem rem accusantium ea! Ad quod saepe doloremque omnis consectetur ut, ipsum nostrum assumenda voluptates alias delectus neque? Ipsum, aperiam?</p>
            <br>
          </div>
  </div>
  <br>
  <br>
  <div class="exit">
    <hr>
    <img src="logo.png" height="150px" width="200px">
</div>
<br>
<br>
<center>
  <p>Designed and developed by<span class="highlight"> Sribalaji</span>.</p>
</center>
    </body>
   
  </head>
</html>

menu.html
<html>
<head>
    <style>
        body {
            background-image: url('akka.jpg');
            background-size: cover; 
            background-attachment: fixed; 
            margin: 0;
            padding: 0;
            height: 100vh;
            font-family: Arial, sans-serif;
            background-color: LightCyan;
        }
        
        .box1 {
            display: flex;
            justify-content: space-around;
            width: 80%;
        }
        .box {
            background-color:rgba(250, 235, 215, 0.553);
            border-color: rgb(25, 27, 27);
            border-radius: 20px;
            border-width: 1px;
            border-style: solid;
            width: 500px;
            padding: 30px;
            line-height: 27px;
            text-align: center;
            margin: 10px;
            display: inline-block;
            height: 550px;
        }

        .box{
            text-align: left;
        }
        .rate li{
            display: flex;
            justify-content: space-between;
            margin: 5px 0;
        }
        .ke{
            color: #097d3d;
          }
        
         
          
           nav{
          background-color: black;
          color: beige;
          border-radius: 20px;
          height: 50px;
          padding-bottom: 30px;
          
        }
        
        li,ul{
          display: inline-block;
          font-size:xx-large; 
          align
        }
        .cd{
          width: 1500px;
         
    
        }
       ul,li{
        padding-bottom: 20px;
       }
        .part{
            margin-top: 20px;
            color: white;
            font-size: 40px;
            text-align: center;
            font-family:Poppins;
            margin-bottom: 50px;
            letter-spacing: 1px;
        }
        nav ul li{
            margin-right: 150px;
        }
    
    </style>
</head>
<body>
    <br>
    <br>
    <center>
      <div class="cd">
        <nav>
         <ul>
          <a href="home.html" style="color:white"><li>home  |</li></a>
          <a href="menu.html" style="color: white;"><li>menu  |</li></a>
          <a href="administration.html" style="color:white"><li>administartion  |</li></a>
          <a href="contact us.html" style="color: white;"><li>contact us    |</li></a>
         </ul>
       </nav>
      </div>
    </center>
    <br>
    <h1 class="part">Food Menu</h1>
    
    <center>
    <div class="box1">
        <div class="box">
            <center><h2>Non Veg</h2></center>
            <hr>
            <ul>
                <div class="rate">
                <li>Mutton Biriyani<span class="ke">$499</span></li> 
                <li>Chicken biriyani<span class="ke">$399</span></li>  
                <li>Grill Chicken<span class="ke">$399</span></li>    
                <li>Barbeque<span class="ke">$349</span></li>
                <li>Chicken Rice<span class="ke">$210</span></li>
                <li>Chiken 65<span class="ke">$149</span></li>
                <li>Shavarma<span class="ke">$149</span></li>
                <li>Boneles Wing Chicken<span class="ke">$ 119</span></li>
                </div>
            </ul>
        </div><br>
        <div class="box">
            <center><h2>Veg</h2></center>
            <hr>
            <ul>
                <div class="rate">
                <li>Meals<span class="ke">$199</span></li>
                <li>Veg Biriyani<span class="ke">$149</span></li>
                <li>Veg Fried rice<span class="ke">$119</span></li>
                <li>Pongal<span class="ke">$99</span></li>
                <li>Ghee rice<span class="ke">$89</span></li>
                <li>Curd rice<span class="ke">$79</span></li>
                <li>Butter Naan<span class="ke">$69</span></li>
                <li>Rotti<span class="ke">$59</span></li>
            </div>
            </ul>
        </div>
        <div class="box">
            <center><h2>Ice & Juice</h2></center>
            <hr>
            <ul>
                <div class="rate">
                    <li>Badam milk<span class="ke">$ 89</span></li>
                <li>Rose Milk<span class="ke">$ 79</span></li>
                <li>Apple Juice<span class="ke">$ 69</span></li>
                <li>lazzy<span class="ke">$ 49</span></li>
                <li>falooda<span class="ke">$ 99</span></li>
                <li>Choco Truffle<span class="ke">$ 79</span></li>
                <li>Triple Bar<span class="ke">$ 59</span></li>
                <li>Choco Bites<span class="ke">$ 20</span></li>
            </div>
            </ul>
        </div>
    </div>
    </center>
</body>
</html>

administration.html
<!DOCTYPE html>
<html lang="en">

<head>
   


    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body{
            background-color: burlywood;
        }
         
       
        .header {
            background-color:beige;
            padding: 5px 0;
            text-align: center;
            margin-top: -10px;
            display: block;
        }
        
        .logo {
            display: flex;
            justify-content: center;
            align-items: center;
        }
        
        .img {
            height: 90px;
            width: auto;
            margin-right: 5px;
        }
        
        .spice{
            font-size: 40px;
            font-weight: 700;
            color:#3d2a1f; 
            font-family: Gloock; 
            text-transform: uppercase;
            letter-spacing: 2px;
        }
        input{
           margin-left: 50px;
            height: 25px;
            width: 300px;
            border-style:dotted;
            border-color:rgb(231, 185, 185);
            background-color: rgb(244, 244, 208);
            border-radius: 5px;
            padding-left: 2px;
        }
        button{
            margin-right: 3px;
            height: 25px;
            width: 60px;
            border-radius: 4px;
            text-align: center;
            border: none;
            background-color: #387051;
            color: white;
            font-family: Poppins;
            font-weight: 700;
            cursor:pointer;
            letter-spacing: 1px;
        
        }
        
        button:hover{
            color:lavender;
            text-decoration: dashed;
        }
        .bar{
            margin-bottom: 10px;
            text-align:center;
        }
        
        
        
        
        .hyper{
            color: white;
            text-decoration: none;
        }
        a:hover{
            color: burlywood;
        }
        
        .menus{
            margin-top: 10px;
            border-color:rgb(2, 2, 2);
            border-style: solid;
            display: inline-block;
            margin-left: 150px;
            border-radius: 10px;
            margin-bottom: 20px;
        }
        
        .items1{
            width: 300px;
            height: 400px; 
            background-image:url("puttin.jpg"); 
            background-size:cover; 
            background-position: center; 
            border-radius: 10px;
            display: flex;
            border: 4px;
        }
        .items2{
            width: 300px;
            height: 400px; 
            background-image:url(hitler.webp); 
            background-size:cover; 
            background-position: center; 
            border-radius: 10px;
            display: flex;
            border: 4px;
            padding-bottom: 100px;
        }
        .items3{
            width: 300px;
            height: 400px; 
            background-image:url(subhas.webp); 
            background-size:cover; 
            background-position: center; 
            border-radius: 10px;
            display: flex;
            border: 4px;
        }
        
        
        .words
        {
            padding-top: 10px;
            padding-left: 10px;
            font-family: Trirong;
            padding-bottom: 20px;
            text-align: center;
        }
        .words:hover{
            cursor: pointer;
            color:darkcyan;
        }
        .order{
            font-size: 20px;
        }
        .order1{
            font-size: 20px;
        }
        .words p.good1{
            max-width: 310px;
            font-size: 15px;
        }
        .words p.good2{
            max-width: 300px;
            font-size: 15px;
        }
        .words p.good3{
            max-width: 300px;
            font-size: 15px;
        }
        .words p.good4{
            white-space:pre wrap;
            max-width: 300px;
            font-size: 15px;
        }
        .words p.good5{
            max-width: 300px;
            font-size: 15px;
        }
        .words p.good6{
            max-width: 300px;
            font-size: 15px;
        }
        .words p.good7{
            max-width: 300px;
            font-size: 15px;
        }
        
        
        .terms
        {
            color:aliceblue;
            text-decoration: none;
        }
        .terms:hover{
            text-decoration: underline;
        }
        .part{
            margin-top: 20px;
            color: #28a560;
            font-size: 40px;
            text-align: center;
            font-family:Poppins;
            margin-bottom: 50px;
            letter-spacing: 2px;
        }
        nav{
          background-color: black;
          color: beige;
          padding: 6px;
          border-radius: 20px;
          height: 65px;
          
        }
        nav ul li{
            margin-right: 150px;
        }
       
        .cd{
          width: 1500px;
          height: 100px; 
        }
        
        li,ul{
          display: inline-block;
          font-size:xx-large; 
          letter-spacing: 1px;
        }
        ul{
          margin-right: 20px;

        }
        li{
          cursor: pointer;
          
        }
        li:hover{
          color:skyblue;
        }
        
    </style>
</head>

<body>
    <br>
    <br>
    <center>
      <div class="cd">
        <nav>
        
         <ul class="ref">
          <a href="home.html" style="color:white"><li>home  |</li></a>
          <a href="menu.html" style="color: white;"><li>menu  |</li></a>
          <a href="administration.html" style="color:white"><li>administartion  |</li></a>
          <a href="contact us.html" style="color: white;"><li>contact us    </li></a>
         </ul>
         
       </nav>
      </div>
    </center>
    <h1 class="part">
        PARTNERS
    </h1>

    <div class="menus">
        <div class="items1">
        </div>
        <div class="words">
            <h2 class="order">Mr.Vladimir Putin</h2>
           
        </div>
    </div>
    <div class="menus">
        <div class="items2">
        </div>
        <div class="words">
            <h2 class="order"> Mr.Adolf Hitler</h2>
  
        </div>
    </div>
    <div class="menus">
        <div class="items3">
        </div>
        <div class="words">
            <h2 class="order">  Mr.Subhas Chandra Bose</h2>
        </div>
    
</body>
</html>

contact us.html
<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }
    
    .header {
        background-color:rgba(165, 165, 15, 0.264);
        padding: 5px 0;
        text-align: center;
        margin-top: -10px;
        display: block;
    }
    
    .logo {
        display: flex;
        justify-content: center;
        align-items: center;
    }
    
    .img {
        height: 90px;
        width: auto;
        margin-right: 5px;
    }
    
    .spice{
        font-size: 40px;
        font-weight: 700;
        color:#3d2a1f; 
        font-family: Gloock; 
        text-transform: uppercase;
        letter-spacing: 2px;
    }
    input{
       margin-left: 50px;
        height: 25px;
        width: 300px;
        border-style:dotted;
        border-color:rgb(192, 146, 146);
        background-color: rgba(178, 178, 30, 0.558);
        border-radius: 5px;
        padding-left: 2px;
    }
    button{
        margin-right: 3px;
        height: 25px;
        width: 60px;
        border-radius: 4px;
        text-align: center;
        border: none;
        background-color: #387051;
        color: rgba(255, 255, 255, 0.415);
        font-family: Poppins;
        font-weight: 700;
        cursor:pointer;
        letter-spacing: 1px;
    
    }
    
    button:hover{
        color:rgba(230, 230, 250, 0.292);
        text-decoration: dashed;
    }
    .bar{
        margin-bottom: 10px;
        text-align:center;
    }
    
    
    .hyper{
        color: rgba(255, 255, 255, 0.71);
        text-decoration: none;
    }
    a:hover{
        color: rgba(222, 184, 135, 0.467);
    }
    .tag{
        font-family: Trirong;
        text-align: center;
        font-size: 20px;
        margin-bottom: 10px;
        text-transform: uppercase;
    }
    
    .location{
        border-radius: 20px;
        display: inline-block;
        color: black ;
        margin-top: 60px;
        padding-left: 40px;
    }
    .iden{
        font-family: Montserrat;
        font-size: 20px;
        padding-top: 5px;
    }
    .ender{
        display: flex;
        width: 100%;
        height: 400px;
        background-color: hsl(0, 12%, 80%);
    }
    .location2{
        border-radius: 20px;
        display: inline-block;
        color: black ;
        margin-top: 50px;
        padding-left: 27%;
    }
    .location3{
        border-radius: 20px;
        display: inline-block;
        color: black ;
        margin-top: 50px;
        padding-left: 20%;
    }
    footer{
        
        background-color: #705138;
        text-align: center;
        height: 70px;
        width: auto;
        padding-top: 5px;
        font-size: 13px;
        color: rgb(230, 230, 250);
        font:small-caps
    }
    h2{
        display: inline;
        margin-right: 50px;
    }
    .terms
    {
        color:rgb(240, 248, 255);
        text-decoration: none;
    }
    .terms:hover{
        text-decoration: underline;
    }
    
    .details-ul{
        font-family: Alumni Sans Pinstripe;
        font-size: 25px;
        margin-top: 10px;
        margin-right: 50px;
        display: inline-block;
    }
    span{
        color:rgb(0, 195, 255);
        font-family: Dancing Script;
    }
     nav{
          background-color: black;
          color: beige;
          padding: 5px;
          border-radius: 20px;
          height: 65px;
        }
        .cd{
          width: 1500px;
          height: 70px;
        }
        nav ul li{
            margin-right: 150px;
        }
        li,ul{
          display: inline-block;
          font-size:xx-large; 
          letter-spacing: 1px;
          
        }
        ul{
          margin-right: 20px;

        }
        li{
          cursor: pointer;
          
        }
        li:hover{
          color:skyblue;
        }
</style>
<br>
<br>
    <center>
      <div class="cd">
        <nav>
         <ul>
          <a href="home.html" style="color:white"><li>home  |</li></a>
          <a href="menu.html" style="color: white;"><li>menu  |</li></a>
          <a href="administration.html" style="color:white"><li>administartion  |</li></a>
          <a href="contact us.html" style="color: white;"><li>contact us    |</li></a>
         </ul>
       </nav>
      </div>
    </center>

    <div class="ender">
        <div class="location">
            <h2 class="tag">Location</h2><br>
            <h3 class="iden">Main Road 24,</h3>
            <h3 class="iden"> Usman Road ,</h3>
            <h3 class="iden">T. Nagar, Chennai,</h3>
            <h3 class="iden">Tamil Nadu - 600017.</h3>
        </div>
        <div class="location2">
            <h2 class="tag">Hours</h2>
            <h3 class="iden">Mon,Tue,Wed,Thur</h3>
            <h3 class="iden"> 10.00 AM - 8.00 PM,</h3>
            <br>
            <h3 class="iden">Fri,Sat</h3>
            <h3 class="iden">10.00 AM - 9.00 PM</h3>
            <br>
            <h3 class="iden">Sun</h3>
            <h3 class="iden">11.00 AM - 4.00 PM</h3>
        </div>
        <div class="location3">
            <h2 class="tag">Find us on</h2>
            <h3 class="iden">Instagram  :</h3>
            <h3 class="iden"> @Rafflesbiriyani</h3>
            <br>
            <h3 class="iden">X :</h3>
            <h3 class="iden">@Rafflesbiriyani </h3>
            <br>
            <h3 class="iden">Facebook :</h3>
            <h3 class="iden">@Rafflesbiriyani</h3>
        </div>
    </div>
    <div class="details">
        <center>
        <ul class="details-ul">
            <li class="details-ul"><b> 📞</b> : +91 9363744498,</li><br>
            <li class="details-ul"><b> 📧 </b> : Rafflesbriyani@gmail.com</li> 
        </ul>
    </center>
    </div>
    <br><br><br>
    <footer>
        <h2><a href="name" class="terms">Terms and conditions </a> </h2>
        <h2><a href="name" class="terms">Cookie Policy </a> </h2>
        <h2><a href="name" class="terms">Privacy Policy </a></h2>
        <br><br>
        <h2> Copyright &copy; 2024 raffles Briyani </h2>
        <h2>Designed and Developed By <span>  Sribalaji</span></h2>
    </footer>
</body>

</html>
```


## OUTPUT:
![alt text](<Screenshot 2025-05-19 214857.png>)
![alt text](<Screenshot 2025-05-19 215450.png>)
![alt text](<Screenshot 2025-05-19 215555.png>)
![alt text](<Screenshot 2025-05-19 215922.png>)
![alt text](<Screenshot 2025-05-19 215857.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
