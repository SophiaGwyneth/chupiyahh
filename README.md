<!DOCTYPE html>
<html lang="en">
<head>
    <title>TECHkid</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css" integrity="sha512-Kc323vGBEqzTmouAECnVceyQqyqdsSiqLQISBL29aUW4U/M7pSPA/gEUZQqv1cwx4OnYxTxve5UMg5GT6L4JJg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css">
    <link rel="stylesheet" href="style.css">
    <link rel="shortcut icon" type="image/x-icon" href="tech.png" />
</head>
<body>
    <nav>
            <ul class="sidebar">
                <li onclick=hideSidebar()><a><svg xmlns="http://www.w3.org/2000/svg" height="26px" viewBox="0 -960 960 960" width="26px" fill="#FFFFFF"><path d="m256-200-56-56 224-224-224-224 56-56 224 224 224-224 56 56-224 224 224 224-56 56-224-224-224 224Z"/></svg></a></li>
                <li><a href="#">Home</a></li>
                <li><a href="login.html">Sign Up</a></li>
                <li><a href="login.html">Login</a></li>
            </ul>
            
            <ul>
                <li><a href="index.html">Techkid</a></li>
                <div class="search-container">
                    <input type="text" placeholder="Search...">
                    <i class="fa fa-search"></i>
                </div>
                <li class="hideOnMobile"><a href="#">Home</a></li>
                <li class="hideOnMobile"><a href="login.html">Sign Up</a></li>
                <li class="hideOnMobile"><a href="login.html">Login</a></li>
                <li onclick=showSidebar()><a><svg xmlns="http://www.w3.org/2000/svg" height="26px" viewBox="0 -960 960 960" width="26px" fill="#FFFFFF"><path d="M120-240v-80h720v80H120Zm0-200v-80h720v80H120Zm0-200v-80h720v80H120Z"/></svg></a></li>
            </ul>
    </nav>

    <div class="carousels carousel-dark slide" id="carouselDemo" data-bs-wrap="true" data-bs-ride="carousel">
        <div class="carousel-inner">
            <div class="carousel-item active" data-bs-interval="2000">
                <img src="slider1.png" class="w-100">
            </div>

            <div class="carousel-item ">
                <img src="slider2.png" class="w-100">
            </div>

            <div class="carousel-item ">
                <img src="slider3.png" class="w-100">
            </div>
        </div>

        <button class="carousel-control-prev" type="button" data-bs-target="#carouselDemo" data-bs-slide="prev">
            <span class="carousel-control-prev-icon"></span>
        </button>

        <button class="carousel-control-next" type="button" data-bs-target="#carouselDemo" data-bs-slide="next">
            <span class="carousel-control-next-icon"></span>
        </button>

    </div>

    <section class="product"> 
        <h1 class="product-category">Deals</h1>
        <button class="pre-btn"><img src="arrow.png" alt=""></button>
        <button class="nxt-btn"><img src="arrow.png" alt=""></button>
        <div class="product-container">
            <div class="product-card">
                <div class="product-image">
                    <span class="discount-tag">8% off</span>
                    <img src="image1.png" class="product-thumb" alt="">
                    <button class="card-btn">Add to wishlist</button>
                </div>
                <div class="product-info">
                    <h3 class="product-brand">Iphone 16 Pro</h3>
                    <p class="product-short-description">Limited Stock</p>
                    <span class="price">₱78,190.80</span><span class="actual-price">₱84,990.00</span>
                </div>
            </div>
            <div class="product-card">
                <div class="product-image">
                    <span class="discount-tag">9% off</span>
                    <img src="image2.png" class="product-thumb" alt="">
                    <button class="card-btn">Add to wishlist</button>
                </div>
                <div class="product-info">
                    <h3 class="product-brand">Iphone 14</h3>
                    <p class="product-short-description">In Stock</p>
                    <span class="price">₱37,300.90</span><span class="actual-price">₱40,990.00</span>
                </div>
            </div>
            <div class="product-card">
                <div class="product-image">
                    <span class="discount-tag">14% off</span>
                    <img src="image3.png" class="product-thumb" alt="">
                    <button class="card-btn">Add to wishlist</button>
                </div>
                <div class="product-info">
                    <h3 class="product-brand">Iphone SE</h3>
                    <p class="product-short-description">In Stock</p>
                    <span class="price">₱28,371.40</span><span class="actual-price">₱32,990.00</span>
                </div>
            </div>
            <div class="product-card">
                <div class="product-image">
                    <span class="discount-tag">5% off</span>
                    <img src="image4.png" class="product-thumb" alt="">
                    <button class="card-btn">Add to wishlist</button>
                </div>
                <div class="product-info">
                    <h3 class="product-brand">Vivo Y19s</h3>
                    <p class="product-short-description">Limited Stocks</p>
                    <span class="price">₱10,449.05</span><span class="actual-price">₱10,999.00</span>
                </div>
            </div>
            <div class="product-card">
                <div class="product-image">
                    <span class="discount-tag">5% off</span>
                    <img src="image5.png" class="product-thumb" alt="">
                    <button class="card-btn">Add to wishlist</button>
                </div>
                <div class="product-info">
                    <h3 class="product-brand">Ipad Mini</h3>
                    <p class="product-short-description">In Stock</p>
                    <span class="price">₱31,340.50</span><span class="actual-price">₱32,990.00</span>
                </div>
            </div>
            <div class="product-card">
                <div class="product-image">
                    <span class="discount-tag">2% off</span>
                    <img src="image6.png" class="product-thumb" alt="">
                    <button class="card-btn">Add to wishlist</button>
                </div>
                <div class="product-info">
                    <h3 class="product-brand">Apple Air Tag</h3>
                    <p class="product-short-description">Out of Stock</p>
                    <span class="price">₱1852.20</span><span class="actual-price">₱1890.00</span>
                </div>
            </div>
            <div class="product-card">
                <div class="product-image">
                    <span class="discount-tag">10% off</span>
                    <img src="image7.png" class="product-thumb" alt="">
                    <button class="card-btn">Add to wishlist</button>
                </div>
                <div class="product-info">
                    <h3 class="product-brand">Xiaomi 13T Pro</h3>
                    <p class="product-short-description">In Stock</p>
                    <span class="price">₱34,199.10</span><span class="actual-price">₱37,999.00</span>
                </div>
            </div>
            <div class="product-card">
                <div class="product-image">
                    <span class="discount-tag">10% off</span>
                    <img src="image8.png" class="product-thumb" alt="">
                    <button class="card-btn">Add to wishlist</button>
                </div>
                <div class="product-info">
                    <h3 class="product-brand">Oppo A60</h3>
                    <p class="product-short-description">In Stock</p>
                    <span class="price">₱8,999.10</span><span class="actual-price">₱9,999.00</span>
                </div>
            </div>
            <div class="product-card">
                <div class="product-image">
                    <span class="discount-tag">5% off</span>
                    <img src="image9.png" class="product-thumb" alt="">
                    <button class="card-btn">Add to wishlist</button>
                </div>
                <div class="product-info">
                    <h3 class="product-brand">Samsung S21</h3>
                    <p class="product-short-description">Limited Stock</p>
                    <span class="price">₱45,590.50</span><span class="actual-price">₱47,990.00</span>
                </div>
            </div>
            <div class="product-card">
                <div class="product-image">
                    <span class="discount-tag">5% off</span>
                    <img src="image10.png" class="product-thumb" alt="">
                    <button class="card-btn">Add to wishlist</button>
                </div>
                <div class="product-info">
                    <h3 class="product-brand">Redmi 13 Pro</h3>
                    <p class="product-short-description">In Stock</p>
                    <span class="price">₱17,479.08</span><span class="actual-price">₱18,999.00</span>
                </div>
            </div>
        </div>
    </section>

    <main>
        <section class="carousel next">
            <div class="list">
                <article class="item other_1">
                    <div class="main-content" 
                    style="background-color: #e2c4a8;">
                        <div class="content">
                            <h2>Iphone 16 Pro</h2>
                            <p class="price">₱78,190.80</p>
                            <p class="description">
                                Dimensions:	149.6 x 71.5 x 8.3 mm (5.89 x 2.81 x 0.33 in) <br>
                                Type:	    LTPO Super Retina XDR OLED, 120Hz, HDR10, Dolby Vision, 1000 nits (typ), 2000 nits (HBM) <br>
                                OS: 	        iOS 18 <br>
                                Chipset:	    Apple A18 Pro (3 nm) <br>                           
                            </p>
                            <button class="addToCard">
                                Add To Cart
                            </button>
                        </div>
                    </div>
                    <figure class="image">
                        <img src="pic1.png" alt="">
                        <figcaption>Iphone 16 Pro</figcaption>
                    </figure>
                </article>
                <article class="item active">
                    <div class="main-content" 
                    style="background-color: #f5bfaf;">
                        <div class="content">
                            <h2>Vivo Y19s</h2>
                            <p class="price">₱10,449.05</p>
                            <p class="description">
                                Dimensions:	165.8 x 76.1 x 8.1 mm (6.53 x 3.00 x 0.32 in) <br>
                                Type:	    IPS LCD, 90Hz, 1000 nits (HBM) <br>
                                OS:	        Android 14, Funtouch 14 <br>
                                Chipset:	    Unisoc Tiger T612 (12 nm)  
                            </p>
                            <button class="addToCard">
                                Add To Cart
                            </button>
                        </div>
                    </div>
                    <figure class="image">
                        <img src="image4.png" alt="">
                        <figcaption>Vivo Y19s</figcaption>
                    </figure>
                </article>
                <article class="item other_2">
                    <div class="main-content" 
                    style="background-color: #dedfe1;">
                        <div class="content">
                            <h2>Xiaomi 13T Pro</h2>
                            <p class="price">₱34,199.10</p>
                            <p class="description">
                                Dimensions:	162.2 x 75.7 x 8.5 mm (6.39 x 2.98 x 0.33 in) <br>
                                Type:	    AMOLED, 68B colors, 144Hz, Dolby Vision, HDR10+ <br>
                                OS:	        Android 13, up to 4 major Android upgrades, HyperOS <br>
                                Chipset:	    Mediatek Dimensity 9200+ (4 nm)
                            </p>
                            <button class="addToCard">
                                Add To Cart
                            </button>
                        </div>
                    </div>
                    <figure class="image">
                        <img src="image7.png" alt="">
                        <figcaption>Xiaomi 13T Pro</figcaption>
                    </figure>
                </article>
                <article class="item">
                    <div class="main-content" 
                    style="background-color: #8cc091;">
                        <div class="content">
                            <h2>Iphone SE</h2>
                            <p class="price">₱28,371.40</p>
                            <p class="description">
                                Dimensions:	138.4 x 67.3 x 7.3 mm (5.45 x 2.65 x 0.29 in) <br>
                                Type:	    Retina IPS LCD, 625 nits <br>
                                OS:	        iOS 13, upgradable to iOS 18 <br>
                                Chipset:	    Apple A13 Bionic (7 nm+) <br>
                            </p>
                            <button class="addToCard">
                                Add To Cart
                            </button>
                        </div>
                    </div>
                    <figure class="image">
                        <img src="pic2.png" alt="">
                        <figcaption>Iphone SE</figcaption>
                    </figure>
                </article>
            </div>
            <div class="arrows">
                <button id="prev"><</button>
                <button id="next">></button>
            </div>
        </section>
    </main>

    <div class="contain">
        <form class="filter">
            <div class="item">
                <label for="">Category</label>
                <select name="category">
                    <option value="">---</option>
                    <option value="Phone">Phone</option>
                    <option value="Tablet">Tablet</option>
                    <option value="Accessories">Accessories</option>
                </select>
            </div>
            <div class="item">
                <label for="">Deals</label>
                <select name="promo">
                    <option value="">---</option>
                    <option value="one">1-5%</option>
                    <option value="two">6-10%</option>
                    <option value="three">10% Above</option>
                </select>
            </div>
            <div class="item">
                <label for="">Name</label>
                <input name="name" type="text">
            </div>
            <div class="item">
                <label for="">Min Price</label>
                <input name="minPrice" type="number">
            </div>
            <div class="item">
                <label for="">Max Price</label>
                <input name="maxPrice" type="number">
            </div>
            <div class="item submit">
                <button>Search</button>
            </div>
        </form>
        <div class="countResults">
            Found <b id="count">5</b> results
        </div>
        <div id="list">
            <div class="item">
                <img src="image1.png">
                <div class="title">Iphone 16 Pro</div>
                <div class="price">₱78,190.80</div>
            </div>
            <div class="item">
                <img src="image2.png">
                <div class="title">Iphone 14</div>
                <div class="price">₱37,300.90</div>
            </div>
            <div class="item">
                <img src="image3.png">
                <div class="title">Iphone SE</div>
                <div class="price">₱28,371.40</div>
            </div>
            <div class="item">
                <img src="image4.png">
                <div class="title">Vivo Y19s</div>
                <div class="price">₱10,449.05</div>
            </div>
            <div class="item">
                <img src="image5.png">
                <div class="title">Ipad Mini</div>
                <div class="price">₱31,340.50</div>
            </div>
            <div class="item">
                <img src="image6.png">
                <div class="title">Apple Air Tag</div>
                <div class="price">₱1852.20</div>
            </div>
            <div class="item">
                <img src="image7.png">
                <div class="title">Xiaomi 13T Pro</div>
                <div class="price">₱34,199.10</div>
            </div>
            <div class="item">
                <img src="image8.png">
                <div class="title">Oppo A60</div>
                <div class="price">₱8,999.10</div>
            </div>
            <div class="item">
                <img src="image9.png">
                <div class="title">Samsung A24</div>
                <div class="price">₱17590.50</div>
            </div>
            <div class="item">
                <img src="image10.png">
                <div class="title">Iphone 16</div>
                <div class="price">₱56479.08</div>
            </div>
        </div>
    </div>

    <section class="footer">
        <div class="social">
            <a href="https://www.instagram.com/prdx_invaderrr7/"><i class="fab fa-instagram"></i></a>
            <a href="https://x.com/sunoohaven624"><i class="fab fa-twitter"></i></a>
            <a href="https://www.facebook.com/profile.php?id=100006323432636"><i class="fab fa-facebook-f"></i></a>
        </div>
        <ul class="list">
            <li>
                <a href="#">Home</a>
            </li>
            <li>
                <a href="#">Terms</a>
            </li>
            <li>
                <a href="#">Privacy Policy</a>
            </li>
        </ul>
        <p class="copyright">
            Sponsored by Google
        </p>
    </section>


<script src="filter.js"></script>
<script src="app.js"></script>
<script src="script.js"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.min.js"></script>
<script>
    function showSidebar(){
        const sidebar = document.querySelector('.sidebar')
        sidebar.style.display = 'flex'
    }
    function hideSidebar(){
        const sidebar = document.querySelector('.sidebar')
        sidebar.style.display = 'none'
    }
</script>
        
   


   
</body>
</html>
