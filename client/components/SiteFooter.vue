<template>
  <div class="footer">
    <!-- <a href="http://www.wxmw.co" target="new">
      <img src="/images/wxmw-logo.png" alt="West by Midwest">
    </a> -->
    &copy; {{ year }} Adam Van Lente
  </div>
</template>

<script>
export default {
  name: 'SiteFooter',
  computed: {
    year() {
      return new Date().getFullYear()
    }
  }
}
</script>

<style scoped>
  .footer {
    font-family: 'Helvetica', sans-serif;
    font-size: 12px;
    color: #bdbdbd;
    margin: 32px auto;
    font-weight: lighter;
    text-align: center;
  }
  img {
    display: block;
    width: 100px;
    margin: 0 auto;
    padding: 24px;
    opacity: 0.1;
  }
</style>
