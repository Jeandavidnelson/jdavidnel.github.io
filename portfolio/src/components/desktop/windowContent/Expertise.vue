<template>
 <section class="colorlib-services" data-section="services">
    <div class="colorlib-narrow-content">
      <div class="row">
        <div class="col-md-12"
        data-animate-effect="fadeInLeft">
          <span class="heading-meta">Qu'est ce que?</span>
          <h2 class="colorlib-heading">Here are some of my expertise</h2>
        </div>
      </div>
      <div class="row row-pt-md">
        <div class="col-md-4 text-center ">
          <div class="services color-1">
            <span class="icon">
              <i class="icon-bulb"></i>
            </span>
            <div class="desc">
              <h3>Innovative Ideas</h3>
              <p>Separated they live in Bookmarksgrove right at the coast of the Semantics</p>
            </div>
          </div>
        </div>
        <div class="col-md-4 text-center ">
          <div class="services color-2">
            <span class="icon">
              <i class="icon-data"></i>
            </span>
            <div class="desc">
              <h3>Software</h3>
              <p>Separated they live in Bookmarksgrove right at the coast of the Semantics</p>
            </div>
          </div>
        </div>
        <div class="col-md-4 text-center ">
          <div class="services color-3">
            <span class="icon">
              <i class="icon-phone3"></i>
            </span>
            <div class="desc">
              <h3>Application</h3>
              <p>Separated they live in Bookmarksgrove right at the coast of the Semantics</p>
            </div>
          </div>
        </div>
        <div class="col-md-4 text-center ">
          <div class="services color-4">
            <span class="icon">
              <i class="icon-layers2"></i>
            </span>
            <div class="desc">
              <h3>Graphic Design</h3>
              <p>Separated they live in Bookmarksgrove right at the coast of the Semantics</p>
            </div>
          </div>
        </div>
        <div class="col-md-4 text-center ">
          <div class="services color-5">
            <span class="icon">
              <i class="icon-data"></i>
            </span>
            <div class="desc">
              <h3>Software</h3>
              <p>Separated they live in Bookmarksgrove right at the coast of the Semantics</p>
            </div>
          </div>
        </div>
        <div class="col-md-4 text-center ">
          <div class="services color-6">
            <span class="icon">
              <i class="icon-phone3"></i>
            </span>
            <div class="desc">
              <h3>Application</h3>
              <p>Separated they live in Bookmarksgrove right at the coast of the Semantics</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator';
import $ from 'jquery';

@Component
export default class Expertise extends Vue {
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
