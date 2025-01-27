<template>
  <div class="hero17-header78">
    <div class="hero17-column thq-section-max-width thq-section-padding">
      <div class="hero17-content">
        <h1 class="hero17-text1 thq-heading-1">
          <slot name="heading1">
            <!--Default content for heading1-->
            <div class="hero17-fragment3">
              <span class="hero17-text6">Empowering Disabled Children</span>
            </div>
          </slot>
        </h1>
        <p class="hero17-text2 thq-body-large">
          <slot name="content1">
            <!--Default content for content1-->
            <div class="hero17-fragment1">
              <span class="hero17-text4">
                Providing professional consultation support for disabled children
                to help them thrive and reach their full potential.
              </span>
            </div>
          </slot>
        </p>
        <h1 class="hero17-text3 thq-heading-1">
          <slot name="heading11">
            <!--Default content for heading11-->
            <div class="hero17-fragment2">
              <span class="hero17-text5">Empowering Disabled Children</span>
            </div>
          </slot>
        </h1>
      </div>
      <div class="hero17-actions"></div>
    </div>
    <div>
      <div class="hero17-container2">
        <DangerousHTML
          html="<style>
    @keyframes scroll-x {
      from {
        transform: translateX(0);
      }
      to {
        transform: translateX(calc(-100% - 16px));
      }
    }
  
    @keyframes scroll-y {
      from {
        transform: translateY(0);
      }
      to {
        transform: translateY(calc(-100% - 16px));
      }
    }
  </style>
  "
        ></DangerousHTML>
      </div>
    </div>
  </div>
</template>

<script>
import DangerousHTML from 'dangerous-html/vue'

export default {
  name: 'Hero17',
  props: {},
  components: {
    DangerousHTML,
  },
}
</script>

<style scoped>
.hero17-header78 {
  gap: var(--dl-space-space-threeunits);
  width: 100%;
  height: 408px;
  display: flex;
  overflow: hidden;
  position: relative;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
}
 
.hero17-column {
  gap: var(--dl-space-space-oneandhalfunits);
  width: auto;
  display: flex;
  align-items: center;
  flex-direction: column;
  padding-bottom: var(--dl-space-space-unit);
}
 
.hero17-content {
  gap: var(--dl-space-space-oneandhalfunits);
  height: 283px;
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
 
.hero17-text1 {
  text-align: center;
}
 
.hero17-text2 {
  text-align: center;
}
 
.hero17-text3 {
  margin-top: 67px;
  text-align: center;
}
 
.hero17-actions {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-space-space-unit);
}
 
.hero17-container2 {
  display: contents;
}
 
.hero17-fragment1 {
  display: contents;
}
 
.hero17-text4 {
  display: inline-block;
}
 
.hero17-fragment2 {
  display: contents;
}
 
.hero17-text5 {
  display: inline-block;
}
 
.hero17-fragment3 {
  display: contents;
}
 
.hero17-text6 {
  display: inline-block;
}
 
@media(max-width: 479px) {
  .hero17-actions {
    width: 100%;
    flex-direction: column;
  }
}
</style>
