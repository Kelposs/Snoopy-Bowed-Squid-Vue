<template>
  <div class="features9-layout186 thq-section-padding">
    <div class="thq-section-max-width thq-flex-column">
      <h2 class="features9-text1 thq-heading-2">
        <slot name="feature1Title">
          <!--Default content for feature1Title-->
          <div class="features9-fragment2">
            <span class="features9-text4">Personalized Guidance</span>
          </div>
        </slot>
      </h2>
      <p class="features9-text2 thq-body-large">
        <slot name="feature1Description">
          <!--Default content for feature1Description-->
          <div class="features9-fragment1">
            <span class="features9-text3">
              Receive one-on-one personalized guidance to address the specific
              needs and challenges of your disabled child.
            </span>
          </div>
        </slot>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Features9',
  props: {},
}
</script>

<style scoped>
.features9-layout186 {
  width: 100%;
  height: auto;
  display: flex;
  overflow: hidden;
  position: relative;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
  justify-content: center;
}
 
.features9-text1 {
  z-index: 2;
  text-align: center;
}
 
.features9-text2 {
  z-index: 2;
  text-align: center;
}
 
.features9-fragment1 {
  display: contents;
}
 
.features9-text3 {
  display: inline-block;
}
 
.features9-fragment2 {
  display: contents;
}
 
.features9-text4 {
  display: inline-block;
}
</style>
