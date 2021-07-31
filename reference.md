# My HTML CSS Reference

## Footer with three sections

```html
<footer>
   <div class="footer-container">
      <div class="footer-section">
         <h3>Contact Address</h3>
         <p>
            Mohan Dev Team<br/>
            Door No 21,<br/>
            South Street<br/>
            Thiruvarur - 610001
         </p>
      </div>
      <div class="footer-section">
         <h3>Connect with us</h3>
         <p>
            <i class="fab fa-facebook"></i> Facebook<br/>
            <i class="fab fa-twitter"></i>Twitter<br/>
            <i class="fab fa-instagram"></i> Instagram
         </p>
      </div>
      <div class="footer-section">
         <h3>About us</h3>
         <p>
            Who we are<br/>
            What we do<br/>
            Contact us
         </p>
      </div>
   </div>
</footer>
```

```css
footer{
    background-color: #C3C4C5;
    height: auto;
    position: absolute;
    left: 0;
    right: 0;
    bottom: 0;
}

.footer-container {
    width: 100%;
    height: auto;
    overflow: hidden;
}

.footer-section {
    width: 33%;
    float: left;
    text-align: center;
}
```

## Navigation bar

```html
 <div class="navmenu">
   <img src="pheonix.png" alt="Bird" class="logo">
   <ul>
      <li><a href="#"><i class="fas fa-home"></i> Home</a></li>
      <li><a href="#"><i class="fas fa-project-diagram"></i> Project</a></li>
      <li><a href="#"><i class="fas fa-cogs"></i> Service</a></li>
      <li><a href="#"><i class="fas fa-running"></i> Career</a></li>
      <li><a href="#"><i class="fas fa-address-card"></i> Contact Us</a></li>
   </ul>
</div>
```

```css
.navmenu{
    background-color: blue;
    color: white;
    height: 50px;
}
.navmenu ul{
    float: right;
}
.navmenu ul li{
    display: inline;
}
.navmenu ul li a{
    text-decoration: none;
    color: white;
    text-transform: uppercase;
    padding: 80px;
}
.navmenu a:hover{
    color: red;
}
```

## Website Background with Opacity limited

```css
body::after{
    content: "";
    background: url(Engg.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    opacity: 0.3;
    top: 0;
    left: 0;
    bottom: 0;
    right: 0;
    position: absolute;
    z-index: -1;   
}
```
