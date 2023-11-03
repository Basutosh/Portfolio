<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="prop.css">
    <title>Protfolio</title>
</head>

<body>
    <div class="top-banner">
        <section id="work">
            <div class="container">
                <nav>
                    <div class="nav-links">
                        <ul class="flex">
                            <li><a href="#work" class="hover-link">Home</a></li>
                            <li><a href="#exp" class="hover-link">About</a></li>
                            <li><a href="#contact" class="hover-link">Contact</a></li>
                            <li><a href="#address" class="hover-link">Address</a></li>
                          <!--  <li><a href="#internship" class="hover-link">Error</a></li>
                            <li><a href="#" class="hover-link">Error</a></li> -->

                        </ul>

                    </div>
                </nav>
            </div>
        </div>
        <header>
           





            <div class="container header-section flex">
                <div class="header-left">
                    <h1>Basutosh Singh</h1>

                    <div class="myPhoto">
                        <img src="C:\Users\basut\OneDrive\Desktop\photo_2023.jpg" alt="Avatar" class="image" style="width:30%" >
                        <div class="middle">
                          <div class="text">Hello People!<br>Welcome to my<br>own creative world</div>
                      </div>
                      </div>
                    <p>
                        Hello, I'm Basutosh, a dedicated B.E. student from at Chitkara University with a passion for technology and innovation.<br>
                        My academic journey has been characterized by a strong commitment to learning, problem-solving, and personal growth.<br>
                        My curiosity and enthusiasm for exploring new concepts have led me to delve into various areas of technology.
                    </p>
    
    
                </div>
            
               
            

                <div class="footertext">
                    <div>
                      <div class="circlemarker" id="accactive" ><p>
                        <br><br>
                        <h2>Secondary<br>School</h2><br><br>
                        <h3>Holy Mary<br>International School</h3><br>
                        <h4>2017-2019<br><br>
                            Scored 92%<br>in 10th board exam
                        </h4>
                      </p></div>
                    </div>
                    <div>
                      <div class="circlemarker" id="accdisabled"><p>
                        <br>
                        <h2>Senior<br>Secondary<br>School</h2><br><br>
                        <h3>Jesus & Mary<br>Academy</h3><br>
                        <h4>2019-2021<br><br>
                            Scored 80%<br>in 12th board exam
                        </h4>
                      </p></div>
                    </div>
                    <div>
                      <div class="circlemarker" id="accprivileged"><p>
                        <br><br><br>
                        <h2>Graduation<br></h2><br><br>
                        <h3>Chitkara University</h3><br>
                        <h4>2021-2025<br><br>
                            Scored 9.34 CGPA<br>
                        </h4>
                      </p></div>
                  </div>
                  </div>


                <div class="header-right">
                    <img src="pic1-modified.png" alt="">
                </div>
            </div>
            </div>
        </header>
        </section>
        <section id="exp"> 
            <section class="section">
                <div class="container">
                    <div class="small-text-bold exp-header">Get In Touch</div>
                    <div class="logos flex">
                        <div class="btn1">
                            <a href="https://www.instagram.com/accounts/login/"><i
                                    class="fa-brands fa-instagram fa-2xl fix1"></i><br>
                                <h3>Instagram</h3>
                            </a>
                        </div>
                        <div class="btn1">
                            <a href="https://github.com"><i
                                    class="fa-brands fa-square-github fa-2xl fix2"></i><br>
                                <h3>Github</h3>
                            </a>
                        </div>
                        <div class="btn1">
                            <a href="https://www.linkedin.com/in/basutoshsingh"><i
                                    class="fa-brands fa-linkedin fa-2xl fix3"></i><br>
                                <h3>LinkedIn</h3>
                            </a>
                        </div>
                        <div class="btn1">
                            <a href="https://www.facebook.com/"><i class="fa-brands fa-facebook fa-2xl fix4"></i><br>
                                <h3>Facebook</h3>
                            </a>
                        </div>
                    </div>
                </div>
            </section>
        </section>
    
        <section class="feature-section">
            <div class="container">
                <div class="features-header">
                    <h2>My Skills</h2>
                    <div class="box">
                        <div class="b1">
                            <i class="fa-brands fa-html5 fa-2xl"></i>
                            <br>
                            <h3>HTML</h3><progress class="pr" value="80" max="100"></progress>
                            <br><br><br><br>
                            <i class="fa-brands fa-java fa-2xl"></i>
                            <br>
                            <h3>JAVA</h3><progress class="pr" value="40" max="100"></progress>
                            <br><br><br><br>
                            
                        </div>
                        <div class="b2">
                            <i class="fa-brands fa-html5 fa-2xl"></i>
                            <br>
                            <h3>CSS</h3><progress class="pr" value="90" max="100"></progress>
                            <br><br><br><br>
                        <i class="fa-brands fa-c fa-2xl"></i>
                        <br>
                        <h3>C++ Programming</h3><progress class="pr" value="70" max="100"></progress>
                    </div>
                </div>
            </div>

        </div>
    </section>
    <section id="contact">
        
            <div class="connect">
                <h2 class="me">Contact Me</h2>
                <h4 class="me">Want to connect? My inbox is always open!</h4> 
                <br><br><br>   
                <!-- form -->
                <div class="form">
                    
                    <form class="f" action="/submit" method="post">
                        <label for="name">Name:</label>
                        <input type="text" id="name" name="name" placeholder="Your Name" required><br><br>
                        <label for="email">Email:</label>
                        <input type="email" id="email" name="email" placeholder="email@domain.com" required><br><br>

                        <label for="message">Message:</label>
                        <textarea id="message" name="message" rows="4" cols="50" placeholder="Type your message" required></textarea><br><br>
                        <label for="gender">Gender:</label>
                        <input type="radio" id="male" name="gender" value="male">
                        <label for="male">Male</label>
                        <input type="radio" id="female" name="gender" value="female">
                        <label for="female">Female</label><br><br>
                        <input onclick="alertfunc()" id="my-submit" type="submit"  value="Submit" >
                    </form>
                </div>
            </div>
        </div>
    <section id="address">
        <div class="address">
            <br><br>
            <h2 class="me">Address</h2>
            <h4 class="me">Sumintra Bhawan, Basera Colony, Saidnagar, L.Sarai, Darbhanga, Pin-846001</h4> <br><br><br>
            <div class="mapouter">
                <div class="gmap_canvas">
                    <iframe class="gmap_iframe" width="100%" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" src="https://maps.google.com/maps?width=600&amp;height=400&amp;hl=en&amp;q=Basera Colony, Darbhanga&amp;t=&amp;z=15&amp;ie=UTF8&amp;iwloc=B&amp;output=embed">    
                    </iframe><a href="https://gachanymph.com/">Gacha Nymph</a></div>
                    <style>
                    .mapouter{position:relative;text-align:center;width:50%;height:400px;}
                    .gmap_canvas {overflow:hidden;background:none!important;width:100%;height:400px; margin-left: 50%;margin-right: 50%;}
                    .gmap_iframe {height:400px!important;}
                    </style></div><br><br>

        </div>
        </section>
        
    <script src="https://kit.fontawesome.com/d7deb1e245.js" crossorigin="anonymous"></script>
    <script>
        function alertfunc(){alert("Thank You!");}
     </script>

<div class="down-banner">
    <section id="work">
        <div class="container">
            <nav>
                <div class="nav-links">
                    <ul class="flex">
                        
                        <li><h43><br>
                            <i class="fa fa-address-card-o fa-2xl fix1"></i>
                            Contacts</h43>
                            <br><br><h5>+91 9570728250<br>basutoshsingh@gmail.com</h5></li>
                            <li><a href="#work" class="hover-link">Back on Top</a></li>
                            <li><h43><br>
                                <i class="fa-solid fa-house fa-2xl fix1"></i>
                                Address</h43>
                                <br><br><h5> Basera Colony<br>Darbhanga, Pin-846001</h5></li>
                       

                    </ul>

                </div>
            </nav>
        </div>
    </div>
</body>

</html>
