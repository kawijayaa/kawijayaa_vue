<template>
  <b-container>
    <b-row cols="1" cols-lg="2" class="landing-row" align-v="center">
      <b-col class="name">
        <h1 class="font-weight-bold">MUHAMMAD OKA</h1>
      </b-col>
      <b-col class="links">
        <b-row class="links-row" cols="3" cols-lg="1" align-v="center">
          <b-col class="links-col">
            <b-link href="https://github.com/kawijayaa">PROGRAMMING</b-link>
          </b-col>
          <b-col class="links-col">
            <b-link to="/okengsukafoto">PHOTOGRAPHY</b-link>
          </b-col>
          <b-col class="links-col">
            <b-link to="/contact">CONTACT</b-link>
          </b-col>
        </b-row>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>

export default {
  name: 'Landing',
  components: {
    
  }
}
</script>
  
<style scoped>
  @media (max-width: 992px) {
    .name {
      text-align: left !important;
      align-self: end;
    }
    .links {
      text-align: left !important;
      align-self: baseline;
    }
    .landing-row {
      justify-content: start !important;
      height: auto;
    }
    .links-row {
      justify-content: start !important;
    }
  }
  @media (max-width: 768px) {
    a {
      font-size: 0.8rem !important;
    }
  }
  .name {
    text-align: left;
  }
  .landing-row {
    justify-content: space-around;
    height: 100vh;
  }
  .links {
    text-align: right;
  }
  .links-row {
    justify-content: right;
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
  a:hover {
    color: var(--blue);
  }
</style>