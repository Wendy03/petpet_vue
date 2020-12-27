<template>
  <header class="header">
    <nav class="navbar navbar-expand-md bg-white fix-top-lg">
      <div class="container">
        <h1>
          <a class="navbar-brand logo ml-md-0 position-relative"
             href="index.html">PETPET</a>
        </h1>
        <button class="navbar-toggler"
                type="button"
                data-toggle="collapse"
                data-target="#navbarSupportedContent"
                aria-controls="navbarSupportedContent"
                aria-expanded="false"
                aria-label="Toggle navigation">
          <span class="material-icons text-warning display-4"> menu </span>
        </button>
        <div class="collapse navbar-collapse justify-content-end"
             id="navbarSupportedContent">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link text-primary text-center mr-0 mr-md-9"
                 href="#">預約服務</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-primary text-center mr-0 mr-md-9"
                 href="#">成為寵物保姆</a>
            </li>
            <li class="nav-item">
              <router-link class="nav-link text-primary text-center"
                           to="/login">登入
              </router-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </header>
</template>

<script>
export default {
  data() {
    return {};
  },
};
</script>
