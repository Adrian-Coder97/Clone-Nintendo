# Clone-Nintendo
Pagina clon de nintendo hecha con bootstrap 5

1. Seccion navbar

![](images/demo1.png)

```
 <nav class="navbar navbar-expand-sm navbar-dark bg-danger">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">
                <img src="img/logo.jpg" alt="" width="200">
            </a>

            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
                aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon">

                </span>
            </button>

            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav ml-auto">
                    <!--ml auto (margin left) pone los elementos a la derecha-->
                    <li class="nav-item"><a class="nav-link" href="#">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Summer Pack</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">About</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Register</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Sign In</a></li>
                </ul>
            </div>
        </div>
    </nav>
```


2. Seccion imagenes (CAROUSEL)

![](images/demo2.png)

```
<div class="carousel slide" id="mainSlider" data-ride="carousel">
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="img/slide01.jpg" alt="" class="d-block w-100">
            </div>
            <div class="carousel-item">
                <img src="img/slide02.jpg" alt="" class="d-block w-100">
            </div>
            <div class="carousel-item">
                <img src="img/slide03.jpg" alt="" class="d-block w-100">
            </div>
        </div>
    </div>
```

3. Seccion ribbon 

![](images/demo3.png)


```
<div id="ribbon">
        <div id="birthday" class="container w-50 pl-5 pr-5 rounded-lg">
            <div class="row align-items-center">
                <!--ALINEAR EN EL CENTRO DEL ROW-->
                <div class="col-sm p-3">
                    <img src="img/image01.png" class="w-75 mx-auto d-block" alt="">
                </div>
                <div class="col-sm p-3 text-light text-center">
                    <p class="text-warning h3">Today is</p>
                    <h4 class="h2 text-shadow">Adrian's Birthday</h4>
                </div>
            </div>
        </div>
    </div>
```
4. Separador Amarillo y seccion games

![](images/demo4.png)

```
<!--SEPARADOR RIBBON-->
    <div id="separador-ribbon">
        <div class="content bg-warning"></div>
    </div>
    
```
```
 <!--GAMES (cards)-->
    <div id="games">
        <div class="container-md p-5">
            <div class="row pt-5">
                <h3 class="text-center pb-5 pt-5 h1">Featured Animal Crossing Games</h3>
            </div>
            <div class="row">
                <div class="col-sm">
                    <div class="card w-100 card-border mb-5">
                        <img src="img/card01.png" class="card-img-top" alt="...">
                        <div class="card-body">
                            <p class="card-text">Some quick example text to build on the card title and make up the bulk
                                of the card's content.</p>
                        </div>
                    </div>
                </div>
                <div class="col-sm">
                    <div class="card w-100 card-border mb-5">
                        <img src="img/card02.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <p class="card-text">Some quick example text to build on the card title and make up the bulk
                                of the card's content.</p>
                        </div>
                    </div>
                </div>
                <div class="col-sm">
                    <div class="card w-100 card-border mb-5">
                        <img src="img/card03.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <p class="card-text">Some quick example text to build on the card title and make up the bulk
                                of the card's content.</p>
                        </div>
                    </div>
                </div>

            </div>

            <div class="row py-5">
                <div class="col">
                    <h3 class="text-center" style="color: var(--bs-blue)">More Games at Nintendo.com</h3>
                </div>
            </div>

            <div class="row justify-content-center">
                <div class="col-3"><a href="">Nintendo Switch</a></div>
                <div class="col-3"><a href="">Nintendo 3DS</a></div>
                <div class="col-2"><a href="">Wii U</a></div>
                <div class="col-2"><a href="">Mobile</a></div>
                <div class="col-2"><a href="">Retro</a></div>
            </div>
        </div>
    </div>
    </div>
```
5. Seccion figures

![](images/demo5.png)

```
    <!--SEPARADOR AMIIBOS (borde ciculado verde)-->
    <div id="separator-amiibos">
        <div class="content bg-success"></div>
    </div>


    <!--AMIIBOS-->
    <div id="amiibos" class="px-5 pb-5 bg-success">
        <div class="container">
            <div class="row">
                <h2 class="text-center text-white text-shadow">Featured Amiibo Figures</h2>
            </div>
            <div class="row row-cols-2 row-cols-sm-2 row-cols-md-4">
                <div class="col-sm">
                    <img src="img/figure01.png" alt="" class="w-100 amiibo">
                    <div class="text-center"><span class="amiibo-name h5 p-2">Isabelle</span></div>
                </div>
                <div class="col-sm">
                    <img src="img/figure02.png" alt="" class="w-100 amiibo">
                    <div class="text-center"><span class="amiibo-name h5 p-2">Kapp'n</span></div>
                </div>
                <div class="col-sm">
                    <img src="img/figure03.png" alt="" class="w-100 amiibo">
                    <div class="text-center"><span class="amiibo-name h5 p-2">Rover</span></div>
                </div>
                <div class="col-sm">
                    <img src="img/figure04.png" alt="" class="w-100 amiibo">
                    <div class="text-center"><span class="amiibo-name h5 p-2">Timmy & Tommy</span></div>
                </div>
            </div>

            <div class="row py-5">
                <div class="col text-center">
                    <a href="" class="link-dark">
                        <button class="btn btn-warning btn-lg rounded-pill p-3 font-weight-bold">View Amiibo
                            Catalog</button>
                    </a>
                </div>
            </div>
            <div id="separator-amiibos-footer">

            </div>
        </div>
    </div>
 ```
 
 6. Seccion play nintendo 
 
 ![](images/demo6.png)
 
 ```
      <!--PLAY NINTENDO-->

    <div id="play">
        <div class="container-sm p-5">
            <div class="row">
                <h3 class="text-center h1">
                    Isabelle and friends on Play Nintendo
                </h3>
                <div class="row justify-content-center align-items-center">
                    <div class="col-3 d-none d-md-block">
                        <!--d-none es para ocultar,  d-md-block mostrara la imagen en una resolucion mas grande a md-->
                        <img src="img/isabelle.png" alt="" class="w-100">
                    </div>
                    <div class="col-9">
                        <!--CARDS DE ARRIBA-->
                        <div class="row">
                            <div class="col p-1">
                                <!--CARD-->
                                <div class="card bg-primary text-white">
                                    <div class="row g-0">
                                        <div class="col-md-6">
                                            <img src="img/ph-01.jpg" class="w-100" alt="...">
                                        </div>
                                        <div class="col-md-6">
                                            <div class="card-body">
                                                <h5 class="card-title">Card title</h5>
                                                <p class="card-text">This is a wider card with supporting text below as
                                                    a natural lead-in to additional content. This content is a little
                                                    bit longer.</p>
                                            </div>
                                        </div>
                                    </div>
                                    <!--CARD-->
                                </div>
                            </div>
                            <div class="col p-1">
                                <!--CARD-->
                                <div class="card bg-success text-white">
                                    <div class="row g-0">

                                        <div class="col-md-6">
                                            <div class="card-body">
                                                <h5 class="card-title">Card title</h5>
                                                <p class="card-text">This is a wider card with supporting text below as
                                                    a natural lead-in to additional content. This content is a little
                                                    bit longer.</p>
                                            </div>
                                        </div>
                                        <div class="col-md-6">
                                            <img src="img/ph-02.jpg" class="w-100" alt="...">
                                        </div>
                                    </div>
                                    <!--CARD-->
                                </div>
                            </div>
                        </div>

                        <!--CARDS DE ABAJO-->
                        <div class="row">
                            <div class="col p-1">
                                <!--CARD-->
                                <div class="card bg-danger text-white">
                                    <div class="row g-0">
                                        <div class="col-md-6">
                                            <img src="img/ph-03.jpg" class="w-100" alt="...">
                                        </div>
                                        <div class="col-md-6">
                                            <div class="card-body">
                                                <h5 class="card-title">Card title</h5>
                                                <p class="card-text">This is a wider card with supporting text below as
                                                    a natural lead-in to additional content. This content is a little
                                                    bit longer.</p>
                                            </div>
                                        </div>
                                    </div>
                                    <!--CARD-->
                                </div>
                            </div>
                            <div class="col p-1">
                                <!--CARD-->
                                <div class="card bg-warning text-white">
                                    <div class="row g-0">

                                        <div class="col-md-6">
                                            <div class="card-body">
                                                <h5 class="card-title">Card title</h5>
                                                <p class="card-text">This is a wider card with supporting text below as
                                                    a natural lead-in to additional content. This content is a little
                                                    bit longer.</p>
                                            </div>
                                        </div>
                                        <div class="col-md-6">
                                            <img src="img/ph-04.jpg" class="w-100" alt="...">
                                        </div>
                                    </div>
                                    <!--CARD-->
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
 ```
 7. Seccion footer

![](images/demo7.png)

 ```
 <div id="footer" class="p-5">
        <!--p-5 es un padding interior-->
        <div class="container w-50 pt-5">
            <div class="row row-cols-md-2 justify-content-md-center">
                <div class="col text-center">
                    <a href="">
                        <!--boton en bootsrarp va con a -->
                        <button class="btn btn-lg rounded-pill btn-warning w-100 p-3 shadow-sm font-weight-bold">Customer
                            Support</button>
                    </a>
                </div>
            </div>
            <div class="row justify-content-md-center py-5">
                <!--py-5 es un padding arriba y abajo-->
                <div class="col text-center font-weight-light">
                    <p>For Nintendo 3DS systems, use Parental Controls to restrict 3D mode for children 6 and under.</p>
                    <p>Internet access required for online features. For more info, go to support.nintendo.com.</p>
                    <p>Games and amiibo accessories sold separately. Figures shown not actual size. Compatibility and
                        functionality of amiibo may vary per game. Visit amiibo.com for specific details on how each
                        amiibo works.</p>
                    <p>© 2001 - 2020 Nintendo. Nintendo properties are trademarks of Nintendo.</p>
                </div>
            </div>
        </div>
    </div>
 ```
 
