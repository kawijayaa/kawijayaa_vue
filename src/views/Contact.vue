<template>
  <b-container>
    <b-row class="landing-row" align-v="center">
      <b-col class="links">
        <b-row class="links-row" cols-lg="1" align-v="center">
          <b-col class="links-col">
            <b-link to="/">&lt;</b-link>
          </b-col>
          <b-col class="links-col">
            <b-link href="mailto:me@kawijayaa.me">EMAIL</b-link>
          </b-col>
          <b-col class="links-col">
            <b-link href="https://instagram.com/kawijayaa">INSTAGRAM</b-link>
          </b-col>
          <b-col class="links-col">
            <b-link href="https://github.com/kawijayaa">GITHUB</b-link>
          </b-col>
        </b-row>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>

export default {
  name: 'Contact',
  components: {
    
  }
}
</script>
  
<style scoped>
  @media (max-width: 992px) {
    .links {
      text-align: left !important;
    }
    .landing-row {
      height: auto;
    }
  }
  @media (max-width: 768px) {
    a {
      font-size: 0.8rem !important;
    }
  }
  .landing-row {
    height: 100vh;
  }
  .links {
    text-align: center;
  }
  .links-row {
    justify-content: center;
  }
  h1 {
    margin: 0;
  }
  .links-col {
    flex: 0 0 auto;
    width: auto;
  }
  a {
    color: var(--dark);
    text-decoration: none !important;
    font-size: 1.1rem;
  }
</style>