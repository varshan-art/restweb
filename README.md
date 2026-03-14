# Ex.06 Restaurant Website
## Date:14-03-2026

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
Publish the website in Localhost.

## PROGRAM:
```


home.html

<html>
    <head>
        <title>Home</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <nav>
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </nav>
        <h1 class="main-title">V Restaurant</h1>
        <h2 class="subtitle">The taste of indian food</h2>
        <p style="margin-left:80px;">
            Indian food is characterized by a complex, aromatic,and layered blend of spices, ranging from mild and creamy to fiery hot.
        </p>
        <div class="image-container">
            <img src="image1.png">
            <img src="image3.png">
            <img src="image2.png">
        </div>
        <footer>NAME-SRI VIJAY VARSHAN.G , REF NO:25008956</footer>
    </body>
</html>

menu.html

<html>
    <head>
        <title>Menu</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <nav>
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </nav>
        <h1 class="main-title">MENU</h1>
        <div class="menu-container">
            <div class="card">
                <img src="imagez.png">
                <h3>Pizza</h3>
                <p>Rs.140</p>
            </div>
            
            <div class="card">
                <img src="imageb.png">
                <h3>biriyani</h3>
                <p>Rs. 150</p>
            </div>

            <div class="card">
                <img src="images.png">
                <h3>samosa</h3>
                <p>Rs.50</p>
            </div>
            <div class="card">
                <img src="imagec.png">
                <h3>chicken 65</h3>
                <p>Rs.250</p>
            </div>
            
            <div class="card">
                <img src="imagebg.png">
                <h3>burger</h3>
                <p>Rs.60</p>
            </div>
            
            <div class="card">
                <img src="imagess.png">
                <h3>shawarma sandwidch</h3>
                <p>Rs.110</p>
            </div>
            <div class="card">
                <img src="imagen.png">
                <h3>noodles</h3>
                <p>Rs.40</p>
            </div>

            <div class="card">
                <img src="imagetc.png">
                <h3>Tandori</h3>
                <p>Rs.160</p>
            </div>

            <div class="card">
                <img src="imageva.png">
                <h3>chicken gravy</h3>
                <p>Rs.100</p>
            </div>

            <div class="card">
                <img src="imagecg.png">
                <h3>chilli chicken</h3>
                <p>Rs.100</p>
            </div>

        </div>

        <footer>NAME-SRI VIJAY VARSHAN.G , REF NO:25008956</footer>
    
    </body>
</html>

admin.html

<html>
    <head>
        <title>Admin</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <nav>
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </nav>
        <h1 class="main-title">ADMINISTRATION TEAM</h1>
        <div class="team-container">
            <div class="team-card">
                <img src="varshan.png">
                <h3>sri vijay varshan.G</h3>
                <p>owner</p>
            </div>
            <div class="team-card">
                <img src="imager.png">
                <h3>Rdj</h3>
                <p>food security manager</p>

            </div>

            <div class="team-card">
                <img src="imagehr.png">
                <h3>hardy</h3>
                <p>assistant chef</p>
            </div>

            <div class="team-card">
                <img src="shawn.png">
                <h3>shawng</h3>
                <p>customer service manager</p>
            </div>
            <div class="team-card">
                <img src="imageto.png">
                <h3>tom</h3>
                <p>Chef</p>
            </div>
        </div>
        <footer>NAME-SRI VIJAY VARSHAN.G , REF NO:25008956</footer>
    </body>
</html>


contact.html

<html>
    <head>
        <title>Contact</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <nav>
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </nav>
        <h1 class="main-title">CONTACT</h1>
        <div class="contact-box">
            <h2>Visit us At:</h2>
            <p>
                V restaurant
                <br>
                chennai area 51
                <br>
                beach Street,pin-code:600070
                <br>
                India
            </p>
            <br>
            <h2>Phone:</h2>
            <p>+91 9025431508</p>
            <br>
            <h2>Email ID:</h2>
            <p>varshang8072@gmail.com</p>
        </div>
        <footer>NAME-SRI VIJAY VARSHAN.G , REF NO:25008956</footer>
    </body>
</html>

style.css

body{
    background-image:url(https://i.pinimg.com/1200x/dd/8c/f6/dd8cf65443d62697299e019d8d87ae5e.jpg);
    background-size:cover;
    background-position:center;
    color:white;
    padding:fixed;
    margin:0;
    bottom:0;
    box-sizing:border-box;
    font-family:Arial;
}

nav{
    position:absolute;
    top:20px;
    right:80px;
    background:linear-gradient(45deg,lightgreen,orange);
    padding:12px 40px;
}

nav a{
    margin:0 20px;
    text-decoration:none;
    color:orangered;
    font-weight:bold;
}

.main-title{
    font-size:90px;
    color:lightgreen;
    margin-left:80px;
    margin-top:120px;
}

.subtitle{
    font-size:30px;
    margin-left:80px;
}

.image-container{
    display:flex;
    justify-content:center;
    gap:80px;
    margin-top:40px;
}

.image-container img{
    width:450px;
    border-radius:10px;
}

.menu-container{
    display:flex;
    justify-content:center;
    gap:25px;
    margin-top:400px;
}

.card{
    background:linear-gradient(45deg,lightgreen,orange);;
    padding:15px;
    border-radius:12px;
    text-align:center;
    width:150px;
    color:black;
}

.card img{
    width:100%;
    border-radius:10px;
}

.card h3{
    margin-top:10px;
}

.card p{
    margin-top:5px;
}

.team-container{
    display:flex;
    justify-content:center;
    gap:30px;
    margin-top:350px;
}

.team-card{
    background:linear-gradient(45deg,lightgreen,orange);
    width:180px;
    padding:20px;
    border-radius:15px;
    text-align:center;
    color:black;
}

.team-card img{
    width:120px;
    height:120px;
    border-radius:40%;
}

.team-card h3{
    margin-top:10px;
}

.contact-box{
    margin-left:90px;
    margin-top:40px;
    line-height:35px;
}

footer{
    text-align:center;
    padding:10px;
    background:linear-gradient(45deg,lightgreen,black,orange);
    color:whitesmoke;
    position:fixed;
    bottom:0;
    width:100%;
}

```

## OUTPUT:
![alt text](<Screenshot 2026-03-14 130452.png>)
![alt text](<Screenshot 2026-03-14 130510.png>)
![alt text](<Screenshot 2026-03-14 130526.png>)
![alt text](<Screenshot 2026-03-14 130540.png>)



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
