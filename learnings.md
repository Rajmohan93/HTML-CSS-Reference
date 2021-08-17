# Learnings 

## Text in center of DIV

If we have only text inside the DIV, please prefer the approach 1

### Approach 1
```html
<div class="col text-center">
   <div>some content</div>
</div>
```

### Approach 2

```html
<div class="d-flex justify-content-center">
   <div>some content</div>
</div>
```
## Remove Gap between col in Bootstrap

```html
<div class="container-fluid mt-5">
        <div class="row no-gutters">
            <div class="col-lg-3 col-sm-6">
                <img src="latest-project-01.jpg" alt="latest-photo" width="100%" height="235px">
            </div>
            <div class="col-lg-3 col-sm-6">
                <img src="latest-project-02.jpg" alt="latest-photo" width="100%" height="235px">
            </div>
            <div class="col-lg-3 col-sm-6">
                <img src="latest-project-03.jpg" alt="latest-photo" width="100%" height="235px">
            </div>
            <div class="col-lg-3 col-sm-6">
                <img src="latest-project-07.jpg" alt="latest-photo" width="100%" height="235px">
            </div>
            <div class="col-lg-3 col-sm-6">
                <img src="latest-project-04.jpg" alt="latest-photo" width="100%" height="235px">
            </div>
            <div class="col-lg-3 col-sm-6">
                <img src="latest-project-05.jpg" alt="latest-photo" width="100%" height="235px">
            </div>
            <div class="col-lg-3 col-sm-6">
                <img src="latest-project-06.jpg" alt="latest-photo" width="100%" height="235px">
            </div>
            <div class="col-lg-3 col-sm-6">
                <img src="latest-project-06.jpg" alt="latest-photo" width="100%" height="235px">
            </div>
        </div>
    </div>
```
