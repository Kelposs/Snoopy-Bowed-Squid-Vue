<template>
  <div class="pricing1-pricing1 thq-section-padding">
    <div class="pricing1-max-width thq-section-max-width">
      <div class="pricing1-section-title">
        <div class="pricing1-content1">
          <h2 class="pricing1-text10 thq-heading-2">
            <slot name="heading1">
              <!--Default content for heading1-->
              <div class="pricing1-fragment3">
                <span class="pricing1-text20">Pricing Options</span>
              </div>
            </slot>
          </h2>
        </div>
      </div>
      <div class="pricing1-content2 thq-card">
        <div class="pricing1-price">
          <p class="pricing1-text11 thq-body-large">
            <slot name="plan1">
              <!--Default content for plan1-->
              <div class="pricing1-fragment2">
                <span class="pricing1-text19">Basic Consultation Package</span>
              </div>
            </slot>
          </p>
          <h3 class="pricing1-text12 thq-heading-3">
            <slot name="plan1Price">
              <!--Default content for plan1Price-->
              <div class="pricing1-fragment8">
                <span class="pricing1-text25">$99</span>
              </div>
            </slot>
          </h3>
          <p class="thq-body-large">
            <slot name="plan1Yearly">
              <!--Default content for plan1Yearly-->
              <div class="pricing1-fragment4">
                <span class="pricing1-text21">(One-time fee)</span>
              </div>
            </slot>
          </p>
        </div>
        <div class="pricing1-list">
          <div class="pricing1-list-item1">
            <svg viewBox="0 0 1024 1024" class="thq-icon-small">
              <path d="M384 690l452-452 60 60-512 512-238-238 60-60z"></path>
            </svg>
            <span class="thq-body-small">
              <slot name="plan1Feature1">
                <!--Default content for plan1Feature1-->
                <div class="pricing1-fragment7">
                  <span class="pricing1-text24">
                    Personalized guidance for your child
                  </span>
                </div>
              </slot>
            </span>
          </div>
          <div class="pricing1-list-item2">
            <svg viewBox="0 0 1024 1024" class="thq-icon-small">
              <path d="M384 690l452-452 60 60-512 512-238-238 60-60z"></path>
            </svg>
            <span class="thq-body-small">
              <slot name="plan1Feature2">
                <!--Default content for plan1Feature2-->
                <div class="pricing1-fragment6">
                  <span class="pricing1-text23">
                    Individualized support sessions
                  </span>
                </div>
              </slot>
            </span>
          </div>
          <div class="pricing1-list-item3">
            <svg viewBox="0 0 1024 1024" class="thq-icon-small">
              <path d="M384 690l452-452 60 60-512 512-238-238 60-60z"></path>
            </svg>
            <span class="thq-body-small">
              <slot name="plan1Feature3">
                <!--Default content for plan1Feature3-->
                <div class="pricing1-fragment1">
                  <span class="pricing1-text18">
                    Tailored advice based on unique needs
                  </span>
                </div>
              </slot>
            </span>
          </div>
        </div>
        <button class="pricing1-button thq-button-filled">
          <span class="thq-body-small">
            <slot name="plan1Action">
              <!--Default content for plan1Action-->
              <div class="pricing1-fragment5">
                <span class="pricing1-text22">Get Started</span>
              </div>
            </slot>
          </span>
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Pricing1',
  props: {},
}
</script>

<style scoped>
.pricing1-pricing1 {
  width: 100%;
  height: auto;
  display: flex;
  overflow: hidden;
  position: relative;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
}
 
.pricing1-max-width {
  gap: var(--dl-space-space-threeunits);
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.pricing1-section-title {
  gap: var(--dl-space-space-unit);
  width: 100%;
  display: flex;
  max-width: 800px;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
}
 
.pricing1-content1 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
 
.pricing1-text10 {
  text-align: center;
}
 
.pricing1-content2 {
  gap: var(--dl-space-space-twounits);
  flex: 1;
  width: 100%;
  display: flex;
  max-width: 560px;
  align-items: center;
  flex-shrink: 0;
  border-color: var(--dl-color-theme-neutral-dark);
  border-style: solid;
  border-width: 1px;
  flex-direction: column;
}
 
.pricing1-price {
  gap: var(--dl-space-space-halfunit);
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.pricing1-text11 {
  font-style: normal;
  font-weight: 600;
}
 
.pricing1-text12 {
  fill: var(--dl-color-theme-neutral-dark);
  color: var(--dl-color-theme-neutral-dark);
  font-size: 48px;
}
 
.pricing1-list {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
 
.pricing1-list-item1 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-shrink: 0;
}
 
.pricing1-list-item2 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-shrink: 0;
}
 
.pricing1-list-item3 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-shrink: 0;
}
 
.pricing1-button {
  width: 100%;
}
 
.pricing1-fragment1 {
  display: contents;
}
 
.pricing1-text18 {
  display: inline-block;
}
 
.pricing1-fragment2 {
  display: contents;
}
 
.pricing1-text19 {
  display: inline-block;
}
 
.pricing1-fragment3 {
  display: contents;
}
 
.pricing1-text20 {
  display: inline-block;
}
 
.pricing1-fragment4 {
  display: contents;
}
 
.pricing1-text21 {
  display: inline-block;
}
 
.pricing1-fragment5 {
  display: contents;
}
 
.pricing1-text22 {
  display: inline-block;
}
 
.pricing1-fragment6 {
  display: contents;
}
 
.pricing1-text23 {
  display: inline-block;
}
 
.pricing1-fragment7 {
  display: contents;
}
 
.pricing1-text24 {
  display: inline-block;
}
 
.pricing1-fragment8 {
  display: contents;
}
 
.pricing1-text25 {
  display: inline-block;
}
 
@media(max-width: 479px) {
  .pricing1-max-width {
    gap: var(--dl-space-space-oneandhalfunits);
  }
  .pricing1-button {
    width: 100%;
  }
}
</style>
