<template>
  <div class="layout">
    <a href="#main-content" class="skip-link">Skip to main content</a>
    <!-- ═══ HEADER / NAVBAR ═══ -->
    <header class="layout-header">
      <!-- Logo -->
      <div class="left-header">
        <svg
          aria-hidden="true"
          xmlns="http://www.w3.org/2000/svg"
          width="40"
          height="30"
          viewBox="0 0 24 24"
        >
          <path
            fill="#101D22"
            d="m8 18l-6-6l6-6l1.425 1.425l-4.6 4.6L9.4 16.6zm8 0l-1.425-1.425l4.6-4.6L14.6 7.4L16 6l6 6z"
          />
        </svg>
        <p>Jonathan.Dev</p>
      </div>
      <!-- Navegación -->
      <div class="center-header">
        <a href="">About</a>
        <a href="">Projects</a>
        <a href="">Experience</a>
        <a href="">Contact</a>
      </div>
      <!-- CTA -->
      <div class="right-header">
        <button>Curriculum Vitae</button>
      </div>
    </header>
    <main class="layout-main" id="main-content">
      <!-- ═══ HERO / MAIN SECTION ═══ -->
      <div class="principal-main">
        <!-- Columna izquierda: contenido principal -->
        <div class="left-main">
          <!-- Overlay badge -->
          <div class="overlay">
            <span class="dot"></span>
            <p>AVAILABLE FOR PROJECTS</p>
          </div>

          <!-- Título principal -->
          <div class="text-main">
            <h1>
              Hi, I'm Jonathan. <span>Crafting</span> Digital Experiences.
            </h1>
          </div>

          <!-- Subtítulo -->
          <div class="subtext-main">
            <p>
              Full-stack developer and UI designer focused on building
              functional, high-performance web applications that solve
              real-world problems.
            </p>
          </div>

          <!-- Botones CTA -->
          <div class="button-main">
            <button class="view-word" aria-label="View Word">
              View Word
              <svg
                aria-hidden="true"
                xmlns="http://www.w3.org/2000/svg"
                width="15"
                height="15"
                viewBox="0 0 24 24"
              >
                <path
                  fill="#101D22"
                  d="M4 11v2h12l-5.5 5.5l1.42 1.42L19.84 12l-7.92-7.92L10.5 5.5L16 11z"
                />
              </svg>
            </button>
            <button class="contact-me">Contact Me</button>
          </div>

          <!-- Redes sociales -->
          <div class="icons-info-main">
            <div class="github">
              <button class="icon-github" aria-label="GitHub">
                <svg
                  aria-hidden="true"
                  xmlns="http://www.w3.org/2000/svg"
                  width="20"
                  height="20"
                  viewBox="0 0 24 24"
                >
                  <path
                    fill="#94A3B8"
                    d="M12 2A10 10 0 0 0 2 12c0 4.42 2.87 8.17 6.84 9.5c.5.08.66-.23.66-.5v-1.69c-2.77.6-3.36-1.34-3.36-1.34c-.46-1.16-1.11-1.47-1.11-1.47c-.91-.62.07-.6.07-.6c1 .07 1.53 1.03 1.53 1.03c.87 1.52 2.34 1.07 2.91.83c.09-.65.35-1.09.63-1.34c-2.22-.25-4.55-1.11-4.55-4.92c0-1.11.38-2 1.03-2.71c-.1-.25-.45-1.29.1-2.64c0 0 .84-.27 2.75 1.02c.79-.22 1.65-.33 2.5-.33s1.71.11 2.5.33c1.91-1.29 2.75-1.02 2.75-1.02c.55 1.35.2 2.39.1 2.64c.65.71 1.03 1.6 1.03 2.71c0 3.82-2.34 4.66-4.57 4.91c.36.31.69.92.69 1.85V21c0 .27.16.59.67.5C19.14 20.16 22 16.42 22 12A10 10 0 0 0 12 2"
                  />
                </svg>
              </button>
              <p>GITHUB</p>
            </div>
            <div class="linkedin">
              <button class="icon-linkedin" aria-label="LinkedIn">
                <svg
                  aria-hidden="true"
                  xmlns="http://www.w3.org/2000/svg"
                  width="20"
                  height="20"
                  viewBox="0 0 24 24"
                >
                  <path
                    fill="#94A3B8"
                    d="M4.75 1.875a2.125 2.125 0 1 0 0 4.25a2.125 2.125 0 0 0 0-4.25m-2 6A.125.125 0 0 0 2.625 8v13c0 .069.056.125.125.125h4A.125.125 0 0 0 6.875 21V8a.125.125 0 0 0-.125-.125zm6.5 0A.125.125 0 0 0 9.125 8v13c0 .069.056.125.125.125h4a.125.125 0 0 0 .125-.125v-7a1.875 1.875 0 1 1 3.75 0v7c0 .069.056.125.125.125h4a.125.125 0 0 0 .125-.125v-8.62c0-2.427-2.11-4.325-4.525-4.106a7.2 7.2 0 0 0-2.169.548l-1.306.56V8a.125.125 0 0 0-.125-.125z"
                  />
                </svg>
              </button>
              <p>LINKEDIN</p>
            </div>
            <div class="whatsapp">
              <button class="icon-whatsapp" aria-label="WhatsApp">
                <svg
                  aria-hidden="true"
                  xmlns="http://www.w3.org/2000/svg"
                  width="20"
                  height="20"
                  viewBox="0 0 24 24"
                >
                  <path
                    fill="#94A3B8"
                    d="M16.6 14c-.2-.1-1.5-.7-1.7-.8s-.4-.1-.6.1s-.6.8-.8 1c-.1.2-.3.2-.5.1c-.7-.3-1.4-.7-2-1.2c-.5-.5-1-1.1-1.4-1.7c-.1-.2 0-.4.1-.5s.2-.3.4-.4c.1-.1.2-.3.2-.4c.1-.1.1-.3 0-.4S9.7 8.5 9.5 8c-.1-.7-.3-.7-.5-.7h-.5c-.2 0-.5.2-.6.3Q7 8.5 7 9.7c.1.9.4 1.8 1 2.6c1.1 1.6 2.5 2.9 4.2 3.7c.5.2.9.4 1.4.5c.5.2 1 .2 1.6.1c.7-.1 1.3-.6 1.7-1.2c.2-.4.2-.8.1-1.2zm2.5-9.1C15.2 1 8.9 1 5 4.9c-3.2 3.2-3.8 8.1-1.6 12L2 22l5.3-1.4c1.5.8 3.1 1.2 4.7 1.2c5.5 0 9.9-4.4 9.9-9.9c.1-2.6-1-5.1-2.8-7m-2.7 14c-1.3.8-2.8 1.3-4.4 1.3c-1.5 0-2.9-.4-4.2-1.1l-.3-.2l-3.1.8l.8-3l-.2-.3c-2.4-4-1.2-9 2.7-11.5S16.6 3.7 19 7.5c2.4 3.9 1.3 9-2.6 11.4"
                  />
                </svg>
              </button>
              <p>WHATSAPP</p>
            </div>
          </div>
        </div>

        <!-- Columna derecha: imagen de perfil -->
        <div class="right-main">
          <div class="img-main">
            <img
              src="../assets/perfil.png"
              alt="Jonathan profile photo, full-stack developer and UI designer"
            />
          </div>
        </div>
      </div>
      <!-- ═══ SECOND SECTION ═══ -->
      <div class="second-main">
        <div class="second-left-main">
          <!-- 1ra sección: Imagen + info -->
          <div class="one_seccion">
            <!--Imagen-->
            <div class="seccionimages">
              <img src="../assets/perfil2.png" alt="" />
              <div class="iconsecurity">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="20"
                  height="20"
                  viewBox="0 0 24 24"
                >
                  <g fill="none">
                    <path
                      d="m12.593 23.258l-.011.002l-.071.035l-.02.004l-.014-.004l-.071-.035q-.016-.005-.024.005l-.004.01l-.017.428l.005.02l.01.013l.104.074l.015.004l.012-.004l.104-.074l.012-.016l.004-.017l-.017-.427q-.004-.016-.017-.018m.265-.113l-.013.002l-.185.093l-.01.01l-.003.011l.018.43l.005.012l.008.007l.201.093q.019.005.029-.008l.004-.014l-.034-.614q-.005-.018-.02-.022m-.715.002a.02.02 0 0 0-.027.006l-.006.014l-.034.614q.001.018.017.024l.015-.002l.201-.093l.01-.008l.004-.011l.017-.43l-.003-.012l-.01-.01z"
                    />
                    <path
                      fill="#101D22"
                      d="M11.298 2.195a2 2 0 0 1 1.232-.055l.172.055l7 2.625a2 2 0 0 1 1.291 1.708l.007.165v5.363a9 9 0 0 1-4.709 7.911l-.266.139l-3.354 1.677a1.5 1.5 0 0 1-1.198.062l-.144-.062l-3.354-1.677a9 9 0 0 1-4.97-7.75l-.005-.3V6.693a2 2 0 0 1 1.145-1.808l.153-.065zM12 4.068L5 6.693v5.363a7 7 0 0 0 3.635 6.138l.235.123L12 19.882l3.13-1.565a7 7 0 0 0 3.865-5.997l.005-.264V6.693zm3.433 4.561a1 1 0 0 1 1.497 1.32l-.083.094l-5.234 5.235a1.1 1.1 0 0 1-1.46.085l-.096-.085l-2.404-2.404a1 1 0 0 1 1.32-1.498l.094.083l1.768 1.768z"
                    />
                  </g>
                </svg>
              </div>
            </div>
            <!--Overlay y textos-->
            <div class="overlay_text">
              <!--Overlay-->
              <div class="overlaytwo">
                <p>THE STORY SO FAR</p>
              </div>
              <!--Textos-->
              <div class="textsecond">
                <h1>Engineering with <span>intent</span>.</h1>
                <p>
                  I'm Jonathan, a full-stack engineer driven by the intersection
                  of performance and aesthetics.
                </p>
              </div>
            </div>
          </div>

          <!-- 2da sección Textos-->
          <div class="subtextsecond">
            <p>
              With over 2 years of coding experience, my trajectory has been
              defined by a relentless curiosity for how things work under the
              hood. I specialize in building scalable web applications that
              don't just function, but delight users through thoughtful
              interaction design.
            </p>
            <p>
              I believe that technical excellence is a prerequisite, but empathy
              is the differentiator. Whether I'm architecting a complex backend
              or polishing a CSS transition, I keep the end-user's experience at
              the heart of every decision.
            </p>
          </div>

          <!-- 3ra sección: Tecnologías con carrusel -->
          <div>
            <p></p>
            <!--Carrusel en constante movimiento horizontal de las tecnologias-->
            <div></div>
          </div>

          <!-- 4ta sección Boton de descarga curriculum-->
          <div></div>
        </div>
        <div class="second-left-main"></div>
      </div>
      <div></div>
      <div></div>
    </main>
    <!-- ═══ FOOTER ═══ -->
    <footer></footer>
  </div>
</template>

<script setup></script>

<style scoped>
/* ═══════════════════════════════════
   LAYOUT
   ═══════════════════════════════════ */
.layout {
  position: relative;
  display: grid;
  grid-template-rows: auto 1fr auto;
  min-height: 100vh;
}

/* ═══════════════════════════════════
   HEADER
   ═══════════════════════════════════ */
.layout-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 100%;
  height: 52px;
  background: rgba(16, 29, 34, 0.8);
  padding: 0 10px;
  position: relative;
  box-sizing: border-box;
}

.left-header {
  display: flex;
  align-items: center;
  gap: 12px;
}
.left-header svg {
  background-color: #13b6ec;
  border-radius: 4px;
  padding: 4px;
}
.left-header p {
  color: var(--color-text);
  font-weight: 700;
}

.center-header {
  display: flex;
  align-items: center;
  gap: 40px;
}

.center-header a {
  color: #ffffff;
  text-decoration: none;
  transition: color 0.3s ease;
}
.center-header a:hover {
  color: #13b6ec;
}

.right-header {
  display: flex;
  align-items: center;
}
.right-header button {
  background-color: #13b6ec;
  color: #101d22;
  border: none;
  padding: 8px 20px;
  border-radius: 6px;
  font-weight: 700;
  font-size: 14px;
  cursor: pointer;
  transition: all 0.3s ease;
}
.right-header button:hover {
  background-color: #0fa0d4;
  transform: scale(1.05);
}

/* ═══════════════════════════════════
   MAIN
   ═══════════════════════════════════ */
.layout-main {
  display: grid;
}

/* ═══════════════════════════════════
   HERO SECTION
   ═══════════════════════════════════ */
.principal-main {
  position: relative;
  width: 100%;
  min-height: 100vh;
  display: flex;
  background:
    radial-gradient(
      141.42% 141.42% at 0% 0%,
      rgba(19, 182, 236, 0.15) 0%,
      rgba(19, 182, 236, 0) 50%
    ),
    radial-gradient(
      141.42% 141.42% at 100% 100%,
      rgba(19, 182, 236, 0.1) 0%,
      rgba(19, 182, 236, 0) 50%
    );
}

/* ═══════════════════════════════════
   LEFT MAIN - Hero content
   ═══════════════════════════════════ */
.left-main {
  display: grid;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  padding-top: 60px;
  gap: 0px;
  position: relative;
  width: 692px;
  max-width: 692px;
}

/* Overlay badge */
.overlay {
  box-sizing: border-box;
  display: flex;
  flex-direction: row;
  align-items: center;
  padding: 4px 12px;
  gap: 8px;
  height: 26px;
  background: rgba(19, 182, 236, 0.1);
  border: 1px solid rgba(19, 182, 236, 0.2);
  border-radius: 9999px;
  flex: none;
  order: 0;
  flex-grow: 0;
  color: #13b6ec;
  justify-self: start;
  animation: fadeInUp 0.6s ease both;
}

/* Blue dot */
.dot {
  display: flex;
  flex-direction: row;
  align-items: flex-start;
  padding: 0px;
  isolation: isolate;
  width: 8px;
  height: 8px;
  flex: none;
  order: 0;
  flex-grow: 0;
  background-color: #13b6ec;
  border-radius: 50%;
}

/* Title */
.text-main {
  width: 592px;
  font-weight: 800;
  font-size: 30px;
  line-height: 72px;
  color: var(--color-text);
  flex: none;
  order: 0;
  align-self: stretch;
  flex-grow: 0;
  animation: fadeInUp 0.6s ease 0.1s both;
}
.text-main h1 {
  margin: 0;
}

.text-main h1 span {
  color: var(--color-accent);
}

/* Subtitle */
.subtext-main {
  width: 576px;
  height: 84px;
  font-weight: 500;
  font-size: 20px;
  line-height: 28px;
  display: flex;
  align-items: center;
  color: #94a3b8;
  flex: none;
  order: 0;
  align-self: stretch;
  flex-grow: 0;
  animation: fadeInUp 0.6s ease 0.2s both;
}

/* Buttons row */
.button-main {
  display: flex;
  flex-direction: row;
  align-items: flex-start;
  padding: 0px;
  gap: 16px;
  width: 592px;
  height: 60px;
  animation: fadeInUp 0.6s ease 0.3s both;
}

/* View Word button */
.view-word {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  padding: 10px;
  gap: 8px;
  width: 120px;
  height: 40px;
  background: #13b6ec;
  border: none;
  border-radius: 12px;
  font-size: 12px;
  font-weight: 700;
  cursor: pointer;
  transition: all 0.3s ease;
  cursor: pointer;
}

.view-word:hover {
  background-color: #0fa0d4;
  transform: translateY(-2px);
  box-shadow: 0 6px 16px rgba(19, 182, 236, 0.3);
}

/* Contact Me button */
.contact-me {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  padding: 10px;
  gap: 8px;
  width: 120px;
  height: 40px;
  background: #101d22;
  color: #ffffff;
  border-radius: 12px;
  font-size: 12px;
  font-weight: 700;
  cursor: pointer;
  transition: all 0.3s ease;
  cursor: pointer;
  border: 1px solid #94a3b8;
  font-size: 15px;
}

.contact-me:hover {
  background: rgba(255, 255, 255, 0.05);
  transform: translateY(-2px);
  box-shadow: 0 6px 16px rgba(255, 255, 255, 0.1);
}

/* Social icons row */
.icons-info-main {
  display: flex;
  flex-direction: row;
  align-items: center;
  padding: 0px;
  gap: 24px;
  animation: fadeInUp 0.6s ease 0.4s both;
}
.github {
  display: flex;
  flex-direction: row;
  align-items: center;
  padding: 0px;
  gap: 8px;
}

/* GitHub icon */
.icon-github {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 0;
  width: 30px;
  height: 30px;
  background: #1e293b;
  border: none;
  border-radius: 8px;
  cursor: pointer;
  transition: all 0.3s ease;
}
.github p {
  color: #94a3b8;
  font-size: 15px;
}

.icon-github:hover {
  background: #334155;
  transform: translateY(-2px);
  box-shadow: 0 6px 16px rgba(30, 41, 59, 0.4);
}
.icon-github:hover svg {
  transform: scale(1.1);
}

.linkedin {
  display: flex;
  flex-direction: row;
  align-items: center;
  padding: 0px;
  gap: 8px;
}

/* LinkedIn icon */
.icon-linkedin {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 0;
  width: 30px;
  height: 30px;
  background: #1e293b;
  border: none;
  border-radius: 8px;
  cursor: pointer;
  transition: all 0.3s ease;
}

.linkedin p {
  color: #94a3b8;
  font-size: 15px;
}

.icon-linkedin:hover {
  background: #334155;
  transform: translateY(-2px);
  box-shadow: 0 6px 16px rgba(30, 41, 59, 0.4);
}

.icon-linkedin:hover svg {
  transform: scale(1.1);
}

.whatsapp {
  display: flex;
  flex-direction: row;
  align-items: center;
  padding: 0px;
  gap: 8px;
}

/* WhatsApp icon */
.icon-whatsapp {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 0;
  width: 30px;
  height: 30px;
  background: #1e293b;
  border: none;
  border-radius: 8px;
  cursor: pointer;
  transition: all 0.3s ease;
}

.whatsapp p {
  color: #94a3b8;
  font-size: 15px;
}

.icon-whatsapp:hover {
  background: #334155;
  transform: translateY(-2px);
  box-shadow: 0 6px 16px rgba(30, 41, 59, 0.4);
}

.icon-whatsapp:hover svg {
  transform: scale(1.1);
}

/* Right column - profile image */
.right-main {
  flex: 1;
  display: flex;
  justify-content: center;
  align-items: center;
  animation: fadeInUp 0.6s ease 0.15s both;
}
/* Profile image */
.img-main img {
  width: 450px;
  height: auto;
  border-radius: 20px;
  box-shadow: 0 0 60px 20px rgba(19, 182, 236, 0.25);
}

/* Skip link (a11y) */
.skip-link {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  white-space: nowrap;
  border: 0;
}

.skip-link:focus {
  position: fixed;
  top: 8px;
  left: 8px;
  width: auto;
  height: auto;
  padding: 12px 24px;
  margin: 0;
  background: #13b6ec;
  color: #101d22;
  font-size: 14px;
  font-weight: 700;
  border-radius: 8px;
  z-index: 9999;
  clip: auto;
  overflow: visible;
  text-decoration: none;
}

.second-main {
  display: grid;
  grid-template-columns: 1.5fr 3fr; /* ← izquierda más angosta, derecha más ancha */
  padding: 80px 60px;
  gap: 60px;
}

.second-left-main {
  display: flex;
  flex-direction: column;
  gap: 48px;
  justify-self: start;
}

.one_seccion {
  display: grid;
  grid-template-columns: auto 1fr;
  gap: 48px;
  align-items: start;
}

.seccionimages {
  position: relative;
  display: inline-block;
}

.seccionimages img {
  width: 400px; /* ← más pequeña */
  height: auto;
  border-radius: 16px;
  display: block;
}

.iconsecurity {
  position: absolute;
  bottom: -8px;
  right: -8px;
  width: 32px;
  height: 32px;
  background-color: var(--color-accent);
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  border: 2px solid var(--color-bg);
}

.iconsecurity svg {
  width: 16px;
  height: 16px;
}

.overlay_text {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  gap: 16px;
}

.overlaytwo {
  box-sizing: border-box;
  display: flex;
  flex-direction: row;
  align-items: center;
  padding: 4px 12px;
  height: 26px;
  background: rgba(19, 182, 236, 0.1);
  border: 1px solid rgba(19, 182, 236, 0.2);
  border-radius: 9999px;
  color: #13b6ec;
  font-size: 12px;
  font-weight: 600;
}

.textsecond h1 {
  font-size: 48px;
  font-weight: 800;
  color: #ffffff;
  margin: 0;
}

.textsecond h1 span {
  color: #13b6ec;
}

.textsecond p {
  font-size: 18px;
  color: #94a3b8;
  line-height: 1.6;
  margin: 8px 0 0;
}

.subtextsecond {
  display: flex;
  flex-direction: column;
  gap: 16px;
}

.subtextsecond p {
  font-size: 18px;
  line-height: 1.7;
  color: #94a3b8;
  margin: 0;
  hyphens: none;              
  overflow-wrap: break-word;   
  word-break: keep-all;

}
/* Focus visible (a11y) */
:focus-visible {
  outline: 2px solid #13b6ec;
  outline-offset: 2px;
}

/* Stagger entrance animation */
@keyframes fadeInUp {
  from {
    opacity: 0;
    transform: translateY(24px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

/* Reduced motion (a11y) */
@media (prefers-reduced-motion: reduce) {
  *,
  *::before,
  *::after {
    animation-duration: 0.01ms !important;
    animation-iteration-count: 1 !important;
    transition-duration: 0.01ms !important;
    scroll-behavior: auto !important;
  }
}
</style>
