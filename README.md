# My-Repository
This is my first Repository
<br>
Author - Shivank Singh
"Hello"
**HTML Code:**
 <div class="menu">
        <a href="#" class="menu-item">Sell With Us</a>
        <span class="separator">|</span>
        <a href="#" class="menu-item">Contact Us</a>
    </div>
    <div id="head">
      <div class="logo">
        <a href="#"><img src="Shopclues_logo.png" width="130" height="60" alt="Logo"></a>
      </div>
      <div class="searchbar">
        <input type="text" placeholder="What is on your Mind today?">
        <button class="btn1">Search</button>
      </div>
      <div class="Location1">
        <span>Share</span><a style="display: block" href="#">Location</a>
      </div>
      <div class="bell">
        <a href="#"><img src="Location_icon.png" alt="Location"></a>
        <a href="#"><img src="Bell_Icon.png" alt="Bell"></a>
        <a href="#"><img src="Favourties_icon.png" alt="Favourties"></a>
        <a href="#"><img src="Cart_icon.png" alt="cart"></a>
        <div>Sign In</div>
      </div>
    </div>
        <div id="head2">
          <img src="Blue_Icon.png" alt="Made in India">
          <div class="nav-list">
            <ul class="list">
              <li>Mobile & More</li>
              <li>Men</li>
              <li>Women</li>
              <li>Home & Kitchen</li>
              <li>Appliances</li>
              <li>Sports & More</li>
              <li>Essentials</li>
              <li>Offers</li>
              <li>Global Shopping</li>
            </ul>
          </div>
    </div>

    **CSS Code**
    body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

#head {
    height: 90px;
    display: flex;
    }

#head2 {
    height: 50px;
    background-color: #24A3B5;
}

.logo {
    padding-top: 22px;
    padding-left: 40px;
}

.searchbar {
    margin: 0 20px;
    padding-top: 35px;
    padding-left: 80px;
}

input {
    width: 400px;
    padding: 12px 65px;
    border: 1px solid #ddd;
    border-radius: 5px 0 0 5px;
    flex: 1;
    background-color: #e8f3f8;
}

input[type="text"]::placeholder {
    font-size: 18px;
}

input:focus {
    background-color: white;
    box-shadow: 0 4px 8px black
}

.btn1 {
    padding: 13px 30px;
    background-color: #FF8E4D;
    border: none;
    border-radius: 2px;
    color: white;
    font-weight: bold;
}

.btn1:hover {
    background-color: #FF8E4D;
    cursor: pointer;
}
/* 
p {
    display: inline;
    padding-left: 20px;
} */

.Location1 {
    padding-left: 50px;
    padding-top: 35px;
}

.bell {
    padding-top: 35px;
}

.bell img {
    padding-left: 20px;
}

.bell div {
    display: inline;
    position: absolute;
    padding-top: 10px;
    padding-left: 20px;
}

.bell div:hover {
    cursor: pointer;
    text-decoration: underline;
}

.Location1 a {
    color: #24A3B5;
    text-decoration: none;
}

span {
    color: #000000;
}

.Location1 a:hover {
    text-decoration: underline #24a3b5;
}

.menu a {
    text-decoration: none;
    color: black;
}

.menu {
    padding-left: 1150px;
}

.menu a:hover {
    text-decoration: underline;
}

#head2 {
    display: flex;
    justify-content: center;
}

#head2 img {
    margin-right: 10px;
}

.list {
    list-style-type: none;
    display: flex;
    gap: 15px;
    padding: 0px;
    margin-top: 15px;
}

.list li {
    color: white;
}

.nav-list .list li:hover {
    background-color: whitesmoke;
    color: #24A3B5;
    cursor: pointer;
}
