<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />

    <link
      rel="stylesheet"
      href="https://unicons.iconscout.com/release/v3.0.6/css/line.css"
    />
    <link rel="stylesheet" href="assets/css/style.css" />
    <link rel="stylesheet" href="assets/css/swiper-bundle.min.css" />
    <link
      rel="stylesheet"
      href="https://unpkg.com/swiper/swiper-bundle.min.css"
    />
    <title>Responsive Portfilio Website</title>
  </head>

  <body>
    <header class="header" id="header">
      <nav class="nav container">
        <a href="#" class="nav__logo">Devyansh Bansal</a>

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
              <a href="#services" class="nav__link">
                <i class="uil uil-briefcase-alt nav__icon"></i> Services
              </a>
            </li>
            <!-- <li class="nav__item">
                        <a href="#portfolio" class="nav__link">
                            <i class="uil uil-scenery nav__icon"></i> Portfolio
                        </a>
                    </li> -->
            <li class="nav__item">
              <a href="#contact" class="nav__link">
                <i class="uil uil-message nav__icon"></i> Contactme
              </a>
            </li>
          </ul>
          <i class="uil uil-times nav__close" id="nav-close"></i>
        </div>

        <div class="nav__btns">
          <!-- Theme Change Button -->
          <i class="uil uil-moon change-theme" id="theme-button"></i>

          <div class="nav__toggle" id="nav-toggle">
            <i class="uil uil-apps"></i>
          </div>
        </div>
      </nav>
    </header>

    <main class="main">
      <section class="home section" id="home">
        <div class="home__container container grid">
          <div class="home__content grid">
            <div class="home__social">
              <a
                href="https://www.linkedin.com/"
                target="_blank"
                class="home__social-icon"
              >
                <i class="uil uil-linkedin-alt"></i>
              </a>

              <a
                href="https://www.github.com/"
                target="_blank"
                class="home__social-icon"
              >
                <i class="uil uil-github-alt"></i>
              </a>

              <a
                href="https://www.instagram.com/"
                target="_blank"
                class="home__social-icon"
              >
                <i class="uil uil-instagram"></i>
              </a>

              <a
                href="https://www.twitter.com/"
                target="_blank"
                class="home__social-icon"
              >
                <i class="uil uil-twitter-alt"></i>
              </a>
            </div>

            <div class="home__img">
              <svg
                class="home__blob"
                viewBox="0 0 200 187"
                xmlns="http://www.w3.org/2000/svg"
                xmlns:xlink="http://www.w3.org/1999/xlink"
              >
                <mask id="mask0" mask-type="alpha">
                  <path
                    d="M190.312 36.4879C206.582 62.1187 201.309 102.826 182.328 134.186C163.346 165.547 
                                130.807 187.559 100.226 186.353C69.6454 185.297 41.0228 161.023 21.7403 129.362C2.45775 
                                97.8511 -7.48481 59.1033 6.67581 34.5279C20.9871 10.1032 59.7028 -0.149132 97.9666 
                                0.00163737C136.23 0.303176 174.193 10.857 190.312 36.4879Z"
                  />
                </mask>
                <g mask="url(#mask0)">
                  <path
                    d="M190.312 36.4879C206.582 62.1187 201.309 102.826 182.328 134.186C163.346 
                                165.547 130.807 187.559 100.226 186.353C69.6454 185.297 41.0228 161.023 21.7403 
                                129.362C2.45775 97.8511 -7.48481 59.1033 6.67581 34.5279C20.9871 10.1032 59.7028 
                                -0.149132 97.9666 0.00163737C136.23 0.303176 174.193 10.857 190.312 36.4879Z"
                  />

                  <image
                    class="home__blob-img"
                    x="7"
                    y="5"
                    xlink:href="assets/img/perfil.png"
                  />
                </g>
              </svg>
            </div>

            <div class="home__data">
              <h1 class="home__title">Hi, I'am Devyansh</h1>
              <h3 class="home__subtitle">Frondend Developer</h3>
              <p class="home__description">
                High level experience in web design and development knowledge,
                producing quality work.
              </p>
              <a href="#contact" class="button button--flex">
                Contact Me <i class="uil uil-message button__icon"></i>
              </a>
            </div>
          </div>

          <div class="home__scroll">
            <a href="#about" class="home__scroll-button button--flex">
              <i class="uil uil-mouse-alt home__scroll-mouse"></i>
              <span class="home__scroll-name">Scroll down</span>
              <i class="uil uil-arrow-down home_scroll-arrow"></i>
            </a>
          </div>
        </div>
      </section>

      <section class="about section" id="about">
        <h2 class="section__title">About Me</h2>
        <span class="section__subtitle">My introduction</span>

        <div class="about__container container grid">
          <img src="assets/img/about.jpeg" alt="" class="about__img" />

          <div class="about__data">
            <p class="about__discription">
              Web developer, with extensive knowledge, like to work in web
              technologies and Ui / Ux design, delivering qulity work
            </p>

            <div class="about__info">
              <div>
                <span class="about__info-title">02+</span>
                <span class="about__info-name"
                  >Years <br />
                  experience</span
                >
              </div>

              <div>
                <span class="about__info-title">05+</span>
                <span class="about__info-name"
                  >Completed <br />
                  project</span
                >
              </div>
            </div>

            <div class="about__buttons">
              <a
                download=""
                href="assets/pdf/cv.pdf"
                class="button button--flex"
              >
                Download Resume<i class="uil uil-download-alt button__icon"></i>
              </a>
            </div>
          </div>
        </div>
      </section>

      <section class="skills section" id="skills">
        <h2 class="section__title">Skills</h2>
        <span class="section__subtitle">My technical level</span>

        <div class="skills__container container grid">
          <div>
            <div class="skills__content skills__open">
              <div class="skills__header">
                <i class="uil uil-brackets-curly skills__icon"></i>

                <div>
                  <h1 class="skills__title">Frontend developer</h1>
                  <span class="skills__subtitle">More than 4 Years</span>
                </div>

                <i class="uil uil-angle-down skills__arrow"></i>
              </div>

              <div class="skills__list grid">
                <div class="skills__data">
                  <div class="skills__title">
                    <h3 class="skills__name">HTML</h3>
                    <span class="skills__number">90%</span>
                  </div>
                  <div class="skills__bar">
                    <span class="skills__percentage skills__html"></span>
                  </div>
                </div>

                <div class="skills__data">
                  <div class="skills__title">
                    <h3 class="skills__name">CSS</h3>
                    <span class="skills__number">80%</span>
                  </div>
                  <div class="skills__bar">
                    <span class="skills__percentage skills__css"></span>
                  </div>
                </div>

                <div class="skills__data">
                  <div class="skills__title">
                    <h3 class="skills__name">JavaScript</h3>
                    <span class="skills__number">60%</span>
                  </div>
                  <div class="skills__bar">
                    <span class="skills__percentage skills__js"></span>
                  </div>
                </div>

                <div class="skills__data">
                  <div class="skills__title">
                    <h3 class="skills__name">React</h3>
                    <span class="skills__number">85%</span>
                  </div>
                  <div class="skills__bar">
                    <span class="skills__percentage skills__react"></span>
                  </div>
                </div>
              </div>
            </div>

            <div class="skills__content skills__close">
              <div class="skills__header">
                <i class="uil uil-server-network skills__icon"></i>

                <div>
                  <h1 class="skills__title">Backend developer</h1>
                  <span class="skills__subtitle">More than 2 Years</span>
                </div>

                <i class="uil uil-angle-down skills__arrow"></i>
              </div>

              <div class="skills__list grid">
                <div class="skills__data">
                  <div class="skills__title">
                    <h3 class="skills__name">PHP</h3>
                    <span class="skills__number">80%</span>
                  </div>
                  <div class="skills__bar">
                    <span class="skills__percentage skills__php"></span>
                  </div>
                </div>

                <div class="skills__data">
                  <div class="skills__title">
                    <h3 class="skills__name">Node JS</h3>
                    <span class="skills__number">70%</span>
                  </div>
                  <div class="skills__bar">
                    <span class="skills__percentage skills__node"></span>
                  </div>
                </div>

                <div class="skills__data">
                  <div class="skills__title">
                    <h3 class="skills__name">Firebase</h3>
                    <span class="skills__number">80%</span>
                  </div>
                  <div class="skills__bar">
                    <span class="skills__percentage skills__firebase"></span>
                  </div>
                </div>

                <div class="skills__data">
                  <div class="skills__title">
                    <h3 class="skills__name">Python</h3>
                    <span class="skills__number">55%</span>
                  </div>
                  <div class="skills__bar">
                    <span class="skills__percentage skills__python"></span>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <div>
            <div class="skills__content skills__close">
              <div class="skills__header">
                <i class="uil uil-swatchbook skills__icon"></i>

                <div>
                  <h1 class="skills__title">Designer</h1>
                  <span class="skills__subtitle">More than 5 Years</span>
                </div>

                <i class="uil uil-angle-down skills__arrow"></i>
              </div>

              <div class="skills__list grid">
                <div class="skills__data">
                  <div class="skills__title">
                    <h3 class="skills__name">Figma</h3>
                    <span class="skills__number">90%</span>
                  </div>
                  <div class="skills__bar">
                    <span class="skills__percentage skills__figma"></span>
                  </div>
                </div>

                <div class="skills__data">
                  <div class="skills__title">
                    <h3 class="skills__name">Sketch</h3>
                    <span class="skills__number">85%</span>
                  </div>
                  <div class="skills__bar">
                    <span class="skills__percentage skills__sketch"></span>
                  </div>
                </div>

                <div class="skills__data">
                  <div class="skills__title">
                    <h3 class="skills__name">Photoshop</h3>
                    <span class="skills__number">85%</span>
                  </div>
                  <div class="skills__bar">
                    <span class="skills__percentage skills__photoshop"></span>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="qualification section">
        <h2 class="section__title">Qualification</h2>
        <span class="section__subtitle">My personal jouorney</span>

        <div class="qualification__container container">
          <div class="qualification__tabs">
            <div
              class="qualification__button button--flex qualification__active"
              data-target="#education"
            >
              <i class="uil uil-graduation-cap qualification__icon"></i>
              Education
            </div>

            <div class="qualification__button button--flex" data-target="#work">
              <i class="uil uil-briefcase-alt qualification__icon"></i>
              Work
            </div>
          </div>

          <div class="qualification__sections">
            <div
              class="qualification__content qualification__active"
              data-content
              id="education"
            >
              <div class="qualification__data">
                <div>
                  <h3 class="qualification__title">Computer Engineer</h3>
                  <span class="qualification__subtitle"
                    >Thapar Institute of Engineering & Technology</span
                  >
                  <div class="qualification__calender">
                    <i class="uil uil-calender-alt"></i>
                    2020 - 2024
                  </div>
                </div>

                <div>
                  <span class="qualification__rounder"></span>
                  <span class="qualification__line"></span>
                </div>
              </div>

              <div class="qualification__data">
                <div></div>

                <div>
                  <span class="qualification__rounder"></span>
                  <span class="qualification__line"></span>
                </div>

                <div>
                  <h3 class="qualification__title">Web Design</h3>
                  <span class="qualification__subtitle">Myself</span>
                  <div class="qualification__calender">
                    <i class="uil uil-calender-alt"></i>
                    2020 - 2024
                  </div>
                </div>
              </div>

              <div class="qualification__data">
                <div>
                  <h3 class="qualification__title">Web Development</h3>
                  <span class="qualification__subtitle"
                    >Thapar Institute of Engineering & Technology</span
                  >
                  <div class="qualification__calender">
                    <i class="uil uil-calender-alt"></i>
                    2020 - 2024
                  </div>
                </div>

                <div>
                  <span class="qualification__rounder"></span>
                  <!-- <span class="qualification__line"></span> -->
                </div>
              </div>
            </div>

            <div class="qualification__content" data-content id="work">
              <div class="qualification__data">
                <div>
                  <h3 class="qualification__title">Computer Engineer</h3>
                  <span class="qualification__subtitle"
                    >Thapar Institute of Engineering & Technology</span
                  >
                  <div class="qualification__calender">
                    <i class="uil uil-calender-alt"></i>
                    2020 - 2024
                  </div>
                </div>

                <div>
                  <span class="qualification__rounder"></span>
                  <span class="qualification__line"></span>
                </div>
              </div>

              <div class="qualification__data">
                <div></div>

                <div>
                  <span class="qualification__rounder"></span>
                  <!-- <span class="qualification__line"></span> -->
                </div>

                <div>
                  <h3 class="qualification__title">Web Design</h3>
                  <span class="qualification__subtitle">Myself</span>
                  <div class="qualification__calender">
                    <i class="uil uil-calender-alt"></i>
                    2020 - 2024
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="services section" id="services">
        <h2 class="section__title">Services</h2>
        <span class="section__subtitle">What I offer</span>

        <div class="services__container container grid">
          <div class="services__content">
            <div>
              <i class="uil uil-web-grid services__icon"></i>
              <h3 class="services__title">
                Ui/Ux <br />
                Designer
              </h3>
            </div>

            <span
              class="button button--flex button--small button--link services__button"
            >
              View More
              <i class="uil uil-arrow-right button__icon"></i>
            </span>

            <div class="services__modal">
              <div class="services__modal-content">
                <h4 class="services__modal-title">
                  Ui/Ux <br />
                  Designer
                </h4>
                <i class="uil uil-times services__modal-close"></i>

                <ul class="services__modal-services grid">
                  <li class="services__modal-service">
                    <i class="uil uil-check-circle services__modal-icon"></i>
                    <p>I develop the user interfaces.</p>
                  </li>

                  <li class="services__modal-service">
                    <i class="uil uil-check-circle services__modal-icon"></i>
                    <p>Web page development.</p>
                  </li>

                  <li class="services__modal-service">
                    <i class="uil uil-check-circle services__modal-icon"></i>
                    <p>I create ux element interactions.</p>
                  </li>

                  <li class="services__modal-service">
                    <i class="uil uil-check-circle services__modal-icon"></i>
                    <p>I position your company brand.</p>
                  </li>
                </ul>
              </div>
            </div>
          </div>

          <div class="services__content">
            <div>
              <i class="uil uil-arrow services__icon"></i>
              <h3 class="services__title">
                Frontend <br />
                Developer
              </h3>
            </div>

            <span
              class="button button--flex button--small button--link services__button"
            >
              View More
              <i class="uil uil-arrow-right button__icon"></i>
            </span>

            <div class="services__modal">
              <div class="services__modal-content">
                <h4 class="services__modal-title">
                  Frontend <br />
                  Developer
                </h4>
                <i class="uil uil-times services__modal-close"></i>

                <ul class="services__modal-services grid">
                  <li class="services__modal-service">
                    <i class="uil uil-check-circle services__modal-icon"></i>
                    <p>I develop the user interfaces.</p>
                  </li>

                  <li class="services__modal-service">
                    <i class="uil uil-check-circle services__modal-icon"></i>
                    <p>Web page development.</p>
                  </li>

                  <li class="services__modal-service">
                    <i class="uil uil-check-circle services__modal-icon"></i>
                    <p>I create ux element interactions.</p>
                  </li>

                  <li class="services__modal-service">
                    <i class="uil uil-check-circle services__modal-icon"></i>
                    <p>I position your company brand.</p>
                  </li>
                </ul>
              </div>
            </div>
          </div>

          <div class="services__content">
            <div>
              <i class="uil uil-pen services__icon"></i>
              <h3 class="services__title">
                Branding <br />
                Designer
              </h3>
            </div>

            <span
              class="button button--flex button--small button--link services__button"
            >
              View More
              <i class="uil uil-arrow-right button__icon"></i>
            </span>

            <div class="services__modal">
              <div class="services__modal-content">
                <h4 class="services__modal-title">
                  Branding <br />
                  Designer
                </h4>
                <i class="uil uil-times services__modal-close"></i>

                <ul class="services__modal-services grid">
                  <li class="services__modal-service">
                    <i class="uil uil-check-circle services__modal-icon"></i>
                    <p>I develop the user interfaces.</p>
                  </li>

                  <li class="services__modal-service">
                    <i class="uil uil-check-circle services__modal-icon"></i>
                    <p>Web page development.</p>
                  </li>

                  <li class="services__modal-service">
                    <i class="uil uil-check-circle services__modal-icon"></i>
                    <p>I create ux element interactions.</p>
                  </li>

                  <li class="services__modal-service">
                    <i class="uil uil-check-circle services__modal-icon"></i>
                    <p>I position your company brand.</p>
                  </li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- <section class="portfolio section" id="portfolio">
            <h2 class="section__title">Portfolio</h2>
            <span class="section__subtitle">Most recent work</span>

            <div class="portfolio__container container swiper mySwiper">
                <div class="swiper-wrapper">
                    <div class="portfolio__content grid swiper-slide">
                        <img src="assets/img/portfolio1.jpg" alt="" class="portfolio__img">

                        <div class="portfolio__data">
                            <h3 class="portfolio__titel">Modern Website</h3>
                            <p class="portfolio__description">Website adaptable to all devices, with ui components and
                                animated interactions.</p>
                            <a href="#" class="button button--flex button--small portfolio__button">
                                Demo
                                <i class="uil uil-arrow-right button__icon"></i>
                            </a>
                        </div>
                    </div>

                    <div class="portfolio__content grid swiper-slide">
                        <img src="assets/img/portfolio2.jpg" alt="" class="portfolio__img">

                        <div class="portfolio__data">
                            <h3 class="portfolio__titel">Brand Design</h3>
                            <p class="portfolio__description">Website adaptable to all devices, with ui components and
                                animated interactions.</p>
                            <a href="#" class="button button--flex button--small portfolio__button">
                                Demo
                                <i class="uil uil-arrow-right button__icon"></i>
                            </a>
                        </div>
                    </div>

                    <div class="portfolio__content grid swiper-slide">
                        <img src="assets/img/portfolio3.jpg" alt="" class="portfolio__img">

                        <div class="portfolio__data">
                            <h3 class="portfolio__titel">Online Store</h3>
                            <p class="portfolio__description">Website adaptable to all devices, with ui components and
                                animated interactions.</p>
                            <a href="#" class="button button--flex button--small portfolio__button">
                                Demo
                                <i class="uil uil-arrow-right button__icon"></i>
                            </a>
                        </div>
                    </div>
                </div>

                <div class="swiper-button-next"></div>
                <div class="swiper-button-prev"></div>

                <div class="swiper-pagination"></div>
            </div>
        </section> -->

      <section class="project section">
        <div class="project__bg">
          <div class="project__container container grid">
            <div class="project__data">
              <h2 class="project__title">You have a new project</h2>
              <p class="project__description">
                If you have a project idea, contact me.
              </p>
              <a href="#contact" class="button button--flex button--white">
                Contact Me
                <i class="uil uil-message project__icon button__icon"></i>
              </a>
            </div>

            <img src="assets/img/about.jpeg" alt="" class="project__img" />
          </div>
        </div>
      </section>

      <section class="contact section" id="contact">
        <h2 class="section__title">Contact Me</h2>
        <span class="section__subtitle">Get in touch</span>

        <div class="contact__container container grid">
          <div>
            <div class="contact__information">
              <i class="uil uil-envelope contact__icon"></i>

              <div>
                <h3 class="contact__title">Email</h3>
                <span class="contact__subtitle"
                  >devyanshbansal123@gmail.com</span
                >
              </div>
            </div>
          </div>

          <form
            action=""
            class="contact__form grid"
            method="post"
            name="myform"
            enctype="text/plain"
            id="form"
            onsubmit="formaction(this)"
          >
            <div class="contact__inputs grid">
              <div class="contact__content">
                <label for="" class="contact__label">Name</label>
                <input type="text" class="contact__input" id="name" />
              </div>

              <div class="contact__content">
                <label for="" class="contact__label">Email</label>
                <input type="email" class="contact__input" id="email" />
              </div>
            </div>

            <div class="contact__content">
              <label for="" class="contact__label">Project</label>
              <input type="text" class="contact__input" id="title" />
            </div>

            <div class="contact__content">
              <label for="" class="contact__label">Message</label>
              <input type="text" class="contact__input" id="description" />
              <!-- <textarea name="" id="description" cols="0" rows="7" class="contact__input"></textarea> -->
            </div>

            <div>
              <input
                type="submit"
                name="submit"
                value="Send Message"
                class="contact--button button button--flex"
                id="submit"
              />
              <!-- <a href="" class="button button--flex" id="submit">
                            Send Message
                            <i class="uil uil-message button__icon"></i>
                        </a> -->
            </div>
          </form>
        </div>
      </section>

      <footer class="footer">
        <div class="footer__bg">
          <div class="footer__container container grid">
            <div>
              <h1 class="footer__title">Devyansh Bansal</h1>
              <span class="footer__subtitle">Frontend Developer</span>
            </div>

            <ul class="footer__links">
              <li>
                <a href="#services" class="footer__link">Services</a>
              </li>

              <!-- <li>
                            <a href="#portfolio" class="footer__link">Portfolio</a>
                        </li> -->

              <li>
                <a href="#contact" class="footer__link">ContactMe</a>
              </li>
            </ul>

            <div class="footer__socials">
              <a
                href="https://github.com/"
                target="_blank"
                class="footer__social"
              >
                <i class="uil uil-github-alt"></i>
              </a>

              <a
                href="https://www.instagram.com/"
                target="_blank"
                class="footer__social"
              >
                <i class="uil uil-instagram"></i>
              </a>

              <a
                href="https://www.twitter.com/"
                target="_blank"
                class="footer__social"
              >
                <i class="uil uil-twitter-alt"></i>
              </a>

              <a
                href="https://www.linkedin.com/"
                target="_blank"
                class="footer__social"
              >
                <i class="uil uil-linkedin-alt"></i>
              </a>
            </div>
          </div>

          <p class="footer__copy">
            &#169; Devyansh Bansal. All rights reserved
          </p>
        </div>
      </footer>

      <a href="#" class="scrollup" id="scroll-up">
        <i class="uil uil-arrow-up scrollup__icon"></i>
      </a>
    </main>

    <script src="assets/js/main.js"></script>
    <script src="assets/js/swiper-bundle.min.js"></script>
    <script src="https://unpkg.com/swiper/swiper-bundle.min.js"></script>
  </body>
</html>
