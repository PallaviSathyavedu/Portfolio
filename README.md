<!DOCTYPE html>
<!-- Website - www.codingnepalweb.com -->
<html lang="en" dir="ltr">
  <head>
    <meta charset="UTF-8" />
    <title>Responsive Portfolio Website HTML CSS| CodingNepal</title>
    <link rel="stylesheet" href="style.css" />
    <!-- Fontawesome CDN Link -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.2/css/all.min.css" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  </head>
  <body>
    <!-- Move to up button -->
    <div class="scroll-button">
      <a href="#home"><i class="fas fa-arrow-up"></i></a>
    </div>
    <!-- navgaition menu -->
    <nav>
      <div class="navbar">
        <div class="logo"><a href="#">Portfolio.</a></div>
        <ul class="menu">
          <li><a href="#home">Home</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#skills">Skills</a></li>
          <li><a href="#services">Services</a></li>
          <li><a href="#contact">Contact</a></li>
          <div class="cancel-btn">
            <i class="fas fa-times"></i>
          </div>
        </ul>
        <div class="media-icons">
          <a href="#"><i class="fab fa-facebook-f"></i></a>
          <a href="#"><i class="fab fa-twitter"></i></a>
          <a href="#"><i class="fab fa-instagram"></i></a>
        </div>
      </div>
      <div class="menu-btn">
        <i class="fas fa-bars"></i>
      </div>
    </nav>

    <!-- Home Section Start -->
    <section class="home" id="home">
      <div class="home-content">
        <div class="text">
          <div class="text-one">Hello,</div>
          <div class="text-two">I'm Pallavi</div>
          <div class="text-three">web Developer</div>
          <div class="text-four">From India</div>
        </div>
        <div class="button">
          <button>Hire Me</button>
        </div>
      </div>
    </section>

    <!-- About Section Start -->
    <section class="about" id="about">
      <div class="content">
        <div class="title"><span>About Me</span></div>
        <div class="about-details">
          <div class="left">
            <img src="images/about.jpg" alt="" />
          </div>
          <div class="right">
            <div class="topic">Designing Is My Passion</div>
            <p>
              
Web development encompasses a broad range of tasks from coding, to technical design, to performance of a website or application running .



Web development is the act of building, creating and maintaining websites. The field encompasses a broad range of tasks including everything from coding, to technical design, to the performance of a website or application running on the internet. Web development consists of front-end and back-end components:

FRONT-END WEB DEVELOPMENT VS. BACK-END WEB DEVELOPMENT
Front-end development consists of the user interface (UI) and the look and feel of the website or application. 
Back-end development consists of the databases, logic, APIs, servers and everything else that powers the website behind the scenes.
 

What Are the 3 Types of Web Development?
There are three main types of web development: front-end, back-end and full-stack.

Web development broadly encompasses the whole of a website's functionality, but the work itself is often broken down into three types: 

Front-end development is responsible for the aspects of a website that users see and interact with: the user interface (UI). Front-end developers are well-versed in HTML, CSS and JavaScript, often working closely with design and UX teams to capture both the intended look and feel of the site, while also creating a quality user experience across multiple device types.

Back-end development is responsible for all the aspects of a website that users do not see. This is also known as server-side development because back-end developers focus primarily on the behind-the-scenes logic, APIs and database interactions that power the site. 

Full-stack development is a more holistic approach where the developers responsible for the site or app take care of the entire development stack, from the inner workings typically performed on the back-end to the presentation layer normally handled by front-end developers.


Web Development Explained in 10 Minutes. | Video: Aaron Jack
FOOD FOR THOUGHT
Front-End vs. Back-End Development: Which Should You Prioritize?

 

What Does a Web Developer Do?
Web developers develop websites, specifically by creating the site’s code, connecting it to a server and maintaining its accessibility to users.

Web development is responsible for creating the sites and applications we use through a web browser in our day-to-day lives. Web developers, often working in teams or alongside other tech professionals like data scientists, UX designers and product managers, use specialized techniques and a thorough knowledge of one or more programming languages to create a foundation for where the website’s database will live, known as a back-en
            </p>
            <div class="button">
              <button>Download CV</button>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- My Skill Section Start -->
    <!-- Section Tag and Other Div will same where we need to put same CSS -->
    <section class="skills" id="skills">
      <div class="content">
        <div class="title"><span>My Skills</span></div>
        <div class="skills-details">
          <div class="text">
            <div class="topic">Skills Reflects Our Knowledge</div>
            <p>The word Web Development is made up of two words, that is:

Web: It refers to websites, web pages or anything that works over the internet.
Development: It refers to building the application from scratch.
Web Development can be classified into two ways:

Frontend Development
Backend Development</p>
            <div class="Fresher">
              
              <div class ="Fresher">
              <div class="topic">Fresher</div>
          
              </div>
            </div>
          </div>
          <div class="boxes">
            <div class="box">
              <div class="topic">HTML</div>
              <div class="per">90%</div>
            </div>
            <div class="box">
              <div class="topic">CSS</div>
              <div class="per">80%</div>
            </div>
            <div class="box">
              <div class="topic">JavScript</div>
              <div class="per">70%</div>
            </div>
            <div class="box">
              <div class="topic">Python</div>
              <div class="per">80%</div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- My Services Section Start -->
    <section class="services" id="services">
      <div class="content">
        <div class="title"><span>My Services</span></div>
        <div class="boxes">
          <div class="box">
            <div class="icon">
              <i class="fas fa-desktop"></i>
            </div>
            <div class="topic">Web Devlopment</div>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Mollitia autem quam odio, qui voluptatem eligendi?</p>
          </div>
          <div class="box">
            <div class="icon">
              <i class="fas fa-paint-brush"></i>
            </div>
            <div class="topic">Graphic Design</div>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Mollitia autem quam odio, qui voluptatem eligendi?</p>
          </div>
          <div class="box">
            <div class="icon">
              <i class="fas fa-chart-line"></i>
            </div>
            <div class="topic">Digital Marketing</div>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Mollitia autem quam odio, qui voluptatem eligendi?</p>
          </div>
          <div class="box">
            <div class="icon">
              <i class="fab fa-android"></i>
            </div>
            <div class="topic">Icon Design</div>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Mollitia autem quam odio, qui voluptatem eligendi?</p>
          </div>
          <div class="box">
            <div class="icon">
              <i class="fas fa-camera-retro"></i>
            </div>
            
          <div class="box">
            <div class="icon">
              <i class="fas fa-tablet-alt"></i>
            </div>
            <div class="topic">Apps Devlopment</div>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Mollitia autem quam odio, qui voluptatem eligendi?</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Contact Me section Start -->
    <section class="contact" id="contact">
      <div class="content">
        <div class="title"><span>Contact Me</span></div>
        <div class="text">
          <div class="topic">Have Any Project?</div>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsam neque ipsum corrupti dolores, facere numquam voluptate aspernatur sit perferendis qui nisi modi! Recusandae deserunt consequatur voluptatibus alias repellendus nobis eligendi.</p>
          <div class="button">
            <button>Let's Chat</button>
          </div>
        </div>
      </div>
    </section>

    <!-- Footer Section Start -->
    <footer>
      <div class="text">
        <span>Created By <a href="#">Pallavi</a> | &#169; 2023 All Rights Reserved</span>
      </div>
    </footer>

    <script src="script.js"></script>
  </body>
</html>
