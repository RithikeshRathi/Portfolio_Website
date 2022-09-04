<?php
    $insert = false;
    if(isset($_POST['name'])){
        $server = "localhost";
        $username = "root";
        $password = "";

        $conn = mysqli_connect($server,$username,$password);

    if(!$conn){
        die("connection to this database failed due to".mysqli_connect_error());
    }
    echo "conneted to db";
    $name = $_POST['name'];
    $email = $_POST['email'];
    $phone = $_POST['phone'];
    $info = $_POST['info'];

    $sql = "INSERT INTO `portfolio_contact`.`contact-info` (`name`, `email`, `phone`, `info`) VALUES ('$name', '$email', '$phone', '$info');";

    if($conn -> query($sql) == true){
        $insert = true;
    }
    else{
        echo "ERROR: $sql <br> $conn->error";
    }
    $conn->close();
    }    
?>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rithikesh Rathi</title>

    <!-- font awesome cdn link  -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.2/css/all.min.css">

    <!-- custom css file link  -->
    <link rel="stylesheet" href="style.css">

</head>
<body>
    
<!-- header section starts  -->

<header>

    <div class="user">
        <img src="images/rathi1.jpeg" alt="">
        <h3 class="name">Rithikesh Rathi</h3>
        <p class="post">full stack developer</p>
    </div>

    <nav class="navbar">
        <ul>
            <li><a href="#home">home</a></li>
            <li><a href="#about">about</a></li>
            <li><a href="#education">education</a></li>
            <li><a href="#portfolio">portfolio</a></li>
            <li><a href="#contact">contact</a></li>
        </ul>
    </nav>

</header>

<!-- header section ends -->

<div id="menu" class="fas fa-bars"></div>

<!-- home section starts  -->

<section class="home" id="home">

    <h3>HI THERE !</h3>
    <h1>I'M <span>Rithikesh Rathi</span></h1>
    <p>I am a full stack web developer and a content creator.
    </p>
    <a href="#about"><button class="btn">about me <i class="fas fa-user"></i></button></a>

</section>

<!-- home section ends -->

<!-- about section starts  -->

<section class="about" id="about">

<h1 class="heading"> <span>about</span> me </h1>

<div class="row">

    <div class="info">
        <h3> <span> name : </span> Rithikesh Rathi </h3>
        <h3> <span> age : </span> 19 </h3>        
        <h3> <span> college : </span> NSUT </h3>        
        <h3> <span> post : </span> full stack developer </h3>
        
        <a href="#"><button class="btn"> download CV <i class="fas fa-download"></i> </button></a>
    </div>

    <div class="counter">

        <div class="box">
            <span>1+</span>
            <h3>years of experience</h3>
        </div>

        <div class="box">
            <span>3</span>
            <h3>project completed</h3>
        </div>

        <div class="box">
            <span>1+</span>
            <h3>happy clients</h3>
        </div>

        <div class="box">
            <span>6+</span>
            <h3>certificates won</h3>
        </div>

    </div>

</div>

</section>

<!-- about section ends -->

<!-- education section starts  -->

<section class="education" id="education">

<h1 class="heading"> my <span>education</span> </h1>

<div class="box-container">

    <div class="box">
        <i class="fas fa-graduation-cap"></i>
        <span>2019</span>
        <h3>Class 10th</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Obcaecati quos alias praesentium. Id autem provident laborum quae, distinctio eaque temporibus!</p>
    </div>

    <div class="box">
        <i class="fas fa-graduation-cap"></i>
        <span>2021</span>
        <h3>Class 12th</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Obcaecati quos alias praesentium. Id autem provident laborum quae, distinctio eaque temporibus!</p>
    </div>

    <div class="box">
        <i class="fas fa-graduation-cap"></i>
        <span>2021</span>
        <h3>JEE Mains and Advanced</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Obcaecati quos alias praesentium. Id autem provident laborum quae, distinctio eaque temporibus!</p>
    </div>

    <div class="box">
        <i class="fas fa-graduation-cap"></i>
        <span>2021</span>
        <h3>front end development</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Obcaecati quos alias praesentium. Id autem provident laborum quae, distinctio eaque temporibus!</p>
    </div>

    <div class="box">
        <i class="fas fa-graduation-cap"></i>
        <span>2022</span>
        <h3>back end development</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Obcaecati quos alias praesentium. Id autem provident laborum quae, distinctio eaque temporibus!</p>
    </div>

    <div class="box">
        <i class="fas fa-graduation-cap"></i>
        <span>2022</span>
        <h3>full stack development</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Obcaecati quos alias praesentium. Id autem provident laborum quae, distinctio eaque temporibus!</p>
    </div>

</div>

</section>

<!-- education section ends -->

<!-- portfolio section starts  -->

<section class="portfolio" id="portfolio">

<h1 class="heading"> my <span>portfolio</span> </h1>

<div class="box-container">

    <div class="box">
        <img src="images/html.webp" alt="">
    </div>

    <div class="box">
        <img src="images/css.webp" alt="">
    </div>

    <div class="box">
        <img src="images/images.jpg" alt="">
    </div>

    <div class="box">
        <img src="images/php.png" alt="">
    </div>

    <div class="box">
        <img src="images/react.png" alt="">
    </div>

    <div class="box">
        <img src="images/pyhton.png" alt="">
    </div>

</div>

</section>

<!-- portfolio section ends -->

<!-- contact section starts  -->

<section class="contact" id="contact">

<h1 class="heading"> <span>contact</span> me </h1>

<div class="row">

    <div class="content">

        <h3 class="title">contact info</h3>

        <div class="info">
            <h3> <i class="fas fa-envelope"></i><a href="mailto:rithikesh0501@gmail.com" target="_blank" style = "color:#eee">email us</a> </h3>
            <h3> <i class="fas fa-phone"></i> (+91) 9999999999 </h3>
            <h3> <i class="fas fa-phone"></i> (+91) 9888888888</h3>
            <h3> <i class="fas fa-map-marker-alt"></i> Gurgaon, india - 122022. </h3>
        </div>

    </div>

    <form action="./contact.php" method="post" >

        <input type="text" name="name" id="name" placeholder="name" class="box">
        <input type="email" name="email" id="email" placeholder="email" class="box">
        <input type="tel" name="phone" id="phone" placeholder="phone" class="box" minlength="10">
        <textarea name="info" id="info" cols="30" rows="10" class="box message" placeholder="message"></textarea>
        <button type="submit" name="submit" id="submit form_submit" class="btn"> send <i class="fas fa-paper-plane"></i> </button>

        <?php
        if($insert == true){
           echo "<p style = 'color: green; font-size:2rem;'>Successfully submitted to database</p>";
        }
        
        ?>
    </form>

</div>

</section>

<!-- contact section ends -->


<!-- scroll top button  -->

<a href="#home" class="top">
    <img src="images/scroll-top-img.png" alt="">
</a>















<!-- jquery cdn link  -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>

<!-- custom js file link  -->
<script src="script.js"></script>


</body>
</html>



