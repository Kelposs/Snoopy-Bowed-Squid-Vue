<template>
  <div class="pricing4-pricing10 thq-section-padding">
    <div class="pricing4-max-width thq-section-max-width">
      <div class="pricing4-section-title">
        <div class="pricing4-content1">
          <h2 class="pricing4-text10 thq-heading-2">
            <slot name="heading1">
              <!--Default content for heading1-->
              <div class="pricing4-fragment7">
                <span class="pricing4-text24">Our Consultation Plans</span>
              </div>
            </slot>
          </h2>
        </div>
      </div>
      <div class="pricing4-content2">
        <div class="pricing4-column thq-card">
          <div class="pricing4-content3">
            <div class="pricing4-price">
              <p class="pricing4-text11 thq-body-large">
                <slot name="plan1">
                  <!--Default content for plan1-->
                  <div class="pricing4-fragment2">
                    <span class="pricing4-text19">Basic Consultation</span>
                  </div>
                </slot>
              </p>
              <h3 class="pricing4-text12 thq-heading-3">
                <slot name="plan1Price">
                  <!--Default content for plan1Price-->
                  <div class="pricing4-fragment3">
                    <span class="pricing4-text20">$50 per session</span>
                  </div>
                </slot>
              </h3>
              <p class="pricing4-text13 thq-body-large">
                <slot name="plan1Yearly">
                  <!--Default content for plan1Yearly-->
                  <div class="pricing4-fragment4">
                    <span class="pricing4-text21">Not applicable</span>
                  </div>
                </slot>
              </p>
            </div>
            <div class="pricing4-list">
              <div class="pricing4-list-item1">
                <svg viewBox="0 0 1024 1024" class="thq-icon-small">
                  <path d="M384 690l452-452 60 60-512 512-238-238 60-60z"></path>
                </svg>
                <span class="thq-body-small">
                  <slot name="plan1Feature1">
                    <!--Default content for plan1Feature1-->
                    <div class="pricing4-fragment6">
                      <span class="pricing4-text23">
                        One-on-one consultation session
                      </span>
                    </div>
                  </slot>
                </span>
              </div>
              <div class="pricing4-list-item2">
                <svg viewBox="0 0 1024 1024" class="thq-icon-small">
                  <path d="M384 690l452-452 60 60-512 512-238-238 60-60z"></path>
                </svg>
                <span class="thq-body-small">
                  <slot name="plan1Feature2">
                    <!--Default content for plan1Feature2-->
                    <div class="pricing4-fragment8">
                      <span class="pricing4-text25">Goal-setting session</span>
                    </div>
                  </slot>
                </span>
              </div>
              <div class="pricing4-list-item3">
                <svg viewBox="0 0 1024 1024" class="thq-icon-small">
                  <path d="M384 690l452-452 60 60-512 512-238-238 60-60z"></path>
                </svg>
                <span class="thq-body-small">
                  <slot name="plan1Feature3">
                    <!--Default content for plan1Feature3-->
                    <div class="pricing4-fragment5">
                      <span class="pricing4-text22">
                        Tailored advice for your child
                      </span>
                    </div>
                  </slot>
                </span>
              </div>
            </div>
          </div>
          <button class="pricing4-button thq-button-outline">
            <span class="thq-body-small">
              <slot name="plan1Action">
                <!--Default content for plan1Action-->
                <div class="pricing4-fragment1">
                  <span class="pricing4-text18">Get Started</span>
                </div>
              </slot>
            </span>
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Pricing4',
  props: {},
}
</script>

<style scoped>
.pricing4-pricing10 {
  width: 100%;
  height: auto;
  display: flex;
  overflow: hidden;
  position: relative;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
}
 
.pricing4-max-width {
  gap: var(--dl-space-space-threeunits);
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.pricing4-section-title {
  gap: var(--dl-space-space-unit);
  width: 100%;
  display: flex;
  max-width: 800px;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
}
 
.pricing4-content1 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
 
.pricing4-text10 {
  text-align: center;
}
 
.pricing4-content2 {
  gap: var(--dl-space-space-twounits);
  width: 100%;
  display: flex;
  align-items: stretch;
  flex-shrink: 0;
}
 
.pricing4-column {
  flex: 1;
  display: flex;
  align-items: center;
  border-color: var(--dl-color-theme-neutral-dark);
  border-style: solid;
  border-width: 1px;
  border-radius: var(--dl-radius-radius-radius4);
  flex-direction: column;
  justify-content: space-between;
}
 
.pricing4-content3 {
  gap: 32px;
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
 
.pricing4-price {
  gap: var(--dl-space-space-halfunit);
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
 
.pricing4-text11 {
  font-style: normal;
  text-align: center;
  font-weight: 600;
}
 
.pricing4-text12 {
  font-size: 48px;
  text-align: center;
}
 
.pricing4-text13 {
  text-align: center;
}
 
.pricing4-list {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
 
.pricing4-list-item1 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-shrink: 0;
}
 
.pricing4-list-item2 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-shrink: 0;
}
 
.pricing4-list-item3 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-shrink: 0;
}
 
.pricing4-button {
  width: 100%;
}
 
.pricing4-fragment1 {
  display: contents;
}
 
.pricing4-text18 {
  display: inline-block;
}
 
.pricing4-fragment2 {
  display: contents;
}
 
.pricing4-text19 {
  display: inline-block;
}
 
.pricing4-fragment3 {
  display: contents;
}
 
.pricing4-text20 {
  display: inline-block;
}
 
.pricing4-fragment4 {
  display: contents;
}
 
.pricing4-text21 {
  display: inline-block;
}
 
.pricing4-fragment5 {
  display: contents;
}
 
.pricing4-text22 {
  display: inline-block;
}
 
.pricing4-fragment6 {
  display: contents;
}
 
.pricing4-text23 {
  display: inline-block;
}
 
.pricing4-fragment7 {
  display: contents;
}
 
.pricing4-text24 {
  display: inline-block;
}
 
.pricing4-fragment8 {
  display: contents;
}
 
.pricing4-text25 {
  display: inline-block;
}
 
@media(max-width: 767px) {
  .pricing4-content2 {
    flex-direction: column;
  }
}
 
@media(max-width: 479px) {
  .pricing4-max-width {
    gap: var(--dl-space-space-oneandhalfunits);
  }
  .pricing4-button {
    width: 100%;
  }
}
</style>
