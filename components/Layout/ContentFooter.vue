<template>
  <footer class="footer">
    <div class="container-fluid">
      <ul class="nav">
        <li class="nav-item">
          <a
            href="https://ioticos.org"
            target="_blank"
            rel="noopener"
            class="nav-link"
          >
            IoTicos.org
          </a>
        </li>
        <li class="nav-item">
          <a
            href="https://ioticos.org"
            target="_blank"
            rel="noopener"
            class="nav-link"
          >
            About Us
          </a>
        </li>
        <li class="nav-item">
          <a
            href="hhttps://ioticos.org"
            target="_blank"
            rel="noopener"
            class="nav-link"
          >
            Blog
          </a>
        </li>
      </ul>
      <div class="copyright">
        &copy; Copyright {{ year }} por

        <a
          href="#"
          target="_blank"
          rel="noopener"
          >Nicolás Dirazar</a
        >
      </div>
    </div>
  </footer>
</template>
<script>
export default {
  data() {
    return {
      year: new Date().getFullYear()
    };
  }
};
</script>
<style></style>
