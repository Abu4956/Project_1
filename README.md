# Project_1
I HAVE MADE A PROJECT OF FOOD DELIVEING WEBSITE USING HTML AND CSS.


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Best Online Food delivery Services in India | MyOnlineMeal.com</title>
    <link rel="apple-touch-icon" sizes="180x180" href="favicon/apple-touch-icon.png">
    <link rel="icon" type="image/png" sizes="32x32" href="favicon/favicon-32x32.png">
    <link rel="icon" type="image/png" sizes="16x16" href="favicon/favicon-32x32.png">
    <link rel="manifest" href="favicon/site.webmanifest">
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" media="screen and(max-width:978px)" href="css/phone.css">
</head>
<body>
    <nav id="navbar">
        <ul>
            <li class="item"><a href="#">Home</a></li>
            <li class="item"><a href="#">Services</a></li>
            <li class="item"><a href="#">About Us</a></li>
            <li class="item"><a href="#">Contact Us</a></li>
           
        </ul>
    </nav>
    <section id="home">
        <h1 class="h-primary">Welcome to MyOnlineMeal</h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ea qui consectetur nesciunt iusto dolore rem aliquam accusamus exercitatione</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing  labore eveniet debitis error dolorem veritatis ipsa.</p>
        <button class="btn">Order Now</button>
    </section>

    <section class="services-container">
        <h1 class="h-primary center">Our Services</h1>
        <div id="services">
            <div class="box">
                <img src="img/3.jpg" alt="">
                <h2 class="h-secondary center">Food Ordering</h2>
                <p class="center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Cum perspiciatis voluptatum assumenda eius suscipit ex temporibus distinctio obcaecati tempora, modi quaerat error, expedita voluptatibus, voluptates harum! Incidunt eos vel explicabo.</p>
            </div>
            <div class="box">
                <img src="img/1.jpg" alt="">
                <h2 class="h-secondary center">Food Catering</h2>
                <p class="center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Cum perspiciatis voluptatum assumenda eius suscipit ex temporibus distinctio obcaecati tempora, modi quaerat error, expedita voluptatibus, voluptates harum! Incidunt eos vel explicabo.</p>
            </div>
            <div class="box">
                <img src="delivery.png">
                <h2 class="h-secondary center">Bulk Ordering</h2>
                <p class="center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Cum perspiciatis voluptatum assumenda eius suscipit ex temporibus distinctio obcaecati tempora, modi quaerat error, expedita voluptatibus, voluptates harum! Incidunt eos vel explicabo.</p>
            </div>
        </div>
    </section>
    <section id="client-section">
        <h1 class="h-primary center">Our clients</h1>
        <div id="clients">
            <div class="client-item">
                <img src="img/logo1.png" alt="Our Clients">
            </div>
            <div class="client-item">
                <img src="img/logo4.png" alt="Our Clients">
            </div>
            <div class="client-item">
                <img src="img/logo3.png" alt="Our Clients">
            </div>
            <div class="client-item">
                <img src="img/logo2.png" alt="Our Clients">
            </div>
        </div>
    </section>

    <section id="contact">
        <h1 class="h-primary center">Contact Us</h1>
        <div id="contact-box">
            <form action="">
                <div class="form-group">
                    <label for="name">Name</label>
                    <input type="text" name="name" id="name" placeholder="Enter your Name">
                </div> 
                <div class="form-group">
                    <label for="name">Email</label>
                    <input type="email" name="name" id="name" placeholder="Enter your Email">
                </div> 
                <div class="form-group">
                    <label for="name">Phone Number</label>
                    <input type="phone" name="name" id="name" placeholder="Enter your Phone Number">
                </div> 
                <div class="form-group">
                    <label for="name">Message</label>
                   <textarea name="message" id="message" cols="30" rows="10"></textarea>
                </div> 
            </form>
        </div>
    </section>

    <footer>
        <div class="center">
            Copyright &copy; www.MyonlineMeal.com. All rights reserved
        </div>
    </footer>
 
</body>
</html>
