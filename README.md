# Netflix-Homepage
AI based 

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Netflix – Watch TV Shows Online, Watch Movies Online</title>
    <link rel="stylesheet" href="style.css" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Martel+Sans:wght@400;600;700;900&family=Lora:wght@400;600&display=swap"
      rel="stylesheet"
    />
  </head>
  <body>

    <!-- ==============================
         HERO SECTION
    ================================== -->
    <section class="hero">

      <!-- TOP NAVIGATION BAR -->
      <nav class="navbar">
        <div class="navbar__logo">
          <svg viewBox="0 0 111 30" class="logo-svg" aria-label="Netflix">
            <path
              d="M105.06 14.28L111 30c-1.75-.25-3.499-.563-5.28-.845l-3.cleaning-7.76-3.8 6.6c-1.653-.26-3.3-.502-4.985-.737l6.19-10.71L94.34 0h5.066l3.516 8.68L106.63 0h5.11l-6.68 14.28zm-20.3 15.64V0h4.67v29.92zm-5.2 0l.008-25.29L74.54 29.92h-4.35L65.24 4.63V29.92h-4.48V0h6.3l4.83 22.84L76.66 0h6.27v29.92h-3.37zm-31.57-25.5v7.3h8.24V16H48v8.92h10.01v4.98H43.31V0h14.7v4.42H47.99zm-17.1 25.5V4.42H25.4V0h14.96v4.42h-5.57V29.92h-4.67zm-17.1 0V17.97L6.6 0h5.11l5.072 11.41L21.75 0h5.11L19.49 17.97V29.92h-4.71zM0 29.92V0h4.67v29.92H0z"
              fill="#E50914"
            />
          </svg>
        </div>
        <div class="navbar__actions">
          <select class="lang-select" aria-label="Language selector">
            <option value="en">🌐 English</option>
            <option value="es">🌐 Español</option>
          </select>
          <a href="#" class="btn btn--signin">Sign In</a>
        </div>
      </nav>

      <!-- HERO CONTENT -->
      <div class="hero__content">
        <h1 class="hero__title">Unlimited movies, TV shows,<br />and more</h1>
        <p class="hero__subtitle">Starts at USD 7.70/month. Cancel anytime.</p>
        <p class="hero__cta-label">
          Ready to watch? Enter your email to create or restart your membership.
        </p>
        <form class="hero__form" action="#" method="get">
          <input
            class="hero__input"
            type="email"
            placeholder="Email address"
            aria-label="Email address"
          />
          <button class="btn btn--getstarted" type="submit">
            Get Started &rsaquo;
          </button>
        </form>
      </div>

      <!-- SEPARATOR -->
      <div class="hero__divider"></div>
    </section>

    <!-- ==============================
         FEATURES SECTION
    ================================== -->
    <main class="features">

      <!-- FEATURE 1: Enjoy on your TV -->
      <article class="feature feature--reverse">
        <div class="feature__text">
          <h2 class="feature__title">Enjoy on your TV</h2>
          <p class="feature__desc">
            Watch on Smart TVs, PlayStation, Xbox, Chromecast, Apple TV,
            Blu-ray players, and more.
          </p>
        </div>
        <div class="feature__media">
          <div class="feature__img-wrapper">
            <img
              src="https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/tv.png"
              alt="Netflix on TV"
              class="feature__img"
              loading="lazy"
            />
            <div class="feature__video-overlay tv-overlay">
              <video
                class="feature__video"
                autoplay
                muted
                loop
                playsinline
              >
                <source
                  src="https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/video-tv-in-0819.m4v"
                  type="video/mp4"
                />
              </video>
            </div>
          </div>
        </div>
      </article>

      <hr class="section-divider" />

      <!-- FEATURE 2: Download shows -->
      <article class="feature">
        <div class="feature__text">
          <h2 class="feature__title">Download your shows<br />to watch offline</h2>
          <p class="feature__desc">
            Save your favourites easily and always have something to watch.
          </p>
        </div>
        <div class="feature__media">
          <div class="feature__download-card">
            <img
              src="https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/mobile-0819.jpg"
              alt="Stranger Things on mobile"
              class="feature__img feature__img--phone"
              loading="lazy"
            />
            <div class="download-badge">
              <img
                src="https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/boxshot.png"
                alt="Stranger Things box art"
                class="download-badge__cover"
                loading="lazy"
              />
              <div class="download-badge__info">
                <span class="download-badge__title">Stranger Things</span>
                <span class="download-badge__status">Downloading...</span>
              </div>
              <div class="download-badge__anim">
                <span></span>
                <span></span>
                <span></span>
              </div>
            </div>
          </div>
        </div>
      </article>

      <hr class="section-divider" />

      <!-- FEATURE 3: Watch everywhere -->
      <article class="feature feature--reverse">
        <div class="feature__text">
          <h2 class="feature__title">Watch everywhere</h2>
          <p class="feature__desc">
            Stream unlimited movies and TV shows on your phone, tablet, laptop,
            and TV.
          </p>
        </div>
        <div class="feature__media">
          <div class="feature__img-wrapper">
            <img
              src="https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/device-pile.png"
              alt="Watch on multiple devices"
              class="feature__img"
              loading="lazy"
            />
            <div class="feature__video-overlay devices-overlay">
              <video
                class="feature__video"
                autoplay
                muted
                loop
                playsinline
              >
                <source
                  src="https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/video-devices-in.m4v"
                  type="video/mp4"
                />
              </video>
            </div>
          </div>
        </div>
      </article>

      <hr class="section-divider" />

      <!-- FEATURE 4: Kids profiles -->
      <article class="feature">
        <div class="feature__text">
          <h2 class="feature__title">Create profiles<br />for kids</h2>
          <p class="feature__desc">
            Send kids on adventures with their favourite characters in a space
            made just for them — free with your membership.
          </p>
        </div>
        <div class="feature__media">
          <img
            src="https://occ-0-2430-2186.1.nflxso.net/dnm/api/v6/19OhWN2dO19C9txTON9tvTFtefw/AAAABejKYujFfMqLEqVkmNnUPpzBXsWlKoO0LmcEJ6noxwVRQUG-JbVDxYMRH3aFN9AaPoUB4KcHY9K3WBrLqQGZ2mPzLzFE-MzYWH8lHk.png"
            alt="Kids profiles"
            class="feature__img"
            loading="lazy"
          />
        </div>
      </article>
    </main>

    <!-- BOTTOM HERO DIVIDER -->
    <div class="bottom-divider"></div>

    <!-- ==============================
         FAQ SECTION
    ================================== -->
    <section class="faq-section">
      <h2 class="faq-section__title">Frequently Asked Questions</h2>

      <div class="faq">
        <details class="faq__item">
          <summary class="faq__question">What is Netflix?</summary>
          <div class="faq__answer">
            <p>
              Netflix is a streaming service that offers a wide variety of
              award-winning TV shows, movies, anime, documentaries, and more on
              thousands of internet-connected devices.
            </p>
          </div>
        </details>

        <details class="faq__item">
          <summary class="faq__question">How much does Netflix cost?</summary>
          <div class="faq__answer">
            <p>
              Watch Netflix on your smartphone, tablet, Smart TV, laptop, or
              streaming device, all for one fixed monthly fee. Plans range from
              USD 7.70 to USD 22.99 a month. No extra costs, no contracts.
            </p>
          </div>
        </details>

        <details class="faq__item">
          <summary class="faq__question">Where can I watch?</summary>
          <div class="faq__answer">
            <p>
              Watch anywhere, anytime. Sign in with your Netflix account to
              watch instantly on the web at netflix.com from your personal
              computer or on any internet-connected device.
            </p>
          </div>
        </details>

        <details class="faq__item">
          <summary class="faq__question">How do I cancel?</summary>
          <div class="faq__answer">
            <p>
              Netflix is flexible. There are no pesky contracts and no
              commitments. You can easily cancel your account online in two
              clicks. There are no cancellation fees – start or stop your
              account anytime.
            </p>
          </div>
        </details>

        <details class="faq__item">
          <summary class="faq__question">What can I watch on Netflix?</summary>
          <div class="faq__answer">
            <p>
              Netflix has an extensive library of feature films, documentaries,
              TV shows, anime, award-winning Netflix originals, and more.
              Watch as much as you want, anytime you want.
            </p>
          </div>
        </details>

        <details class="faq__item">
          <summary class="faq__question">Is Netflix good for kids?</summary>
          <div class="faq__answer">
            <p>
              The Netflix Kids experience is included in your membership to give
              parents control while kids enjoy family-friendly TV shows and
              movies in their own space.
            </p>
          </div>
        </details>
      </div>

      <p class="faq-section__cta-label">
        Ready to watch? Enter your email to create or restart your membership.
      </p>
      <form class="hero__form faq-section__form" action="#" method="get">
        <input
          class="hero__input"
          type="email"
          placeholder="Email address"
          aria-label="Email address"
        />
        <button class="btn btn--getstarted" type="submit">
          Get Started &rsaquo;
        </button>
      </form>
    </section>

    <!-- ==============================
         FOOTER
    ================================== -->
    <footer class="footer">
      <div class="footer__inner">
        <p class="footer__contact">
          Questions? Call
          <a href="tel:1-844-505-2993" class="footer__link">1-844-505-2993</a>
        </p>

        <div class="footer__grid">
          <ul class="footer__col">
            <li><a href="#" class="footer__link">FAQ</a></li>
            <li><a href="#" class="footer__link">Investor Relations</a></li>
            <li><a href="#" class="footer__link">Buy Gift Cards</a></li>
            <li><a href="#" class="footer__link">Cookie Preferences</a></li>
            <li><a href="#" class="footer__link">Legal Notices</a></li>
          </ul>
          <ul class="footer__col">
            <li><a href="#" class="footer__link">Help Center</a></li>
            <li><a href="#" class="footer__link">Jobs</a></li>
            <li><a href="#" class="footer__link">Ways to Watch</a></li>
            <li><a href="#" class="footer__link">Corporate Information</a></li>
            <li><a href="#" class="footer__link">Only on Netflix</a></li>
          </ul>
          <ul class="footer__col">
            <li><a href="#" class="footer__link">Account</a></li>
            <li><a href="#" class="footer__link">Netflix Shop</a></li>
            <li><a href="#" class="footer__link">Terms of Use</a></li>
            <li><a href="#" class="footer__link">Contact Us</a></li>
            <li><a href="#" class="footer__link">Do Not Sell or Share My Personal Information</a></li>
          </ul>
          <ul class="footer__col">
            <li><a href="#" class="footer__link">Media Center</a></li>
            <li><a href="#" class="footer__link">Redeem Gift Cards</a></li>
            <li><a href="#" class="footer__link">Privacy</a></li>
            <li><a href="#" class="footer__link">Speed Test</a></li>
            <li><a href="#" class="footer__link">Ad Choices</a></li>
          </ul>
        </div>

        <div class="footer__bottom">
          <select class="lang-select" aria-label="Language selector">
            <option value="en">🌐 English</option>
            <option value="es">🌐 Español</option>
          </select>
          <p class="footer__copy">Netflix Clone &copy; 2026. For educational purposes only.</p>
        </div>
      </div>
    </footer>

  </body>
</html>

CSS 
/* ============================================================
   NETFLIX LANDING PAGE CLONE — style.css
   Author: Professional Front-End Clone
   Fonts: Martel Sans (headings) + Lora (body)
   ============================================================ */

/* ----------------------------------------------------------
   CSS CUSTOM PROPERTIES (Variables)
   ---------------------------------------------------------- */
:root {
  --netflix-red:    #E50914;
  --netflix-dark:   #141414;
  --section-bg:     #000000;
  --surface:        #222222;
  --border-color:   #3d3d3d;
  --text-primary:   #ffffff;
  --text-secondary: #b3b3b3;
  --font-heading:   'Martel Sans', sans-serif;
  --font-body:      'Lora', serif;
  --max-width:      1100px;
  --transition:     0.25s ease;
}

/* ----------------------------------------------------------
   CSS RESET & BASE
   ---------------------------------------------------------- */
*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

html {
  scroll-behavior: smooth;
  font-size: 16px;
}

body {
  font-family: var(--font-body);
  background-color: var(--section-bg);
  color: var(--text-primary);
  line-height: 1.6;
  overflow-x: hidden;
}

img,
video {
  display: block;
  max-width: 100%;
}

a {
  text-decoration: none;
  color: inherit;
}

ul {
  list-style: none;
}

/* ----------------------------------------------------------
   REUSABLE BUTTON STYLES
   ---------------------------------------------------------- */
.btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  cursor: pointer;
  font-family: var(--font-heading);
  font-weight: 700;
  border: none;
  border-radius: 4px;
  transition: background var(--transition), transform var(--transition);
  white-space: nowrap;
}

/* Sign In Button */
.btn--signin {
  background-color: var(--netflix-red);
  color: var(--text-primary);
  padding: 7px 18px;
  font-size: 0.875rem;
  border-radius: 4px;
  letter-spacing: 0.3px;
}

.btn--signin:hover {
  background-color: #c40811;
}

/* Get Started Button */
.btn--getstarted {
  background-color: var(--netflix-red);
  color: var(--text-primary);
  padding: 14px 28px;
  font-size: 1.125rem;
  border-radius: 4px;
  letter-spacing: 1px;
  flex-shrink: 0;
}

.btn--getstarted:hover {
  background-color: #c40811;
  transform: scale(1.02);
}

/* ----------------------------------------------------------
   LANGUAGE SELECT DROPDOWN
   ---------------------------------------------------------- */
.lang-select {
  background-color: transparent;
  color: var(--text-primary);
  border: 1px solid var(--text-secondary);
  border-radius: 4px;
  padding: 6px 28px 6px 10px;
  font-family: var(--font-body);
  font-size: 0.875rem;
  cursor: pointer;
  appearance: none;
  -webkit-appearance: none;
  background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='12' height='8' viewBox='0 0 12 8'%3E%3Cpath d='M1 1l5 5 5-5' stroke='%23fff' stroke-width='1.5' fill='none' stroke-linecap='round'/%3E%3C/svg%3E");
  background-repeat: no-repeat;
  background-position: right 8px center;
}

.lang-select:focus {
  outline: 1px solid var(--text-primary);
}

/* ----------------------------------------------------------
   HERO SECTION
   ---------------------------------------------------------- */
.hero {
  position: relative;
  width: 100%;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  background-image:
    linear-gradient(
      to bottom,
      rgba(0, 0, 0, 0.65) 0%,
      rgba(0, 0, 0, 0.3) 40%,
      rgba(0, 0, 0, 0.3) 60%,
      rgba(0, 0, 0, 0.75) 100%
    ),
    url("https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/home-bg.jpg");
  background-size: cover;
  background-position: center center;
  background-repeat: no-repeat;
  text-align: center;
  border-bottom: 8px solid var(--border-color);
}

/* ---- NAVBAR ---- */
.navbar {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 22px 56px;
  z-index: 10;
}

.navbar__logo {
  display: flex;
  align-items: center;
}

.logo-svg {
  width: 148px;
  height: auto;
  fill: var(--netflix-red);
}

.navbar__actions {
  display: flex;
  align-items: center;
  gap: 16px;
}

/* ---- HERO CONTENT ---- */
.hero__content {
  max-width: 700px;
  padding: 0 24px;
  z-index: 2;
  animation: fadeUp 0.9s ease both;
}

.hero__title {
  font-family: var(--font-heading);
  font-size: clamp(2rem, 5vw, 3.25rem);
  font-weight: 900;
  line-height: 1.18;
  margin-bottom: 20px;
  letter-spacing: -0.5px;
  color: var(--text-primary);
}

.hero__subtitle {
  font-family: var(--font-heading);
  font-size: clamp(1rem, 2.5vw, 1.5rem);
  font-weight: 400;
  margin-bottom: 20px;
  color: var(--text-primary);
}

.hero__cta-label {
  font-family: var(--font-heading);
  font-size: 1.1rem;
  font-weight: 600;
  margin-bottom: 18px;
  color: var(--text-primary);
}

/* ---- HERO FORM ---- */
.hero__form {
  display: flex;
  gap: 0;
  max-width: 620px;
  margin: 0 auto;
  border-radius: 4px;
  overflow: hidden;
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.5);
}

.hero__input {
  flex: 1;
  padding: 14px 20px;
  font-size: 1rem;
  font-family: var(--font-body);
  border: none;
  outline: none;
  background-color: rgba(22, 22, 22, 0.85);
  color: var(--text-primary);
  border: 1.5px solid #8c8c8c;
  border-right: none;
  border-radius: 4px 0 0 4px;
}

.hero__input::placeholder {
  color: #b0b0b0;
}

.hero__input:focus {
  border-color: var(--text-primary);
  background-color: rgba(22, 22, 22, 0.97);
}

.hero__form .btn--getstarted {
  border-radius: 0 4px 4px 0;
  padding: 14px 24px;
  font-size: 1.1rem;
}

/* ---- HERO DIVIDER ---- */
.hero__divider {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  height: 8px;
  background-color: var(--border-color);
}

/* ----------------------------------------------------------
   FEATURES SECTION
   ---------------------------------------------------------- */
.features {
  background-color: var(--section-bg);
}

.feature {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 40px;
  max-width: var(--max-width);
  margin: 0 auto;
  padding: 70px 56px;
  flex-direction: row;
}

/* Reverse layout for alternating features */
.feature--reverse {
  flex-direction: row-reverse;
}

/* ---- Feature Text ---- */
.feature__text {
  flex: 1;
  max-width: 480px;
}

.feature__title {
  font-family: var(--font-heading);
  font-size: clamp(1.75rem, 3.5vw, 2.75rem);
  font-weight: 900;
  line-height: 1.2;
  margin-bottom: 20px;
  color: var(--text-primary);
}

.feature__desc {
  font-family: var(--font-heading);
  font-size: clamp(1rem, 1.8vw, 1.4rem);
  font-weight: 400;
  color: var(--text-primary);
  line-height: 1.6;
}

/* ---- Feature Media ---- */
.feature__media {
  flex: 1;
  display: flex;
  justify-content: center;
  align-items: center;
  position: relative;
}

.feature__img {
  width: 100%;
  max-width: 500px;
  object-fit: contain;
  position: relative;
  z-index: 2;
}

.feature__img-wrapper {
  position: relative;
  display: inline-block;
}

/* ---- TV Video Overlay ---- */
.feature__video-overlay {
  position: absolute;
  z-index: 1;
  overflow: hidden;
}

.tv-overlay {
  top: 10.5%;
  left: 14%;
  width: 73%;
  height: 54%;
}

.devices-overlay {
  top: 4%;
  left: 15%;
  width: 63%;
  height: 47%;
}

.feature__video {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

/* ---- Download Badge Card ---- */
.feature__download-card {
  position: relative;
  display: inline-block;
}

.feature__img--phone {
  max-width: 280px;
  border-radius: 20px;
}

.download-badge {
  position: absolute;
  bottom: 8%;
  left: 50%;
  transform: translateX(-50%);
  display: flex;
  align-items: center;
  gap: 12px;
  background: #0f0f0f;
  border: 1.5px solid #3d3d3d;
  border-radius: 12px;
  padding: 10px 18px 10px 10px;
  width: 260px;
  box-shadow: 0 4px 24px rgba(0, 0, 0, 0.8);
  z-index: 5;
}

.download-badge__cover {
  width: 48px;
  height: 68px;
  border-radius: 6px;
  object-fit: cover;
  flex-shrink: 0;
}

.download-badge__info {
  flex: 1;
  display: flex;
  flex-direction: column;
  gap: 4px;
}

.download-badge__title {
  font-family: var(--font-heading);
  font-size: 0.9rem;
  font-weight: 700;
  color: var(--text-primary);
}

.download-badge__status {
  font-family: var(--font-heading);
  font-size: 0.78rem;
  color: #0071eb;
}

/* Animated downloading dots */
.download-badge__anim {
  display: flex;
  align-items: flex-end;
  gap: 3px;
  height: 20px;
}

.download-badge__anim span {
  display: block;
  width: 4px;
  background-color: #0071eb;
  border-radius: 2px;
  animation: bounce 1.2s ease-in-out infinite;
}

.download-badge__anim span:nth-child(1) { height: 8px;  animation-delay: 0s; }
.download-badge__anim span:nth-child(2) { height: 14px; animation-delay: 0.2s; }
.download-badge__anim span:nth-child(3) { height: 8px;  animation-delay: 0.4s; }

@keyframes bounce {
  0%, 100% { transform: scaleY(1);   opacity: 0.6; }
  50%       { transform: scaleY(1.6); opacity: 1; }
}

/* ---- Section Dividers ---- */
.section-divider {
  border: none;
  border-top: 8px solid var(--border-color);
  margin: 0;
}

.bottom-divider {
  height: 8px;
  background-color: var(--border-color);
}

/* ----------------------------------------------------------
   FAQ SECTION
   ---------------------------------------------------------- */
.faq-section {
  background-color: var(--section-bg);
  padding: 70px 56px;
  text-align: center;
  border-top: 8px solid var(--border-color);
  border-bottom: 8px solid var(--border-color);
}

.faq-section__title {
  font-family: var(--font-heading);
  font-size: clamp(1.75rem, 3.5vw, 2.75rem);
  font-weight: 900;
  margin-bottom: 16px;
  color: var(--text-primary);
}

/* FAQ Accordion */
.faq {
  max-width: 800px;
  margin: 0 auto 40px;
  display: flex;
  flex-direction: column;
  gap: 8px;
  text-align: left;
}

.faq__item {
  background-color: var(--surface);
  cursor: pointer;
  transition: background var(--transition);
}

.faq__item:hover {
  background-color: #3d3d3d;
}

.faq__question {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 20px 24px;
  font-family: var(--font-heading);
  font-size: clamp(1rem, 1.5vw, 1.35rem);
  font-weight: 400;
  color: var(--text-primary);
  list-style: none;
  user-select: none;
}

/* Custom expand icon using pseudo-element */
.faq__question::after {
  content: "+";
  font-size: 2rem;
  font-weight: 200;
  line-height: 1;
  flex-shrink: 0;
  transition: transform var(--transition);
}

.faq__item[open] .faq__question::after {
  transform: rotate(45deg);
}

.faq__answer {
  border-top: 1px solid var(--border-color);
}

.faq__answer p {
  padding: 20px 24px;
  font-family: var(--font-heading);
  font-size: clamp(0.95rem, 1.2vw, 1.2rem);
  font-weight: 300;
  color: var(--text-primary);
  line-height: 1.7;
}

/* FAQ CTA */
.faq-section__cta-label {
  font-family: var(--font-heading);
  font-size: 1.1rem;
  font-weight: 600;
  margin-bottom: 18px;
  color: var(--text-primary);
}

.faq-section__form {
  max-width: 620px;
  margin: 0 auto;
}

/* ----------------------------------------------------------
   FOOTER
   ---------------------------------------------------------- */
.footer {
  background-color: var(--section-bg);
  padding: 56px 56px 40px;
  color: var(--text-secondary);
}

.footer__inner {
  max-width: var(--max-width);
  margin: 0 auto;
}

.footer__contact {
  font-family: var(--font-heading);
  font-size: 1rem;
  margin-bottom: 28px;
  color: var(--text-secondary);
}

.footer__link {
  color: var(--text-secondary);
  transition: text-decoration var(--transition), color var(--transition);
}

.footer__link:hover {
  text-decoration: underline;
  color: #d0d0d0;
}

/* Footer link grid */
.footer__grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 16px;
  margin-bottom: 32px;
}

.footer__col {
  display: flex;
  flex-direction: column;
  gap: 12px;
}

.footer__col li a {
  font-family: var(--font-heading);
  font-size: 0.82rem;
  color: var(--text-secondary);
  line-height: 1.4;
}

.footer__col li a:hover {
  text-decoration: underline;
  color: #d0d0d0;
}

/* Footer bottom row */
.footer__bottom {
  display: flex;
  align-items: center;
  gap: 20px;
  flex-wrap: wrap;
  margin-top: 16px;
}

.footer__copy {
  font-family: var(--font-heading);
  font-size: 0.78rem;
  color: var(--text-secondary);
}

/* ----------------------------------------------------------
   ANIMATIONS
   ---------------------------------------------------------- */
@keyframes fadeUp {
  from {
    opacity: 0;
    transform: translateY(30px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

/* ----------------------------------------------------------
   RESPONSIVE — Tablet & Mobile (≤ 900px)
   ---------------------------------------------------------- */
@media (max-width: 900px) {

  .navbar {
    padding: 18px 28px;
  }

  .logo-img {
  width: 148px;
  height: auto;
  object-fit: contain;
}


  .hero__content {
    padding: 0 20px;
  }

  .hero__form {
    flex-direction: column;
    border-radius: 4px;
    overflow: visible;
    gap: 10px;
  }

  .hero__input {
    border-radius: 4px;
    border-right: 1.5px solid #8c8c8c;
    width: 100%;
  }

  .hero__form .btn--getstarted {
    border-radius: 4px;
    width: 100%;
    padding: 16px;
    font-size: 1.1rem;
  }

  .feature,
  .feature--reverse {
    flex-direction: column;
    padding: 50px 28px;
    text-align: center;
    gap: 30px;
  }

  .feature__text {
    max-width: 100%;
  }

  .feature__img {
    max-width: 360px;
  }

  .faq-section {
    padding: 50px 28px;
  }

  .faq-section__form {
    flex-direction: column;
    gap: 10px;
  }

  .faq-section__form .hero__input {
    border-radius: 4px;
    border-right: 1.5px solid #8c8c8c;
  }

  .faq-section__form .btn--getstarted {
    border-radius: 4px;
  }

  .footer {
    padding: 48px 28px 36px;
  }

  .footer__grid {
    grid-template-columns: repeat(2, 1fr);
    gap: 12px;
  }
}

@media (max-width: 500px) {

  .navbar__actions {
    gap: 10px;
  }

  .logo-svg {
    width: 90px;
  }

  .footer__grid {
    grid-template-columns: 1fr 1fr;
  }

  .download-badge {
    width: 220px;
    padding: 8px 12px 8px 8px;
  }
}
```__
