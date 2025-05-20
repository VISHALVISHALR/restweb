# Ex.07 Restaurant Website
## Date:20.5.25

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
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home - My Restaurant</title>
    <style>
   *{
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    font-size: 2.5rem;
    margin-bottom: 10px;
}

nav ul {
    list-style-type: none;
    display: flex;
    justify-content: center;
    gap: 20px;
}

nav a {
    color: #fff;
    text-decoration: none;
    font-size: 1.2rem;
    transition: color 0.3s ease;
}

nav a:hover {
    color: #f4a261; 
}

main {
    text-align: center;
    padding: 40px 20px;
}

.banner {
    width: 100%;
    height: auto;
    max-height: 700px; 
    object-fit: cover; 
    margin-bottom: 30px;
}

h2 {
    font-size: 2rem;
    margin-bottom: 20px;
    color: #333;
}

p {
    font-size: 1.2rem;
    color: #777;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}
</style>
</head>
<body>
    <header>
        <h1>Come hungry, leave happy!</h1>
        
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <img src="banner.png" alt="Restaurant Banner" class="banner">
        <h2>Food tastes better when shared!</h2>
        <p>Eat. Drink. Enjoy the moment.</p>
    </main>
    <footer>
        <p>&copy; Designed and Developed by Charithrakshi</p>
    </footer>
</body>
</html>

administration.html

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - My Restaurant</title>
    <style>
     *{
        margin: 0;
        padding: 0;
        box-sizing: border-box;
      }

body {
    font-family: Arial, sans-serif;
    background-color: #baadad;
    color: #473434;
}

header {
    background-color: #1b1111;
    color: #c0b0b0;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    font-size: 2.5rem;
    margin-bottom: 10px;
}

nav ul {
    list-style-type: none;
    display: flex;
    justify-content: center;
    gap: 20px;
}

nav a {
    color: #ede0e0;
    text-decoration: none;
    font-size: 1.2rem;
    transition: color 0.3s ease;
}

nav a:hover {
    color: #99d71c; 
}

main {
    padding: 40px;
    text-align: center;
}

h2 {
    font-size: 5rem;
    margin-bottom: 200px;
    color: #160d0d;
}


.team {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    gap: 100px;
    justify-items: center;
    margin-top: 200px;
}



.member img {
    width: 100%;
    height: auto;
    border-radius: 50%;
    margin-bottom: 15px;
    border: 4px solid #090607; 
}

.member h3 {
    font-size: 3rem;
    margin-bottom: 10px;
    color: #151313;
}

.member p {
    font-size: 1.1rem;
    color: #080808;
}

.member:hover {
    transform: translateY(-5px);
    box-shadow: 0 6px 12px rgba(210, 195, 195, 0.15);
}

h3 {
    margin-bottom: 10px;
    font-size: 1.5rem;
    color: #d7caca;
}

footer {
    background-color: #6a2424;
    color: #fff;
    text-align: center;
    padding: 100px;
    position: fixed;
    bottom: 0;
    width: 10%;
}
</style>
</head>
<body>
    <header>
        <h1>Administration Team</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h2>Administration Members </h2>
        <div class="team">
            <div class="member">
                <img src="mypic.jpg" alt="Member 1">
                <h3>CHARITHRAKSHI K</h3>
                <p>CEO</p>
            </div>
            <div class="member">
                <img src="shwetha.png" alt="Member 2">
                <h3>SHWETHA<h3>
                <p>Marketing Manager</p>
            </div>
            <div class="member">
                <img src="jane.png" alt="Member 3">
                <h3>Henry<h3>
                <p>Operations Manager</p>
            </div>
            <div class="member">
                <img src="sara.png" alt="Member 4">
                <h3>Sara</h3>
                <p>HR Manager</p>
            </div>
            <div class="member">
                <img src="ram.png" alt="Member 5">
                <h3>Ram<h3>
                <p>Executive Chef</p>
            </div>
            <div class="member">
                <img src="clara.png" alt="Member 6">
                <h3>Clara<h3>
                <p>Customer Service Manger</p>
            </div>
        </div>
    </main>
</body>
</html>

menu.html

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - My Restaurant</title>
   <style>
    *{
        margin: 0;
        padding: 0;
        box-sizing: border-box;
     }

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    font-size: 2.5rem;
    margin-bottom: 10px;
}

nav ul {
    list-style-type: none;
    display: flex;
    justify-content: center;
    gap: 20px;
}

nav a {
    color: #fff;
    text-decoration: none;
    font-size: 1.2rem;
    transition: color 0.3s ease;
}

nav a:hover {
    color: #f4a261; /* Light orange on hover */
}

main {
    padding: 40px 20px;
    text-align: center;
}

h2 {
    font-size: 2rem;
    margin-bottom: 20px;
    color: #333;
}

.menu-list {
    list-style-type: none;
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    gap: 20px;
    justify-items: center;
}

.menu-list li {
    background-color: #fff;
    padding: 15px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    width: 100%;
    text-align: center;
}

.menu-list img {
    width: 100%;
    height: auto;
    border-radius: 5px;
    margin-bottom: 15px;
}

.menu-list li p {
    font-size: 1.1rem;
    color: #333;
    font-weight: bold;
}

.menu-list li:hover {
    transform: translateY(-5px);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
}


footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}
</style>
</head>
<body>
    <header>
        <h1>Plates of the Day</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h2>Food Items</h2>
        <ul class="menu-list">
            <li><img src="avocadotoast.png" alt="Food Item 1">Avocado Toast <br>Rs.150 </li><br>
            <li><img src="bruschetta.png" alt="Food Item 2">Bruschetta trio <br> Rs.350</li><br>
            <li><img src="sandwich.png" alt="Food Item 3">Grilled Chicken & Waffle Sandwich<br>Rs.500</li><br>
            <li><img src="bbq.png" alt="Food Item 4">Korean BBQ Tacos <br> Rs.400</li><br>
            <li><img src="buddhabowl.png" alt="Food Item 5">Vegetarian Buddha Bowl<br>Rs.350 </li><br>
            <li><img src="cheeseburger.png" alt="Food Item 6">Vegan Cheeseburger<br>Rs.200</li><br>
            <li><img src="cauli.png" alt="Food Item 7">Spicy Roasted Cauliflower <br>Rs.150</li><br>
            <li><img src="cheese.png" alt="Food Item 8">Mac & Cheese with Lobster<br>Rs.400</li><br>
            <li><img src="cake.png" alt="Food Item 9">Matcha Cheesecake<br>Rs.300</li><br>
            <li><img src="sorbet.png" alt="Food Item 10">Raspberry Sorbet<br>Rs.400</li><br>
            <li><img src="margarita.png" alt="Food Item 11">Spicy Margarita <br>Rs.200</li><br>
            <li><img src="smash.png" alt="Food Item 12">Cucumber & Basil Smash<br>Rs.150</li><br>

        </ul>
    </main>
    <footer>
        <p>&copy; Designed and developed by Charithrakshi</p>
    </footer>
</body>
</html>

contact.html

<body>
    <style>
    *{
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
  
  body {
    font-family: Arial, sans-serif;
    background-color: #0a0808;
    color: #333;
  }
  #contact {
    background-color: #f3eeee;
    padding: 400px 200px;
    margin: 40px auto;
    max-width: 600px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
  }
  
  #contact h2 {
    font-size: 2rem;
    margin-bottom: 20px;
    color: #333;
  }
  
  #contact p {
    font-size: 1.2rem;
    margin-bottom: 20px;
    color: #555;
  }
  
  address {
    font-size: 1.1rem;
    line-height: 1.6;
    color: #333;
  }
  
  address br {
    margin-bottom: 10px;
  }
  
  #contact:hover {
    transform: translateY(-5px);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
  }
    </style>
     <section id="contact">
    <h2>Contact Us</h2>
    <p>RESTAURANT LOCATION:</p>
    <address>
      ANNA NAGAR,CHENNAI
      <br>
      Phone: 1234567890
      <br>
      Email: urbanfeast@gmail.com
    </address>
  </section>
  </body>
  </html>
  
  
   
```



## OUTPUT:
![alt text](<Screenshot 2024-12-16 202150.png>)
![alt text](<Screenshot 2024-12-16 202201.png>)
![alt text](<Screenshot 2024-12-16 202210.png>)
![alt text](<Screenshot 2024-12-16 202221.png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
