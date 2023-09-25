<!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
       
        <!--==================== UNICONS ====================-->
        <link rel="stylesheet" href="https://unicons.iconscout.com/release/v4.0.0/css/line.css">
        
        <!--==================== SWIPER CSS ====================-->
        <link rel="stylesheet" href="assets/css/swiper-bundle.min.css">
        
        <!--==================== CSS ====================-->
        <link rel="stylesheet" href="assets/css/styles.css">

        <!--==================== EMAIL SERVICE ====================-->
        <!-- Sweet Alert -->
        <script src="https://unpkg.com/sweetalert/dist/sweetalert.min.js"></script>
        <!-- Email.JS -->
        <script type="text/javascript" src="https://cdn.jsdelivr.net/npm/@emailjs/browser@3/dist/email.min.js"></script>
        <script type="text/javascript">
            (function() {
                emailjs.init('gF3M_-jS8KuvoCpV4');
            })();
        </script>

        <!--==================== CALENDAR SERVICE ====================-->
        <link href="https://assets.calendly.com/assets/external/widget.css" rel="stylesheet">
        <script src="https://assets.calendly.com/assets/external/widget.js" type="text/javascript" async></script>

        <!--==================== TITLE and Favicon ====================-->
        <title>Erol Bicer's Portfolio 👋</title>
        <!-- <link rel="shortcut icon" type="image/png" href="assets/img/"> --> 
        <link rel="apple-touch-icon" sizes="180x180" href="/assets/favicon_io/apple-touch-icon.png">
        <link rel="icon" type="image/png" sizes="32x32" href="/assets/favicon_io/favicon-32x32.png">
        <link rel="icon" type="image/png" sizes="16x16" href="/assets/favicon_io/favicon-16x16.png">
        <!-- <link rel="manifest" href="/site.webmanifest"> -->

        <!-- MS Tile - for Microsoft apps-->
        <meta name="msapplication-TileImage" content="https://github.com/nucerl/myPortfolio/blob/main/assets/snaps/light.png?raw=true" />    

        <!-- HTML Meta Tags -->
        <title>Erol Bicer's Portfolio 👋</title>
        <meta name="description" content="High-level experience in nuclear safety analysis and multinational nuclear project development.">

        <!-- Facebook Meta Tags -->
        <meta property="og:url" content="https://www.erolbicer.com/">
        <meta property="og:type" content="website">
        <meta property="og:title" content="Erol Bicer's Portfolio 👋">
        <meta property="og:description" content="High-level experience in nuclear safety analysis and multinational nuclear project development.">
        <meta property="og:image" content="https://github.com/nucerl/myPortfolio/blob/main/assets/snaps/light.png?raw=true">

        <!-- Twitter Meta Tags -->
        <meta name="twitter:card" content="summary_large_image">
        <meta property="twitter:domain" content="erolbicer.com">
        <meta property="twitter:url" content="https://www.erolbicer.com/">
        <meta name="twitter:title" content="Erol Bicer's Portfolio 👋">
        <meta name="twitter:description" content="High-level experience in nuclear safety analysis and multinational nuclear project development.">
        <meta name="twitter:image" content="https://github.com/nucerl/myPortfolio/blob/main/assets/snaps/light.png?raw=true">

        <!-- Google tag (gtag.js) -->
        <script async src="https://www.googletagmanager.com/gtag/js?id=G-2367QRTG56"></script>
        <script>
        window.dataLayer = window.dataLayer || [];
        function gtag(){dataLayer.push(arguments);}
        gtag('js', new Date());

        gtag('config', 'G-2367QRTG56');
        </script>

    </head>

    <body>
        <!--==================== HEADER ====================-->
        <header class="header" id="header">
            <nav class="nav container">
                <a href="#" class="nav__logo">Erol Bicer</a>

                <div class="nav__menu" id="nav-menu">
                    <ul class="nav__list grid">
                        <li class="nav__item">
                            <a href="#home" class="nav__link active-link">
                                <i class="uil uil-estate nav__icon"></i> Home
                            </a>
                        </li>
                        <li class="nav__item">
                            <a href="#about" class="nav__link">
                                <i class="uil uil-user nav__icon"></i> About
                            </a>
                        </li>
                        <li class="nav__item">
                            <a href="#skills" class="nav__link">
                                <i class="uil uil-file-alt nav__icon"></i> Skills
                            </a>
                        </li>
                        <li class="nav__item">
                            <a href="#projects" class="nav__link">
                                <i class="uil uil-briefcase-alt nav__icon"></i> Projects
                            </a>
                        </li>
                        <li class="nav__item">
                            <a href="#paper" class="nav__link">
                                <i class="uil uil-scenery nav__icon"></i> Papers
                            </a>
                        </li>
                        <li class="nav__item">
                            <a href="#contact" class="nav__link">
                                <i class="uil uil-message nav__icon"></i> Contact
                            </a>
                        </li>
                    </ul>
                    <i class="uil uil-times nav__close" id="nav-close"></i>
                </div>

                <div class="nav__btns">
                    <!-- Theme Change Buttons -->
                    <i class="uil uil-moon change-theme" id="theme-button"></i>


                    <div class="nav__toggle" id="nav-toggle">
                        <i class="uil uil-apps"></i>
                    </div>
                </div>
            </nav>
        </header>

        <!--==================== MAIN ====================-->
        <main class="main">
            <!--==================== HOME ====================-->
            <section class="home section" id="home" data-id="home">
                <div class="home__container container grid">
                    <div class="home__content grid">
                        <div class="home__social">
                            <a href="https://www.linkedin.com/in/erolbicer/" target="_blank" class="home__social-icon">
                                <i class="uil uil-linkedin-alt"></i>
                            </a>
                            <a href="https://www.researchgate.net/profile/Erol-Bicer/research" target="_blank" class="home__social-icon">
                                <i class="uil uil-book-open"></i>
                            </a>
                            <a href="https://github.com/nucerl" target="_blank" class="home__social-icon">
                                <i class="uil uil-github-alt"></i>
                            </a>
                        </div>

                        <div class="home__img">
                            <svg class="home__blob" viewBox="0 0 200 187" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
                                <mask id="mask0" mask-type="alpha">
                                    <path d="M190.312 36.4879C206.582 62.1187 201.309 102.826 182.328 134.186C163.346 165.547 
                                    130.807 187.559 100.226 186.353C69.6454 185.297 41.0228 161.023 21.7403 129.362C2.45775 
                                    97.8511 -7.48481 59.1033 6.67581 34.5279C20.9871 10.1032 59.7028 -0.149132 97.9666 
                                    0.00163737C136.23 0.303176 174.193 10.857 190.312 36.4879Z"/>
                                </mask>
                                <g mask="url(#mask0)">
                                    <path d="M190.312 36.4879C206.582 62.1187 201.309 102.826 182.328 134.186C163.346 
                                    165.547 130.807 187.559 100.226 186.353C69.6454 185.297 41.0228 161.023 21.7403 
                                    129.362C2.45775 97.8511 -7.48481 59.1033 6.67581 34.5279C20.9871 10.1032 59.7028 
                                    -0.149132 97.9666 0.00163737C136.23 0.303176 174.193 10.857 190.312 36.4879Z"/>

                                    <image class="home__blob-img" x='12' y='18' xlink:href="assets/img/perfil.png"/>
                                </g>
                            </svg>
                        </div>

                        <div class="home__data">
                            <h1 class="home__title">Hi, I am Erol.</h1>
                            <h3 class="home__subtitle">Associate Nuclear Engineer</h3>
                            <p class="home__description">High-level experience in nuclear safety analysis at the plant, system, and component levels and multinational nuclear project development.</p>
                            <a href="#contact" class="button button--flex">
                                Contact Me <i class="uil uil-message button__icon"></i>
                            </a>
                        </div>
                    </div>

                    <div class="home__scroll">
                        <a href="#about" class="home__scroll-button button--flex">
                            <i class="uil uil-mouse-alt home__scroll-mouse"></i>
                            <span class="home__scroll-name">Scroll Down</span>
                            <i class="uil uil-arrow-down home__scroll-arrow"></i>
                        </a>
                    </div>
                </div>
            </section>

            <!--==================== ABOUT ====================-->
            <section class="about section" id="about" data-id="about">
                <h2 class="section__title">About Me</h2>
                <span class="section__subtitle">Introduction</span>

                <div class="about__container container grid">
                    <img src="assets/img/about.png" alt="Erol Bicer Nuclear Power Plants Summit Session" class="about__img">


                    <div class="about__data">
                        <p class="about__description">Nuclear engineer, with extensive knowledge and years of experience, specialized in nuclear safety using safety analysis and computational fluid dynamics codes.</p>

                        <div class="about__info">
                            <div>
                                <span class="about__info-title">07+</span>
                                <span class="about__info-name">Years' <br> Experience</span>
                            </div>

                            <div>
                                <span class="about__info-title">11+</span>
                                <span class="about__info-name">Projects <br> Completed</span>
                            </div>

                            <div>
                                <span class="about__info-title">08</span>
                                <span class="about__info-name">Papers <br> Published</span>
                            </div>
                        </div>

                        <div class="about__buttons">
                            <a download="" href="assets/pdf/ErolBicer-Resume.pdf" class="button button--flex">
                                Download CV<i class="uil uil-download-alt button__icon"></i>
                            </a>
                        </div>
                    </div>
                </div>
            </section>

            <!--==================== SKILLS ====================-->
            <section class="skills section" id="skills" data-id="skills">
                <h2 class="section__title">Skills</h2>
                <span class="section__subtitle">Technical Competence</span>

                <div class="skills__container container grid">
                    <div>
                        <!--==================== SKILLS 1 ====================-->
                        <div class="skills__content skills__open">
                            <div class="skills__header">
                                <i class="uil uil-brackets-curly skills__icon"></i>

                                <div>
                                    <h1 class="skills__titles">System Codes</h1>
                                    <!-- <span class="skills__subtitle">More than 8 years</span> -->
                                </div>

                                <i class="uil uil-angle-down skills__arrow"></i>
                            </div>

                            <div class="skills__list grid">
                                <div class="skills__data">
                                    <div class="skills__titles">
                                        <h3 class="skills__name">RELAP5</h3>
                                        <span class="skills__number">Advanced</span> 
                                    </div>
                                    <div class="skills__bar">
                                        <span class="skills__percantage skills__sys-code"></span>
                                    </div>
                                </div>

                                <!-- <div class="skills__data">
                                    <div class="skills__titles">
                                        <h3 class="skills__name">SNAP</h3>
                                        <span class="skills__number">Advanced</span> 
                                    </div>
                                    <div class="skills__bar">
                                        <span class="skills__percantage skills__sys-code"></span>
                                    </div>
                                </div> -->

                                <div class="skills__data">
                                    <div class="skills__titles">
                                        <h3 class="skills__name">GOTHIC</h3>
                                        <span class="skills__number">Advanced</span> 
                                    </div>
                                    <div class="skills__bar">
                                        <span class="skills__percantage skills__sys-code"></span>
                                    </div>
                                </div>

                                <div class="skills__data">
                                    <div class="skills__titles">
                                        <h3 class="skills__name">MARS-KS</h3>
                                        <span class="skills__number">Advanced</span> 
                                    </div>
                                    <div class="skills__bar">
                                        <span class="skills__percantage skills__sys-code"></span>
                                    </div>
                                </div>

                                <div class="skills__data">
                                    <div class="skills__titles">
                                        <h3 class="skills__name">SPACE</h3>
                                        <span class="skills__number">Advanced</span> 
                                    </div>
                                    <div class="skills__bar">
                                        <span class="skills__percantage skills__sys-code"></span>
                                    </div>
                                </div>

                                <div class="skills__data">
                                    <div class="skills__titles">
                                        <h3 class="skills__name">CAP</h3>
                                        <span class="skills__number">Advanced</span> 
                                    </div>
                                    <div class="skills__bar">
                                        <span class="skills__percantage skills__sys-code"></span>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!--==================== SKILLS 2 ====================-->
                        <div class="skills__content skills__close">
                            <div class="skills__header">
                                <i class="uil uil-vector-square skills__icon"></i>

                                <div>
                                    <h1 class="skills__titles">CFD Codes</h1>
                                    <!-- <span class="skills__subtitle">More than 2 years</span> -->
                                </div>

                                <i class="uil uil-angle-down skills__arrow"></i>
                            </div>

                            <div class="skills__list grid">
                                <div class="skills__data">
                                    <div class="skills__titles">
                                        <h3 class="skills__name">OpenFOAM</h3>
                                        <span class="skills__number">Proficient</span> 
                                    </div>
                                    <div class="skills__bar">
                                        <span class="skills__percantage skills__80"></span>
                                    </div>
                                </div>

                                <div class="skills__data">
                                    <div class="skills__titles">
                                        <h3 class="skills__name">CUPID</h3>
                                        <span class="skills__number">Beginner</span> 
                                    </div>
                                    <div class="skills__bar">
                                        <span class="skills__percantage skills__20"></span>
                                    </div>
                                </div>

                            </div>
                        </div>                        
                    </div>

                    <div>
                        <!--==================== SKILLS 3 ====================-->
                        <div class="skills__content skills__close">
                            <div class="skills__header">
                                <i class="uil uil-arrow skills__icon"></i>

                                <div>
                                    <h1 class="skills__titles">Programming Codes</h1>
                                    <!-- <span class="skills__subtitle">More than 2 years</span> -->
                                </div>

                                <i class="uil uil-angle-down skills__arrow"></i>
                            </div>

                            <div class="skills__list grid">
                                <div class="skills__data">
                                    <div class="skills__titles">
                                        <h3 class="skills__name">MATLAB</h3>
                                        <span class="skills__number">Proficient</span> 
                                    </div>
                                    <div class="skills__bar">
                                        <span class="skills__percantage skills__60"></span>
                                    </div>
                                </div>

                                <div class="skills__data">
                                    <div class="skills__titles">
                                        <h3 class="skills__name">FORTRAN</h3>
                                        <span class="skills__number">Intermediate</span> 
                                    </div>
                                    <div class="skills__bar">
                                        <span class="skills__percantage skills__40"></span>
                                    </div>
                                </div>

                                <div class="skills__data">
                                    <div class="skills__titles">
                                        <h3 class="skills__name">C++</h3>
                                        <span class="skills__number">Beginner</span> 
                                    </div>
                                    <div class="skills__bar">
                                        <span class="skills__percantage skills__20"></span>
                                    </div>
                                </div>
                                
                                <div class="skills__data">
                                    <div class="skills__titles">
                                        <h3 class="skills__name">HTML/CSS</h3>
                                        <span class="skills__number">Intermediate</span> 
                                    </div>
                                    <div class="skills__bar">
                                        <span class="skills__percantage skills__40"></span>
                                    </div>
                                </div>


                            </div>
                        </div>  

                        <!--==================== SKILLS 4 ====================-->
                        <div class="skills__content skills__close">
                            <div class="skills__header">
                                <i class="uil uil-code-branch skills__icon"></i>

                                <div>
                                    <h1 class="skills__titles">Miscellaneous </h1>
                                    <!-- <span class="skills__subtitle">More than 2 years</span> -->
                                </div>

                                <i class="uil uil-angle-down skills__arrow"></i>
                            </div>

                            <div class="skills__list grid">
                                <div class="skills__data">
                                    <div class="skills__titles">
                                        <h3 class="skills__name">DOS/UNIX</h3>
                                        <span class="skills__number">Beginner</span> 
                                    </div>
                                    <div class="skills__bar">
                                        <span class="skills__percantage skills__20"></span>
                                    </div>
                                </div>

                                <div class="skills__data">
                                    <div class="skills__titles">
                                        <h3 class="skills__name">CATIA</h3>
                                        <span class="skills__number">Intermediate</span> 
                                    </div>
                                    <div class="skills__bar">
                                        <span class="skills__percantage skills__40"></span>
                                    </div>
                                </div>

                                <div class="skills__data">
                                    <div class="skills__titles">
                                        <h3 class="skills__name">Origin</h3>
                                        <span class="skills__number">Advanced</span> 
                                    </div>
                                    <div class="skills__bar">
                                        <span class="skills__percantage skills__100"></span>
                                    </div>
                                </div>
                                
                                <div class="skills__data">
                                    <div class="skills__titles">
                                        <h3 class="skills__name">ParaView</h3>
                                        <span class="skills__number">Proficient</span> 
                                    </div>
                                    <div class="skills__bar">
                                        <span class="skills__percantage skills__80"></span>
                                    </div>
                                </div>

                                <div class="skills__data">
                                    <div class="skills__titles">
                                        <h3 class="skills__name">Mathcad</h3>
                                        <span class="skills__number">Proficient</span> 
                                    </div>
                                    <div class="skills__bar">
                                        <span class="skills__percantage skills__80"></span>
                                    </div>
                                </div>

                                <div class="skills__data">
                                    <div class="skills__titles">
                                        <h3 class="skills__name">Git/GitHub</h3>
                                        <span class="skills__number">Intermediate</span> 
                                    </div>
                                    <div class="skills__bar">
                                        <span class="skills__percantage skills__60"></span>
                                    </div>
                                </div>

                                <div class="skills__data">
                                    <div class="skills__titles">
                                        <h3 class="skills__name">MS Office</h3>
                                        <span class="skills__number">Advanced</span> 
                                    </div>
                                    <div class="skills__bar">
                                        <span class="skills__percantage skills__100"></span>
                                    </div>
                                </div>
                            </div>
                        </div>  

                    </div> 
                </div>
            </section>

            <!--==================== QUALIFICATION ====================-->
            <section class="qualification section">
                <h2 class="section__title">Qualifications</h2>
                <span class="section__subtitle">Academic and Professional Career</span>

                <div class="qualification__container container">
                    <div class="qualification__tabs">
                        <div class="qualification__button button--flex qualification__active" data-target="#education">
                            <i class="uil uil-graduation-cap qualification__icon"></i>
                            Education
                        </div>

                        <div class="qualification__button button--flex" data-target="#work">
                            <i class="uil uil-briefcase-alt qualification__icon"></i>
                            Work
                        </div>
                    </div>
                    <div class="qualification__sections">
                        <!--==================== QUALIFICATION CONTENT 1 ====================-->
                        <div class="qualification__content qualification__active" data-content id="education">
                             <!--==================== QUALIFICATION  1 ====================-->
                             <div class="qualification__data">
                                <div>
                                    <span class="qualification__degree">B.Sc.</span>
                                    <h3 class="qualification__tittle">Nuclear Energy Engineering</h3>
                                    <span class="qualification__subtitle">Hacettepe University</span>
                                    <div class="qualification__calendar">
                                        <i class="uil uil-calendar-alt"></i>
                                        2008 - 2013
                                    </div>
                                </div>
                                <div>
                                    <span class="qualification__rounder"></span>
                                    <span class="qualification__line"></span>
                                </div>
                            </div>

                             <!--==================== QUALIFICATION  2 ====================-->
                             <div class="qualification__data">
                                <div></div>
                                <div>
                                    <span class="qualification__rounder"></span>
                                    <span class="qualification__line"></span>
                                </div>

                                <div>
                                    <span class="qualification__degree">M.Sc.</span>
                                    <h3 class="qualification__tittle">Nuclear Power Plant Engineering</h3>
                                    <span class="qualification__subtitle">KINGS</span>
                                    <div class="qualification__calendar">
                                        <i class="uil uil-calendar-alt"></i>
                                        2014 - 2016
                                    </div>
                                </div>

                            </div>

                             <!--==================== QUALIFICATION  3 ====================-->
                             <div class="qualification__data">
                                <div>
                                    <span class="qualification__degree">Ph.D.</span>
                                    <h3 class="qualification__tittle">Nuclear Engineering</h3>
                                    <span class="qualification__subtitle">Seoul National University</span>
                                    <div class="qualification__calendar">
                                        <i class="uil uil-calendar-alt"></i>
                                        2017 - Present
                                    </div>
                                </div>
                                <div>
                                    <span class="qualification__rounder"></span>
                                    <!-- <span class="qualification__line"></span> -->
                                </div>
                            </div>

                             <!--==================== QUALIFICATION  4 ====================-->
                             <div class="qualification__data">
                                <!-- <div></div> -->

                                <!-- <div>
                                    <span class="qualification__rounder"></span> -->
                                    <!-- <span class="qualification__line"></span> -->
                                <!-- </div> -->

                                <!-- <div>
                                    <h3 class="qualification__tittle">Nuclear Engineer</h3>
                                    <span class="qualification__subtitle">Hacettepe University</span>
                                    <div class="qualification__calendar">
                                        <i class="uil uil-calendar-alt"></i>
                                        2008 - 2013
                                    </div>
                                </div> -->


                                
                            </div>

                        </div>

                        <!--==================== QUALIFICATION CONTENT 2 ====================-->
                        <div class="qualification__content" data-content id="work">
                            <!--==================== QUALIFICATION  1 ====================-->
                            <div class="qualification__data">
                               <div>
                                   <h3 class="qualification__tittle">R&D Engineer</h3>
                                   <span class="qualification__subtitle">Bil-Plas Industry</span>
                                   <div class="qualification__calendar">
                                       <i class="uil uil-calendar-alt"></i>
                                       2013 - 2014
                                   </div>
                               </div>
                               <div>
                                   <span class="qualification__rounder"></span>
                                   <span class="qualification__line"></span>
                               </div>
                           </div>

                            <!--==================== QUALIFICATION  2 ====================-->
                            <div class="qualification__data">
                               <div></div>
                               <div>
                                   <span class="qualification__rounder"></span>
                                   <span class="qualification__line"></span>
                               </div>

                               <div>
                                   <h3 class="qualification__tittle">Assistant Manager</h3>
                                   <span class="qualification__subtitle">FNC Technology</span>
                                   <div class="qualification__calendar">
                                       <i class="uil uil-calendar-alt"></i>
                                       2016 - 2019
                                   </div>
                               </div>

                           </div>

                            <!--==================== QUALIFICATION  3 ====================-->
                            <div class="qualification__data">
                               <div>
                                   <h3 class="qualification__tittle">Associate Manager</h3>
                                   <span class="qualification__subtitle">FNC Technology</span>
                                   <div class="qualification__calendar">
                                       <i class="uil uil-calendar-alt"></i>
                                       2019 - Present
                                   </div>
                               </div>
                               <div>
                                   <span class="qualification__rounder"></span>
                                   <!-- <span class="qualification__line"></span> -->
                               </div>
                           </div>

                       </div>

                    </div>
                </div>
            </section>

            <!--==================== PROJECTS ====================-->
            <section class="projects section" id="projects" data-id="projects">
                <h2 class="section__title">Projects</h2>
                <span class="section__subtitle">Involved Projects</span>

                <div class="projects__container container grid">
                    <!--==================== PROJECTS 1 ====================-->
                    <div class="projects__content">
                        <div>
                            <i class="uil uil-swatchbook projects__icon"></i>
                            <h3 class="projects__title">SMR & MMR</h3>
                        </div>

                        <span class="button button--flex button--small button--link projects__button">
                            View More
                            <i class="uil uil-arrow-right button__icon"></i>
                        </span>

                        <div class="projects__modal">
                            <div class="projects__modal-content">
                                <h4 class="projects__modal-title">Small and Micro Modular Reactors Technology Analyses </h4>
                                <i class="uil uil-times projects__modal-close"></i>

                                <ul class="projects__modal-projects grid">
                                    <li class="projects__modal-project">
                                        <i class="uil uil-check-circle projects__modal-icon"></i>
                                        <p>Literature and Technology Review</p>
                                    </li>
                                    <li class="projects__modal-project">
                                        <i class="uil uil-check-circle projects__modal-icon"></i>
                                        <p>Technical Feasibility Analysis</p>
                                    </li>
                                    <li class="projects__modal-project">
                                        <i class="uil uil-check-circle projects__modal-icon"></i>
                                        <p>Commercial Feasibility Analysis</p>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div> 

                    <!--==================== PROJECTS 2 ====================-->
                    <div class="projects__content">
                        <div>
                            <i class="uil uil-swatchbook projects__icon"></i>
                            <h3 class="projects__title">SMART</h3>
                        </div>

                        <span class="button button--flex button--small button--link projects__button">
                            View More
                            <i class="uil uil-arrow-right button__icon"></i>
                        </span>

                        <div class="projects__modal">
                            <div class="projects__modal-content">
                                <h4 class="projects__modal-title">System-Integrated Modular Advanced Reactor Passive Containment Cooling System</h4>
                                <i class="uil uil-times projects__modal-close"></i>

                                <ul class="projects__modal-projects grid">
                                    <li class="projects__modal-project">
                                        <i class="uil uil-check-circle projects__modal-icon"></i>
                                        <p>Modeling of SMART CPRSS through GOTHIC</p>
                                    </li>
                                    <li class="projects__modal-project">
                                        <i class="uil uil-check-circle projects__modal-icon"></i>
                                        <p>Literature Survey for the Design and Arrangement of Sparger Layout for SMART CPRSS</p>
                                    </li>
                                        <li class="projects__modal-project-ind">
                                            <i class="uil uil-check projects__modal-icon"></i>
                                            <p>Direct contact condensation</p>
                                        </li>
                                        <li class="projects__modal-project-ind">
                                            <i class="uil uil-check projects__modal-icon"></i>
                                            <p>Chugging</p>
                                        </li>
                                    <li class="projects__modal-project">
                                        <i class="uil uil-check-circle projects__modal-icon"></i>
                                        <p>Modeling of SISTA through MARS-KS</p>
                                    </li>
                                    <li class="projects__modal-project">
                                        <i class="uil uil-check-circle projects__modal-icon"></i>
                                        <p>CAP Verification</p>
                                    </li>
                                        <li class="projects__modal-project-ind">
                                            <i class="uil uil-check projects__modal-icon"></i>
                                            <p>Simulations of condensation and boiling conceptual problems through MARS</p>
                                        </li>
                                        <li class="projects__modal-project-ind">
                                            <i class="uil uil-check projects__modal-icon"></i>
                                            <p>Simulations of a conceptual problem through MARS and SPACE</p>
                                        </li>
                                    <li class="projects__modal-project">
                                        <i class="uil uil-check-circle projects__modal-icon"></i>
                                        <p>CAP Input Preparation for sub P/T Analysis</p>
                                    </li>
                                    <li class="projects__modal-project">
                                        <i class="uil uil-check-circle projects__modal-icon"></i>
                                        <p>CPRSS Hydraulics and Heat structure Calculation Sheet Preparation for CAP</p>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>         

                    <!--==================== PROJECTS 3 ====================-->
                    <div class="projects__content">
                        <div>
                            <i class="uil uil-swatchbook projects__icon"></i>
                            <h3 class="projects__title">PGSFR</h3>
                        </div>

                        <span class="button button--flex button--small button--link projects__button">
                            View More
                            <i class="uil uil-arrow-right button__icon"></i>
                        </span>

                        <div class="projects__modal">
                            <div class="projects__modal-content">
                                <h4 class="projects__modal-title">Prototype Gen-IV Sodium-Cooled Fast Reactor Condition Analysis Project</h4>
                                <i class="uil uil-times projects__modal-close"></i>

                                <ul class="projects__modal-projects grid">
                                    <li class="projects__modal-project">
                                        <i class="uil uil-check-circle projects__modal-icon"></i>
                                        <p>Simulations of Design Basis Events through MARS-LMR</p>
                                    </li>
                                        <li class="projects__modal-project-ind">
                                            <i class="uil uil-check projects__modal-icon"></i>
                                            <p>Leakage of Intermediate Heat Transport System Pipe</p>
                                        </li>
                                        <li class="projects__modal-project-ind">
                                            <i class="uil uil-check projects__modal-icon"></i>
                                            <p>Reactor Vessel Leak into the Containment Vessel</p>
                                        </li>
                                </ul>
                            </div>
                        </div>
                    </div>

                    <!--==================== PROJECTS 4 ====================-->
                    <div class="projects__content">
                        <div>
                            <i class="uil uil-swatchbook projects__icon"></i>
                            <h3 class="projects__title">SMART DEC</h3>
                        </div>

                        <span class="button button--flex button--small button--link projects__button">
                            View More
                            <i class="uil uil-arrow-right button__icon"></i>
                        </span>

                        <div class="projects__modal">
                            <div class="projects__modal-content">
                                <h4 class="projects__modal-title">Feasibility Study of the SPACE Code Application on DEC Accident Analysis of SMART</h4>
                                <i class="uil uil-times projects__modal-close"></i>

                                <ul class="projects__modal-projects grid">
                                    <li class="projects__modal-project">
                                        <i class="uil uil-check-circle projects__modal-icon"></i>
                                        <p>SPACE Code Calculation Sheet Preparation</p>
                                    </li>
                                        <li class="projects__modal-project-ind">
                                            <i class="uil uil-check projects__modal-icon"></i>
                                            <p>Passive Safety Injection System (PSIS)</p>
                                        </li>
                                        <li class="projects__modal-project-ind">
                                            <i class="uil uil-check projects__modal-icon"></i>
                                            <p>Passive Residual Heat Removal System (PRHRS)</p>
                                        </li>
                                </ul>
                            </div>
                        </div>
                    </div>
                    
                    <!--==================== PROJECTS 5 ====================-->
                    <div class="projects__content">
                        <div>
                            <i class="uil uil-swatchbook projects__icon"></i>
                            <h3 class="projects__title">PCCS</h3>
                        </div>

                        <span class="button button--flex button--small button--link projects__button">
                            View More
                            <i class="uil uil-arrow-right button__icon"></i>
                        </span>

                        <div class="projects__modal">
                            <div class="projects__modal-content">
                                <h4 class="projects__modal-title">Conceptual Design and Development of Passive Containment Cooling System for APR1400</h4>
                                <i class="uil uil-times projects__modal-close"></i>

                                <ul class="projects__modal-projects grid">
                                    <li class="projects__modal-project">
                                        <i class="uil uil-check-circle projects__modal-icon"></i>
                                        <p>Literature Survey on Condensation with Non-condensable Gases</p>
                                    </li>
                                        <li class="projects__modal-project-ind">
                                            <i class="uil uil-check projects__modal-icon"></i>
                                            <p>Separate and integral test facilities to validate the MARS condensation model</p>
                                        </li>
                                        <li class="projects__modal-project-ind">
                                            <i class="uil uil-check projects__modal-icon"></i>
                                            <p>Available condensation models (e.g. Colburn-Hougen, Peterson's Model)</p>
                                        </li>
                                        <li class="projects__modal-project-ind">
                                            <i class="uil uil-check projects__modal-icon"></i>
                                            <p>Review of MARS condensation model</p>
                                        </li>
                                    <li class="projects__modal-project">
                                        <i class="uil uil-check-circle projects__modal-icon"></i>
                                        <p>COPAIN Test Facility (on-plane condensation) Simulations through MARS-KS</p>
                                    </li>
                                    <li class="projects__modal-project">
                                        <i class="uil uil-check-circle projects__modal-icon"></i>
                                        <p>Dehbi, Kawakubo, Su, Lee Experiments (on-tube condensation) Simulations through MARS-KS</p>
                                    </li>
                                        <li class="projects__modal-project-ind">
                                            <i class="uil uil-check projects__modal-icon"></i>
                                            <p>MARS trouble report to KINS: Volume average velocity deficiency</p>
                                        </li>
                                    <li class="projects__modal-project">
                                        <i class="uil uil-check-circle projects__modal-icon"></i>
                                        <p>Multi-Compartment and Multi-Dimension Simulations (conceptual) through GOTHIC</p>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>                       

                    <!--==================== PROJECTS 6 ====================-->
                    <div class="projects__content">
                        <div>
                            <i class="uil uil-swatchbook projects__icon"></i>
                            <h3 class="projects__title">ATLAS</h3>
                        </div>

                        <span class="button button--flex button--small button--link projects__button">
                            View More
                            <i class="uil uil-arrow-right button__icon"></i>
                        </span>

                        <div class="projects__modal">
                            <div class="projects__modal-content">
                                <h4 class="projects__modal-title">Determination of ATLAS Heat Loss and Improvement of MARS Input Model</h4>
                                <i class="uil uil-times projects__modal-close"></i>

                                <ul class="projects__modal-projects grid">
                                    <li class="projects__modal-project">
                                        <i class="uil uil-check-circle projects__modal-icon"></i>
                                        <p>ATLAS Experimental Facility Heat Loss Quantification of RCS side</p>
                                    </li>
                                    <li class="projects__modal-project">
                                        <i class="uil uil-check-circle projects__modal-icon"></i>
                                        <p>Integral and Differential Approaches</p>
                                    </li>
                                    <li class="projects__modal-project">
                                        <i class="uil uil-check-circle projects__modal-icon"></i>
                                        <p>Implementation of Heat Loss Modeling to MARS Input</p>
                                    </li>
                                    <li class="projects__modal-project">
                                        <i class="uil uil-check-circle projects__modal-icon"></i>
                                        <p>Simulations of OECD and DSP Problems with the new MARS Input</p>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div> 

                    <!--==================== PROJECTS 7 ====================-->
                    <div class="projects__content">
                        <div>
                            <i class="uil uil-swatchbook projects__icon"></i>
                            <h3 class="projects__title">NON-LOCA</h3>
                        </div>

                        <span class="button button--flex button--small button--link projects__button">
                            View More
                            <i class="uil uil-arrow-right button__icon"></i>
                        </span>

                        <div class="projects__modal">
                            <div class="projects__modal-content">
                                <h4 class="projects__modal-title">SPACE Code Input Deck Preparation and Validation</h4>
                                <i class="uil uil-times projects__modal-close"></i>

                                <ul class="projects__modal-projects grid">
                                    <li class="projects__modal-project">
                                        <i class="uil uil-check-circle projects__modal-icon"></i>
                                        <p>HANUL 1&2 Hydraulics and Heat Structure Calculation Sheet Preparation for SPACE</p>
                                    </li>
                                        <li class="projects__modal-project-ind">
                                            <i class="uil uil-check projects__modal-icon"></i>
                                            <p>Reactor pressure vessel</p>
                                        </li>
                                        <li class="projects__modal-project-ind">
                                            <i class="uil uil-check projects__modal-icon"></i>
                                            <p>Steam generators</p>
                                        </li>
                                        <li class="projects__modal-project-ind">
                                            <i class="uil uil-check projects__modal-icon"></i>
                                            <p>Steam generators</p>
                                        </li>
                                        <li class="projects__modal-project-ind">
                                            <i class="uil uil-check projects__modal-icon"></i>
                                            <p>Secondary Systems</p>
                                        </li>
                                    <li class="projects__modal-project">
                                        <i class="uil uil-check-circle projects__modal-icon"></i>
                                        <p>HANUL 5&6 Hydraulics and Heat Structure Calculation Sheet Preparation for SPACE</p>
                                    </li>
                                        <li class="projects__modal-project-ind">
                                            <i class="uil uil-check projects__modal-icon"></i>
                                            <p>Steam generators</p>
                                        </li>
                                        <li class="projects__modal-project-ind">
                                            <i class="uil uil-check projects__modal-icon"></i>
                                            <p>Steam lines</p>
                                        </li>
                                        <li class="projects__modal-project-ind">
                                            <i class="uil uil-check projects__modal-icon"></i>
                                            <p>Safety systems</p>
                                        </li>
                                        <li class="projects__modal-project-ind">
                                            <i class="uil uil-check projects__modal-icon"></i>
                                            <p>SPACE Code Validation</p>
                                        </li>
                                        <li class="projects__modal-project-ind">
                                            <i class="uil uil-check projects__modal-icon"></i>
                                            <p>DSP01 - ATLAS DVI line break SBLOCA simulation</p>
                                        </li>
                                        <li class="projects__modal-project-ind">
                                            <i class="uil uil-check projects__modal-icon"></i>
                                            <p>DSP02 - ATLAS CL SBLOCA</p>
                                        </li>
                                        <li class="projects__modal-project-ind">
                                            <i class="uil uil-check projects__modal-icon"></i>
                                            <p>Marviken sensitivity tests</p>
                                        </li>
                                </ul>
                            </div>
                        </div>
                    </div>

                    <!--==================== PROJECTS 8 ====================-->
                    <div class="projects__content">
                        <div>
                            <i class="uil uil-swatchbook projects__icon"></i>
                            <h3 class="projects__title">PAFS</h3>
                        </div>

                        <span class="button button--flex button--small button--link projects__button">
                            View More
                            <i class="uil uil-arrow-right button__icon"></i>
                        </span>

                        <div class="projects__modal">
                            <div class="projects__modal-content">
                                <h4 class="projects__modal-title">Passive Auxiliary Feedwater System Development</h4>
                                <i class="uil uil-times projects__modal-close"></i>

                                <ul class="projects__modal-projects grid">
                                    <li class="projects__modal-project">
                                        <i class="uil uil-check-circle projects__modal-icon"></i>
                                        <p>Calculation of Pipe Flow Resistance Coefficients</p>
                                    </li>
                                    <li class="projects__modal-project">
                                        <i class="uil uil-check-circle projects__modal-icon"></i>
                                        <p>RELAP5 Input Deck Preparation for HANUL5&6</p>
                                    </li>
                                        <li class="projects__modal-project-ind">
                                            <i class="uil uil-check projects__modal-icon"></i>
                                            <p>Full steady-state input model</p>
                                        </li>
                                        <li class="projects__modal-project-ind">
                                            <i class="uil uil-check projects__modal-icon"></i>
                                            <p>Code-to-code verification with SPACE</p>
                                        </li>
                                </ul>
                            </div>
                        </div>
                    </div>

                    <!--==================== PROJECTS 9 ====================-->
                    <div class="projects__content">
                        <div>
                            <i class="uil uil-swatchbook projects__icon"></i>
                            <h3 class="projects__title">ACHX</h3>
                        </div>

                        <span class="button button--flex button--small button--link projects__button">
                            View More
                            <i class="uil uil-arrow-right button__icon"></i>
                        </span>

                        <div class="projects__modal">
                            <div class="projects__modal-content">
                                <h4 class="projects__modal-title">Air Cooling Heat Exchanger Experiment Simulations through MARS-KS</h4>
                                <i class="uil uil-times projects__modal-close"></i>

                                <ul class="projects__modal-projects grid">
                                    <li class="projects__modal-project">
                                        <i class="uil uil-check-circle projects__modal-icon"></i>
                                        <p>Fin Efficiency</p>
                                    </li>
                                    <li class="projects__modal-project">
                                        <i class="uil uil-check-circle projects__modal-icon"></i>
                                        <p>Fouling</p>
                                    </li>
                                    <li class="projects__modal-project">
                                        <i class="uil uil-check-circle projects__modal-icon"></i>
                                        <p>Heat Transfer Coefficient</p>
                                    </li>
                                    <li class="projects__modal-project">
                                        <i class="uil uil-check-circle projects__modal-icon"></i>
                                        <p>Loss Coefficient</p>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div> 

                    <!--==================== PROJECTS 10 ====================-->
                    <div class="projects__content">
                        <div>
                            <i class="uil uil-swatchbook projects__icon"></i>
                            <h3 class="projects__title">IoT</h3>
                        </div>

                        <span class="button button--flex button--small button--link projects__button">
                            View More
                            <i class="uil uil-arrow-right button__icon"></i>
                        </span>

                        <div class="projects__modal">
                            <div class="projects__modal-content">
                                <h4 class="projects__modal-title"> Review of Regulatory Criteria for using IoT Technologies in Radioactive Waste Management</h4>
                                <i class="uil uil-times projects__modal-close"></i>

                                <ul class="projects__modal-projects grid">
                                    <li class="projects__modal-project">
                                        <i class="uil uil-check-circle projects__modal-icon"></i>
                                        <p>Review of RFID (Radio Frequency Identification System) and IoT technologies</p>
                                    </li>
                                    <li class="projects__modal-project">
                                        <i class="uil uil-check-circle projects__modal-icon"></i>
                                        <p>Review of IoT applications in radioactive waste management</p>
                                    </li>
                                    <li class="projects__modal-project">
                                        <i class="uil uil-check-circle projects__modal-icon"></i>
                                        <p>Review of global IoT standards and best practices</p>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div> 

                    <!--==================== PROJECTS 11 ====================-->
                    <div class="projects__content">
                        <div>
                            <i class="uil uil-swatchbook projects__icon"></i>
                            <h3 class="projects__title">EUR</h3>
                        </div>

                        <span class="button button--flex button--small button--link projects__button">
                            View More
                            <i class="uil uil-arrow-right button__icon"></i>
                        </span>

                        <div class="projects__modal">
                            <div class="projects__modal-content">
                                <h4 class="projects__modal-title">APR1000 PAFS Standard Design Development and EUR Certification Support</h4>
                                <i class="uil uil-times projects__modal-close"></i>

                                <ul class="projects__modal-projects grid">
                                    <li class="projects__modal-project">
                                        <i class="uil uil-check-circle projects__modal-icon"></i>
                                        <p>Literature Review</p>
                                    </li>
                                    <li class="projects__modal-project">
                                        <i class="uil uil-check-circle projects__modal-icon"></i>
                                        <p>Technical Support</p>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div> 
                </div>
            </section>

            <!--==================== PAPERS ====================-->
            <section class="paper section" id="paper" data-id="paper">
                <h2 class="section__title">Papers</h2>
                <span class="section__subtitle">Published Papers</span>
                
                <div class="paper__container container swiper">
                    <div class="swiper-wrapper">
                        <!--==================== PAPER 1 ====================-->
                        <div class="paper__content grid swiper-slide">
                            <img src="assets/img/paper1.jpg" alt="CFD code OpenFOAM mesh for pool scrubbing geometry" class="paper__img">

                            <div class="paper__dat">
                                <h3 class="paper__title">#poolscrubbing</h3>
                                <p class="paper__description">CFD Simulation of High Inlet Velocity Air Flow into a Large Tank at Pool Scrubbing Conditions</p>
                                <a href="https://www.researchgate.net/publication/355117622_CFD_Simulation_of_High_Inlet_Velocity_Air_Flow_into_a_Large_Tank_at_Pool_Scrubbing_Conditions" target="_blank" class="button button--flex button--small paper__button">
                                    Read
                                    <i class="uil uil-arrow-right button__icon"></i>
                                </a>
                            </div>
                        </div>  

                        <!--==================== PAPER 2 ====================-->
                        <div class="paper__content grid swiper-slide">
                            <img src="assets/img/paper2.jpg" alt="Small modular reactor containment pressure and radioactivity" class="paper__img">

                            <div class="paper__dat">
                                <h3 class="paper__title">#PTanalysis</h3>
                                <p class="paper__description">CAP Code Version-up to 3.0 and Its Application to Pressure and Temperature Analysis</p>
                                <a href="https://www.researchgate.net/publication/346875695_CAP_Code_Version-up_to_30_and_Its_Application_to_Pressure_and_Temperature_Analysis" target="_blank" class="button button--flex button--small paper__button">
                                    Read
                                    <i class="uil uil-arrow-right button__icon"></i>
                                </a>
                            </div>
                        </div>   

                        <!--==================== PAPER 3 ====================-->
                        <div class="paper__content grid swiper-slide">
                            <img src="assets/img/paper3.jpg" alt="Integral experiment test facility" class="paper__img">

                            <div class="paper__dat">
                                <h3 class="paper__title">#heatloss</h3>
                                <p class="paper__description">System Code Analysis of ATLAS Facility Including Heat Loss Evaluation</p>
                                <a href="https://www.researchgate.net/publication/333992851_System_Code_Analysis_of_ATLAS_Facility_Including_Heat_Loss_Evaluations" target="_blank" class="button button--flex button--small paper__button">
                                    Read
                                    <i class="uil uil-arrow-right button__icon"></i>
                                </a>
                            </div>
                        </div>                       

                        <!--==================== PAPER 4 ====================-->
                        <div class="paper__content grid swiper-slide">
                            <img src="assets/img/paper4.jpg" alt="Wall condensation experiment" class="paper__img">

                            <div class="paper__dat">
                                <h3 class="paper__title">#wallcondensation</h3>
                                <p class="paper__description">Capability of MARS-KS on Predicting Wall Condensation in the Presence of Non-Condensable Gases</p>
                                <a href="https://www.researchgate.net/publication/306224035_Capability_of_MARS-KS_on_Predicting_Wall_Condensation_in_the_Presence_of_Non-Condensable_Gases" target="_blank" class="button button--flex button--small paper__button">
                                    Read
                                    <i class="uil uil-arrow-right button__icon"></i>
                                </a>
                            </div>
                        </div> 

                        <!--==================== PAPER 5 ====================-->
                        <div class="paper__content grid swiper-slide">
                            <img src="assets/img/paper5.jpg" alt="MARS-KS, GOTHIC, CUPID, and CFX codes comparison on COPAIN test facility" class="paper__img">

                            <div class="paper__dat">
                                <h3 class="paper__title">#codetocodecomparison</h3>
                                <p class="paper__description">Prediction of Wall Condensation in the Presence of Non-Condensable Gases through Various Thermal-Hydraulic Codes</p>
                                <a href="https://www.researchgate.net/publication/306224130_Prediction_of_Wall_Condensation_in_the_Presence_of_Non-Condensable_Gases_through_Various_Thermal-Hydraulic_Codes" target="_blank" class="button button--flex button--small paper__button">
                                    Read
                                    <i class="uil uil-arrow-right button__icon"></i>
                                </a>
                            </div>
                        </div> 
                        
                        <!--==================== PAPER 6 ====================-->
                        <div class="paper__content grid swiper-slide">
                            <img src="assets/img/paper6.jpg" alt="Small break loca accident facility" class="paper__img">

                            <div class="paper__dat">
                                <h3 class="paper__title">#scalinganlaysis</h3>
                                <p class="paper__description">Scaling Analysis for DVI Line Break Accident of APR1400 based on ATLAS Experiment</p>
                                <a href="https://www.researchgate.net/publication/306400133_Scaling_Analysis_for_DVI_Line_Break_Accident_of_APR1400_based_on_ATLAS_Experiment" target="_blank" class="button button--flex button--small paper__button">
                                    Read
                                    <i class="uil uil-arrow-right button__icon"></i>
                                </a>
                            </div>
                        </div>                         
                        
                        <!--==================== PAPER 7 ====================-->
                        <div class="paper__content grid swiper-slide">
                            <img src="assets/img/paper7.jpg" alt="Water velocity vector plot" class="paper__img">

                            <div class="paper__dat">
                                <h3 class="paper__title">#bubblediameter</h3>
                                <p class="paper__description">Bubble Diameter Evaluation in Pool Scrubbing Geometries</p>
                                <a href="https://www.researchgate.net/publication/370289690_Bubble_Diameter_Evaluation_in_Pool_Scrubbing_Geometries" target="_blank" class="button button--flex button--small paper__button">
                                    Read
                                    <i class="uil uil-arrow-right button__icon"></i>
                                </a>
                            </div>
                        </div>                         
                        
                        <!--==================== PAPER 8 ====================-->
                        <div class="paper__content grid swiper-slide">
                            <img src="assets/img/paper8.jpg" alt="Water velocity vector plot" class="paper__img">

                            <div class="paper__dat">
                                <h3 class="paper__title">#turbulence</h3>
                                <p class="paper__description">Influence of Inlet Turbulent Boundary Conditions on Bubble Diameter Calculation</p>
                                <a href="https://www.researchgate.net/publication/370902232_Influence_of_Inlet_Turbulent_Boundary_Conditions_on_Bubble_Diameter_Calculation" target="_blank" class="button button--flex button--small paper__button">
                                    Read
                                    <i class="uil uil-arrow-right button__icon"></i>
                                </a>
                            </div>
                        </div>                         

                    </div>

                        <!-- Add Arrows -->
                        <div class="swiper-button-next">
                            <i class="uil uil-angle-right-b swiper-paper-icon"></i>
                        </div>
                        <div class="swiper-button-prev">
                            <i class="uil uil-angle-left-b swiper-paper-icon"></i>
                        </div>

                        <!-- Add Pagination -->
                        <div class="swiper-pagination"></div>
                </div>
            </section>

            <!--==================== REQUEST MEETING ====================-->
            <section class="project section" id="meeting">
                <div class="project__bg">
                    <div class="project__container container grid">
                        <div class="project__data">
                            <h2 class="project__title">Do you have any questions?</h2>
                            <p class="project__description">Schedule a meeting and lets discuss!</p>
                            <!-- <a href="#meeting" class="button button--flex button--white">
                                Send a Request
                                <i class="uil uil-message project_icon button__icon"></i>
                            </a> -->
                            <a href="#meeting" onclick="Calendly.initPopupWidget({url: 'https://calendly.com/erolbicer/onlinemeeting?hide_gdpr_banner=1&text_color=7c716a&primary_color=f9660b'});return false;" class="button button--flex button--white">
                                Send a Request
                                <i href="#meeting" class="uil uil-message project_icon button__icon"></i>
                            </a>
                        </div>
                        <img src="assets/img/perfil.png" alt="Erol Bicer" class="project__img">
                    </div>
                </div>
            </section>

            <!--==================== TESTIMONIAL ====================-->
            <section class="testimonial section" id="testimonials">
                <h2 class="section__title">References</h2>
                <span class="section__subtitle">Testimonials</span>

                <div class="testimonial__container container swiper">
                    <div class="swiper-wrapper">
                         <!--==================== TESTIMONIAL 1 ====================-->
                         <div class="testimonial__content swiper-slide">
                            <div class="testimonial__data">
                                <div class="testimonial__header">
                                    <img src="assets/img/dsk.jpg" alt="" class="testimonial__img">

                                    <div>
                                        <h3 class="testimonial__name">Mr. David S. Kessel</h3>
                                        <span class="testimonial__client">KINGS, Research Professor</span>
                                    </div>
                                </div>
                                <!-- <div>
                                    <i class="uil uil-star testimonial__icon-star"></i>
                                    <i class="uil uil-star testimonial__icon-star"></i>
                                    <i class="uil uil-star testimonial__icon-star"></i>
                                    <i class="uil uil-star testimonial__icon-star"></i>
                                    <i class="uil uil-star testimonial__icon-star"></i>
                                </div> -->
                            </div>
                            <p class="testimonial__description">I have known Erol since 2014 when he was in my systems engineering class at KINGS and I can say without reservation that he is bright, hard working, and of the highest integrity.</p>
                         </div>
                         
                         <!--==================== TESTIMONIAL 2 ====================-->
                         <div class="testimonial__content swiper-slide">
                            <div class="testimonial__data">
                                <div class="testimonial__header">
                                    <img src="assets/img/ad.jpg" alt="" class="testimonial__img">

                                    <div>
                                        <h3 class="testimonial__name">Dr. Aya Diab</h3>
                                        <span class="testimonial__client">KINGS, Associate Professor</span>
                                    </div>
                                </div>
                                <!-- <div>
                                    <i class="uil uil-star testimonial__icon-star"></i>
                                    <i class="uil uil-star testimonial__icon-star"></i>
                                    <i class="uil uil-star testimonial__icon-star"></i>
                                    <i class="uil uil-star testimonial__icon-star"></i>
                                    <i class="uil uil-star testimonial__icon-star"></i>
                                </div> -->
                            </div>
                            <p class="testimonial__description">I met Erol in 2016, and ever since he always impressed me with his zeal to expand his knowledge, hone his skills and take on new challenges to enhance his career.</p>
                         </div>
                    </div>

                    <!-- Add Pagination -->
                    <div class="swiper-pagination swiper-pagination-testimonial"></div>
                </div>
            </section>

            <!--==================== VIDEOS ====================-->
            <section class="videos section" id="videos">
                <h2 class="section__title">Videos</h2>
                <span class="section__subtitle">Appearances</span>

                <div class="videos__container container grid">
                    <div class="videos__content-top">
                        <div class="iframe__container">
                            <span class="videos__subtitle">Global SMR & MMR Development Activities</span>
                            <iframe class="iframe" width="100%" height="100%" src="https://www.youtube.com/embed/qrbo3MOFXLc?rel=0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                        </div>
                    </div>
                    <div class="videos__content">
                        <div class="iframe__container">
                            <span class="videos__subtitle">KNS Workshop on SMR & MMR</span>
                            <iframe class="iframe" width="100%" height="100%" src="https://www.youtube.com/embed/mbRFUEH-VB8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                        </div>
                        <div class="iframe__container">
                            <span class="videos__subtitle">What is the age of Sunlight? </span>
                            <iframe class="iframe" width="100%" height="100%" src="https://www.youtube.com/embed/Y2ZKCvnSVag?rel=0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                        </div>
                        <div class="iframe__container">
                            <span class="videos__subtitle">Half Life & Radioactive Decay</span>
                            <iframe class="iframe" width="100%" height="100%" src="https://www.youtube.com/embed/CyPew95u3ws?rel=0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                        </div>
                        <div class="iframe__container">
                            <span class="videos__subtitle">Nuclear Engineering Conversations</span>
                            <iframe class="iframe" width="100%" height="100%" src="https://www.youtube.com/embed/EP2NPvoiEsw?rel=0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                        </div>
                    </div>   
                 </div>
            </section>

            <!--==================== PRESENTATION ====================-->
            <section class="presentation section" id="presentation">
                <h2 class="section__title">Presentations</h2>
                <span class="section__subtitle">Talks and Meetings</span>

                <div class="presentation__container container grid">
                    <div class="presentation__content">
                        <div class="iframe__container">
                            <span class="presentation__subtitle">FNC Technology Company Introduction</span>
                            <iframe allowfullscreen class="iframe" width="100%" height="100%"  src="https://www.beautiful.ai/embed/-N99gCWOIluAxGaB3Ki_?utm_source=beautiful_player&utm_medium=embed&utm_campaign=-MzlkefNLC76aJ1MLXfh"></iframe>
                        </div>                        
                        <div class="iframe__container">
                            <span class="presentation__subtitle">SMR & MMR Development Status in the World</span>
                            <iframe allowfullscreen class="iframe" width="100%" height="100%"  src="https://www.beautiful.ai/embed/-N9WTeD278rsbcimSTFQ?utm_source=beautiful_player&utm_medium=embed&utm_campaign=-N9WS-JQcqI9yrHAPO0K"></iframe>
                        </div>                                             
                        <div class="iframe__container">
                            <span class="presentation__subtitle">Non-electric Applications of Nuclear Energy</span>
                            <iframe allowfullscreen class="iframe" width="100%" height="100%"  src="https://www.beautiful.ai/embed/-N9ApKSzKtHuNwFS2cEY?utm_source=beautiful_player&utm_medium=embed&utm_campaign=-N9AnjGmWtBp2Tgf5cej"></iframe>
                        </div>                                             
                    </div>   
                 </div>
            </section>

            <!--==================== ONLINE MEETING ====================-->
            <!-- <section class="meeting section" id="meeting">
                <h2 class="section__title">Online Meeting</h2>
                <span class="section__subtitle">Send a Request</span>

                <div class="meeting__container container grid">
                    <div class="meeting__content">
                        <div class="zeeg__container">
                            <iframe class="iframe-meeting" width="100%" height="100%" src="https://zeeg.me/erol/onlinemeeting"></iframe>
                         </div>                        
                    </div>   
                 </div>
            </section> -->

            <!--==================== CONTACT ME ====================-->
            <section class="contact section" id="contact" data-id="contact">
                <h2 class="section__title">Contact Me</h2>
                <span class="section__subtitle">Get in Touch</span>

                <div class="contact__container container grid">
                    <div>
                        <div class="contact__information">
                            <i class="uil uil-phone contact__icon"></i>

                            <div>
                                <h3 class="contact__title">Call Me</h3>
                                <span class="contact__subtitle">+82-10-7497-0705</span>
                            </div>
                        </div>

                        <div class="contact__information">
                            <i class="uil uil-envelope contact__icon"></i>

                            <div>
                                <h3 class="contact__title">Email</h3>
                                <!-- <span class="contact__subtitle">erolbicer@live.com</span> -->
                                <p><a class="contact__subtitle" href="mailto:erolbicer@live.com">erolbicer@live.com</a></p>
                            </div>
                        </div>

                        <div class="contact__information">
                            <i class="uil uil-map-marker contact__icon"></i>

                            <div>
                                <h3 class="contact__title">Location</h3>
                                <span class="contact__subtitle">South Korea</span>
                            </div>
                        </div>
                    </div>

                    <form action="" class="contact__form grid">
                        <div class="contact__inputs grid">
                            <div class="contact__content">
                                <label for="" class="contact__label">Full Name</label>
                                <input type="text" placeholder="Enter full name" class="contact__input" id="fullName" onkeyup="validateName()">
                                <span id="name-error" class="contact__subtitle"></span>
                            </div>
                            <div class="contact__content">
                                <label for="" class="contact__label">Email</label>
                                <input type="email" placeholder="Enter email address" class="contact__input" id="email_id" onkeyup="validateEmail()">
                                <span id="email-error" class="contact__subtitle"></span>
                            </div>
                        </div>
                        <div class="contact__content">
                            <label for="" class="contact__label">Subject</label>
                            <input type="text" id="subject" placeholder="Enter a subject line" class="contact__input">
                        </div>
                        <div class="contact__content">
                            <label for="" class="contact__label">Message</label>
                            <textarea name="" cols="0" rows="7" placeholder="Enter your message" class="contact__input" id="message" onkeyup="validateMessage()"></textarea>
                            <span id="message-error" class="contact__subtitle"></span>
                        </div>
                        <div>
                            <a onclick="return SendMail()" class="button button--flex">
                            Send Message
                            <i class="uil uil-message button__icon"></i>
                        </a>
                        </div>
                    </form>
                </div>
            </section>
        </main>

        <!--==================== FOOTER ====================-->
        <footer class="footer">
            <div class="footer__bg">
                <div class="footer__container container grid">
                    <div>
                        <a href="#" class="footer__title">Erol Bicer</a><br>
                        <span class="footer__subtitle">Nuclear Engineer</span>
                    </div>

                    <ul class="footer__links">
                        <li>
                            <a href="#projects" class="footer__link">Projects</a>
                        </li>
                        <li>
                            <a href="#paper" class="footer__link">Papers</a>
                        </li>
                        <li>
                            <a href="#testimonials" class="footer__link">References</a>
                        </li>
                        <li>
                            <a href="#videos" class="footer__link">Videos</a>
                        </li>
                        <li>
                            <a href="#meeting" class="footer__link">Meeting</a>
                        </li>
                        <li>
                            <a href="#presentation" class="footer__link">Presentations</a>
                        </li>
                    </ul>

                    <div class="footer__socials">
                        <a href="https://www.linkedin.com/in/erolbicer/" target="_blank" class="footer__social">
                            <i class="uil uil-linkedin-alt"></i>
                        </a>

                        <a href="https://www.researchgate.net/profile/Erol-Bicer/research" target="_blank" class="footer__social">
                            <i class="uil uil-book-open"></i>
                        </a>

                        <a href="https://github.com/nucerl" target="_blank" class="footer__social">
                            <i class="uil uil-github-alt"></i>
                        </a>

                    </div>
                </div>

                <p class="footer__copy">&#169; All rights reserved.</p>
            </div>
        </footer>
        
        <!--==================== SCROLL TOP ====================-->
        <a href="" class="scrollup" id="scroll-up">
            <i class="uil uil-arrow-up scrollup__icon"></i>
        </a>

        <!--==================== SWIPER JS ====================-->
        <script src="assets/js/swiper-bundle.min.js"></script>

        <!--==================== MAIN JS ====================-->
        <script src="assets/js/main.js"></script>
    </body>
</html>
