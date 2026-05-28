<template>
  <div class="layout">
    <header class="layout-header">
      <div class="left-header">
        <svg
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
      <div class="center-header">
        <a href="">About</a>
        <a href="">Projects</a>
        <a href="">Experience</a>
        <a href="">Contact</a>
      </div>
      <div class="right-header">
        <button>
          Hoja de vida
        </button>
      </div>
    </header>
    <main class="layout-main">
      <div class="principal-main"></div>
      <div></div>
      <div></div>
      <div></div>
    </main>
    <footer></footer>
  </div>
</template>

<script setup></script>

<style scoped>
.layout {
  display: grid;
  grid-template-rows: auto 1fr auto;
  min-height: 100vh;
}

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
  background-color: #13B6EC;
  border-radius: 4px;
  padding: 4px;
}
.left-header p {
  color: #FFFFFF;
}

.center-header {
display: flex;
align-items: center;
gap: 40px;
}

.center-header a {
  color: #FFFFFF;
  text-decoration: none;
  transition: color 0.3s ease;
}
.center-header a:hover {
  color: #13B6EC;
}

.right-header {
  display: flex;
  align-items: center;
}
.right-header button {
  background-color: #13B6EC;
  color: #101D22;
  border: none;
  padding: 8px 20px;
  border-radius: 6px;
  font-weight: 700;
  font-size: 14px;  
  cursor: pointer;
  transition: all 0.3s ease;
}
.right-header button:hover {
  background-color: #0FA0D4;
  transform: scale(1.05);
}

.layout-main {
  display: grid;
}

.principal-main {
  position: relative;
  width: 100%;
  height: 915px;
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
</style>
