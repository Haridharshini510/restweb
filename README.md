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
restHomePage.html

<html>
    <head>
        <link rel="stylesheet" href="homepage.css">
    </head>
    <body>
      <div class="logo">
        <img src="WhatsApp Image 2024-12-06 at 8.48.04 PM (7).jpeg" alt="logo"></img>
        <h1>BORA RESTAURANT</h1>
      </div>
      <div class="navbar">
        <h1><a href="restHomePage.html">Home</a></h1>
       <h1><a href="menu.html">
          Menu
        </a>  
      </h1> 
      <h1> 
        <a href="administration.html">
         Administration
        </a>
      </h1>   
      <h1>
        <a href="contact.html">
          Contact Us
        </a>
      </h1>
      </div>
      <div class="container">
      </div>
      <div class="welcome"><h1>WELCOME TO<br> BORA RESTAURANT!!</h1></div>
      <p class="signature">Where elegance meets flavor and every meal is a celebration.<br>
        Experience the warmth of our hospitality and the richness of our cuisine.<br>
        Don't miss our signature dish, The Bora Royale - a taste of perfection awaits you!</p>
      <img src="signaturedish.png" class="signaturedish">
      <div class="containers">

        <div class="container1">
          <h3>Our new menu</h3>
          <img src="WhatsApp Image 2024-12-06 at 8.48.04 PM (4).jpeg" class="newdish">
          <p class="para">Delight in the rich and aromatic flavors of our latest creation, the Saffron Infused Risotto. This luxurious dish combines perfectly cooked Arborio rice with a delicate infusion of premium saffron, creating a creamy, vibrant masterpiece.</p>
          <a href="menu.html" class="anchor2">Check out our new menu here</a>
        </div>
        <div class="container2">
          <h3>Book a table</h3>
          <img src="WhatsApp Image 2024-12-06 at 8.48.04 PM (5).jpeg" class="newdish">
          <p class="para">Experience the elegance and charm of dining at Bora. Whether it's an intimate dinner, a casual lunch, or a celebration with loved ones, we're here to make it special. Book your table now and immerse yourself in our signature dishes.
            </p>
            <a href="tablebooking.html" class="anchor2">Book your table now!</a>
        </div>
        <div class="container3">
          <h3>Opening hours</h3>
         <img src="WhatsApp Image 2024-12-06 at 8.48.04 PM (3).jpeg" class="newdish">
          <p class="para">At Bora, we're here to serve you the finest dining experience every day of the week.
            <br>
            Monday to Friday: 11:00 AM - 10:00 PM
            Saturday: 11:00 AM - 11:00 PM<br>
            Sunday: 12:00 PM - 10:00 PM<br>
            Join us for lunch, dinner, or anytime in between for exceptional meals and service.
           </p>
        </div>
      </div>

    </body>
</html>

homepage.css

body{
    margin: 0px;
    padding: 0px;
    background-color: beige;
}
.logo{
    width:100vw;
    height:130px;
    background-color: #39387a;
    display: flex;
    justify-content: center;
    align-items: center;
    color:beige;
    font-family:Georgia, 'Times New Roman', Times, serif;
}
.navbar{
    margin-top:40px;
    margin-left: 40px;
    margin-right: 30px;
    width:1200px;
    height: 50px;
    background-color:#39387a;
    display: flex;
    justify-content: center;
    align-items: center;
    justify-content: space-around;
    border-radius: 12px;
}
a{
    text-decoration: none;
    color: beige;
    font-size: 25px;
}
.container{ 
  margin:30px;
  margin-left: 40px;
  margin-right: 30px;
  height: 400px;
  background-image: url("WhatsApp\ Image\ 2024-12-06\ at\ 8.48.05\ PM\ \(2\).jpeg");
  background-size: cover;
  background-repeat: no-repeat;
  display: flex;
  justify-content:center ;
  align-items: center;
  height: 350px;
  border-radius: 12px;
  opacity: 50%;
}
.welcome{
  position: absolute;
  top: 250px;
  left: 80px;
  color: beige;
  font-size: 30px;
}
.signaturedish{
  position: absolute;
  width: 330px;
  top: 250px;
  right:100px;
}
.signature{
  position: absolute;
  top: 450px;
  left: 80px;
  color: beige;
}
.container1{
  width: 320px;
  height: 400px;
  background-color: #39387a;
  border-radius: 12px;
  color: beige;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items:center;
  font-size: 22px;
}
.container2{
  width: 320px;
  height: 400px;
  background-color: #39387a;
  margin-left: 40px;
  border-radius: 12px;
  color: beige;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items:center;
  font-size: 22px;

}
.container3{
  width: 320px;
  height: 400px;
  background-color: #39387a;
  margin-left: 40px;
  border-radius: 12px;
  color: beige;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items:center;
  font-size: 22px;

}
.containers{
  display: flex;
  justify-content: center;
  align-items: center;
  justify-content: space-around;
  color: beige;

}
.newdish{
  width: 230px;
  height: 120px;
}
.para{
  padding: 13px;
  font-size: 15px;
}
.anchor2{
  font-size: 18px;
}
a:hover{
    color:cornflowerblue;
}
h1{
  font-variant: small-caps;
}


home.html

<html>
    <head>
        <link rel="stylesheet" href="homepage.css">
    </head>
    <body>
      <div class="logo">
        <img src="WhatsApp Image 2024-12-06 at 8.48.04 PM (7).jpeg" alt="logo"></img>
        <h1>BORA RESTAURANT</h1>
      </div>
      <div class="navbar">
        <h1><a href="restHomePage.html">Home</a></h1>
       <h1><a href="menu.html">
          Menu
        </a>  
      </h1> 
      <h1> 
        <a href="administration.html">
         Administration
        </a>
      </h1>   
      <h1>
        <a href="contact.html">
          Contact Us
        </a>
      </h1>
      </div>
      <div class="container">
      </div>
      <div class="welcome"><h1>WELCOME TO<br> BORA RESTAURANT!!</h1></div>
      <p class="signature">Where elegance meets flavor and every meal is a celebration.<br>
        Experience the warmth of our hospitality and the richness of our cuisine.<br>
        Don't miss our signature dish, The Bora Royale - a taste of perfection awaits you!</p>
      <img src="signaturedish.png" class="signaturedish">
      <div class="containers">

        <div class="container1">
          <h3>Our new menu</h3>
          <img src="WhatsApp Image 2024-12-06 at 8.48.04 PM (4).jpeg" class="newdish">
          <p class="para">Delight in the rich and aromatic flavors of our latest creation, the Saffron Infused Risotto. This luxurious dish combines perfectly cooked Arborio rice with a delicate infusion of premium saffron, creating a creamy, vibrant masterpiece.</p>
          <a href="menu.html" class="anchor2">Check out our new menu here</a>
        </div>
        <div class="container2">
          <h3>Book a table</h3>
          <img src="WhatsApp Image 2024-12-06 at 8.48.04 PM (5).jpeg" class="newdish">
          <p class="para">Experience the elegance and charm of dining at Bora. Whether it's an intimate dinner, a casual lunch, or a celebration with loved ones, we're here to make it special. Book your table now and immerse yourself in our signature dishes.
            </p>
            <a href="tablebooking.html" class="anchor2">Book your table now!</a>
        </div>
        <div class="container3">
          <h3>Opening hours</h3>
         <img src="WhatsApp Image 2024-12-06 at 8.48.04 PM (3).jpeg" class="newdish">
          <p class="para">At Bora, we're here to serve you the finest dining experience every day of the week.
            <br>
            Monday to Friday: 11:00 AM - 10:00 PM
            Saturday: 11:00 AM - 11:00 PM<br>
            Sunday: 12:00 PM - 10:00 PM<br>
            Join us for lunch, dinner, or anytime in between for exceptional meals and service.
           </p>
        </div>
      </div>

    </body>
</html>



menu.html


<html>
    <head>
     <link rel="stylesheet" href="menu.css">
     <style>
        body{
  background-color:beige; 
  color:#39387a;
  margin: 0px;
    padding: 0px;
        }
        h1{
    text-align: center;
    font-variant: small-caps;
    text-decoration: underline;
     }
     h2{
        font-variant: small-caps;
        text-decoration: underline;
        padding-left: 10px;
     }
     h4{
        font-variant: small-caps;
     }
     .container{
        display: flex;
        justify-content: center;
        align-items: center;
        justify-content: space-around;
     }
    img{
        width: 170px;
        height: 170px;
        border: solid 3px #39387a;
    }
    .item1{
        text-align: center;
    }
    .item2{
        text-align: center;
    }
    .item3{
        text-align: center;
    }
    .item4{
        text-align: center;
    }
    .navbar{
    margin-top:40px;
    margin-left: 40px;
    margin-right: 30px;
    width:1200px;
    height: 50px;
    background-color:#39387a;
    display: flex;
    justify-content: center;
    align-items: center;
    justify-content: space-around;
    border-radius: 12px;
}
a{
    text-decoration: none;
    color: beige;
    font-size: 25px;
}
a:hover{
    color:cornflowerblue;
}
.logo{
    
        width:100vw;
    height:130px;
    background-color: #39387a;
    display: flex;
    justify-content: center;
    align-items: center;
    color:beige;
    font-family:Georgia, 'Times New Roman', Times, serif;
}
.pic{
    width: 130px;
    height: 100px;
}
     </style>
    </head>
    <body>
    </head>
    <body>
      <div class="logo">
        <img src="WhatsApp Image 2024-12-06 at 8.48.04 PM (7).jpeg" alt="logo" class="pic"></img>
        <h1>BORA RESTAURANT</h1>
      </div>
        <div class="navbar">
            <h1><a href="restHomePage.html">Home</a></h1>
           <h1><a href="menu.html">
              Menu
            </a>  
          </h1> 
          <h1> 
            <a href="administration.html">
             Administration
            </a>
          </h1>   
          <h1>
            <a href="contact.html">
              Contact Us
            </a>
          </h1>
        </div>
        <h1>Our menu</h1>
        <h2>Starters</h2>
        <div class="container">
            <div class="item1">
                <img src="s1.jpg">
                <h4>Truffle-infused Mushroom Arancini</h4>
            </div>
            <div class="item2">
                <img src="s2.jpg">
            <h4>Roasted Beet Tartare</h4>
            </div>
            <div class="item3">
                <img src="s3.jpg">
                <h4>Stuffed Zucchini Flowers</h4>
            </div>
            <div class="item4">
                <img src="s4.jpg">
                <h4>Caramelized Onion and Goat Cheese Tart</h4>
            </div>
        </div>

        <h2>Main course</h2>
        <div class="container">
            <div class="item1">
                <img src="m1.jpg">
                <h4>Crimson Glazed Salmon</h4>
            </div>
            <div class="item2">
                <img src="m2.jpg">
                <h4>Truffle Infused Risotto</h4>
            </div>
            <div class="item3">
                <img src="m3.jpg">
                <h4>Golden Spice Butter Chicken</h4>
            </div>
            <div class="item4">
                <img src="m4.jpg">
                <h4>Velvet Peppercorn Tenderloin</h4>
            </div>
        </div>
        <h2>Dessert</h2>
        <div class="container">
            <div class="item1">
                <img src="d1.jpg">
                <h4>Golden Citrus Tart</h4>
            </div>
            <div class="item2">
                <img src="d2.jpg">
                <h4>ChocoLuxe Symphony</h4>
            </div>
            <div class="item3">
                <img src="d3.jpeg">
                <h4>Tropical Bliss Parfait</h4>
            </div>
            <div class="item4">
                <img src="d4.jpeg">
                <h4>Ambrosia Cheesecake</h4>
            </div>
        </div>
    </body>
</html>



administration.html

<html>
    <head>
        <style>
            body{
    margin: 0px;
    padding: 0px;
    background-color: beige;
}
.logo{
    width:100vw;
    height:130px;
    background-color: #39387a;
    display: flex;
    justify-content: center;
    align-items: center;
    color:beige;
    font-family:Georgia, 'Times New Roman', Times, serif;
}
.navbar{
    margin-top:40px;
    margin-left: 40px;
    margin-right: 30px;
    width:1200px;
    height: 50px;
    background-color:#39387a;
    display: flex;
    justify-content: center;
    align-items: center;
    justify-content: space-around;
    border-radius: 12px;
}
a{
    text-decoration: none;
    color: beige;
    font-size: 25px;
}
.head{
    text-align: center;
    color: #39387a;
    text-decoration: underline;
}
h2{
    color: #39387a;
    text-decoration: underline; 
    text-align: center;
}
.container{
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
    align-items: center;
    justify-content: space-around;
}
img{
    width: 150px;
    padding-left: 20px;
}
h3{
    color: #39387a;
    text-align: center;
}
.img6{
    padding-left: 40px;
}
        </style>
    </head>
    <body>
        <div class="logo">
            <img src="WhatsApp Image 2024-12-06 at 8.48.04 PM (7).jpeg" alt="logo"></img>
            <h1>BORA RESTAURANT</h1>
          </div>
          <div class="navbar">
            <h1><a href="restHomePage.html">Home</a></h1>
           <h1><a href="menu.html">
              Menu
            </a>  
          </h1> 
          <h1> 
            <a href="administration.html">
             Administration
            </a>
          </h1>   
          <h1>
            <a href="contact.html">
              Contact Us
            </a>
          </h1>
          </div>
    <h1 class="head">Administration</h1>
    <div class="container">
        <div class="item">
            <h2>Restaurant manager</h2>
            <img src="mee.png">
            <h3>Haridharshini</h3>
        </div>
        <div class="item">
            <h2>Executive chef</h2>
            <img src="p2-photoaidcom-cropped.jpg">
            <h3>Jake</h3>
        </div>
        <div class="item">
            <h2>Sous chef</h2>
            <img src="p3-photoaidcom-cropped.jpg">
            <h3>James</h3>
        </div>
        
    <!-- </div>
    <div class="container"> -->
        <div class="item">
            <h2>Service manager</h2>
            <img src="p4-photoaidcom-cropped.jpg">
            <h3>Lily</h3>
        </div>
        <div class="item">
            <h2>Event coordinator</h2>
            <img src="p5-photoaidcom-cropped.jpg">
            <h3>Sara</h3>
        </div>
        <div class="item">
            <h2>Front of house manager</h2>
            <img src="p6-photoaidcom-cropped (1).jpg" class="img6">
            <h3>David</h3>
        </div>
    <!-- </div> -->
    </body>
</html>



contact.html

<html>
    <head>
        <style>
            body{
    margin: 0px;
    padding: 0px;
    background-color: beige;
}
.logo{
    width:100vw;
    height:130px;
    background-color: #39387a;
    display: flex;
    justify-content: center;
    align-items: center;
    color:beige;
    font-family:Georgia, 'Times New Roman', Times, serif;
}
.navbar{
    margin-top:40px;
    margin-left: 40px;
    margin-right: 30px;
    width:1200px;
    height: 50px;
    background-color:#39387a;
    display: flex;
    justify-content: center;
    align-items: center;
    justify-content: space-around;
    border-radius: 12px;
}
a{
    text-decoration: none;
    color: beige;
    font-size: 25px;
}
.head{
    text-align: center;
    color: #39387a;
    text-decoration: underline;
}
p{

    text-align: center;
    padding: 15px;
    color: #39387a;
    font-size: 22px;
}
.container{
  display: flex;
  justify-content: center;
  align-items: center;
  color:#39387a;
  justify-content: space-around;
  font-size: 22px;

}
.last{
  color: #39387a;
  font-size: 22px;
text-align: center;
}

        </style>
    </head>
<body>
    <div class="logo">
        <img src="WhatsApp Image 2024-12-06 at 8.48.04 PM (7).jpeg" alt="logo"></img>
        <h1>BORA RESTAURANT</h1>
      </div>
      <div class="navbar">
        <h1><a href="restHomePage.html">Home</a></h1>
       <h1><a href="menu.html">
          Menu
        </a>  
      </h1> 
      <h1> 
        <a href="administration.html">
         Administration
        </a>
      </h1>   
      <h1>
        <a href="contact.html">
          Contact Us
        </a>
      </h1>
      </div>
      <h1 class="head">
        Contact Us
      </h1>
      <p>We'd love to hear from you! Whether you have questions about our menu, want to make a reservation, or need assistance planning your special event, our team is here to help.</p>
      <div class="container">

        <div class="item">
          
          <p>--Our Location<br>
            Bora Restaurant<br>
            No:07,Bora land,<br>
          Bora street,Bora city,<br>
          Bora Nation-0007.<br>
        </div>
        
        <div class="item">
          
          --Operating Hours<br>
          Monday to Sunday: 11:00 AM - 10:00 PM<br>
        </div>
        <div class="item">
          --Phone<br>
          For any queries, call us at-- 9876543210   <br>     
          --Email<br>
          borarestaurant@gmail.com<br>
        </div>
      </div>
      <div class="last">

        We Value Your Feedback!<br>
        We look forward to welcoming you to Bora, where every moment is crafted to perfection!</p>
      </div>
</body>
</html>



tablebooking.html

<html>
    <head>
<style>

body{
    margin: 0px;
    padding: 0px;
    background-color: beige;
}
.logo{
    width:100vw;
    height:130px;
    background-color: #39387a;
    display: flex;
    justify-content: center;
    align-items: center;
    color:beige;
    font-family:Georgia, 'Times New Roman', Times, serif;
}
.navbar{
    margin-top:40px;
    margin-left: 40px;
    margin-right: 30px;
    width:1200px;
    height: 50px;
    background-color:#39387a;
    display: flex;
    justify-content: center;
    align-items: center;
    justify-content: space-around;
    border-radius: 12px;
}
a{
    text-decoration: none;
    color: beige;
    font-size: 25px;
}
p{
    padding: 10px;
    color: #39387a;
    font-size: 20px;
}
.last{
    text-align: center;
}
</style>
    </head>
    <body>
        <div class="logo">
            <img src="WhatsApp Image 2024-12-06 at 8.48.04 PM (7).jpeg" alt="logo"></img>
            <h1>BORA RESTAURANT</h1>
          </div>
          <div class="navbar">
            <h1><a href="restHomePage.html">Home</a></h1>
           <h1><a href="menu.html">
              Menu
            </a>  
          </h1> 
          <h1> 
            <a href="administration.html">
             Administration
            </a>
          </h1>   
          <h1>
            <a href="contact.html">
              Contact Us
            </a>
          </h1>
          </div>
        <p>Planning a visit to Bora? Make your dining experience seamless with our easy table reservation system. Whether it's a dinner, a family gathering, or a business meeting, we ensure a table is ready for you at your convenience.</p>
        <div class="last">
            <p>Available table sizes: <br>
                2-in-1<br>
                4-in-1<br>
                6-in-1<br>
                8-in-1<br>
                To book a table, reach us at<br>
                Phone: 9876543210<br>
                Mail: borarestaurant@gmail.com<br>
            </p>
        </div>
        <p>Special Requests?
            Do you have a favorite spot in the restaurant, dietary preferences, or other requirements? Let us know while booking, and we'll do our best to accommodate them.
            
            Group Reservations & Private Events
            For larger groups or private gatherings, reach out to our events team. Bora is the perfect place to celebrate life's special moments.
            
            Reserve your table today and experience the elegance of Bora's fine dining.</p>
    </body>
</html>

```

## OUTPUT:


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
