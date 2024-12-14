# Ex.07 Restaurant Website
## Date:13.12.2024

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
    <title>Timeless Tastes Tavern 
       
    </title>
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
    text-align:center;
    height:100%;
    width:100%;
    align-items: center;

}



h2 {
    font-size: 2rem;
    margin-top: 20px;
    color: #333;
    text-align: center;
    align-items: center;
}

p {
    font-size: 1.2rem;
    color: #20ac46;
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
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administrative.html">Administrative</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h1>TASTE OF INDIA</h1>
        <p>Symphony of flavors, on a plate, where taste buds dance and hearts celebrate.</p>
        <img src="C:\Users\keert\restweb\vijay\restapp\static\Screenshot (70).jpg" alt="Restaurant Banner">
        
    </main>
    <footer>
        <p>&copy; KEERTHANA D</p>
    </footer>
</body>
</html>

menu.html

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dishes in Restaraunt</title>
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
    background-color: #d2cfcf;
    color: #882e2e;
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
        <h1>Available Dishes</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administrative.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h2>Food items</h2>
        <ul class="menu-list">
            <li><img src="C:\Users\keert\restweb\vijay\restapp\static\Screenshot (85).jpg" alt="Food Item 1">Pizza - $25</li>
            <li><img src="C:\Users\keert\restweb\vijay\restapp\static\Screenshot (79).jpg" alt="Food Item 2">Burger - $20</li>
            <li><img src="C:\Users\keert\restweb\vijay\restapp\static\Screenshot (80).jpg" alt="Food Item 3">Three Types of Pasta - $100</li>
            <li><img src="C:\Users\keert\restweb\vijay\restapp\static\Screenshot (88).jpg" alt="Food Item 5">Noodles - $30</li>
            <li><img src="C:\Users\keert\restweb\vijay\restapp\static\Screenshot (71).jpg" alt="Food Item 6">Favourite Recipes - $50</li>
            <li><img src="C:\Users\keert\restweb\vijay\restapp\static\Screenshot (81).jpg" alt="Food Item 8">Chicken Fries - $45</li>
            <li><img src="C:\Users\keert\restweb\vijay\restapp\static\Screenshot (89).jpg" alt="Food Item 9">Potato Fries - $90</li>
            <li><img src="C:\Users\keert\restweb\vijay\restapp\static\Screenshot (84).jpg" alt="Food Item 10">Chocolate Cake - $6</li>
            <li><img src="C:\Users\keert\restweb\vijay\restapp\static\Screenshot (91).jpg" alt="Food Item 11">Varities Of Non-Veg - $100</li>
            <li><img src="C:\Users\keert\restweb\vijay\restapp\static\Screenshot (92).jpg" alt="Food Item 12">Fish Sambar - $50</li>
            <li><img src="C:\Users\keert\restweb\vijay\restapp\static\Screenshot (93).jpg"  alt="Food Item 13">Egg Rice - $80</li>

        </ul>
    </main>
    <footer>
        <p>&copy; KEERTHANA D</p>
    </footer>
</body>
</html>

administrative.html

   <html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Team Members of Our Restaraunt</title>
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
    padding: 40px 20px;
    text-align: center;
}

h2 {
    font-size: 2rem;
    margin-bottom: 20px;
    color: #333;
}


.team {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    gap: 30px;
    justify-items: center;
    margin-top: 30px;
}

.member {
    background-color: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.member img {
    width: 100%;
    height: auto;
    border-radius: 50%;
    margin-bottom: 15px;
    border: 4px solid #f4a261; 
}

.member h3 {
    font-size: 1.5rem;
    margin-bottom: 10px;
    color: #333;
}

.member p {
    font-size: 1.1rem;
    color: #777;
}

.member:hover {
    transform: translateY(-5px);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
}

h3 {
    margin-bottom: 10px;
    font-size: 1.5rem;
    color: #333;
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
        <h1>Our Team Members</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administrative.html">Administrative</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h2>Pillars of our Restraunt</h2>
        <div class="team">
            <div class="member">
                <img src="C:\Users\keert\restweb\vijay\restapp\static\keerthana.jpg" alt="Member 1">
                <h3>KEERTHANA.D</h3>
                <p>Manager</p>
            </div>
            <div class="member">
                <img src="C:\Users\keert\restweb\vijay\restapp\static\Screenshot (74).jpg" alt="Member 2">
                <h3>NITHIYA SREE THEIVA<h3>
                <p>Assistant  Manager</p>
            </div>
            <div class="member">
                <img src="C:\Users\keert\restweb\vijay\restapp\static\Screenshot (86).jpg" alt="Member 3">
                <h3>AJAI<h3>
                <p>Chef</p>
            </div>
            <div class="member">
                <img src="C:\Users\keert\restweb\vijay\restapp\static\Screenshot (73).jpg" alt="Member 4">
                <h3>GAJA LAKSHIMI<h3>
                <p>HR Manager</p>
            </div>
            <div class="member">
                <img src="C:\Users\keert\restweb\vijay\restapp\static\Screenshot (76).jpg" alt="Member 5">
                <h3>ATCHAYA<h3>
                <p>Counter</p>
            </div>
            <div class="member">
                <img src="C:\Users\keert\restweb\vijay\restapp\static\Screenshot (75).jpg" alt="Member 6">
                <h3>SIRANJEEVI<h3>
                <p>Customer Service Manger</p>
            </div>
        </div>
    </main>
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
  background-color: #f4f4f4;
  color: #333;
}
#contact {
  background-color: #fff;
  padding: 40px 20px;
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
  <p>Visit us :</p>
  <address>
    78/92 South Street Vaniyambadi.
    <br>
    Phone: 9894305410
    <br>
    Email: taste@myrestaurant.com
  </address>
</section>
</body>
</html>


```

       

## OUTPUT:
![alt text](<Screenshot (94).png>)
![alt text](<Screenshot (95)-1.png>)
![alt text](<Screenshot (96)-1.png>)
![alt text](<Screenshot (97)-1.png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
