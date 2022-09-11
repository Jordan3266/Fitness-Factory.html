# Fitness-Factory.html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fitness Factory Gym</title>
</head>
<link href="https://fonts.googleapis.com/css2?family=Baloo+2&display=swap" rel="stylesheet">
<link rel="stylesheet" href="style.css">
<style>
    /* css reset */
    body {
        font-family: 'Baloo 2', cursive;
        color: white;
        margin: 0px;
        padding: 0px;
        background: url('img/gym.jpg');
        
    }

    .left {
        display: inline-block;
        position: absolute;
        left: 40px;
        top: 16px;
    }

    .left img {
        width: 136px;
        filter: invert(100%);
    }

    .left div {
        line-height: 19px;
        font-size: 20px;
        text-align: center;
        font-style: bold;
    }

    .mid {
        display: block;
        width: 36%;
        margin: 12px auto;

    }

    .right {
        position: absolute;
        right: 40px;
        top: 16px;
        display: inline-block;

    }

    .navbar {
        display: inline-block;

    }

    .navbar li {
        display: inline-block;
        font-size: 15px;

    }

    .navbar li a {
        color: white;
        text-decoration: none;
        padding: 34px 23px;
    }

    .navbar li a:hover,
    .navbar li a:active {
        text-decoration: underline;
        color: red;
    }

    .btn {
        font-family: 'Baloo 2', cursive;
        margin: 0px 9px;
        padding: 4px 14px;
        border-radius: 10px;
        border: 2px solid grey;
        cursor: pointer;
    }

    .btn:hover {
        background-color: red;
    }

    .container {
        border: 2px solid white
        margin: 106px 80px;
        padding: 70px;
        width: 33%;
        border-radius: 28px;
    }

    .formgroup input {
        text-align: center;
        display: block;
        width: 34px;
        padding: 6px;
        border: 2px solid red;
        margin: 110px auto;
        font-family: 'Baloo 2', cursive;
    }

    .container h1 {
        text-align: center;
    }

    .container button {
        display: block;
        width: 23%;
        margin: auto;
    }

    .container button {
        display: block;
        width: 40%;
        margin: 20px auto;
    }
</style>

<body>
    <header class="header">
        <!-- left box for logo -->
        <div class="left">
            <img src="img/barbell.jpg" alt="">
            <div>Fitness Factory</div>
        </div>
        <!-- mid box for navbar -->
        <div class="mid">
            <ul class="navbar">
                <li><a href="#" class="active">Home</a></li>
                <li><a href="#">About Us</a></li>
                <li><a href="#"> Contact Us</a></li>
                <li><a href="#">Fitness Calculator</a></li>

            </ul>
        </div>
        <!-- right box for butons -->
        <div class="right">
            <button class="btn">Log In</button>
            <button class="btn">Email</button>
            <button class="btn">Call Us</button>
        </div>
    </header>
    <div class="container">
        <h1>Join the best gym of Bokaro now</h1>
        <form action="noaction.php">
            <div class="form group">
                <input type="tel" name="" placeholder="Enter your Name">
                <input type="tel" name="" placeholder="Enter  Phone no.">
                <input type="tel" name="" placeholder="Enter your Gender">
                <input type="tel" name="" placeholder="Enter your Email">
            </div>
            <button class="btn">Submit</button>
        </form>
    </div>
</body>

</html>
