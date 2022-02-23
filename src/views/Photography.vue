<template>
  <b-container class="photography" align-h="center">
    <b-row class="nav-row">
      <b-col class="nav-col">
        <b-link to=""><b-img class="back" src="..\assets\back-arrow.png"></b-img></b-link>
        <b-link href="https://instagram.com/okengsukafoto"><b-img class="logo" src="..\assets\osf\osf_logo.svg"></b-img></b-link>
      </b-col>
      <b-col class="osf-col">
        <b-link href="https://instagram.com/okengsukafoto" class="contact" align-v="center">INSTAGRAM</b-link>
        <b-link href="mailto:osf@kawijayaa.me" class="contact" align-v="center">EMAIL</b-link>
      </b-col>
    </b-row>
    <b-row class="img-row" align-h="center">
      <b-col class="img-col">
        <b-img class="image" src="..\assets\osf\osf_5457.jpg"></b-img>
      </b-col>
      <b-col class="img-col">
        <b-img class="image" src="..\assets\osf\osf_5073.jpg"></b-img>
      </b-col>
      <b-col class="img-col">
        <b-img class="image" src="..\assets\osf\osf_4970.jpg"></b-img>
      </b-col>
      <b-col class="img-col">
        <b-img class="image" src="..\assets\osf\osf_4747.jpg"></b-img>
      </b-col>
      <b-col class="img-col">
        <b-img class="image" src="..\assets\osf\osf_4767.jpg"></b-img>
      </b-col>
      <b-col class="img-col">
        <b-img class="image" src="..\assets\osf\osf_4728.jpg"></b-img>
      </b-col>
      <b-col class="img-col">
        <b-img class="image" src="..\assets\osf\osf_4612.jpg"></b-img>
      </b-col>
      <b-col class="img-col">
        <b-img class="image" src="..\assets\osf\osf_4259.jpg"></b-img>
      </b-col>
      <b-col class="img-col">
        <b-img class="image" src="..\assets\osf\osf_4239.jpg"></b-img>
      </b-col>
      <b-col class="img-col">
        <b-img class="image" src="..\assets\osf\osf_4059.jpg"></b-img>
      </b-col>
      <b-col class="img-col">
        <b-img class="image" src="..\assets\osf\osf_3811.jpg"></b-img>
      </b-col>
      <b-col class="img-col">
        <b-img class="image" src="..\assets\osf\osf_3761.jpg"></b-img>
      </b-col>
      <b-col class="img-col">
        <b-img class="image" src="..\assets\osf\osf_1779.jpg"></b-img>
      </b-col>
      <b-col class="img-col">
        <b-img class="image" src="..\assets\osf\osf_9713.jpg"></b-img>
      </b-col>
      <b-col class="img-col">
        <b-img class="image" src="..\assets\osf\osf_9659.jpg"></b-img>
      </b-col>
      <b-col class="img-col">
        <b-img class="image" src="..\assets\osf\osf_1281.jpg"></b-img>
      </b-col>
      <b-col class="img-col">
        <b-img class="image" src="..\assets\osf\osf_0778.jpg"></b-img>
      </b-col>
      <b-col class="img-col">
        <b-img class="image" src="..\assets\osf\osf_8908.jpg"></b-img>
      </b-col>
      <b-col class="img-col">
        <b-img class="image" src="..\assets\osf\osf_4885.jpg"></b-img>
      </b-col>
      <b-col class="img-col">
        <b-img class="image" src="..\assets\osf\osf_3857.jpg"></b-img>
      </b-col>
      <b-col class="img-col">
        <b-img class="image" src="..\assets\osf\osf-17.jpg"></b-img>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
  export default {
    name: 'Photography',
    components: {

    }
  }
</script>
  
<style scoped>
  @media (max-width: 768px) {
    .contact {
      text-align: center;
      margin: 0 1vw 0 1vw !important;
      font-size: 1em;
    }
    .nav-row {
      justify-content: center  !important;;
    }
    .back {
      margin-right: 1.5vw !important;
    }
    .osf-col {
      margin: 0 !important;
      padding: 0;
    }
  }
  @media (max-width: 992px) {
    .nav-row {
      margin: 10vh 0 10vh 0;
    }
  }
  .logo {
    height: 80px;
  }
  .back {
    height: 40px;
    margin-right: 1vw;
  }
  .nav-col {
    flex: 0 0 auto !important;
    width: auto !important;
    text-align: left;
  }
  .nav-row {
    margin: 10vh 7vh 10vh 7vh;
    justify-content: space-between;
  }
  .image {
    width: 40vh;
    object-fit: cover;
  }
  .img-col {
    flex: 0 0 auto !important;
    width: auto !important;
    padding: 0 !important;
  }
  .img-row {
    margin-bottom: 15vh;
  }
  .contact {
    text-align: right;
    margin: 0 0.5vw 0 0.5vw;
    font-size: 1.5em;
    text-decoration: none;
    color: var(--dark);
  }
  .contact:hover {
    color: var(--blue);
  }
  .osf-col {
    flex: 0 0 auto !important;
    width: auto !important;
    align-self: center;
    margin-right: 2vw;
  }
</style>