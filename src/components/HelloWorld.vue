<template>
<!-- ***** Header ***** -->

<header class="header" role="banner" id="top">
  <div class="row">
    <nav class="nav" role="navigation">
      <ul class="nav__items">
        <li class="nav__item"><a href="#work" class="nav__link">Work</a></li>
        <li class="nav__item"><a href="#clients" class="nav__link">Clients</a></li>
        <li class="nav__item">
          <a href="#about" class="nav__link">About</a>
        </li>
        <li class="nav__item">
          <a href="#contact" class="nav__link">Contact</a>
        </li>
      </ul>
    </nav>
  </div>
  <div class="header__text-box row">
    <div class="header__text">
      <h1 class="heading-primary">
        <!-- Replace the following name with your name -->
        <span>Ghulam Mustafa</span>
      </h1>
      <!-- Put a small paragraph about yourself -->
      <p>A Web Developer based in Meblorn, Australia</p>
      <a href="#contact" class="btn btn--pink">Get in touch</a>
    </div>
  </div>
</header>

<main role="main">

  <!-- ***** Work ***** -->

  <section class="work" id="work">
    <div class="row">
      <h2>My Work</h2>
      <div class="work__boxes">

        <!-- Each div with the work__box class is a project. -->

        <div class="work__box">
          <div class="work__text">
            <h3>Portfolio Website</h3>
            <p>
             A practiced porfolio website on HTML,CSS and Javascript.
            </p>
            <ul class="work__list">
              <li>HTML</li>
              <li>CSS</li>
              <li>JavaScript</li>
             
            </ul>

            <div class="work__links">
              <a href="#" target="_blank" class="link__text">
                Visit Site <span>&rarr;</span>
              </a>
              <a href="#" title="View Source Code" target="_blank">
                <img src="./images/github.svg" class="work__code" alt="GitHub">
              </a>
            </div>
          </div>
          <div class="work__image-box">
            <img src="./images/project-1.png" class="work__image" alt="Project 1" />
          </div>
        </div>

        <div class="work__box">
          <div class="work__text">
            <h3>Calculator</h3>
            <p>
              This calcululator is designed with emerging technologies including HTML,CSS AND JAVASCRIPT on VSCODE IDE with full responsiveness <br>
              and attractive design using hexadicimal colours.It works with javascript functions and It always give perfect calculated result.
            </p>
            <ul class="work__list">
              <li>React</li>
              <li>Next.js</li>
              <li>Node</li>
              <li>MongoDB</li>
            </ul>

            <div class="work__links">
              <a href="#" class="link__text">
                Visit Site <span>&rarr;</span>
              </a>
              <a href="#">
                <img src="./images/github.svg" class="work__code" title="View Source Code" alt="GitHub">
              </a>
            </div>
          </div>
          <div class="work__image-box">
            <img src="./images/project-2.png" class="work__image" alt="Project 1" />
          </div>
        </div>

        <div class="work__box">
          <div class="work__text">
            <h3>Notificator</h3>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Quod,
              eius.
            </p>
            <ul class="work__list">
              <li>React</li>
              <li>Next.js</li>
              <li>Node</li>
              <li>MongoDB</li>
            </ul>

            <div class="work__links">
              <a href="#" class="link__text">
                Visit Site <span>&rarr;</span>
              </a>
              <a href="#">
                <img src="./images/github.svg" class="work__code" title="View Source Code" alt="GitHub">
              </a>
            </div>
          </div>
          <div class="work__image-box">
            <img src="./images/project-3.png" class="work__image" alt="Project 3" />
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ***** Clients ***** -->

  <section class="client" id="clients">
    <div class="row">
      <h2>Clients</h2>
      <div class="client__logos">
        <!-- Add logos of the clients or companies you'have worked with. -->
        <img src="./images/ronjones.png" class="client__logo" alt="Company 2" />
        <img src="./images/goldengrid.png" class="client__logo" alt="Company 3" />
        <img src="./images/bullseye.png" class="client__logo" alt="Company 1" />
        <img src="./images/mighty-furnitures.png" class="client__logo" alt="Company 1" />
        <img src="./images/fastlane.png" class="client__logo" alt="Company 3" />
        <img src="./images/chippy.png" class="client__logo" alt="Company 1" />
      </div>
    </div>
  </section>

  <!-- ***** About ***** -->

  <section class="about" id="about">
    <div class="row">
      <h2>About Me</h2>
      <div class="about__content">
        <div class="about__text">
          <!-- Replace the below paragraph with info about yourself -->
          <p>
            I'm Ghulam Mustafa, a Melbourne-based individual driven by my two great passions: cars and sports. From a young age, the allure of automobiles has fascinated me. I've spent countless hours researching and admiring the intricate designs, powerful engines, and cutting-edge technology that make cars more than just machines. In parallel, my love for sports has fueled my competitive spirit. Whether it's a fast-paced game of football or the thrill of a Formula 1 race, I relish the adrenaline rush and the camaraderie that sports bring. 
Melbourne, with its vibrant culture and world-class educational institutions, has welcomed me as a student, providing the perfect backdrop for pursuing my academic goals. Here,
 I'm not only expanding my knowledge but also forging friendships with like-minded individuals who share my passions.
With a future that holds the promise of combining my love for cars and sports, I'm excited to explore the roads ahead and score goals both on and off the field of life..
          </p>
          <!-- Provide a link to your resume -->
          <a href="#" class="btn">My Resume</a>
        </div>

        <div class="about__photo-container">
          <!-- Add a nice photo of yourself -->
          <img class="about__photo" src="./images/Ghulam-Mustafa.jpg" style="height: 66rem;"  alt="My professional picture for my linked inn ,github and university" />
        </div>
      </div>
    </div>
  </section>
</main>


<!-- ***** Contact ***** -->

<section class="contact" id="contact">
  <div class="row">
    <h2>Get in Touch</h2>
    <div class="contact__info">
      <p>
        Are you looking for a fast-performing and user-friendly website to
        represent your product or business? or looking for any kind of
        consultation? or want to ask questions? or have some advice for me
        or just want to say "Hi 👋" in any case feel free to Let me know. I
        will do my best to respond back. 😊 The quickest way to reach out to
        me is via an email.
      </p>
      
      <!-- My the email  -->
      <a href="mailto:you@example.com" class="btn">shayansamad@gmail.com</a>
    </div>
  </div>
  <div class="section_10">
  <div class="responsive-container-block container">
    <form id="iox4">
      <div class="responsive-container-block form-container">
        <div class="responsive-cell-block wk-desk-6 wk-ipadp-6 wk-tab-12 wk-mobile-12 first-name" id="i10mt-5">
          <p class="text-blk input-title">
            Full Name
          </p>
          <input class="input" id="ijowk-5" name="FirstName" placeholder="First Name">
        </div>
        <br>
        <div class="responsive-cell-block wk-desk-6 wk-ipadp-6 wk-tab-12 wk-mobile-12">
          <p class="text-blk input-title">
            Email Address
          </p>
          <input class="input" id="ipmgh-5" name="Email" placeholder="Email">
        </div>
        <br>
        <div class="responsive-cell-block wk-tab-12 wk-mobile-12 wk-desk-12 wk-ipadp-12" id="i634i-5">
          <p class="text-blk input-title">
            Message
          </p>
          <textarea class="textinput" id="i5vyy-5" placeholder="Write a message..."></textarea>
          <br />
        </div>
        
        <div class="responsive-cell-block wk-tab-12 wk-mobile-12 wk-desk-12 wk-ipadp-12">
          <button class="submit-btn" id="w-c-s-bgc_p-1-dm-id-3">
            Send Message
          </button>
        </div>
      </div>
    </form>
  </div>
</div>
</section>

<!-- ***** Footer ***** -->

<footer role="contentinfo" class="footer">
  <div class="row">
    <!-- Update the links to point to your accounts -->
    <ul class="footer__social-links">
      <li class="footer__social-link-item">
        <a href="#" title="Link to Twitter Profile">
          <img src="./images/twitter.svg" class="footer__social-image" alt="Twitter">
        </a>
      </li>
      <li class="footer__social-link-item">
        <a href="#" title="Link to Github Profile">
          <img src="./images/github.svg" class="footer__social-image" alt="Github">
        </a>
      </li>
      <li class="footer__social-link-item">
        <a href="#" title="Link to Codepen Profile">
          <img src="./images/codepen.svg" class="footer__social-image" alt="Codepen">
        </a>
      </li>
      <li class="footer__social-link-item">
        <a href="#">
          <img src="./images/linkedin.svg" title="Link to Linkedin Profile" class="footer__social-image" alt="Linkedin">
        </a>
      </li>
    </ul>

    <!-- If you give me some credit by keeping the below paragraph, will be huge for me 😊 Thanks. -->
    <p>
      &copy; 2023 - Website designed & developed by <a href="" class="link">Ghulam Mustafa</a>.
    </p>

  </div>
</footer>

<a href="#top" class="back-to-top" title="Back to Top">
  <img src="./images/arrow-up.svg" alt="Back to Top" class="back-to-top__image"/>
</a>

<!-- <script src="./index.js"></script> -->

</template>

<script>
export default {
  name: 'HelloWorld',

  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import 'index.css';
</style>
