<template>
  <footer
    class="footer"
    :class="{ [`footer-${type}`]: type }"
    :data-background-color="backgroundColor"
  >
    <div class="container">
      <nav>
        <ul>
          <li>
            <a href="https://www.instagram.com/joeniofarias/">
              Joenio-Insta
            </a>
          </li>
          <li>
            <a href="https://www.instagram.com/andre_spk/">
              André-Insta
            </a>
          </li>
          <li>
            <a href="https://mandatudousa.com.br/">
              Manda Tudo USA
            </a>
          </li>
        </ul>
      </nav>
      <!--<div class="copyright">
        &copy; {{ year }}, Designed by
        <a href="https:///www.invisionapp.com" target="_blank" rel="noopener"
          >Invision</a
        >. Coded by
        <a href="https://binarcode.com" target="_blank" rel="noopener"
          >BinarCode</a
        >
        and
        <a href="https://www.creative-tim.com" target="_blank" rel="noopener"
          >Creative Tim</a
        >.
      </div> !-->
    </div>
  </footer>
</template>
<script>
export default {
  props: {
    backgroundColor: String,
    type: String
  },
  data() {
    return {
      year: new Date().getFullYear()
    };
  }
};
</script>
<style></style>
