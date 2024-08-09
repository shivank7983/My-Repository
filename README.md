# My-Repository
This is my first Repository Based on Amazon
<br>
Author - Shivank Singh
**HTML Code:**
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=<device-width>, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"
        integrity="sha512-iecdLmaskl7CVkqkXNQ/ZH/XLlvWZOJyj7Yy7tcenmpD1ypASozpmT/E0iPtmFIB46ZmdtAc9eNBvH0H/ZpiBw=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="amazonstyle.css">
</head>

<body>
    <header>
        <div class="navbar">
            <div class="nav-logo border">
                <div class="logo"></div>
            </div>

            <div class="nav-address border">
                <p class="add-first">Delivering to Lucknow 226012</p>
                <div class="add-icon">
                    <p class="add-sec">Update location</p>
                </div>
            </div>
            <div class="nav-search">
                <select class="search-select">
                    <option>All</option>
                </select>
                <input placeholder="Search Amazon" class="search-input">
                <div class="search-icon">
                    <i class="fa-solid fa-magnifying-glass"></i>
                </div>
            </div>
            <div class="nav-select border">
                <img src="flag.png" alt="flag">
                <p>EN</p>
                <i class="fa-duotone fa-solid fa-caret-down"></i>
            </div>
            <div class="nav-link border">
                <p class="link-first">Hello, sign in</p>
                <div class="link-icon">
                    <p class="link-sec">Account & Lists</p>
                    <i class="fa-sharp-duotone fa-solid fa-caret-down"></i>
                </div>
            </div>
            <div class="nav-text border">
                <p class="text-first">Return</p>
                <div class="text">
                    <p class="text-sec">& Orders</p>
                </div>
            </div>

            <div class="nav-cart border">
                <i class="fa-solid fa-cart-shopping"></i>
                Cart
            </div>
        </div>

        <div class="panel">
            <div class="panel-all border">
                <i class="fa-solid fa-bars"></i>
                All
            </div>
            <div class="panel-ops">
                <p class="border">Fresh</p>
                <p class="border">Amazon miniTV</p>
                <p class="border">Sell</p>
                <p class="border">Best Deals</p>
                <p class="border">Today's Deals</p>
                <p class="border">Mobile</p>
                <p class="border">Prime</p>
                <p class="border">Customer service</p>
                <p class="border">Electronics</p>
                <p class="border">Fashion</p>
                <p class="border">New Releases</p>
                <p class="border">Kitchen & Homes</p>
                <p class="border">Amazon Pay</p>
                <p class="border">Computers</p>
                <p class="border">Books</p>
            </div>
            <div class="panel-deals border">

            </div>
        </div>
    </header>

    <div class="hero-section">
        <div class="hero-msg">
            <p>You are on amazon.com. You can also shop on Amazon india for millions of products with fast local delivery. <a>Click here to go to amazon.in</a></p>
        </div>
    </div>
</body>
</html>


**CSS Code**
* {
    padding: 0px;
    margin: 0px;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    border: border-box;
}

.navbar {
    height: 65px;
    background-color: black;
    color: white;
    display: flex;   
    align-items: center;
}

.nav-logo {
    height: 50px;
    /* width: 110px; */
    padding-top: 6px;
    /* padding-left: 70px; */
    margin-left: 60px;
}

.logo {
    background-image: url("Amazon_icon.JPG");
    background-size: cover;
    height: 50px;
    width: 110px;
}

.border {
    border: 2px solid transparent;
}

.border:hover {
    border: 2px solid white;
}

.nav-address {
    margin-left: 35px;
    padding: 3px 6px;
}

.add-first {
    color: #cccccc;
    font-size: 0.80rem;
    margin-left: 20px;
}

.add-sec {
    font-size: 1rem;
    margin-left: 20px;
    font-weight: bold;
}

/** Box 3 **/
.nav-search {
    display: flex;
    justify-content: space-evenly;
     width: 800px;
     height: 40px;
     border-radius: 4px;
     padding-left: 70px;
}

.search-icon {
    background-color: rgb(255, 180, 0);
    width: 60px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 1.2rem;
    color: #0f1111;
    border-top-right-radius: 4px;
    border-bottom-right-radius: 4px;
}

.search-select {
    background-color: #f3f3f3;
    padding: 0px 0px 0px 5px;
    font: 14px;
    color: #0f1111;
    width: 50px;
    text-align: center;
    border-top-left-radius: 4px;
    border-bottom-left-radius: 4px;
    border: none;
}

.search-input {
    width: 800px;
    font-size: 1rem;
    border: none;
}

/** Box4 **/
.nav-select img {
    width: 18px;
    height: 20px;
    margin-top: 2px;
}

.nav-select {
    display: flex;
    margin-left: 50px;
    padding: 10px 15px;
}

.nav-select i {
    margin-top: 5px;
    margin-left: 2px;
}

/** Box5 **/
.nav-link {
    margin-top: 3px;
    margin-left: 40px;
    padding: 5px 10px;
}

.link-icon {
    display: flex;
}

.link-icon i {
    margin-top: 5px;
    margin-left: 2px;
}

.link-first {
    font-size: 0.80rem;
}

.link-sec {
    font-size: 1rem;
    font-weight: bold;
}

/** box6 **/
.nav-text {
    padding: 5px 10px;
    margin-left: 40px;
}

.text-first {
    font-size: 0.80rem;
}

.text-sec {
    font-size: 1rem;
    font-weight: bold;
}

/** box7 **/
.nav-cart i {
    font-size: 30px;
}

.nav-cart {
    font-size: 0.85rem;
    font-weight: 700;
    padding: 5px 10px;
    margin-left: 40px;
}

/** panel css **/
.panel {
    height: 45px;
    background-color: #222F3d;
    display: flex;
    color: white;
    align-items: center;
    justify-content: space-evenly;
}

.panel-ops {
    width: 80%;
    margin-right: 100px;
}

.panel-all i {
    color: white;
    margin-left: 4px;
    font-size: 1.25rem;
    margin: 7px 4px;
}

.panel-deals {
    background-image: url("Capture.JPG");
    background-size: cover;
    height: 40px;
    width: 205px;
    margin-top: -3px;
}

.panel-ops p {
    display: inline;
    margin-left: 15px;
    font-size: 0.85rem;
    padding: 8px 8px;
}

/** Hero Section */
.hero-section {
    background-image: url("smartwatch.jpg");
    background-size: cover;
    height: 400px;
    display: flex;
    justify-content: center;
    align-items: flex-end;
}

.hero-msg {
    background: linear-gradient(to right, orange, whitesmoke, green);
    height: 40px;
    color: black;
    font-weight: bold;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 0.85rem;
    width: 90%;
    margin-bottom: 25px;
}

.hero-msg a {
    color: white;
}
