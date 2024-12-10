<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>responsive coffee heaven website</title>
    <!-- font awesome cdn link -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">

    <!-- custon css file link -->
    <link rel="stylesheet" href="style.css">

</head>
<body>
    
<!-- header section starts -->

<header class="header">
    <a href="#" class="logo">
        <img src="logo1.png.jpg" alt="">
    </a>

    <nav class="navbar">
        <a href="#home">home</a>
        <a href="#about">about</a>
        <a href="#menu">menu</a>
        <a href="#products">products</a>
        <a href="#review">review</a>
        <a href="#contact">contact</a>
        <a href="#blogs">blogs</a>

    </nav>

    <div class="icons">
        <div class="fas fa-search" id="search-btn"></div>
        <div class="fas fa-shopping-cart" id="cart-btn"></div>
        <div class="fas fa-bars" id="menu-btn"></div>
    </div>

    <div class="search-form">
        <input type="search" id="search-box" placeholder="search here...">
        <label for="search-box" class="fas fa-search"></label>
    </div>


    <div class="cart-items-container">

        <div class="cart-item">
            <span class="fas fa-times"></span>
            <img src="cart1.png" alt="">
            <div class="content">
                <h3>cart item 01</h3>
                <div class="price">$15.99/-</div>
            </div>
        </div>    

        <div class="cart-item">
            <span class="fas fa-times"></span>
            <img src="cart2.png" alt="">
            <div class="content">
                <h3>cart item 02</h3>
                <div class="price">$15.99/-</div>
            </div>
        </div>

        <div class="cart-item">
            <span class="fas fa-times"></span>
            <img src="cart3.png" alt="">
            <div class="content">
                <h3>cart item 03</h3>
                <div class="price">$15.99/-</div>
            </div>
        </div>


                <a href="#" class="btn">checkout now</a>
    </div>

</header>
<!-- header section ends -->

<!-- home section starts -->

<section class="home" id="home">

    <div class="content">
        <h3>fresh coffee in the morning</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Laudantium exercitationem reiciendis consectetur, tenetur id tempora!</p>
        <a href="#" class="btn">get yours now</a>
    </div>
</section>


<!-- home section ends -->

<!-- about section starts -->

<section class="about" id="about">
    <h1 class="heading"> <span>about</span> us </h1>

    <div class="row">

        <div class="image">
            <img src="about.png" alt="">
        </div>

        <div class="content">
            <h3>what makes our coffee special</h3>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Tempore sit quidem commodi repudiandae. Commodi impedit dolorem pariatur, harum aut excepturi voluptates repellendus labore facilis rem? Veritatis eos necessitatibus delectus asperiores!</p>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nihil architecto aut placeat? Consectetur sit recusandae dignissimos beatae at ut tempore?</p>
            <a href="#" class="btn">learn more</a>
        </div>
    </div>

</section>

<!-- about section ends -->


<!-- menu section starts -->


<section class="menu" id="menu">

    <h1 class="heading"> our <span>menu</span> </h1>

    <div class="box-container">

        <div class="box">

            <img src="blackcoffee.png" alt="">
            <h3>tasty and healthy</h3>
            <div class="price">$15.99 <span>20.99</span></div>
            <a href="#" class="btn">add to cart</a>
        </div>



        <div class="box">

            <img src= "Cappuccino.png" alt="">
            <h3>tasty and healthy</h3>
            <div class="price">$15.99 <span>20.99</span></div>
            <a href="#" class="btn">add to cart</a>
        </div>


        <div class="box">

            <img src= "espresso.png" alt="">
            <h3>tasty and healthy</h3>
            <div class="price">$15.99 <span>20.99</span></div>
            <a href="#" class="btn">add to cart</a>
        </div>

        <div class="box">

            <img src= "latte2.png" alt="">
            <h3>tasty and healthy</h3>
            <div class="price">$15.99 <span>20.99</span></div>
            <a href="#" class="btn">add to cart</a>
        </div>

        <div class="box">

            <img src= "Iced-Americano.png" alt="">
            <h3>tasty and healthy</h3>
            <div class="price">$15.99 <span>20.99</span></div>
            <a href="#" class="btn">add to cart</a>
        </div>

        <div class="box">

            <img src= "frappe.png" alt="">
            <h3>tasty and healthy</h3>
            <div class="price">$15.99 <span>20.99</span></div>
            <a href="#" class="btn">add to cart</a>
        </div>


    </div>

</section>



<!-- menu section ends -->

<!-- product section starts -->


<section class="products" id="products">

    <h1 class="heading"> our <span>products</span></h1>

    <div class="box-container">

        <div class="box">
            <div class="icons">
                <a href="#" class="fas fa-shopping-cart"></a>
                <a href="#" class="fas fa-heart"></a>
                <a href="#" class="fas fa-eye"></a>
            </div>
            <div class="image">
                <img src="product1.png.jpg" alt="">
            </div>

            <div class="content">

            <h3>fresh coffee</h3>
            <div class="stars">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star-half-alt"></i>
            </div>
            <div class="price">$15.99 <span>$20.99</span></div>
            </div>
        </div>



        <div class="box">
            <div class="icons">
                <a href="#" class="fas fa-shopping-cart"></a>
                <a href="#" class="fas fa-heart"></a>
                <a href="#" class="fas fa-eye"></a>
            </div>
            <div class="image">
                <img src="product2.png.jpg" alt="">
            </div>

            <div class="content">

            <h3>fresh coffee</h3>
            <div class="stars">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star-half-alt"></i>
            </div>
            <div class="price">$15.99 <span>$20.99</span></div>
            </div>
        </div>

        <div class="box">
            <div class="icons">
                <a href="#" class="fas fa-shopping-cart"></a>
                <a href="#" class="fas fa-heart"></a>
                <a href="#" class="fas fa-eye"></a>
            </div>
            <div class="image">
                <img src="product3.png.jpg" alt="">
            </div>

            <div class="content">

            <h3>fresh coffee</h3>
            <div class="stars">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star-half-alt"></i>
            </div>
            <div class="price">$15.99 <span>$20.99</span></div>
            </div>
        </div>


    </div>
</section>

<!-- product section ends -->


<!-- review section starts -->

<section class="review" id="review">

    <h1 class="heading"> customer's <span>review</span></h1>

    <div class="box-container">

        <div class="box"> 

            <img src="reviewlogo.png" alt="" class="quote">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Temporibus, corporis expedita! Deleniti alias magnam nihil numquam suscipit omnis nemo quam quia esse quis labore, natus quaerat totam sunt! Atque, dignissimos.</p>
            <img src="person1.png" class="user" alt="">
            <h3>john deo</h3>
            <div class="stars">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star-half-alt"></i>
            </div>

        </div>

        <div class="box"> 

            <img src="reviewlogo.png" alt="" class="quote">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Temporibus, corporis expedita! Deleniti alias magnam nihil numquam suscipit omnis nemo quam quia esse quis labore, natus quaerat totam sunt! Atque, dignissimos.</p>
            <img src="person2.png" class="user" alt="">
            <h3>clark wilson</h3>
            <div class="stars">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star-half-alt"></i>
            </div>

        </div>

        <div class="box"> 

            <img src="reviewlogo.png" alt="" class="quote">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Temporibus, corporis expedita! Deleniti alias magnam nihil numquam suscipit omnis nemo quam quia esse quis labore, natus quaerat totam sunt! Atque, dignissimos.</p>
            <img src="person3.png" class="user" alt="">
            <h3>francesca taylor</h3>
            <div class="stars">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star-half-alt"></i>
            </div>

        </div>



    </div>

</section>


<!-- review section ends -->

<!-- contact section starts -->

<section class="contact" id="contact">

    <h1 class="heading"> <span>contact</span> us </h1>

    <div class="row">

        <iframe class="map" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d14319.002356274814!2d78.19112565!3d26.204790449999997!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3976c41cad36d4ef%3A0xa8a44d5fbc80c4a3!2sCity%20Center%2C%20Jiwaji%20University%2C%20Mahalgaon%2C%20Gwalior%2C%20Madhya%20Pradesh!5e0!3m2!1sen!2sin!4v1697794566962!5m2!1sen!2sin"  allowfullscreen="" loading="lazy"></iframe>

        <form action="">
            <h3>get in touch</h3>
            <div class="inputBox">
                <span class="fas fa-user"></span>
                <input type="text" placeholder="name">
            </div>

            <div class="inputBox">
                <span class="fas fa-user"></span>
                <input type="email" placeholder="email">
            </div>

            <div class="inputBox">
                <span class="fas fa-user"></span>
                <input type="number" placeholder="number">
            </div>
            <input type="submit" value="contact now" class="btn">

        </form>


    </div>

</section>
<!--contact section ends here-->

<!--blogs section starts-->
<section class="blogs" id="blogs">
    <h1 class="heading"> our <span>blogs</span></h1>
    <div class="box-container">
        <div class="box">
            <div class="image">
                <img src="blog1.png" alt="">
            </div>
            <div class="content">
                <a href="#" class="title">tasty and refreshing coffee</a>
                <span>by admin / 25th october,2023</span>
                <p>Lorem, ipsum dolor sit amet consectetur adipi sicingelit. Deserunt, magnam?</p>
                <a href="#" class="btn"> read more</a>
            </div>

        </div>
        <div class="box">
            <div class="image">
                <img src="blog2.png" alt="">
            </div>
            <div class="content">
                <a href="#" class="title">tasty and refreshing coffee</a>
                <span>by admin / 25th october,2023</span>
                <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Deserunt, magnam?</p>
                <a href="#" class="btn"> read more</a>
            </div>

        </div>
        <div class="box">
            <div class="image">
                <img src="blog3.png" alt="">
            </div>
            <div class="content">
                <a href="#" class="title">tasty and refreshing coffee</a>
                <span>by admin / 25th october,2023</span>
                <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Deserunt, magnam?</p>
                <a href="#" class="btn"> read more</a>
            </div>

        </div>
        <div class="box">
            <div class="image">
                <img src="blog4.png" alt="">
            </div>
            <div class="content">
                <a href="#" class="title">tasty and refreshing coffee</a>
                <span>by admin / 25th october,2023</span>
                <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Deserunt, magnam?</p>
                <a href="#" class="btn"> read more</a>
            </div>

        </div>
    </div>

</section>
<!--blogs section ends here-->

<!--footer section starts-->

<section class="footer">
    <div class="share">
        <a href="#" class="fab fa-facebook-f"></a>
        <a href="#" class="fab fa-twitter"></a>
        <a href="#" class="fab fa-instagram"></a>
        <a href="#" class="fab fa-linkedin"></a>
        <a href="#" class="fab fa-pinterest"></a>
        

    </div>
    <div class="links">
        <a href="#">home</a>
        <a href="#">about</a>
        <a href="#">menu</a>
        <a href="#">products</a>
        <a href="#">review</a>
        <a href="#">contact us</a>
        <a href="#">blogs</a>
    </div>
    <div class="credit"> created by<span> mrs.web designer</span> | all rights reserved</div>
</section>
<!--footer section ends here-->



<!-- contact section ends -->



    <!-- custom js file link -->
<script src="script.js"></script>

</body>
</html>
