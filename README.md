<h1 align="center">
  <a href="#"><img src="https://i.imgur.com/kIeJdDm.png" alt="Hotdog"></a>
  Hotdog 🌭
</h1>
<p align="center">
    <img alt="Size" src="https://img.shields.io/github/languages/code-size/WilardzySenpai/Hotdog">
    <img alt="discord-ver" src="https://img.shields.io/badge/discord.js-v12.5.3-blue">
    <img alt="database" src="https://img.shields.io/badge/database-mongodb-informational?style=flat&logo=mongodb&logoColor=white&color=blue">
    <img alt="Stars" src="https://img.shields.io/github/stars/WilardzySenpai/Hotdog">
    <img alt="Fork" src="https://img.shields.io/github/forks/WilardzySenpai/Hotdog">
    <img alt="License" src="https://img.shields.io/github/license/WilardzySenpai/Hotdog">
</p>

## 💻 Requirements
1. Nodejs 12: **[Link](https://nodejs.org)**
2. Git: **[Link](https://git-scm.com)**
3. Discord Bot Token: **[Link](https://discord.com/developers/applications)**
4. OsuClientApi: **[Link](https://osu.ppy.sh/home/account/edit#new-oauth-application)**
5. MongoDB Database's URI: **[Link](https://www.mongodb.com)**

## 📖License
Released under the [MIT License](https://github.com/WilardzySenpai/Hotdog/blob/main/LICENSE)

   <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="shortcut icon" href="https://i.imgur.com/sLf1MVL.png" type="image/x-icon">
        <link href="https://cdn.jsdelivr.net/npm/remixicon@2.5.0/fonts/remixicon.css" rel="stylesheet">
        <link rel="stylesheet" href="views/assets/css/styles.css">
        <title>Hotdog - 🌭</title>
      <meta name="theme-color" content="#ffcc00">
  <meta name="title" content="Hotdog - 🌭">
  <meta name="description" content="Hotdog support Music, Economy, Games, Fun, Moderation, and more!">
  <meta name="keywords" content="Hotdog">
  <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
  <meta name="language" content="English">
  <meta property="og:image" content="https://i.imgur.com/xaFKENg.png" />
    </head>
    <body oncontextmenu="return false;">
        <!--=============== HEADER ===============-->
        <header class="header" id="header">
            <nav class="nav container">
                <a href="#" class="nav__logo">
                    <img src="https://i.imgur.com/xaFKENg.png" alt="">
                </a>

                <div class="nav__menu" id="nav-menu">
                    <ul class="nav__list">
                        <li class="nav__item">
                            <a href="#home" class="nav__link active-link">Home</a>
                        </li>
                        <li class="nav__item">
                            <a href="#commands" class="nav__link">Commands</a>
                        </li>
                        <li class="nav__item">
                            <a href="#premium" class="nav__link">Premium</a>
                        </li>
                    </ul>

                    <div class="nav__close" id="nav-close">
                        <i class="ri-close-line"></i>
                    </div>
                </div>

                <div class="nav__toggle" id="nav-toggle">
                    <i class="ri-function-line"></i>
                </div>
            </nav>
        </header>

        <main class="main">
            <!--=============== HOME ===============-->
            <section class="home section" id="home">
                <div class="home__container container grid">
                    <div>
                        <img src="https://i.imgur.com/yhJ5pcC.png" alt="" class="home__img">
                    </div>
                    
                    <div class="home__data">
                        <div class="home__header">
                            <h1 class="home__title">Hakdog</h1>
                            <h2 class="home__subtitle">Hotdog</h2>
                        </div>

                        <div class="home__footer">
                            <h3 class="home__title-description">Overview</h3>
                            <p class="home__description">Hotdog support Music, Economy, Games, Fun, Moderation, and more!
                            </p>
                            <a href="https://discord.com/api/oauth2/authorize?client_id=953247413869633536&permissions=18756398167&scope=bot" class="button button--flex">
                                <span class="button--flex">
                                    <i class="ri-links-line button__icon"></i></i> Invite Now!
                            </a>
                        </div>
                    </div>
                </div>
            </section>

            <!--=============== SPECS ===============-->
            <section class="specs section grid" id="commands">
                <h2 class="section__title section__title-gradient">Commands</h2>

                <div class="specs__container container grid">
                    <div class="specs__content grid">
                        <div class="specs__data">
                            <i class="ri-music-2-line specs__icon"></i>
                            <h3 class="specs__title">Music</h3>
                            <span class="specs__subtitle">play music from youtube</span>
                        </div>
    
                        <div class="specs__data">
                            <i class="ri-coins-line specs__icon"></i>
                            <h3 class="specs__title">Economy</h3>
                            <span class="specs__subtitle">A game to play with friends</span>
                        </div>
    
                        <div class="specs__data">
                            <i class="ri-shield-line specs__icon"></i>
                            <h3 class="specs__title">Moderation</h3>
                            <span class="specs__subtitle">To moderate you're server</span>
                        </div>
    
                        <div class="specs__data">
                            <i class="ri-account-circle-line specs__icon"></i>
                            <h3 class="specs__title">Welcome and Verify</h3>
                            <span class="specs__subtitle">To Welcome you're new member's joined <br> and Verification</span>
                        </div>
                    </div>
                    
                    <div>
                        <img src="https://i.imgur.com/vPOqIWJ.png" alt="" class="specs__img">
                    </div>
                </div>
            </section>

            <!--=============== CASE ===============-->
            <section class="case section grid" id="premium">
                <h2 class="section__title section__title-gradient">Premium</h2>

                <div class="case__container container grid">
                    <div>
                        <img src="https://i.imgur.com/dGyNDLm.png" alt="" class="case__img">
                    </div>

                    <div class="case__data">
                        <p class="case__description">Hotdogs have some premium commands, this is only to support us! and you can use a code hotdogs! for free premium!
                        </p>
                        <a href="#premium" class="button button--flex">
                            <i class="ri-vip-diamond-line button__icon"></i> Use code Hotdogs!
                        </a>
                    </div>
                </div>
            </section>

            <!--=============== DISCOUNT ===============-->
            <section class="discount section">
                <div class="discount__container container grid">
                    <div class="discount__animate">
                        <h2 class="discount__title">Eat Hotdogs don't let Hotdogs <br> Eat you!</h2>
                        <p class="discount__description">Invite Hotdog to you're server!</p>
                        <a href="https://discord.com/api/oauth2/authorize?client_id=953247413869633536&permissions=18756398167&scope=bot" class="button button--flex">
                            <i class="ri-links-line button__icon"></i> Hotdog!
                        </a>
                    </div>

                    <img src="https://i.imgur.com/nZWhoZT.png" alt="" class="discount__img">
                </div>
            </section>

        <!--=============== FOOTER ===============-->
        <footer class="footer section">
            <div class="footer__container container grid">
                <a href="#" class="footer__logo">
                    <img src="assets/img/logo.png" alt="">
                </a>
    
                <div class="footer__content">
                    <h3 class="footer__title">Hotdogs</h3>
    
                    <ul class="footer__links">
                        <li>
                            <a href="?#home" class="footer__link">Home</a>
                        </li>
                        <li>
                            <a href="https://discord.com/api/oauth2/authorize?client_id=953247413869633536&permissions=18756398167&scope=bot" class="footer__link">Invite</a>
                        </li>
                        <li>
                            <a href="?#commands" class="footer__link">Commands</a>
                        </li>
                        <li>
                            <a href="?#premium" class="footer__link">Premium</a>
                        </li>
                    </ul>
                </div>
    
                <div class="footer__content">
                    <h3 class="footer__title">Support</h3>
    
                    <ul class="footer__links">
                        <li>
                            <a href="https://discord.gg/PQFq6efKbJ" class="footer__link">Server</a>
                        </li>
                    </ul>
                </div>
    
                <div class="footer__content">
                  <div class="footer__social">
                        <a href="https://www.facebook.com/" target="_blank" class="footer__social-link">
                            <i class="ri-facebook-fill"></i>
                        </a>
                        <a href="https://www.instagram.com/" target="_blank" class="footer__social-link">
                            <i class="ri-instagram-line"></i>
                        </a>
                        <a href="https://twitter.com/" target="_blank" class="footer__social-link">
                            <i class="ri-twitter-line"></i>
                        </a>
                    </div>
                </div>
            </div>

            <p class="footer__copy">
                <a href="https://discord.gg/PQFq6efKbJ" target="_blank" class="footer__copy-link">&#169; Hotdogs. All right reserved</a>
            </p>
        </footer>

        <!--=============== SCROLL UP ===============-->
        <a href="#" class="scrollup" id="scroll-up">
            <i class="ri-arrow-up-s-line scrollup__icon"></i>
        </a>
        
        <!--=============== SCROLL REVEAL ===============-->
        <script src="https://unpkg.com/scrollreveal"></script>

        <!--=============== MAIN JS ===============-->
        <script>/*=============== SHOW MENU ===============*/
const navMenu = document.getElementById('nav-menu'),
      navToggle = document.getElementById('nav-toggle'),
      navClose = document.getElementById('nav-close')

/*===== MENU SHOW =====*/
/* Validate if constant exists */
if(navToggle){
    navToggle.addEventListener('click', () =>{
        navMenu.classList.add('show-menu')
    })
}

/*===== MENU HIDDEN =====*/
/* Validate if constant exists */
if(navClose){
    navClose.addEventListener('click', () =>{
        navMenu.classList.remove('show-menu')
    })
}

/*=============== REMOVE MENU MOBILE ===============*/
const navLink = document.querySelectorAll('.nav__link')

function linkAction(){
    const navMenu = document.getElementById('nav-menu')
    // When we click on each nav__link, we remove the show-menu class
    navMenu.classList.remove('show-menu')
}
navLink.forEach(n => n.addEventListener('click', linkAction))

/*=============== CHANGE BACKGROUND HEADER ===============*/
function scrollHeader(){
    const header = document.getElementById('header')
    // When the scroll is greater than 50 viewport height, add the scroll-header class to the header tag
    if(this.scrollY >= 50) header.classList.add('scroll-header'); else header.classList.remove('scroll-header')
}
window.addEventListener('scroll', scrollHeader)

/*=============== SHOW SCROLL UP ===============*/ 
function scrollUp(){
    const scrollUp = document.getElementById('scroll-up');
    // When the scroll is higher than 200 viewport height, add the show-scroll class to the a tag with the scroll-top class
    if(this.scrollY >= 200) scrollUp.classList.add('show-scroll'); else scrollUp.classList.remove('show-scroll')
}
window.addEventListener('scroll', scrollUp)

/*=============== SCROLL SECTIONS ACTIVE LINK ===============*/
const sections = document.querySelectorAll('section[id]')

function scrollActive(){
    const scrollY = window.pageYOffset

    sections.forEach(current =>{
        const sectionHeight = current.offsetHeight
        const sectionTop = current.offsetTop - 50;
        sectionId = current.getAttribute('id')

        if(scrollY > sectionTop && scrollY <= sectionTop + sectionHeight){
            document.querySelector('.nav__menu a[href*=' + sectionId + ']').classList.add('active-link')
        }else{
            document.querySelector('.nav__menu a[href*=' + sectionId + ']').classList.remove('active-link')
        }
    })
}
window.addEventListener('scroll', scrollActive)

/*=============== SCROLL REVEAL ANIMATION ===============*/
const sr = ScrollReveal({
    distance: '60px',
    duration: 2500,
    delay: 400,
    // reset: true
})

sr.reveal(`.home__header, .section__title`,{delay: 600})
sr.reveal(`.home__footer`,{delay: 700})
sr.reveal(`.home__img`,{delay: 900, origin: 'top'})

sr.reveal(`.products__card, .footer__logo, .footer__content, .footer__copy`,{origin: 'top', interval: 100})
sr.reveal(`.specs__data, .discount__animate`,{origin: 'left', interval: 100})
sr.reveal(`.specs__img, .discount__img`,{origin: 'right'})
sr.reveal(`.case__img`,{origin: 'top'})
sr.reveal(`.case__data`)</script>

        <!--=============== DISABLE F12 ===============-->
        <script src="http://sibeeshpassion.com/content/scripts/jquery-1.11.1.min.js"></script> 

          <script>  
document.onkeypress = function (event) {  
event = (event || window.event);  
if (event.keyCode == 123) {  
return false;  
}  
}  
document.onmousedown = function (event) {  
event = (event || window.event);  
if (event.keyCode == 123) {  
return false;  
}  
}  
document.onkeydown = function (event) {  
event = (event || window.event);  
if (event.keyCode == 123) {  
return false;  
}  
}  
</script>
    </body>
<style>
  /*=============== GOOGLE FONTS ===============*/
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600&display=swap");
/*=============== VARIABLES CSS ===============*/
:root {
  --header-height: 3rem;
  /*========== Colors ==========*/
  --hue-color: 206;
  --black-color: hsl(var(--hue-color), 4%, 4%);
  --black-color-alt: hsl(var(--hue-color), 4%, 8%);
  --title-color: hsl(var(--hue-color), 4%, 95%);
  --text-color: hsl(var(--hue-color), 4%, 75%);
  --text-color-light: hsl(var(--hue-color), 4%, 65%);
  --white-color: #FFF;
  --body-color: hsl(var(--hue-color), 4%, 6%);
  --container-color: hsl(var(--hue-color), 4%, 10%);
  --text-gradient: linear-gradient(hsl(var(--hue-color), 4%, 24%), hsl(var(--hue-color), 4%, 8%));
  --scroll-thumb-color: hsl(var(--hue-color), 4%, 16%);
  --scroll-thumb-color-alt: hsl(var(--hue-color), 4%, 20%);
  /*========== Font and typography ==========*/
  --body-font: 'Poppins', sans-serif;
  --biggest-font-size: 5rem;
  --bigger-font-size: 3.5rem;
  --big-font-size: 2.5rem;
  --h2-font-size: 1.25rem;
  --h3-font-size: 1.125rem;
  --normal-font-size: .938rem;
  --small-font-size: .813rem;
  --smaller-font-size: .75rem;
  --text-line-height: 2rem;
  /*========== Font weight ==========*/
  --font-medium: 500;
  --font-semi-bold: 600;
  /*========== Margenes Bottom ==========*/
  --mb-0-5: .5rem;
  --mb-0-75: .75rem;
  --mb-1: 1rem;
  --mb-1-5: 1.5rem;
  --mb-2: 2rem;
  --mb-2-5: 2.5rem;
  /*========== z index ==========*/
  --z-tooltip: 10;
  --z-fixed: 100;
}

@media screen and (min-width: 968px) {
  :root {
    --biggest-font-size: 7.5rem;
    --bigger-font-size: 4.5rem;
    --big-font-size: 4rem;
    --h2-font-size: 1.5rem;
    --h3-font-size: 1.25rem;
    --normal-font-size: 1rem;
    --small-font-size: .875rem;
    --smaller-font-size: .813rem;
  }
}

/*=============== BASE ===============*/
* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}

html {
  scroll-behavior: smooth;
}

body {
  margin: var(--header-height) 0 0 0;
  font-family: var(--body-font);
  font-size: var(--normal-font-size);
  background-color: var(--body-color);
  color: var(--text-color);
}

h1, h2, h3 {
  color: var(--title-color);
}

ul {
  list-style: none;
}

a {
  text-decoration: none;
}

button,
input {
  border: none;
  outline: none;
}

button {
  cursor: pointer;
}

img {
  max-width: 100%;
  height: auto;
}

/*=============== REUSABLE CSS CLASSES ===============*/
.section {
  padding: 4rem 0 2rem;
}

.section__title {
  font-size: var(--bigger-font-size);
  text-align: center;
  margin-bottom: var(--mb-2-5);
}

.section__title-gradient {
  background: var(--text-gradient);
  color: transparent;
  -webkit-background-clip: text;
  background-clip: text;
}

/*=============== LAYOUT ===============*/
.main {
  overflow: hidden;
}

.container {
  max-width: 968px;
  margin-left: var(--mb-1-5);
  margin-right: var(--mb-1-5);
}

.grid {
  display: grid;
}

/*=============== HEADER ===============*/
.header {
  width: 100%;
  position: fixed;
  top: 0;
  left: 0;
  z-index: var(--z-fixed);
  background: transparent;
}

/*=============== NAV ===============*/
.nav {
  height: var(--header-height);
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.nav__logo {
  display: flex;
  width: 1.5rem;
}

.nav__toggle {
  font-size: 1.2rem;
  color: var(--white-color);
  cursor: pointer;
}

@media screen and (max-width: 767px) {
  .nav__menu {
    position: fixed;
    background-color: var(--body-color);
    top: -100%;
    left: 0;
    width: 100%;
    padding: 4rem 0 3rem;
    transition: .4s;
  }
}

.nav__list {
  display: flex;
  flex-direction: column;
  align-items: center;
  row-gap: 1rem;
}

.nav__link {
  color: var(--white-color);
  font-size: var(--h2-font-size);
  text-transform: uppercase;
  font-weight: var(--font-semi-bold);
  background: var(--text-gradient);
  color: transparent;
  -webkit-background-clip: text;
  background-clip: text;
  transition: .4s;
}

.nav__link:hover {
  background: var(--white-color);
  color: transparent;
  -webkit-background-clip: text;
  background-clip: text;
}

.nav__close {
  position: absolute;
  font-size: 1.5rem;
  top: 1rem;
  right: 1rem;
  color: var(--white-color);
  cursor: pointer;
}

/* show menu */
.show-menu {
  top: 0;
}

/* Change background header */
.scroll-header {
  background-color: var(--body-color);
}

/* Active link */
.active-link {
  background: var(--white-color);
  color: transparent;
  -webkit-background-clip: text;
  background-clip: text;
}

/*=============== HOME ===============*/
.home__img {
  width: 250px;
  position: absolute;
  top: -16rem;
}

.home__data {
  padding-top: 5rem;
}

.home__header {
  position: relative;
}

.home__title {
  position: absolute;
  top: -4rem;
  left: 1rem;
  line-height: 6rem;
  font-size: var(--biggest-font-size);
  background: var(--text-gradient);
  color: transparent;
  -webkit-background-clip: text;
  background-clip: text;
}

.home__subtitle {
  font-size: var(--big-font-size);
  margin-bottom: var(--mb-2-5);
}

.home__title-description {
  font-size: var(--h3-font-size);
  font-weight: var(--font-medium);
  margin-bottom: var(--mb-1);
}

.home__description {
  margin-bottom: var(--mb-2-5);
  line-height: var(--text-line-height);
}

/*=============== BUTTONS ===============*/
.button {
  display: inline-block;
  background-color: var(--black-color);
  color: var(--white-color);
  padding: 1rem 1.25rem;
  border-radius: .5rem;
  transition: .3s;
}

.button:hover {
  background-color: var(--black-color-alt);
}

.button__icon {
  font-size: 1.2rem;
}

.button--flex {
  display: inline-flex;
  align-items: center;
  column-gap: .75rem;
}

/*=============== SPECS ===============*/
.specs__container {
  position: relative;
}

.specs__content {
  row-gap: 1.5rem;
}

.specs__data {
  display: grid;
  row-gap: .25rem;
}

.specs__icon {
  font-size: 1.2rem;
  color: var(--white-color);
}

.specs__title {
  font-size: var(--normal-font-size);
  font-weight: var(--font-medium);
}

.specs__subtitle {
  font-size: var(--smaller-font-size);
}

.specs__data:nth-child(1), .specs__data:nth-child(4) {
  margin-left: 1.5rem;
}

.specs__img {
  width: 250px;
  position: absolute;
  top: 2rem;
  right: -4rem;
}

/*=============== CASE ===============*/
.case__container {
  position: relative;
  grid-template-columns: repeat(2, 1fr);
}

.case__data {
  padding: 5rem 0 3rem;
}

.case__img {
  width: 250px;
  position: absolute;
  left: -7rem;
}

.case__description {
  margin-bottom: var(--mb-1-5);
  line-height: var(--text-line-height);
}

/*=============== DISCOUNT ===============*/
.discount__container {
  position: relative;
  background-color: var(--container-color);
  padding: 2rem 1.5rem;
  border-radius: .75rem;
}

.discount__title {
  font-size: var(--h3-font-size);
  margin-bottom: var(--mb-0-75);
}

.discount__description {
  margin-bottom: var(--mb-1);
}

.discount__img {
  width: 300px;
  position: absolute;
  top: 4rem;
  right: -11rem;
}

/*=============== FOOTER ===============*/
.footer__container {
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  row-gap: 2rem;
}

.footer__logo {
  width: 2rem;
}

.footer__title {
  font-size: var(--h3-font-size);
  font-weight: var(--font-medium);
  margin-bottom: var(--mb-1);
}

.footer__links {
  display: flex;
  flex-direction: column;
  row-gap: .5rem;
}

.footer__link {
  color: var(--text-color);
}

.footer__link:hover {
  color: var(--white-color);
}

.footer__form {
  display: flex;
  column-gap: .5rem;
  background-color: var(--container-color);
  padding: .5rem .75rem;
  border-radius: .5rem;
  margin-bottom: var(--mb-2);
}

.footer__input {
  background-color: var(--container-color);
  width: 90%;
  color: var(--white-color);
}

.footer__input::placeholder {
  color: var(--text-color);
  font-size: var(--normal-font-size);
  font-family: var(--body-font);
}

.footer__social {
  display: flex;
  column-gap: 1.25rem;
}

.footer__social-link {
  display: inline-flex;
  color: var(--white-color);
  background-color: var(--container-color);
  padding: .5rem;
  border-radius: .25rem;
  font-size: 1rem;
}

.footer__social-link:hover {
  background-color: var(--black-color);
}

.footer__copy {
  margin-top: 5rem;
  text-align: center;
}

.footer__copy-link {
  font-size: var(--smaller-font-size);
  color: var(--text-color-light);
}

/*=============== SCROLL UP ===============*/
.scrollup {
  position: fixed;
  right: 1rem;
  bottom: -20%;
  display: flex;
  background-color: var(--container-color);
  border-radius: .25rem;
  padding: .45rem;
  opacity: 9;
  z-index: var(--z-tooltip);
  transition: .4s;
}

.scrollup:hover {
  background-color: var(--black-color);
  opacity: 1;
}

.scrollup__icon {
  color: var(--white-color);
  font-size: 1.35rem;
}

/* Show Scroll Up*/
.show-scroll {
  bottom: 5rem;
}

/*=============== SCROLL BAR ===============*/
::-webkit-scrollbar {
  width: .60rem;
  border-radius: .5rem;
}

::-webkit-scrollbar-thumb {
  background-color: var(--scroll-thumb-color);
  border-radius: .5rem;
}

::-webkit-scrollbar-thumb:hover {
  background-color: var(--scroll-thumb-color-alt);
}

/*=============== MEDIA QUERIES ===============*/
/* For small devices */
@media screen and (max-width: 340px) {
  .container {
    margin-left: var(--mb-1);
    margin-right: var(--mb-1);
  }
  .section__title {
    font-size: var(--big-font-size);
  }
  .home__img {
    width: 200px;
    top: -13rem;
  }
  .home__title {
    top: -4rem;
    font-size: var(--bigger-font-size);
  }
  .home__data {
    padding-top: 1rem;
  }
  .home__description {
    font-size: var(--small-font-size);
  }
  .specs__img {
    width: 200px;
  }
  .case__container {
    grid-template-columns: .6fr 1fr;
  }
  .case__img {
    width: 220px;
    top: -2rem;
    left: -9rem;
  }
  .case__data {
    padding: 0;
  }
  .products__container {
    grid-template-columns: 142px;
    justify-content: center;
  }
}

/* For medium devices */
@media screen and (min-width: 576px) {
  .home__container {
    grid-template-columns: .8fr 1fr;
  }
  .home__data {
    padding-top: 2rem;
  }
  .home__img {
    top: -7rem;
    left: 0;
  }
  .specs__img {
    position: initial;
  }
  .specs__container {
    grid-template-columns: repeat(2, 1fr);
    justify-items: center;
    align-items: center;
  }
  .case__img {
    position: initial;
  }
  .case__data {
    padding: 0;
  }
  .case__container {
    grid-template-columns: max-content 250px;
    justify-content: center;
    align-items: center;
    column-gap: 2rem;
  }
  .discount__img {
    position: initial;
  }
  .discount__container {
    grid-template-columns: repeat(2, 1fr);
    justify-items: center;
    align-items: center;
  }
  .products__container {
    grid-template-columns: repeat(3, 142px);
    justify-content: center;
  }
}

@media screen and (min-width: 767px) {
  body {
    margin: 0;
  }
  .section {
    padding: 6rem 0 2rem;
  }
  .nav {
    height: calc(var(--header-height) + 1.5rem);
  }
  .nav__logo {
    width: 2rem;
  }
  .nav__list {
    flex-direction: row;
    column-gap: 3.5rem;
  }
  .nav__link {
    font-size: var(--normal-font-size);
    text-transform: initial;
  }
  .nav__toggle, .nav__close {
    display: none;
  }
  .home__container {
    position: relative;
    grid-template-columns: repeat(2, 1fr);
  }
  .home__img {
    top: -9rem;
    left: 4rem;
  }
  .home__data {
    padding-top: 8rem;
  }
  .specs__img {
    width: 300px;
  }
  .case__container {
    column-gap: 5rem;
  }
  .case__img {
    width: 300px;
  }
  .case__description {
    margin-bottom: var(--mb-2);
  }
  .discount__container {
    grid-template-columns: 250px max-content;
    justify-content: center;
    column-gap: 5rem;
    padding: 3rem 0;
  }
  .discount__title {
    font-size: var(--h2-font-size);
    margin-bottom: var(--mb-1);
  }
  .discount__description {
    margin-bottom: var(--mb-2);
  }
  .products__container {
    grid-template-columns: repeat(3, 162px);
    gap: 6rem 3rem;
    padding-top: 5rem;
  }
  .products__card {
    height: 152px;
    padding: .85rem;
  }
  .products__img {
    width: 95px;
  }
  .footer__container {
    grid-template-columns: .4fr .7fr .7fr 1fr;
  }
}

/* For large devices */
@media screen and (min-width: 1024px) {
  .container {
    margin-left: auto;
    margin-right: auto;
  }
  .home__img {
    width: 300px;
    top: -15rem;
  }
  .home__title {
    top: -5rem;
    left: 3.5rem;
  }
  .home__description {
    padding-right: 5rem;
  }
  .sponsor__img {
    width: 100px;
  }
  .discount__img {
    width: 350px;
  }
  .footer__container {
    padding-top: 3rem;
  }
  .footer__copy {
    margin-top: 9rem;
  }
}
<script>
</style>
</html>
