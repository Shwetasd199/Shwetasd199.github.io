<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">

        <link rel="stylesheet" href="assets/css/styles.css">

        <!-- =====BOX ICONS===== -->
        <link href='https://cdn.jsdelivr.net/npm/boxicons@2.0.5/css/boxicons.min.css' rel='stylesheet'>

        <title>Portfolio website complete</title>
    </head>
    <body>
        <!--===== HEADER =====-->
        <header class="l-header">
            <nav class="nav bd-grid">
                <div>
                    <a href="#" class="nav__logo">Shwetas</a>
                </div>

                <div class="nav__menu" id="nav-menu">
                    <ul class="nav__list">
                        <li class="nav__item"><a href="#home" class="nav__link active">Home</a></li>
                        <li class="nav__item"><a href="#about" class="nav__link">About</a></li>
                        <li class="nav__item"><a href="#skills" class="nav__link">Skills</a></li>
                        <li class="nav__item"><a href="#work" class="nav__link">Work</a></li>
                        <li class="nav__item"><a href="#contact" class="nav__link">Contact</a></li>
                    </ul>
                </div>

                <div class="nav__toggle" id="nav-toggle">
                    <i class='bx bx-menu'></i>
                </div>
            </nav>
        </header>

        <main class="l-main">
            <!--===== HOME =====-->
            <section class="home bd-grid" id="home">
                <div class="home__data">
                    <h1 class="home__title">Hi,<br>I'am <span class="home__title-color">Shwetas</span><br> Web Designer</h1>

                    <a href="#" class="button">Contact</a>
                </div>

                <div class="home__social">
                    <a href="https://www.linkedin.com/in/shwetas-dhake-5a371a226/" class="home__social-icon"><i class='bx bxl-linkedin'></i></a>
                    <a href="https://www.linkedin.com/in/shwetas-dhake-5a371a226/" class="home__social-icon"><i class='bx bxl-behance' ></i></a>
                    <a href="https://www.linkedin.com/in/shwetas-dhake-5a371a226/" class="home__social-icon"><i class='bx bxl-github' ></i></a>
                </div>

                <div class="home__img">
                    <svg class="home__blob" viewBox="0 0 479 467" xmlns=" " xmlns:xlink=" ">
                        <mask id="mask0" mask-type="alpha">
                            <path d="M9.19024 145.964C34.0253 76.5814 114.865 54.7299 184.111 29.4823C245.804 6.98884 311.86 -14.9503 370.735 14.143C431.207 44.026 467.948 107.508 477.191 174.311C485.897 237.229 454.931 294.377 416.506 344.954C373.74 401.245 326.068 462.801 255.442 466.189C179.416 469.835 111.552 422.137 65.1576 361.805C17.4835 299.81 -17.1617 219.583 9.19024 145.964Z"/>
                        </mask>
                        <g mask="url(#mask0)">
                            <path d="M9.19024 145.964C34.0253 76.5814 114.865 54.7299 184.111 29.4823C245.804 6.98884 311.86 -14.9503 370.735 14.143C431.207 44.026 467.948 107.508 477.191 174.311C485.897 237.229 454.931 294.377 416.506 344.954C373.74 401.245 326.068 462.801 255.442 466.189C179.416 469.835 111.552 422.137 65.1576 361.805C17.4835 299.81 -17.1617 219.583 9.19024 145.964Z"/>
                            <image class="home__blob-img" x="50" y="60" href="assets/img/perfil.jpg"/>
                        </g>
                    </svg>
                </div>
            </section>

            <!--===== ABOUT =====-->
            <section class="about section " id="about">
                <h2 class="section-title">About</h2>

                <div class="about__container bd-grid">
                    <div class="about__img">
                        <img src="assets/img/about.jpg" alt="">
                    </div>
                    
                    <div>
                        <h2 class="about__subtitle">I'am Marlon</h2>
                        <p class="about__text">
                            <h3> I consider myself to be programmer and upcoming software engineer whose area of expertise are: </h3>
                            <p> 
                                In Programing:
                                <p> * React, </p>
                                <p> * Node Js, </p>
                                <p> * Firebase, </p>
                                <p> * Python, C++, JAVA(Programming Language),</p>
                                <p> * Flutter,</p>
                                <p> * Html, Javascript, CSS and User Interface Design. </p> 
                                <br>
                                <p>
                                 <h3> Other than programming my areas of expertise/interests also rope in: </h3> </p>
                                <p> > Rhetoric communication </p>
                                <p> > Problem Solving </p>
                                <p> > Team Management </p>
                                <p> > Trading and Marketing. </p>

                            </p>
                        </p>           
                    </div>                                   
                </div>
            </section>

            <!--===== SKILLS =====-->
            <section class="skills section" id="skills">
                <h2 class="section-title">Skills</h2>

                <div class="skills__container bd-grid">          
                    <div>
                        <h2 class="skills__subtitle">Profesional Skills</h2>
                        <p class="skills__text">Having excellent problem-solving skills, confidence to achieve, and a can-do attitude toward any challenge are important software developer competencies, which make that developer a valued resource in any organization.</p>
                        <div class="skills__data">
                            <div class="skills__names">
                                <i class='bx bxl-html5 skills__icon'></i>
                                <span class="skills__name">HTML5</span>
                            </div>
                            <div class="skills__bar skills__html">

                            </div>
                            <div>
                                <span class="skills__percentage">95%</span>
                            </div>
                        </div>
                        <div class="skills__data">
                            <div class="skills__names">
                                <i class='bx bxl-css3 skills__icon'></i>
                                <span class="skills__name">CSS3</span>
                            </div>
                            <div class="skills__bar skills__css">
                                
                            </div>
                            <div>
                                <span class="skills__percentage">85%</span>
                            </div>
                        </div>
                        <div class="skills__data">
                            <div class="skills__names">
                                <i class='bx bxl-javascript skills__icon' ></i>
                                <span class="skills__name">JAVASCRIPT</span>
                            </div>
                            <div class="skills__bar skills__js">
                                
                            </div>
                            <div>
                                <span class="skills__percentage">65%</span>
                            </div>
                        </div>
                        <div class="skills__data">
                            <div class="skills__names">
                                <i class='bx bxs-paint skills__icon'></i>
                                <span class="skills__name">UX/UI</span>
                            </div>
                            <div class="skills__bar skills__ux">
                                
                            </div>
                            <div>
                                <span class="skills__percentage">85%</span>
                            </div>
                        </div>
                    </div>
                    
                    <div>              
                        <img src="assets/img/work3.jpg" alt="" class="skills__img">
                    </div>
                </div>
            </section>

            <!--===== WORK =====-->
            <section class="work section" id="work">
                <h2 class="section-title">Work</h2>

                <div class="work__container bd-grid">
                    <a href="" class="work__img">
                        <img src="assets/img/work1.jpg" alt="">
                    </a>
                    <a href="" class="work__img">
                        <img src="assets/img/work2.jpg" alt="">
                    </a>
                    <a href="" class="work__img">
                        <img src="assets/img/work3.jpg" alt="">
                    </a>
                    <a href="" class="work__img">
                        <img src="assets/img/work4.jpg" alt="">
                    </a>
                    <a href="" class="work__img">
                        <img src="assets/img/work5.jpg" alt="">
                    </a>
                    <a href="" class="work__img">
                        <img src="assets/img/work6.jpg" alt="">
                    </a>
                </div>
            </section>

            <!--===== CONTACT =====-->
            <section  class="contact section" id="contact">
                <h2 class="section-title">Contact</h2>

                <div class="contact__container bd-grid">
                    <form action="" class="contact__form">
                        <input type="text" placeholder="Name" class="contact__input">
                        <input type="mail" placeholder="Email" class="contact__input">
                        <textarea name="" id="" cols="0" rows="10" class="contact__input"></textarea>
                        <input type="button" value="Submit" class="contact__button button">
                    </form>
                </div>
            </section>
        </main>

 


        <!--===== SCROLL REVEAL =====-->
        <script src="https://unpkg.com/scrollreveal"></script>

        <!--===== MAIN JS =====-->
        <script src="assets/js/main.js"></script>
    </body>
</html>
