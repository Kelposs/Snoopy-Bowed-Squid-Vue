<template>
  <div class="contact11-container thq-section-padding">
    <div class="contact11-max-width thq-section-max-width">
      <div class="contact11-section-title">
        <div class="contact11-content1">
          <h2 class="thq-heading-2">
            <slot name="heading1">
              <!--Default content for heading1-->
              <div class="contact11-fragment3">
                <span class="contact11-text18">Get in Touch</span>
              </div>
            </slot>
          </h2>
          <p class="thq-body-large">
            <slot name="content1">
              <!--Default content for content1-->
              <div class="contact11-fragment5">
                <span class="contact11-text20">
                  Feel free to reach out to us for any inquiries or to schedule a
                  consultation session.
                </span>
              </div>
            </slot>
          </p>
        </div>
      </div>
      <div class="contact11-content2 thq-flex-row">
        <div class="contact11-content3">
          <div class="contact11-content4">
            <svg viewBox="0 0 1024 1024" class="thq-icon-medium">
              <path
                d="M854 342v-86l-342 214-342-214v86l342 212zM854 170q34 0 59 26t25 60v512q0 34-25 60t-59 26h-684q-34 0-59-26t-25-60v-512q0-34 25-60t59-26h684z"
              ></path>
            </svg>
            <div class="contact11-contact-info1">
              <h3 class="contact11-text12 thq-heading-3">Email</h3>
              <span class="thq-body-small">
                <slot name="email">
                  <!--Default content for email-->
                  <div class="contact11-fragment2">
                    <span class="contact11-text17">
                      contact@empowerabledkids.com
                    </span>
                  </div>
                </slot>
              </span>
            </div>
          </div>
          <div class="contact11-content5">
            <svg viewBox="0 0 1024 1024" class="thq-icon-medium">
              <path
                d="M282 460q96 186 282 282l94-94q20-20 44-10 72 24 152 24 18 0 30 12t12 30v150q0 18-12 30t-30 12q-300 0-513-213t-213-513q0-18 12-30t30-12h150q18 0 30 12t12 30q0 80 24 152 8 26-10 44z"
              ></path>
            </svg>
            <div class="contact11-contact-info2">
              <h3 class="contact11-text13 thq-heading-3">Phone</h3>
              <span class="thq-body-small">
                <slot name="phone1">
                  <!--Default content for phone1-->
                  <div class="contact11-fragment1">
                    <span class="contact11-text16">+1-123-456-7890</span>
                  </div>
                </slot>
              </span>
            </div>
          </div>
          <div class="contact11-content6">
            <svg viewBox="0 0 1024 1024" class="thq-icon-medium">
              <path
                d="M512 0c-176.732 0-320 143.268-320 320 0 320 320 704 320 704s320-384 320-704c0-176.732-143.27-320-320-320zM512 512c-106.040 0-192-85.96-192-192s85.96-192 192-192 192 85.96 192 192-85.96 192-192 192z"
              ></path>
            </svg>
            <div class="contact11-contact-info3">
              <h3 class="contact11-text15 thq-heading-3">Office</h3>
              <span class="thq-body-small">
                <slot name="address1">
                  <!--Default content for address1-->
                  <div class="contact11-fragment4">
                    <span class="contact11-text19">
                      123 Main Street, Cityville, State, 12345
                    </span>
                  </div>
                </slot>
              </span>
            </div>
          </div>
        </div>
        <iframe
          :src="location1GoogleMap"
          title="Map"
          class="contact11-iframe thq-img-ratio-16-9"
        ></iframe>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Contact11',
  props: {
    location1GoogleMap: {
      type: String,
      default:
        'https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3274.961090465633!2d135.4936257!3d34.83207079999999!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x6000fbd0e968dffb%3A0xe55292dd16766cb8!2z55u46KuH5pSv5o-05LqL5qWt5omAIOOBruOCkw!5e0!3m2!1sen!2sjp!4v1736661526418!5m2!1sen!2sjp',
    },
  },
}
</script>

<style scoped>
.contact11-container {
  display: flex;
  position: relative;
  align-items: flex-start;
  flex-direction: column;
}
 
.contact11-max-width {
  align-self: center;
}
 
.contact11-section-title {
  width: 100%;
  margin-bottom: var(--dl-space-space-threeunits);
}
 
.contact11-content1 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
 
.contact11-content2 {
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
 
.contact11-content3 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.contact11-content4 {
  gap: 16px;
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
 
.contact11-contact-info1 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
 
.contact11-text12 {
  align-self: flex-start;
  text-align: center;
}
 
.contact11-content5 {
  gap: 16px;
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
 
.contact11-contact-info2 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
 
.contact11-text13 {
  align-self: flex-start;
  text-align: center;
}
 
.contact11-content6 {
  gap: 16px;
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
 
.contact11-contact-info3 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
 
.contact11-text15 {
  align-self: flex-start;
  text-align: center;
}
 
.contact11-iframe {
  height: 664px;
}
 
.contact11-fragment1 {
  display: contents;
}
 
.contact11-text16 {
  display: inline-block;
}
 
.contact11-fragment2 {
  display: contents;
}
 
.contact11-text17 {
  display: inline-block;
}
 
.contact11-fragment3 {
  display: contents;
}
 
.contact11-text18 {
  display: inline-block;
}
 
.contact11-fragment4 {
  display: contents;
}
 
.contact11-text19 {
  display: inline-block;
}
 
.contact11-fragment5 {
  display: contents;
}
 
.contact11-text20 {
  display: inline-block;
}
 
@media(max-width: 991px) {
  .contact11-content2 {
    position: relative;
    align-items: flex-start;
    flex-direction: column;
  }
}
</style>
