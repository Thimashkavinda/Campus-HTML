<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NIBM Campus</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Calistoga&family=Oswald:wght@200..700&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
   <style>
        /* Additional styles can be added here or in an external style sheet */
        body {
            margin: 0;
            padding: 0;
            font-family: 'Poppins', sans-serif;
            background-color: #2ec90f;
        }

        /* Header styles */
        .header {
            background-image: url('Images/header-background.jpg');
            background-size: cover;
            background-position: center;
            color: #fff;
            text-align: center;
            padding: 100px 0;
        }

        .header h1 {
            font-size: 3em;
            margin-bottom: 20px;
        }

        .header p {
            font-size: 1.2em;
            margin-bottom: 30px;
        }

        /* Navigation styles */
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 50px;
        }

        .nav-links ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
        }

        .nav-links ul li {
            margin-right: 20px;
        }

        .nav-links ul li a {
            text-decoration: none;
            color: #fff;
            transition: color 0.3s ease;
        }

        .nav-links ul li a:hover {
            color: #ffc107;
        }

        .text-box {
            max-width: 800px;
            margin: 0 auto;
        }

        /* Course section styles */
        .course {
            padding: 80px 0;
            text-align: center;
        }

        .course h1 {
            margin-bottom: 40px;
        }

        .row {
            display: flex;
            justify-content: center;
            align-items: center;
            flex-wrap: wrap;
        }

        .course-col {
            flex: 1;
            padding: 0 20px;
            margin-bottom: 30px;
        }

        .course-col h3 {
            margin-bottom: 10px;
        }

        /* Campus section styles */
        .campus {
            background-color: #fff;
            padding: 80px 0;
            text-align: center;
        }

        .campus h1 {
            margin-bottom: 40px;
        }

        .campus-col {
            flex: 1;
            padding: 0 20px;
            margin-bottom: 30px;
        }

        .campus-col img {
            width: 100%;
            border-radius: 10px;
        }

        /* Facilities section styles */
        .facilities {
            padding: 80px 0;
            text-align: center;
        }

        .facilities h1 {
            margin-bottom: 40px;
        }

        .facilities-col {
            flex: 1;
            padding: 0 20px;
            margin-bottom: 30px;
        }

        .facilities-col img {
            width: 100%;
            border-radius: 10px;
        }

        /* Testimonials section styles */
        .testimonials {
            background-color: #f2f2f2;
            padding: 80px 0;
            text-align: center;
        }

        .testimonials h1 {
            margin-bottom: 40px;
        }

        .testimonials-col {
            flex: 1;
            padding: 0 20px;
            margin-bottom: 30px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
            padding: 20px;
            text-align: left;
        }

        .testimonials-col img {
            width: 100%;
            border-radius: 10px;
            margin-bottom: 20px;
        }

        .testimonials-col p {
            font-size: 0.9em;
            color: #555;
            margin-bottom: 20px;
        }

        .testimonials-col h3 {
            margin-bottom: 10px;
            color: #333;
        }

        .testimonials-col .fa-star {
            color: #ffc107;
        }

        .testimonials-col .fa-star-o {
            color: #ccc;
        }
    </style>
</head>

<body>

    <section class="header">
        <nav>
            <a href="index.html"><img src="Images/13.png" alt="NIBM Logo"></a>
            <div class="nav-links" id="navLinks">
                <i class="fa fa-times" onclick="hideMenu()"></i>
                <ul>
                    <li><a href="#">HOME</a></li>
                    <li><a href="#">ABOUT</a></li>
                    <li><a href="#">COURSE</a></li>
                    <li><a href="#">BLOG</a></li>
                    <li><a href="#">CONTACT</a></li>
                </ul>
            </div>
            <i class="fa fa-bars" onclick="showMenu()"></i>
        </nav>
        <div class="text-box">
            <h1>NIBM SCHOOL OF BUSINESS</h1>
            <p>NIBM School of Business is at the cutting edge of business education and research. We offer a range of programs that enable prospective students to start at practically any prior educational level.</p>
            <a href="#" class="hero-btn">Visit Us To Know More</a>
        </div>
    </section>

    <section class="course">
        <h1>COURSES WE OFFER</h1>
        <p>This text is styled with some of the text formatting properties. The heading uses the text-align, text-transform, and color properties. The paragraph is indented, aligned, and the space between characters is specified. The underline is removed from this colored <a target="_blank" href="tryit.asp?filename=trycss_text">"Try it Yourself"</a> link.</p>
        <div class="row">
            <div class="course-col">
                <h3>Diploma</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing.</p>
            </div>
            <div class="course-col">
                <h3>Higher National Diploma</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing.</p>
            </div>
            <div class="course-col">
                <h3>Degree</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing.</p>
            </div>
        </div>
    </section>

    <section class="campus">
        <h1>OUR GLOBAL CAMPUS</h1>
        <p>NIBM School of Business is at the cutting edge of business education and research. We offer a range of programs that enable prospective students to start at practically any prior educational level.</p>
        <div class="row">
            <div class="campus-col">
                <img src="Images/12.jpg" alt="Colombo Campus">
                <div class="layer">
                    <h3>Colombo</h3>
                </div>
            </div>
            <div class="campus-col">
                <img src="Images/1.jpg" alt="Galle Campus">
                <div class="layer">
                    <h3>Galle</h3>
                </div>
            </div>
            <div class="campus-col">
                <img src="Images/10.jpg" alt="Kandy Campus">
                <div class="layer">
                    <h3>Kandy</h3>
                </div>
            </div>
        </div>
    </section>

    <section class="facilities">
        <h1>OUR FACILITIES</h1>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Suscipit, quasi.</p>
        <div class="row">
            <div class="facilities-col">
                <img src="Images/16.jpg" alt="Cafeteria">
                <h3>Cafeteria</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Beatae nihil quam autem vero consequatur accusamus?</p>
            </div>
            <div class="facilities-col">
                <img src="Images/17.jpg" alt="World Class Library">
                <h3>World Class Library</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Beatae nihil quam autem vero consequatur accusamus?</p>
            </div>
            <div class="facilities-col">
                <img src="Images/21.jpg" alt="Seating Area">
                <h3>Seating Area</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Beatae nihil quam autem vero consequatur accusamus?</p>
            </div>
        </div>
    </section>

    <section class="testimonials">
        <h1>WHAT OUR STUDENTS SAY</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempore, dicta non? Excepturi iusto sed cum praesentium.</p>
        <div class="row">
            <div class="testimonials-col">
                <img src="Images/26.jpg" alt="Student Image">
                <div>
                    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Veritatis temporibus sed eos perferendis at!</p>
                    <h3>John Doe</h3>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star"></span>
                    <span class="fa fa-star"></span>
                </div>
            </div>
            <div class="testimonials-col">
                <img src="Images/27.jfif" alt="Student Image">
                <div>
                    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Veritatis temporibus sed eos perferendis at!</p>
                    <h3>Jane Doe</h3>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                     <span class="fa fa-star"></span>
                    <span class="fa fa-star-half-o"></span>
                </div>
            </div>
            <div class="testimonials-col">
                <img src="Images/28.jfif" alt="Student Image">
                <div>
                    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Veritatis temporibus sed eos perferendis at!</p>
                    <h3>Emily Smith</h3>
                    <span class="fa fa-star checked"></span>
                     <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                     <span class="fa fa-star"></span>
                     <span class="fa fa-star-half-o"></span>
                </div>
            </div>
        </div>
    </section>
    <section class="cta">
         <h1>Enroll The Our Online Cources</h1>
         <a href="" class="hero-btn">Contact Us</a>
    </section>
    <section class="footer">
        <h4>About Us<h4></h4>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Doloribus nulla blanditiis excepturi repellat temporibus maiores. Ut quibusdam quis fuga cumque!</p>
        <div class="icons">
            <span class="fa fa-facebook checked"></span>
            <span class="fa fa-instagram checked"></span>
            <span class="fa fa-twitter checked"></span>
            <span class="fa fa-linkedin checked"></span>
        </div>
        <p>Made With <span class="fa fa-heart-o checked">by Thimash Kavinda</span></p>
    </section>

    <script>
        var navLinks = document.getElementById("navLinks");

        function showMenu() {
            navLinks.style.right = "0";
        }

        function hideMenu() {
            navLinks.style.right = "-200px";
        }
    </script>

</body>
</html>
