# Carousel

## Carousel with Round Button


```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

    <link rel="stylesheet" type="text/css" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
    <link href="style2.css" rel="stylesheet" type="text/css">

    <title>Carousel</title>
</head>

<body>
    <div class="container">
        <div class="row">
            <div class="col-xs-12 col-lg-12 col-sm-12 col-md-12 col-xl-12">
                <div id="myCarousel" class="carousel slide" data-ride="carousel">

                    <!-- Carousel indicators -->

                    <ol class="carousel-indicators">
                        <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
                        <li data-target="#myCarousel" data-slide-to="1"></li>
                        <li data-target="#myCarousel" data-slide-to="2"></li>
                    </ol>

                    <!-- Carousel items -->

                    <div class="carousel-inner">
                        <div class="carousel-item active ">
                            <img src="service-01.jpg" class="d-block w-100" alt="First slide">
                            <div class="carousel-caption d-lg-block  d-sm-block d-md-block d-xl-block  ">
                                <h3><span>WE ARE ARCH</span><br/>YOUR BEST SOLUTION</h3>
                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.<br/>Soluta fugit similique nobis consequuntur assumenda eius sunt dicta ut</p>
                                <button type="button" class="btn btn-dark rounded-pill button-theme bg-transparent">See More</button>
                                <br>
                            </div>
                        </div>

                        <div class="carousel-item ">
                            <img src="service-01.jpg" class="d-block w-100" alt="First slide">
                            <div class="carousel-caption d-none d-block d-lg-block d-sm-block d-md-block d-xl-block ">
                                <p>ECOMMERCE INTERIOR</p>
                            </div>
                        </div>

                        <div class="carousel-item">
                            <img src="service-02.jpg" class="d-block w-100" alt="Second slide">
                            <div class="carousel-caption d-none d-block d-lg-block d-sm-block d-md-block d-xl-block">
                                <p>AGENCY INTERIOR</p>
                            </div>
                        </div>

                        <div class="carousel-item">
                            <img src="service-03.jpg" class="d-block w-100" alt="Third slide">
                            <div class="carousel-caption d-none d-block d-lg-block d-sm-block d-md-block d-xl-block ">
                                <p>RESIDENTIAL INTERIOR</p>
                            </div>
                        </div>

                    </div>

                    <!-- Left and right controls -->

                    <a class="carousel-control-prev" href="#myCarousel" role="button" data-slide="prev">
                        <span class="carousel-control-prev-icon"></span>
                    </a>
                    <a class="carousel-control-next" href="#myCarousel" role="button" data-slide="next">
                        <span class="carousel-control-next-icon"></span>
                    </a>
                </div>
            </div>
        </div>
    </div>
</body>

</html>
```

```css
.carousel-indicators li {
    width: 10px;
    height: 10px;
    border-radius: 100%;
}

.carousel-inner img {
    width: 100%;
    height: 25%;
  }

  @media only screen and (max-width: 280px) {
   
   h3{
       font-size: x-small;
   }
   p{
       font-size: xx-small;
   }
   button{
       font-size: x-small;
   }
  
}
@media only screen and (max-width: 375px) {
    h3{
        font-size: x-small;
    }
    p{
        font-size: xx-small;
    }
    button{
        font-size: x-small;
    }
   
}
@media only screen and (max-width: 414px) {
    h3{
        font-size: x-small;
    }
    p{
        font-size: xx-small;
    }
    button{
        font-size: x-small;
    }
   
}
```
