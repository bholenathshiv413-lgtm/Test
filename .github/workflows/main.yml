<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Shopping Bag Store</title>

<style>

body{
font-family: Arial;
background:#f4f4f4;
margin:0;
text-align:center;
}

header{
background:#222;
color:white;
padding:20px;
font-size:28px;
}

.container{
display:flex;
flex-wrap:wrap;
justify-content:center;
margin-top:20px;
}

.product{
background:white;
margin:15px;
padding:15px;
border-radius:10px;
box-shadow:0 0 10px rgba(0,0,0,0.1);
width:250px;
}

.product img{
width:100%;
border-radius:8px;
}

button{
background:#28a745;
color:white;
border:none;
padding:10px 15px;
margin-top:10px;
cursor:pointer;
border-radius:5px;
}

button:hover{
background:#218838;
}

form{
background:white;
max-width:400px;
margin:40px auto;
padding:20px;
border-radius:10px;
box-shadow:0 0 10px rgba(0,0,0,0.2);
}

input,select,textarea{
width:100%;
padding:10px;
margin:8px 0;
border-radius:5px;
border:1px solid #ccc;
}

footer{
background:#222;
color:white;
padding:20px;
margin-top:40px;
}

</style>

<script>

function selectProduct(product){
document.getElementById("product").value = product;
window.location.href="#order";
}

</script>

</head>

<body>

<header>
Shopping Bag Product Store
</header>

<div class="container">

<div class="product">
<img src="https://i.ibb.co/39CvXdQ2/17722607362618396886365153203158.jpg">
<h3>Shopping Bag 1</h3>
<button onclick="selectProduct('Shopping Bag 1')">Add to Cart</button>
</div>

<div class="product">
<img src="https://i.ibb.co/Zbxv1k6/17722606525215261458211229649014.jpg">
<h3>Shopping Bag 2</h3>
<button onclick="selectProduct('Shopping Bag 2')">Add to Cart</button>
</div>

<div class="product">
<img src="https://i.ibb.co/20r8Rbgp/17722604132509058731193443975821.jpg">
<h3>Shopping Bag 3</h3>
<button onclick="selectProduct('Shopping Bag 3')">Add to Cart</button>
</div>

</div>


<!-- ORDER FORM -->

<form id="order" action="mailto:bholenathshiv413@gmail.com" method="post" enctype="text/plain">

<h2>Place Your Order</h2>

<label>Selected Product</label>
<input type="text" id="product" name="Product">

<label>Your Name</label>
<input type="text" name="Name" required>

<label>Email</label>
<input type="email" name="Email" required>

<label>Quantity</label>
<input type="number" name="Quantity" min="1" required>

<label>Delivery Address</label>
<textarea name="Address" required></textarea>

<button type="submit">Submit Order</button>

</form>


<footer>

<p>Image reference from  
<a href="https://www.freepik.com/free-photo/present-sale-buy-empty-colorful_1088296.htm" style="color:#ffd700;">
Freepik
</a>
</p>

<p>Contact Email: bholenathshiv413@gmail.com</p>

</footer>

</body>
</html>
