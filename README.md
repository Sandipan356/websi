<!DOCTYPE html>
<html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive website</title>
    <link rel="stylesheet" type="text/css" href="css/style.css">
    <script src="js/costum.js"></script>
    <script src="https://code.jquery.com/jquery-3.6.0.js"></script>
    <script src="js/typed.min.js"></script>
</head>

<body>
    <header>
        <nav>
            <div Class="logo">PORTFO<span>LIO</span></div>
            <div class="menu">
                <a href="#">Home</a>
                <a href="#">About</a>
                <a href="#">Skills</a>
                <a href="#">Services</a>

            </div>
        </nav>
        <div class="text">
            <p>Hello,I am</p>
            <h1>Sandipan Chakraborty</h1>
            <p>And I am a<span id="ani" style="color:crimson;"></span></p>
            <button class="c-btn">Hire me</button>
        </div>



    </header>
    <section id="about">
        <div class="section-info">
            <h1>About</h1>
            <p>Who I am?</p>
        </div>
        <div class="about-row">
            <div class="about-left-col">
                <img src="img/about.jpg">
            </div>
            <div class="about-right-col">
                <p id="pro">
                    Hello, I'm Sandipan <span id="ani2" style="color:crimson;"></span>
                </p>
                <p>A front end developer has one general responsibility: to ensure that website visitors can easily interact with the page. They do this through the combination of design, technology and programming to code a website’s appearance, as well
                    as taking care of debugging. Whenever you visit a website, anything that you see, click on or otherwise use is the work of a front end developer.</p>
                <button class="c-btn">Download CV</button>
            </div>
        </div>
    </section>
    <section id="skills">

        <div class="section-info">
            <h1 style="color:white;">Skill's</h1>
            <p>Who I am?</p>
        </div>
        <div class="skills-row">
            <div class="skills-left-col">
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Voluptate, aut ipsam! Itaque impedit quisquam est, dolor quas ad modi, ab exercitationem ipsum temporibus quod eum animi dolorum quae nam fuga aliquid dicta possimus earum magni.
                    Iusto ut cumque magnam dolorem aliquid fugit, quae amet unde accusantium praesentium. Itaque, porro esse.0</p>
                <button class="c-btn">Read more</button>
            </div>
            <div class="skills-right-col">
                <div class="progress-div">
                    <p>
                        <span>HTML</span><br>
                        <progress value="90" max="100"></progress>
                        <span>90%</span>
                    </p>
                    <p>
                        <span>CSS</span><br>
                        <progress value="70" max="100"></progress>
                        <span>70%</span>
                    </p>
                    <p>
                        <span>JAVA SCRIPT</span><br>
                        <progress value="60" max="100"></progress>
                        <span>60%</span>
                    </p>
                    <p>
                        <span>DJANGO</span><br>
                        <progress value="50" max="100"></progress>
                        <span>50%</span>
                    </p>
                    <p>
                        <span>BOOTSTRAP</span><br>
                        <progress value="78" max="100"></progress>
                        <span>78%</span>
                    </p>

                </div>
            </div>
        </div>
    </section>
    <section id="service">
        <div class="section-info">
            <h1>Services</h1>
            <p>What we Provide</p>
        </div>
        <div class="service-row">
            <div class="service-box" data-tilt>
                <img src="img/b2.png">
                <h2>Web design</h2>
                <p>Web design refers to the design of websites that are displayed on the internet. </p>
            </div>
            <div class="service-box" data-tilt>
                <img src="img/b2.png">
                <h2>App Devlopment</h2>
                <p>Application development is the process of creating a computer program or a s.</p>
            </div>
            <div class="service-box" data-tilt>
                <img src="img/b2.png" width=50>
                <h2>Web Devlopment</h2>
                <p>Web development is the work involved in developing a Web site for the Inte.</p>
            </div>
        </div>
    </section>
    <section id="contact">
        <div class="section-info" style="color:white;">
            <h1>Get in touch</h1>
            <p style="color:black;">We are available</p>
        </div>
        <div class="contact-row">
            <div class="contact-left-col">
                <img src="img/b3.png">
            </div>
            <div class="contact-right-col">
                <form>
                    <h2>Connect with us</h2>
                    <input type="text" name="" placeholder="Name">
                    <input type="email" name="" placeholder="E-mail">
                    <br>
                    <textarea cols="40" rows="10" placeholder="Message"></textarea>
                    <br>
                    <button class="c-btn">Submit</button>
                </form>
            </div>
        </div>
    </section>
    <section id="footer">
        <h2>Devloped By Sandy</h2>
        <img src="img/icon.png" width=100>

    </section>
    <script src="js/jquery.ripples-min.js"></script>
    <script>
        jQuery(document).ready(function() {
            $('header').ripples({
                dropRadius: 20,
                perturbance: 0.03,

            });


        });
    </script>
    <script>
        let animate = new Typed('#ani', {
            strings: ["Front End Devloper", "Web devloper", "Software Devloper"],
            typedSpeed: 100,
            backspeed: 100,
            loop: true,
        })
    </script>
    <script>
        let animat = new Typed('#ani2', {
            strings: ["Front End Devloper", "Web devloper", "Software Devloper"],
            typedSpeed: 100,
            backspeed: 100,
            loop: true,
        })
    </script>
    <script src="js/tilt.jquery.min.js"></script>





</body>

</html>
