<template>
  <div class="features21-layout349 thq-section-padding">
    <div class="features21-max-width thq-section-max-width thq-grid-auto-300">
      <div class="features21-container1 thq-card thq-flex-column">
        <img
          :alt="feature1ImageAlt"
          :src="feature1ImageSrc"
          class="features21-image1 thq-img-ratio-1-1 thq-img-round"
        />
        <h2 class="thq-heading-2">
          <slot name="feature1Title">
            <!--Default content for feature1Title-->
            <div class="features21-fragment4">
              <span class="features21-text21">Tailored Advice</span>
            </div>
          </slot>
        </h2>
        <span class="features21-text11 thq-body-small">
          <slot name="feature1Description">
            <!--Default content for feature1Description-->
            <div class="features21-fragment8">
              <span class="features21-text25">
                Receive personalized guidance and recommendations based on the
                specific needs and abilities of your child.
              </span>
            </div>
          </slot>
        </span>
      </div>
      <div class="features21-container2 thq-card thq-flex-column">
        <img
          :alt="feature2ImageAlt"
          :src="feature2ImageSrc"
          class="features21-image2 thq-img-ratio-1-1 thq-img-round"
        />
        <h2 class="thq-heading-2">
          <slot name="feature2Title">
            <!--Default content for feature2Title-->
            <div class="features21-fragment1">
              <span class="features21-text18">Goal-Setting Sessions</span>
            </div>
          </slot>
        </h2>
        <span class="features21-text13 thq-body-small">
          <slot name="feature2Description">
            <!--Default content for feature2Description-->
            <div class="features21-fragment6">
              <span class="features21-text23">
                Engage in interactive goal-setting sessions to establish clear
                objectives and milestones for your child&apos;s development.
              </span>
            </div>
          </slot>
        </span>
      </div>
      <div class="features21-container3 thq-card thq-flex-column">
        <img
          :alt="feature3ImageAlt"
          :src="feature3ImageSrc"
          class="features21-image3 thq-img-ratio-1-1 thq-img-round"
        />
        <h2 class="thq-heading-2">
          <slot name="feature3Title">
            <!--Default content for feature3Title-->
            <div class="features21-fragment7">
              <span class="features21-text24">Individualized Support</span>
            </div>
          </slot>
        </h2>
        <span class="features21-text15 thq-body-small">
          <slot name="feature3Description">
            <!--Default content for feature3Description-->
            <div class="features21-fragment2">
              <span class="features21-text19">
                Benefit from one-on-one support sessions tailored to address your
                child&apos;s unique challenges and strengths.
              </span>
            </div>
          </slot>
        </span>
      </div>
      <div class="features21-container4 thq-card thq-flex-column">
        <img
          :alt="feature4ImageAlt"
          :src="feature4ImageSrc"
          class="features21-image4 thq-img-ratio-1-1 thq-img-round"
        />
        <h2 class="thq-heading-2">
          <slot name="feature4Title">
            <!--Default content for feature4Title-->
            <div class="features21-fragment3">
              <span class="features21-text20">Consultation Packages</span>
            </div>
          </slot>
        </h2>
        <span class="features21-text17 thq-body-small">
          <slot name="feature4Description">
            <!--Default content for feature4Description-->
            <div class="features21-fragment5">
              <span class="features21-text22">
                Choose from a variety of consultation packages with flexible
                pricing options to suit your needs and budget.
              </span>
            </div>
          </slot>
        </span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Features21',
  props: {
    feature2ImageAlt: {
      type: String,
      default: 'Goal-Setting Sessions Image Alt',
    },
    feature3ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1675654567483-45ac53aa8078?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNDQyODIxMXw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    feature1ImageAlt: {
      type: String,
      default: 'Tailored Advice Image Alt',
    },
    feature4ImageAlt: {
      type: String,
      default: 'Consultation Packages Image Alt',
    },
    feature3ImageAlt: {
      type: String,
      default: 'Individualized Support Image Alt',
    },
    feature4ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1571844345075-5a71d1e6e8ef?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNDQyODIxMnw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    feature2ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1729089049653-24312fdca908?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNDQyODIxMXw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    feature1ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1580892621648-ceee4eacafe4?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNDQyODIxMnw&ixlib=rb-4.0.3&q=80&w=1080',
    },
  },
}
</script>

<style scoped>
.features21-layout349 {
  display: flex;
  overflow: hidden;
  position: relative;
  align-items: center;
  flex-direction: column;
}
 
.features21-max-width {
  display: flex;
  align-items: center;
}
 
.features21-container1 {
  color: var(--dl-color-theme-neutral-light);
  height: auto;
  display: flex;
  align-self: flex-start;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  background-color: var(--dl-color-theme-primary1);
}
 
.features21-image1 {
  width: var(--dl-size-size-medium);
  height: var(--dl-size-size-medium);
  object-fit: cover;
}
 
.features21-text11 {
  text-align: center;
}
 
.features21-container2 {
  color: var(--dl-color-theme-neutral-light);
  height: auto;
  display: flex;
  align-self: flex-start;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  background-color: var(--dl-color-theme-primary2);
}
 
.features21-image2 {
  width: var(--dl-size-size-medium);
  height: var(--dl-size-size-medium);
  object-fit: cover;
}
 
.features21-text13 {
  text-align: center;
}
 
.features21-container3 {
  color: var(--dl-color-theme-neutral-light);
  height: auto;
  display: flex;
  align-self: flex-start;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  background-color: var(--dl-color-theme-primary1);
}
 
.features21-image3 {
  width: var(--dl-size-size-medium);
  height: var(--dl-size-size-medium);
  object-fit: cover;
}
 
.features21-text15 {
  text-align: center;
}
 
.features21-container4 {
  color: var(--dl-color-theme-neutral-light);
  height: auto;
  display: flex;
  align-self: flex-start;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  background-color: var(--dl-color-theme-primary2);
}
 
.features21-image4 {
  width: var(--dl-size-size-medium);
  height: var(--dl-size-size-medium);
  object-fit: cover;
}
 
.features21-text17 {
  text-align: center;
}
 
.features21-fragment1 {
  display: contents;
}
 
.features21-text18 {
  display: inline-block;
}
 
.features21-fragment2 {
  display: contents;
}
 
.features21-text19 {
  display: inline-block;
}
 
.features21-fragment3 {
  display: contents;
}
 
.features21-text20 {
  display: inline-block;
}
 
.features21-fragment4 {
  display: contents;
}
 
.features21-text21 {
  display: inline-block;
}
 
.features21-fragment5 {
  display: contents;
}
 
.features21-text22 {
  display: inline-block;
}
 
.features21-fragment6 {
  display: contents;
}
 
.features21-text23 {
  display: inline-block;
}
 
.features21-fragment7 {
  display: contents;
}
 
.features21-text24 {
  display: inline-block;
}
 
.features21-fragment8 {
  display: contents;
}
 
.features21-text25 {
  display: inline-block;
}
 
@media(max-width: 991px) {
  .features21-max-width {
    gap: var(--dl-space-space-twounits);
    flex-direction: column-reverse;
  }
}
 
@media(max-width: 767px) {
  .features21-container1 {
    width: 100%;
  }
  .features21-container2 {
    width: 100%;
  }
  .features21-container3 {
    width: 100%;
  }
  .features21-container4 {
    width: 100%;
  }
}
</style>
