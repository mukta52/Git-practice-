# Git-practice-

<body>
<header>
<img src="" alt="logo">
<div>search box</div>
<button>Login</button>
<button>Registration</button>
<button>Shopping basket</button>
</header>
<aside>
<div>filter</div>
<div>filter</div>
<div>filter</div>
</aside>
<main>
<div>product</div>
<div>product</div>
<div>product</div>
<div>product</div>
<div>product</div>
<div>product</div>
</main>
</body>

<body>
<header>
<img id='logo' src="" alt="logo">
<div id='searchbox' >search box</div>
<button>Login</button>
<button>Registration</button>
<button>Shopping basket</button>
</header>
<aside>
<div class="filter">filter</div>
<div class="filter">filter</div>
<div class="filter">filter</div>
</aside>
<main>
<div class="product">product</div>
<div class="product">product</div>
<div class="product">product</div>
<div class="product">product</div>
<div class="product">product</div>
<div class="product">product</div>
</main>
</body>

div,header,aside,main {
border: solid lightblue;
box-sizing: border-box;
margin: 1%;
padding: 10px;}
header {width: 95%;}
#logo {width: 100px;}
#searchbox {width: 300px;}
#logo, #searchbox {
height: 50px;
display: inline-block;}
button {
height: 50px;
margin: 20px;
padding: 10px;}
aside {
width: 20%;
float: left;}
main {
width: 70%;
margin-left: 25%;}
.filter {
width: 80%;
min-height: 100px;}
.product {
width: 200px;
height: 200px;
display: inline-block;}

 header {
grid-column: 1 / 3;
grid-row: 1;
}
aside {
grid-column: 1;
grid-row: 2;
}
article {
grid-column: 2;
grid-row: 2;
}