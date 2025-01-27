<template>
  <div class="features16-layout300 thq-section-padding">
    <div class="features16-max-width thq-section-max-width">
      <div class="features16-section-title">
        <div class="features16-content1">
          <h2 class="features16-text10 thq-heading-2">
            <slot name="heading1">
              <!--Default content for heading1-->
              <div class="features16-fragment7">
                <span class="features16-text30">Our Services</span>
              </div>
            </slot>
          </h2>
          <span class="features16-text11 thq-body-large">
            <slot name="content1">
              <!--Default content for content1-->
              <div class="features16-fragment4">
                <span class="features16-text23">
                  We offer personalized consultation support and services for
                  disabled children to help them thrive and reach their full
                  potential.
                </span>
              </div>
            </slot>
          </span>
        </div>
      </div>
      <div class="features16-content2">
        <div class="features16-row thq-flex-row">
          <div class="features16-feature1">
            <img
              :alt="feature1ImageAlt"
              :src="feature1ImageSrc"
              class="thq-img-ratio-4-3"
            />
            <div class="features16-content3">
              <h3 class="features16-feature1-title1 thq-heading-3">
                <slot name="feature1Title">
                  <!--Default content for feature1Title-->
                  <div class="features16-fragment2">
                    <span class="features16-text13">
                      <span>Personalized Guidance</span>
                      <br />
                      <span>d</span>
                      <br />
                    </span>
                  </div>
                </slot>
              </h3>
              <span class="thq-body-small">
                <slot name="feature1Description">
                  <!--Default content for feature1Description-->
                  <div class="features16-fragment8">
                    <span class="features16-text31">
                      Tailored consultation and support to meet the unique needs
                      of each disabled child.
                    </span>
                  </div>
                </slot>
              </span>
            </div>
          </div>
          <div class="features16-feature2">
            <img
              :alt="feature2ImageAlt"
              :src="feature2ImageSrc"
              class="thq-img-ratio-4-3"
            />
            <div class="features16-content4">
              <h3 class="features16-feature1-title2 thq-heading-3">
                <slot name="feature1Title1">
                  <!--Default content for feature1Title1-->
                  <div class="features16-fragment3">
                    <span class="features16-text18">
                      <span>Personalized Guidance</span>
                      <br />
                      <span>d</span>
                      <br />
                    </span>
                  </div>
                </slot>
              </h3>
              <span class="thq-body-small">
                <slot name="feature2Description">
                  <!--Default content for feature2Description-->
                  <div class="features16-fragment1">
                    <span class="features16-text12">
                      Interactive sessions designed to empower disabled children
                      and boost their confidence.
                    </span>
                  </div>
                </slot>
              </span>
            </div>
          </div>
          <div class="features16-feature3">
            <img
              :alt="feature3ImageAlt"
              :src="feature3ImageSrc"
              class="thq-img-ratio-4-3"
            />
            <div class="features16-content5">
              <h3 class="features16-feature1-title3 thq-heading-3">
                <slot name="feature1Title2">
                  <!--Default content for feature1Title2-->
                  <div class="features16-fragment5">
                    <span class="features16-text24">
                      <span>Personalized Guidance</span>
                      <br />
                      <span>d</span>
                      <br />
                    </span>
                  </div>
                </slot>
              </h3>
              <span class="thq-body-small">
                <slot name="feature3Description">
                  <!--Default content for feature3Description-->
                  <div class="features16-fragment6">
                    <span class="features16-text29">
                      Assistance in setting achievable goals and milestones for
                      disabled children&apos;s development.
                    </span>
                  </div>
                </slot>
              </span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Features16',
  props: {
    feature3ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1584513727612-d7b63876b18c?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNDQwODIwOHw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    feature3ImageAlt: {
      type: String,
      default: 'Image depicting goal setting support',
    },
    feature1ImageAlt: {
      type: String,
      default: 'Image depicting personalized guidance',
    },
    feature1ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1557424120-32c81c3d50e3?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNDQwODIwOHw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    feature2ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1673890634026-80226550fc1d?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNDQwODIwOHw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    feature2ImageAlt: {
      type: String,
      default: 'Image depicting empowerment sessions',
    },
  },
}
</script>

<style scoped>
.features16-layout300 {
  width: 100%;
  height: auto;
  display: flex;
  overflow: hidden;
  position: relative;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
}
 
.features16-max-width {
  gap: var(--dl-space-space-threeunits);
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.features16-section-title {
  gap: 16px;
  width: 100%;
  display: flex;
  max-width: 800px;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
}
 
.features16-content1 {
  gap: 24px;
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
 
.features16-text10 {
  text-align: center;
}
 
.features16-text11 {
  text-align: center;
}
 
.features16-content2 {
  gap: 48px;
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
 
.features16-row {
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-shrink: 0;
  justify-content: center;
}
 
.features16-feature1 {
  gap: var(--dl-space-space-twounits);
  flex: 1;
  width: 100%;
  display: flex;
  overflow: hidden;
  align-items: flex-start;
  flex-shrink: 0;
  flex-direction: column;
}
 
.features16-content3 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
 
.features16-feature1-title1 {
  width: 313px;
  height: 75px;
  text-align: center;
}
 
.features16-feature2 {
  gap: var(--dl-space-space-twounits);
  flex: 1;
  width: 100%;
  display: flex;
  overflow: hidden;
  align-items: flex-start;
  flex-shrink: 0;
  flex-direction: column;
}
 
.features16-content4 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
 
.features16-feature1-title2 {
  width: 313px;
  height: 75px;
  text-align: center;
}
 
.features16-feature3 {
  gap: var(--dl-space-space-twounits);
  flex: 1;
  width: 100%;
  display: flex;
  overflow: hidden;
  align-items: flex-start;
  flex-shrink: 0;
  flex-direction: column;
}
 
.features16-content5 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
 
.features16-feature1-title3 {
  width: 313px;
  height: 75px;
  text-align: center;
}
 
.features16-fragment1 {
  display: contents;
}
 
.features16-text12 {
  display: inline-block;
}
 
.features16-fragment2 {
  display: contents;
}
 
.features16-text13 {
  display: inline-block;
}
 
.features16-fragment3 {
  display: contents;
}
 
.features16-text18 {
  display: inline-block;
}
 
.features16-fragment4 {
  display: contents;
}
 
.features16-text23 {
  display: inline-block;
}
 
.features16-fragment5 {
  display: contents;
}
 
.features16-text24 {
  display: inline-block;
}
 
.features16-fragment6 {
  display: contents;
}
 
.features16-text29 {
  display: inline-block;
}
 
.features16-fragment7 {
  display: contents;
}
 
.features16-text30 {
  display: inline-block;
}
 
.features16-fragment8 {
  display: contents;
}
 
.features16-text31 {
  display: inline-block;
}
 
@media(max-width: 991px) {
  .features16-section-title {
    width: 100%;
  }
}
 
@media(max-width: 767px) {
  .features16-max-width {
    gap: var(--dl-space-space-oneandhalfunits);
  }
  .features16-section-title {
    width: auto;
  }
  .features16-text10 {
    text-align: center;
  }
  .features16-row {
    flex-direction: column;
  }
  .features16-feature2 {
    width: auto;
  }
  .features16-feature3 {
    width: auto;
  }
}
</style>
