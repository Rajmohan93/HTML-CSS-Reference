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
