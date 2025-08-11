<template>
  <header class="navbar">
    <!-- Logo -->
    <div class="logo">
      <div class="logo-icon">
        <svg viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg">
          <g clip-path="url(#clip0_6_319)">
            <path
              d="M8.57829 8.57829C5.52816 11.6284 3.451 15.5145 2.60947 19.7452C1.76794 23.9758 2.19984 28.361 3.85056 32.3462C5.50128 36.3314 8.29667 39.7376 11.8832 42.134C15.4698 44.5305 19.6865 45.8096 24 45.8096C28.3135 45.8096 32.5302 44.5305 36.1168 42.134C39.7033 39.7375 42.4987 36.3314 44.1494 32.3462C45.8002 28.361 46.2321 23.9758 45.3905 19.7452C44.549 15.5145 42.4718 11.6284 39.4217 8.57829L24 24L8.57829 8.57829Z"
              fill="currentColor"
            />
          </g>
          <defs>
            <clipPath id="clip0_6_319">
              <rect width="48" height="48" fill="white" />
            </clipPath>
          </defs>
        </svg>
      </div>
      <h2>SUTING</h2>
    </div>

    <!-- Hamburger Menu -->
    <button class="hamburger" @click="isMenuOpen = !isMenuOpen">
      <svg
        width="28"
        height="28"
        fill="none"
        stroke="currentColor"
        stroke-width="2"
        viewBox="0 0 24 24"
        stroke-linecap="round"
        stroke-linejoin="round"
      >
        <line x1="3" y1="12" x2="21" y2="12" />
        <line x1="3" y1="6" x2="21" y2="6" />
        <line x1="3" y1="18" x2="21" y2="18" />
      </svg>
    </button>

    <!-- Desktop Nav -->
    <nav class="nav-links">
      <a href="#">Services</a>
      <a href="#">Pricing</a>
      <a href="#">Contact</a>
      <button class="primary-btn">Download Our App</button>
    </nav>

    <!-- Mobile Menu -->
    <transition name="slide-fade">
      <div v-if="isMenuOpen" class="mobile-menu">
        <a href="#">Services</a>
        <a href="#">Pricing</a>
        <a href="#">Contact</a>
        <button class="primary-btn">Download Our App</button>
      </div>
    </transition>
  </header>
</template>

<script setup>
import { ref } from "vue";
const isMenuOpen = ref(false);
</script>

<style scoped>
/* Layout */
.navbar {
  display: flex;
  align-items: center;
  justify-content: space-between;
  border-bottom: 1px solid #f0f2f4;
  padding: 12px 16px;
  background: white;
  position: sticky;
  top: 0;
  z-index: 50;
}

/* Logo */
.logo {
  display: flex;
  align-items: center;
  gap: 8px;
}
.logo-icon {
  width: 24px;
  height: 24px;
  color: #196be5;
}
.logo h2 {
  font-size: 1.125rem;
  font-weight: bold;
  color: black;
  margin: 0;
}

/* Nav Links */
.nav-links {
  display: flex;
  align-items: center;
  gap: 24px;
}
.nav-links a {
  font-size: 0.9rem;
  color: black;
  text-decoration: none;
  font-weight: 500;
  transition: color 0.2s ease;
}

/* Primary Button */
.primary-btn {
  background: #196be5;
  color: white;
  font-size: 0.9rem;
  font-weight: bold;
  padding: 8px 16px;
  border-radius: 9999px;
  border: none;
  cursor: pointer;
  transition: background 0.2s ease;
}

/* Hamburger */
.hamburger {
  display: none;
  background: none;
  border: none;
  cursor: pointer;
  color: black;
}
.hamburger:hover {
  color: #196be5;
}

/* Mobile Menu */
.mobile-menu {
  position: absolute;
  top: 100%;
  left: 0;
  width: 100%;
  background: white;
  border-top: 1px solid #f0f2f4;
  display: flex;
  flex-direction: column;
  gap: 16px;
  padding: 16px;
}
.mobile-menu a {
  font-size: 0.9rem;
  color: black;
  text-decoration: none;
  font-weight: 500;
  transition: color 0.2s ease;
}
.mobile-menu a:hover {
  color: #196be5;
}
.mobile-menu .primary-btn {
  width: 100%;
}

/* Animations */
.slide-fade-enter-active,
.slide-fade-leave-active {
  transition: all 0.25s ease;
}
.slide-fade-enter-from,
.slide-fade-leave-to {
  opacity: 0;
  transform: translateY(-8px);
}

/* Responsive */
@media (max-width: 640px) {
  .nav-links {
    display: none;
  }
  .hamburger {
    display: flex;
    align-items: center;
  }
}
</style>
