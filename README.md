# Product Card Design with Hover Effect using CSS
## Date:

## AIM:
To design a Product Card for an E-commerce website using HTML and CSS and apply hover effects, transitions, and styling techniques to create an interactive user interface.

## DESIGN STEPS:

### Step 1:
Create a basic HTML structure using ```<!DOCTYPE html>, <html>, <head>, and <body>```.

### Step 2:
Add a container div for the product card.

### Step 3:
Insert the product image using the ```<img>``` tag.

### Step 4:
Add product name, description, and price using ```<h3>``` and ```<p>``` tags.

### Step 5:
Create an Add to Cart button using the ```<button>``` tag.

### Step 6:
Style the product card using CSS by applying:
<ul>
  <li>width</li>
  <li>padding</li>
  <li>border-radius</li>
  <li>box-shadow</li>
</ul>

### Step 7:
Align the card content using text-align and spacing properties.

### Step 8:
Add hover effects using :hover selector.

### Step 9:
Apply transform: translateY() to move the card slightly upward on hover.

### Step 10:
Increase the box-shadow to create a lifting effect.

### Step 11:
Add transform: scale() to slightly zoom the product image on hover.

### Step 12:
Apply transition property to make the hover animation smooth.

### Step 13:
Create a footer section at the bottom of the page.

### Step 14:
Display Learner Name and Register Number inside the footer.

### Step 15:
Style the footer using background color and center alignment.

### Step 10:
Test your webpage in a browser.

## PROGRAM:
~~~
<html>
<head>
<title>Product Card</title>

<style>

body{
text-align:center;
font-family:Arial;
}


.card{
width:300px;
border:1px solid white;
border-radius:10px;
padding:15px;
margin:auto;
transition:0.3s;
}


.card:hover{
transform:translateY(-5px);
box-shadow:0 5px 10px gray;
}

img{
width:100%;
transition:0.3s;
}

.card:hover img{
transform:scale(1.2);
}

button{
padding:8px 15px;
background:blue;
color:white;
border:none;
border-radius:5px;
}

button:hover{
background:red;
}

footer{
margin-top:50px;
background:red;
padding:10px;
}

</style>
</head>

<body>

<div class="card">

<h3>Headphones</h3>

<p>Good quality wireless headphones.</p>

<h4>₹1500</h4>

<button>Add to Cart</button>

</div>

<footer>
Name: SYED ADIL S <br>
Register No: 212225040453
</footer>

</body>
</html>
~~~
## OUTPUT:
<img width="553" height="444" alt="Screenshot 2026-03-09 142638" src="https://github.com/user-attachments/assets/1b353f1e-5021-4ec6-bc27-b38fd3730ab0" />

## RESULT:
The Product Card with Hover Effect was successfully designed using HTML and CSS.
