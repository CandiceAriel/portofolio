<template>
  <div class="container-fluid">
    <Header />
    <div class="container-fluid content__services">
      <div class="wrapper__service">
        <h3>Web Design</h3>
        <p>UI Design for yout websites</p>
      </div>
      <div class="wrapper__service">
        <h3>Front End Development</h3>
        <p>HTML, CSS, Bootstrap, SCSS, Vue.js, React.js</p>
      </div>
    </div>
  </div>
</template>

<script>
import '../scss/homepage.scss';
import Header from '../components/Header.vue';

export default {
  name: 'Homepage',
  components: {
    Header
  }
}
</script>