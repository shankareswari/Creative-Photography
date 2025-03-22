# Creative-Photography
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Creative Photography Studio</title>
    <style>
        body {
            background-image: url(https://fastly.picsum.photos/id/454/4403/2476.jpg?hmac=pubXcBaPumNk0jElL63xrQYiSwQWA_DtS8uNNV8PmIE);
            background-size: cover;
            color: white;
            font-family: Arial, sans-serif;
            text-align: center;
        }
        h1 {
            margin-top: 20px;
        }
        p, pre {
            font-size: 18px;
        }
        .services, .about, .gallery, .contact {
            margin: 20px;
            padding: 15px;
            background: rgba(0, 0, 0, 0.7);
            border-radius: 10px;
        }
        nav a {
            display: inline-block;
            margin: 10px;
            padding: 10px 20px;
            background: gold;
            color: black;
            text-decoration: none;
            border-radius: 5px;
        }
        .gallery img {
            width: 200px;
            height: 150px;
            margin: 10px;
            border-radius: 10px;
        }
        h1{
            color: black;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
    </style>
</head>
<body>
    <h1>CREATIVE PHOTOGRAPHY STUDIO</h1>
    <hr>
    <div class="about">
        <h2>About Us</h2>
        <p>Welcome to our Creative Photography Studio! We specialize in capturing breathtaking moments through the lens, bringing out the beauty of nature, people, and special occasions.</p>
    </div>
    
    <div class="services">
        <h2>Our Services</h2>
        <pre>
            Travel Photography
            Wedding Photography
            Portrait & Macro Photography
            Commercial Photography
            Fashion Photography
        </pre>
    </div>
    
    <div class="gallery">
        <h2>Gallery</h2>
        <img src="https://picsum.photos/200/150?random=1" alt="Sample Photo">
        <img src="https://picsum.photos/200/150?random=2" alt="Sample Photo">
        <img src="https://picsum.photos/200/150?random=3" alt="Sample Photo">
        <img src="https://picsum.photos/200/150?random=4" alt="Sample Photo">
    </div>
    
    <div class="contact">
        <h2>Contact Us</h2>
        <p>Email: contact@creativephotostudio.com</p>
        <p>Phone: +123 456 7890</p>
    </div>
    
    <nav>
        <a href="in1.html">BOOK NOW</a>
    </nav>
</body>
</html>
#in1.html
<style>
    body {
        background-image: url(https://fastly.picsum.photos/id/456/3823/2549.jpg?hmac=d_xvaCWRiYc9iO87BIW3VK5BqITrMITiygpQkPEhnMo);
        background-size: cover;
        font-family: Arial, sans-serif;
        color: white;
        text-align: center;
    }
    .form-container {
        background: rgba(0, 0, 0, 0.7);
        padding: 20px;
        width: 50%;
        margin: auto;
        border-radius: 10px;
        margin-top: 50px;
    }
    input {
        width: 80%;
        padding: 10px;
        margin: 10px 0;
        border-radius: 5px;
        border: none;
    }
    button {
        background: gold;
        color: black;
        padding: 10px 20px;
        border: none;
        border-radius: 5px;
        cursor: pointer;
        font-size: 16px;
    }
    img {
        width: 100px;
        height: 100px;
        border-radius: 50%;
    }
</style>
</head>
<body>
<div class="form-container">
    <h1>EVENT BOOKING</h1>
    <img src="https://fastly.picsum.photos/id/64/4326/2884.jpg?hmac=9_SzX666YRpR_fOyYStXpfSiJ_edO3ghlSRnH2w09Kg" alt="Event Icon">
    <form>
        <label for="name">  Name: </label>
        <input type="text" id="name" placeholder="Enter your name"> <br>
        <label for="email"> Email:</label>
        <input type="email" id="email" placeholder="Enter your email"> <br>
        <label for="phone"> Phone No: </label>
        <input type="number" id="phone" placeholder="Enter your phone number"> <br>
        <label for="date"> Event Date: </label>
        <input type="date" id="date"> <br><br>
        <button type="submit"> Submit </button>
    </form>
</div>
</body>
</html>
