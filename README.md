# online-education-platform
online education platform 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>home</title>

    <!-- font awesome cdn link  -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">

    <!-- custom css file link  -->
    <link rel="stylesheet" href="css/style.css">
<style>
   .btn {
  --btn-gradient: var(--btn-gradient-from),var(--btn-gradient-to);
  border: 0 none;
  appearance: none;
  transition: all .3s;
  border-radius: 10px;
  background-color: var(--btn-bg);
  box-shadow: 0 0 2px 2px var(--btn-shadow), 0 0 4px 4px var(--btn-shadow), 0 0 8px 8px var(--btn-shadow);
}

.btn,
.btn * {
  box-sizing: border-box;
}

.btn-inner {
  position: relative;
  border-radius: inherit;
  border: 2px solid transparent;
  font-size: 1rem;
  display: flex;
  align-items: center;
  min-width: 10rem;
  padding: 1rem 2rem;
  overflow: hidden;
  color: var(--btn-text-color);
}

.btn-label {
  position: absolute;
  bottom: 1px;
  left: 1px;
  right: 1px;
  top: 1px;
  border-radius: inherit;
  z-index: 10;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: var(--btn-bg);
  background-image: linear-gradient(to bottom,var(--btn-gradient));
}

.btn:hover {
  transform: translateY(-5px);
  letter-spacing: 3px;
  box-shadow: rgba(0, 131, 253, 0.596) 0px 1px 80px 40px;
}

.btn:active {
  border-radius: 40px;
  transform: translateY(4px);
  transition: 0.1s;
  letter-spacing: 3px;
  box-shadow: rgb(0, 131, 253) 0px 1px 80px 40px;
}

.btn:active .btn-blur:before {
  --transition: 0.5s;
}

.btn--primary {
  --btn-bg: #111111;
  --btn-gradient-from: #111111;
  --btn-gradient-to: rgba(29, 6, 240, 0.5);
  --btn-text-color: #ffffff;
  --btn-shadow: #9b14c438;
}

@keyframes turn {
  0% {
    transform: translateY(-50%) rotate(0deg)
  }

  to {
    transform: translateY(-50%) rotate(1turn)
  }
}
.footer .credit{
  color: white;
}

</style>
</head>
<body>
    
<!-- header section starts  -->

<header class="header">

    <a href="home.html" class="logo"> <i class="fas fa-graduation-cap"></i> educa </a>

    <div id="menu-btn" class="fas fa-bars"></div>

    <nav class="navbar">
        <ul>
            <li><a href="home.html">home</a></li>
            <li><a href="about.html">about</a></li>
            <li><a href="#">courses +</a>
                <ul>
                    <li><a href="course-1.html">course 01</a></li>
                    <li><a href="course-2.html">course 02</a></li>
                    <li><a href="course-3.html">course 03</a></li>
                </ul>
            </li>
            <li><a href="#">pages +</a>
                <ul>
                    <li><a href="teachers.html">teachers</a></li>
                    <li><a href="blog.html">blogs</a></li>
                </ul>
            </li>
            <li><a href="contact.html">contact</a></li>
            <li><a href="login.html">Login</a></li>
        </ul>
    </nav>

</header>

<!-- header section ends -->

<!-- home section starts  -->

<section class="home">

    <div class="image">
        <img src="images/home-img.png" alt="example image" id="myImage">
        <script>
            var image = document.getElementById("myImage");
            var counter = 1;
            setInterval(function() {
              if (counter % 2 == 0) {
                image.src = "images/home-img.png";
              } else if(counter % 3 == 0){
                image.src = "images/7.jpg";
                
              }
              else{
                image.src = "images/8.jpg";
              }
            
              counter++;
            }, 1500);
            </script>
    </div>

    <div class="content" >
        <h3>your course to success</h3>
        <p>May your past close in sweet memories and future open in bright hopes!!!!!!</p>
        <a href="course-1.html"> <button class="btn btn--primary" >

            <span class="btn-inner">
              <span class="btn-label" >
              Start Course 
              </span>
            </span>
            
          </button> </a>
    </div>

</section>

<!-- home section ends -->

<!-- categories section starts  -->

<section class="category">

    <a href="https://www.coursera.org/browse/computer-science" class="box">
        <img src="images/category-1.png" alt="">
        <h3>computer science</h3>
    </a>

    <a href="https://www.simplilearn.com/masters-in-artificial-intelligence?tag=intruduction%20to%20ai" class="box">
      <img src="images/category-2.png" alt="">
      <h3>Artificial intelligence </h3>
  </a>

    <a href="https://www.coursera.org/projects/business-analysis-using-spreadsheets" class="box">
        <img src="images/category-3.png" alt="">
        <h3>business analysis</h3>
    </a>

    <a href="https://www.quicknode.com/?utm_term=block%20chain%20technology&utm_campaign=Web3+General+2.0&utm_source=google&utm_medium=cpc&hsa_acc=1365030395&hsa_cam=19608595398&hsa_grp=146462199118&hsa_ad=646152798708&hsa_src=g&hsa_tgt=kwd-318582907907&hsa_kw=block%20chain%20technology&hsa_mt=p&hsa_net=adwords&hsa_ver=3&gclid=CjwKCAiAxvGfBhB-EiwAMPakqt7zVT0t0B-4TutBep-q7k0fW7PEYDeM7D0_nSXTmeNs20jKLLo-WhoCTH4QAvD_BwE" class="box">
        <img src="images/category-4.png" alt="">
        <h3>Block Chain</h3>
    </a>

    <a href="https://www.simplilearn.com/pgp-data-analytics-certification-training-course?tag=data%20analysis" class="box">
        <img src="images/category-5.png" alt="">
        <h3>data analysis</h3>
    </a>

</section>

<!-- categories section ends -->












<!-- footer section starts  -->

<section class="footer">

    <div class="box-container">

        <div class="box">
            <h3>explore</h3>
            <a href="home.html"> <i class="fas fa-arrow-right"></i> home </a>
            <a href="about.html"> <i class="fas fa-arrow-right"></i> about </a>
            <a href="course-1.html"> <i class="fas fa-arrow-right"></i> course-1 </a>
            <a href="course-2.html"> <i class="fas fa-arrow-right"></i>course-2 </a>
            <a href="course-3.html"> <i class="fas fa-arrow-right"></i> course-3 </a>
            <a href="teachers.html"> <i class="fas fa-arrow-right"></i> teachers </a>
            <a href="blog.html"> <i class="fas fa-arrow-right"></i> blog </a>
            <a href="contact.html"> <i class="fas fa-arrow-right"></i> contact </a>
        </div>

        <div class="box">
            <h3> Pdf Notes <br> </h3>
            <a href="https://www.academia.edu/30864618/Learning_Web_Design_A_Beginners_Guide_to_HTML_CSS_Graphics_and_Beyond"> <i class="fas fa-arrow-right"></i> web design </a>
            <a href="https://www.aiga.org/sites/default/files/2021-03/1A_IntroductionToGraphicDesign.pdf"> <i class="fas fa-arrow-right"></i> graphic design</a>
            <a href="https://libribook.com/ebook/14489/basics-uiux-design-fundamentals-pdf/?bookid=45368"> <i class="fas fa-arrow-right"></i> UI / UX design</a>
            <a href="https://onlinecourses.nptel.ac.in/noc23_cs17/unit?unit=118&lesson=119"> <i class="fas fa-arrow-right"></i> Data Science For Engineers</a>
            <a href="#"> <i class="fas fa-arrow-right"></i> digital marketing</a>
            <a href="#"> <i class="fas fa-arrow-right"></i> email marketing</a>
            <a href="course-1.html"> <i class="fas fa-arrow-right"></i> all courses</a>
        </div>

        <div class="box">
            <h3>quick links</h3>
            <a href="#"> <i class="fas fa-arrow-right"></i> my account </a>
            <a href="#"> <i class="fas fa-arrow-right"></i> feedback </a>
            <a href="contact.html"> <i class="fas fa-arrow-right"></i> help center </a>
            <a href="#"> <i class="fas fa-arrow-right"></i> certificates </a>
            <a href="#"> <i class="fas fa-arrow-right"></i> newsletter </a>
        </div>

        <div class="box">
            <h3>follow us</h3>
            <a href="https://www.instagram.com/educaa_23/"> <i class="fab fa-instagram"></i> instagram </a>
            <a href="#"> <i class="fab fa-facebook-f"></i> facebook </a>
            <a href="#"> <i class="fab fa-twitter"></i> twitter </a>
            <a href="#"> <i class="fab fa-linkedin"></i> linkedin </a>
          
            <a href="#"> <i class="fab fa-pinterest"></i> pinterest </a>
            <a href="#"> <i class="fab fa-github"></i> github </a>
        </div>
        <div class="box">
     
       
            <div  id="close-vid" class="fas fa-times"></div>
            <video  width="600" height="300" preload="auto" loop="loop"  src="images/promo video.mp4"  autoplay controls muted></video>
         
      </div>
    </div>

    <div  class="credit"> created by  <span>Team.Hustle</span> || All Rights Reserved! </div>

</section>

<!-- footer section ends -->

<!-- custom js file link  -->
<script src="js/script.js"></script>

</body>
</html>
