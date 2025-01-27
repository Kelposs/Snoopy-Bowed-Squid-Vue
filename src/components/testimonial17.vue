<template>
  <div class="thq-section-padding">
    <div class="testimonial17-max-width thq-section-max-width">
      <div class="testimonial17-container10">
        <h2 class="thq-heading-2">
          <slot name="heading1">
            <!--Default content for heading1-->
            <div class="testimonial17-fragment21">
              <span class="testimonial17-text35">Testimonials</span>
            </div>
          </slot>
        </h2>
        <span class="testimonial17-text11 thq-body-small">
          <slot name="content1">
            <!--Default content for content1-->
            <div class="testimonial17-fragment20">
              <span class="testimonial17-text34">
                Read what our clients have to say about our consultation support
                for disabled children.
              </span>
            </div>
          </slot>
        </span>
      </div>
      <div class="thq-grid-2">
        <div class="thq-animated-card-bg-2">
          <div class="thq-animated-card-bg-1">
            <div data-animated="true" class="thq-card testimonial17-card1">
              <div class="testimonial17-container12">
                <img
                  :alt="author1Alt"
                  :src="author1Src"
                  class="testimonial17-image1"
                />
                <div class="testimonial17-container13">
                  <strong class="thq-body-large">
                    <slot name="author1Name">
                      <!--Default content for author1Name-->
                      <div class="testimonial17-fragment19">
                        <span class="testimonial17-text33">Sarah Johnson</span>
                      </div>
                    </slot>
                  </strong>
                  <span class="thq-body-small">
                    <slot name="author1Position">
                      <!--Default content for author1Position-->
                      <div class="testimonial17-fragment12">
                        <span class="testimonial17-text26">
                          Parent of a disabled child
                        </span>
                      </div>
                    </slot>
                  </span>
                </div>
              </div>
              <span class="testimonial17-text14 thq-body-small">
                <slot name="review1">
                  <!--Default content for review1-->
                  <div class="testimonial17-fragment13">
                    <span class="testimonial17-text27">
                      The consultation provided by the team was invaluable in
                      helping us navigate the challenges of raising a disabled
                      child. Highly recommended!
                    </span>
                  </div>
                </slot>
              </span>
            </div>
          </div>
        </div>
        <div class="thq-animated-card-bg-2">
          <div class="thq-animated-card-bg-1">
            <div data-animated="true" class="thq-card testimonial17-card2">
              <div class="testimonial17-container14">
                <img
                  :alt="author2Alt"
                  :src="author2Src"
                  class="testimonial17-image2"
                />
                <div class="testimonial17-container15">
                  <strong class="thq-body-large">
                    <slot name="author2Name">
                      <!--Default content for author2Name-->
                      <div class="testimonial17-fragment10">
                        <span class="testimonial17-text24">Michael Lee</span>
                      </div>
                    </slot>
                  </strong>
                  <span class="thq-body-small">
                    <slot name="author2Position">
                      <!--Default content for author2Position-->
                      <div class="testimonial17-fragment15">
                        <span class="testimonial17-text29">
                          Special Education Teacher
                        </span>
                      </div>
                    </slot>
                  </span>
                </div>
              </div>
              <span class="testimonial17-text17 thq-body-small">
                <slot name="review2">
                  <!--Default content for review2-->
                  <div class="testimonial17-fragment22">
                    <span class="testimonial17-text36">
                      I have seen a significant improvement in my students after
                      implementing the strategies suggested during the
                      consultation. Thank you!
                    </span>
                  </div>
                </slot>
              </span>
            </div>
          </div>
        </div>
        <div class="thq-animated-card-bg-2">
          <div class="thq-animated-card-bg-1">
            <div data-animated="true" class="thq-card testimonial17-card3">
              <div class="testimonial17-container16">
                <img
                  :alt="author3Alt"
                  :src="author3Src"
                  class="testimonial17-image3"
                />
                <div class="testimonial17-container17">
                  <strong class="thq-body-large">
                    <slot name="author3Name">
                      <!--Default content for author3Name-->
                      <div class="testimonial17-fragment17">
                        <span class="testimonial17-text31">Emily Chen</span>
                      </div>
                    </slot>
                  </strong>
                  <span class="thq-body-small">
                    <slot name="author3Position">
                      <!--Default content for author3Position-->
                      <div class="testimonial17-fragment23">
                        <span class="testimonial17-text37">
                          Occupational Therapist
                        </span>
                      </div>
                    </slot>
                  </span>
                </div>
              </div>
              <span class="testimonial17-text20 thq-body-small">
                <slot name="review3">
                  <!--Default content for review3-->
                  <div class="testimonial17-fragment18">
                    <span class="testimonial17-text32">
                      Working with the team has been a pleasure. Their expertise
                      in supporting disabled children is evident in the positive
                      outcomes we have seen.
                    </span>
                  </div>
                </slot>
              </span>
            </div>
          </div>
        </div>
        <div class="thq-animated-card-bg-2">
          <div class="thq-animated-card-bg-1">
            <div data-animated="true" class="thq-card testimonial17-card4">
              <div class="testimonial17-container18">
                <img
                  :alt="author4Alt"
                  :src="author4Src"
                  class="testimonial17-image4"
                />
                <div class="testimonial17-container19">
                  <strong class="thq-body-large">
                    <slot name="author4Name">
                      <!--Default content for author4Name-->
                      <div class="testimonial17-fragment14">
                        <span class="testimonial17-text28">David Patel</span>
                      </div>
                    </slot>
                  </strong>
                  <span class="thq-body-small">
                    <slot name="author4Position">
                      <!--Default content for author4Position-->
                      <div class="testimonial17-fragment16">
                        <span class="testimonial17-text30">
                          Child Psychologist
                        </span>
                      </div>
                    </slot>
                  </span>
                </div>
              </div>
              <span class="testimonial17-text23 thq-body-small">
                <slot name="review4">
                  <!--Default content for review4-->
                  <div class="testimonial17-fragment11">
                    <span class="testimonial17-text25">
                      I collaborate with the team regularly to ensure holistic
                      support for children with disabilities. Their dedication is
                      commendable.
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
  name: 'Testimonial17',
  props: {
    author4Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1493655161922-ef98929de9d8?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNDM5ODM0OHw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    author1Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1492288991661-058aa541ff43?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNDM5ODM0OHw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    author2Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1599566150163-29194dcaad36?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNDM5ODM0OHw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    author2Alt: {
      type: String,
      default: 'Image of Michael Lee',
    },
    author3Alt: {
      type: String,
      default: 'Image of Emily Chen',
    },
    author1Alt: {
      type: String,
      default: 'Image of Sarah Johnson',
    },
    author3Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1525219884637-43180fbb6455?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNDM5ODM0OHw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    author4Alt: {
      type: String,
      default: 'Image of David Patel',
    },
  },
}
</script>

<style scoped>
.testimonial17-max-width {
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.testimonial17-container10 {
  gap: var(--dl-space-space-unit);
  display: flex;
  max-width: 600px;
  align-items: center;
  margin-bottom: var(--dl-space-space-fourunits);
  flex-direction: column;
}
 
.testimonial17-text11 {
  text-align: center;
}
 
.testimonial17-container12 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-self: flex-start;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
 
.testimonial17-image1 {
  width: var(--dl-size-size-small);
  height: var(--dl-size-size-small);
  object-fit: cover;
  border-radius: var(--dl-radius-radius-round);
}
 
.testimonial17-container13 {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
 
.testimonial17-text14 {
  text-align: left;
}
 
.testimonial17-container14 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-self: flex-start;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
 
.testimonial17-image2 {
  width: var(--dl-size-size-small);
  height: var(--dl-size-size-small);
  object-fit: cover;
  border-radius: var(--dl-radius-radius-round);
}
 
.testimonial17-container15 {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
 
.testimonial17-text17 {
  text-align: left;
}
 
.testimonial17-container16 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-self: flex-start;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
 
.testimonial17-image3 {
  width: var(--dl-size-size-small);
  height: var(--dl-size-size-small);
  object-fit: cover;
  border-radius: var(--dl-radius-radius-round);
}
 
.testimonial17-container17 {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
 
.testimonial17-text20 {
  text-align: left;
}
 
.testimonial17-container18 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-self: flex-start;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
 
.testimonial17-image4 {
  width: var(--dl-size-size-small);
  height: var(--dl-size-size-small);
  object-fit: cover;
  border-radius: var(--dl-radius-radius-round);
}
 
.testimonial17-container19 {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
 
.testimonial17-text23 {
  text-align: left;
}
 
.testimonial17-fragment10 {
  display: contents;
}
 
.testimonial17-text24 {
  display: inline-block;
}
 
.testimonial17-fragment11 {
  display: contents;
}
 
.testimonial17-text25 {
  display: inline-block;
}
 
.testimonial17-fragment12 {
  display: contents;
}
 
.testimonial17-text26 {
  display: inline-block;
}
 
.testimonial17-fragment13 {
  display: contents;
}
 
.testimonial17-text27 {
  display: inline-block;
}
 
.testimonial17-fragment14 {
  display: contents;
}
 
.testimonial17-text28 {
  display: inline-block;
}
 
.testimonial17-fragment15 {
  display: contents;
}
 
.testimonial17-text29 {
  display: inline-block;
}
 
.testimonial17-fragment16 {
  display: contents;
}
 
.testimonial17-text30 {
  display: inline-block;
}
 
.testimonial17-fragment17 {
  display: contents;
}
 
.testimonial17-text31 {
  display: inline-block;
}
 
.testimonial17-fragment18 {
  display: contents;
}
 
.testimonial17-text32 {
  display: inline-block;
}
 
.testimonial17-fragment19 {
  display: contents;
}
 
.testimonial17-text33 {
  display: inline-block;
}
 
.testimonial17-fragment20 {
  display: contents;
}
 
.testimonial17-text34 {
  display: inline-block;
}
 
.testimonial17-fragment21 {
  display: contents;
}
 
.testimonial17-text35 {
  display: inline-block;
}
 
.testimonial17-fragment22 {
  display: contents;
}
 
.testimonial17-text36 {
  display: inline-block;
}
 
.testimonial17-fragment23 {
  display: contents;
}
 
.testimonial17-text37 {
  display: inline-block;
}
 
@media(max-width: 991px) {
  .testimonial17-container10 {
    margin-bottom: var(--dl-space-space-threeunits);
  }
}
 
@media(max-width: 767px) {
  .testimonial17-container10 {
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
  .testimonial17-card1 {
    width: 100%;
  }
  .testimonial17-card2 {
    width: 100%;
  }
  .testimonial17-card3 {
    width: 100%;
  }
  .testimonial17-card4 {
    width: 100%;
  }
}
</style>
