<template>
  <div class="thq-section-padding team12-team8">
    <div class="team12-max-width thq-section-max-width">
      <div class="team12-section-title">
        <div class="team12-content1">
          <h2 class="thq-heading-2">
            <slot name="heading1">
              <!--Default content for heading1-->
              <div class="team12-fragment16">
                <span class="team12-text51">田中　孝幸（たなか　たかゆき）</span>
              </div>
            </slot>
          </h2>
          <p class="thq-body-large team12-text11">
            <slot name="content2">
              <!--Default content for content2-->
              <div class="team12-fragment13">
                <span class="team12-text46">
                  <span>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    <span v-html="raw11xt"></span>
                  </span>
                  <span><span v-html="rawtf1x"></span></span>
                </span>
              </div>
            </slot>
          </p>
        </div>
      </div>
      <div class="team12-card1">
        <div class="team12-content2">
          <span class="team12-text12 thq-body-small">
            <slot name="member1Content">
              <!--Default content for member1Content-->
              <div>
                <span>
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                  Suspendisse varius enim in eros elementum tristique.
                </span>
              </div>
            </slot>
          </span>
        </div>
      </div>
      <div
        data-thq="slider"
        data-navigation="true"
        data-pagination="true"
        class="team12-slider swiper"
      >
        <div data-thq="slider-wrapper" class="swiper-wrapper">
          <div data-thq="slider-slide" class="team12-slider-slide1 swiper-slide">
            <div class="team12-card2">
              <img
                :alt="member1Alt"
                :src="member1Src"
                class="team12-placeholder-image1 thq-img-ratio-1-1 thq-img-round"
              />
              <div class="team12-content3">
                <div class="team12-title1">
                  <span class="team12-text13 thq-body-small">
                    <span>Full name</span>
                    <slot name="member1">
                      <!--Default content for member1-->
                      <div class="team12-fragment11">
                        <span class="team12-text44">Full name</span>
                      </div>
                    </slot>
                  </span>
                  <span class="team12-text15 thq-body-small">
                    <span>Job title</span>
                    <slot name="member1Job">
                      <!--Default content for member1Job-->
                      <div class="team12-fragment10">
                        <span class="team12-text43">Job title</span>
                      </div>
                    </slot>
                  </span>
                </div>
                <span class="team12-text17 thq-body-small">
                  <span>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Suspendisse varius enim in eros elementum tristique.
                  </span>
                  <slot name="member1Content">
                    <!--Default content for member1Content-->
                    <div class="team12-fragment14">
                      <span class="team12-text49">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                        Suspendisse varius enim in eros elementum tristique.
                      </span>
                    </div>
                  </slot>
                </span>
              </div>
              <div class="team12-social-icons1">
                <svg viewBox="0 0 877.7142857142857 1024" class="thq-icon-small">
                  <path
                    d="M135.429 808h132v-396.571h-132v396.571zM276 289.143c-0.571-38.857-28.571-68.571-73.714-68.571s-74.857 29.714-74.857 68.571c0 37.714 28.571 68.571 73.143 68.571h0.571c46.286 0 74.857-30.857 74.857-68.571zM610.286 808h132v-227.429c0-121.714-65.143-178.286-152-178.286-70.857 0-102.286 39.429-119.429 66.857h1.143v-57.714h-132s1.714 37.143 0 396.571v0h132v-221.714c0-11.429 0.571-23.429 4-32 9.714-23.429 31.429-48 68-48 47.429 0 66.286 36 66.286 89.714v212zM877.714 237.714v548.571c0 90.857-73.714 164.571-164.571 164.571h-548.571c-90.857 0-164.571-73.714-164.571-164.571v-548.571c0-90.857 73.714-164.571 164.571-164.571h548.571c90.857 0 164.571 73.714 164.571 164.571z"
                  ></path></svg
                ><svg viewBox="0 0 950.8571428571428 1024" class="thq-icon-small">
                  <path
                    d="M925.714 233.143c-25.143 36.571-56.571 69.143-92.571 95.429 0.571 8 0.571 16 0.571 24 0 244-185.714 525.143-525.143 525.143-104.571 0-201.714-30.286-283.429-82.857 14.857 1.714 29.143 2.286 44.571 2.286 86.286 0 165.714-29.143 229.143-78.857-81.143-1.714-149.143-54.857-172.571-128 11.429 1.714 22.857 2.857 34.857 2.857 16.571 0 33.143-2.286 48.571-6.286-84.571-17.143-148-91.429-148-181.143v-2.286c24.571 13.714 53.143 22.286 83.429 23.429-49.714-33.143-82.286-89.714-82.286-153.714 0-34.286 9.143-65.714 25.143-93.143 90.857 112 227.429 185.143 380.571 193.143-2.857-13.714-4.571-28-4.571-42.286 0-101.714 82.286-184.571 184.571-184.571 53.143 0 101.143 22.286 134.857 58.286 41.714-8 81.714-23.429 117.143-44.571-13.714 42.857-42.857 78.857-81.143 101.714 37.143-4 73.143-14.286 106.286-28.571z"
                  ></path>
                </svg>
              </div>
            </div>
          </div>
          <div data-thq="slider-slide" class="team12-slider-slide2 swiper-slide">
            <div class="team12-card3">
              <img
                :alt="member2Alt"
                :src="member2Src"
                class="team12-placeholder-image2 thq-img-ratio-1-1 thq-img-round"
              />
              <div class="team12-content4">
                <div class="team12-title2">
                  <span class="team12-text19 thq-body-small">Full name</span>
                  <span class="team12-text20 thq-body-small">Job title</span>
                </div>
                <span class="team12-text21 thq-body-small">
                  <span>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Suspendisse varius enim in eros elementum tristique.
                  </span>
                  <slot name="member2Content">
                    <!--Default content for member2Content-->
                    <div class="team12-fragment12">
                      <span class="team12-text45">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                        Suspendisse varius enim in eros elementum tristique.
                      </span>
                    </div>
                  </slot>
                </span>
              </div>
              <div class="team12-social-icons2">
                <svg viewBox="0 0 877.7142857142857 1024" class="thq-icon-small">
                  <path
                    d="M135.429 808h132v-396.571h-132v396.571zM276 289.143c-0.571-38.857-28.571-68.571-73.714-68.571s-74.857 29.714-74.857 68.571c0 37.714 28.571 68.571 73.143 68.571h0.571c46.286 0 74.857-30.857 74.857-68.571zM610.286 808h132v-227.429c0-121.714-65.143-178.286-152-178.286-70.857 0-102.286 39.429-119.429 66.857h1.143v-57.714h-132s1.714 37.143 0 396.571v0h132v-221.714c0-11.429 0.571-23.429 4-32 9.714-23.429 31.429-48 68-48 47.429 0 66.286 36 66.286 89.714v212zM877.714 237.714v548.571c0 90.857-73.714 164.571-164.571 164.571h-548.571c-90.857 0-164.571-73.714-164.571-164.571v-548.571c0-90.857 73.714-164.571 164.571-164.571h548.571c90.857 0 164.571 73.714 164.571 164.571z"
                  ></path></svg
                ><svg viewBox="0 0 950.8571428571428 1024" class="thq-icon-small">
                  <path
                    d="M925.714 233.143c-25.143 36.571-56.571 69.143-92.571 95.429 0.571 8 0.571 16 0.571 24 0 244-185.714 525.143-525.143 525.143-104.571 0-201.714-30.286-283.429-82.857 14.857 1.714 29.143 2.286 44.571 2.286 86.286 0 165.714-29.143 229.143-78.857-81.143-1.714-149.143-54.857-172.571-128 11.429 1.714 22.857 2.857 34.857 2.857 16.571 0 33.143-2.286 48.571-6.286-84.571-17.143-148-91.429-148-181.143v-2.286c24.571 13.714 53.143 22.286 83.429 23.429-49.714-33.143-82.286-89.714-82.286-153.714 0-34.286 9.143-65.714 25.143-93.143 90.857 112 227.429 185.143 380.571 193.143-2.857-13.714-4.571-28-4.571-42.286 0-101.714 82.286-184.571 184.571-184.571 53.143 0 101.143 22.286 134.857 58.286 41.714-8 81.714-23.429 117.143-44.571-13.714 42.857-42.857 78.857-81.143 101.714 37.143-4 73.143-14.286 106.286-28.571z"
                  ></path>
                </svg>
              </div>
            </div>
          </div>
          <div data-thq="slider-slide" class="team12-slider-slide3 swiper-slide">
            <div class="team12-card4">
              <img
                :alt="member3Alt"
                :src="member3Src"
                class="team12-placeholder-image3 thq-img-ratio-1-1 thq-img-round"
              />
              <div class="team12-content5">
                <div class="team12-title3">
                  <span class="team12-text23 thq-body-small">
                    <span>Full name</span>
                    <slot name="member3">
                      <!--Default content for member3-->
                      <div class="team12-fragment15">
                        <span class="team12-text50">Full name</span>
                      </div>
                    </slot>
                  </span>
                  <span class="team12-text25 thq-body-small">
                    <span>Job title</span>
                    <slot name="member3Job">
                      <!--Default content for member3Job-->
                      <div class="team12-fragment22">
                        <span class="team12-text57">Job title</span>
                      </div>
                    </slot>
                  </span>
                </div>
                <span class="team12-text27 thq-body-small">
                  <span>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Suspendisse varius enim in eros elementum tristique.
                  </span>
                  <slot name="member3Content">
                    <!--Default content for member3Content-->
                    <div class="team12-fragment28">
                      <span class="team12-text63">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                        Suspendisse varius enim in eros elementum tristique.
                      </span>
                    </div>
                  </slot>
                </span>
              </div>
              <div class="team12-social-icons3">
                <svg viewBox="0 0 877.7142857142857 1024" class="thq-icon-small">
                  <path
                    d="M135.429 808h132v-396.571h-132v396.571zM276 289.143c-0.571-38.857-28.571-68.571-73.714-68.571s-74.857 29.714-74.857 68.571c0 37.714 28.571 68.571 73.143 68.571h0.571c46.286 0 74.857-30.857 74.857-68.571zM610.286 808h132v-227.429c0-121.714-65.143-178.286-152-178.286-70.857 0-102.286 39.429-119.429 66.857h1.143v-57.714h-132s1.714 37.143 0 396.571v0h132v-221.714c0-11.429 0.571-23.429 4-32 9.714-23.429 31.429-48 68-48 47.429 0 66.286 36 66.286 89.714v212zM877.714 237.714v548.571c0 90.857-73.714 164.571-164.571 164.571h-548.571c-90.857 0-164.571-73.714-164.571-164.571v-548.571c0-90.857 73.714-164.571 164.571-164.571h548.571c90.857 0 164.571 73.714 164.571 164.571z"
                  ></path></svg
                ><svg viewBox="0 0 950.8571428571428 1024" class="thq-icon-small">
                  <path
                    d="M925.714 233.143c-25.143 36.571-56.571 69.143-92.571 95.429 0.571 8 0.571 16 0.571 24 0 244-185.714 525.143-525.143 525.143-104.571 0-201.714-30.286-283.429-82.857 14.857 1.714 29.143 2.286 44.571 2.286 86.286 0 165.714-29.143 229.143-78.857-81.143-1.714-149.143-54.857-172.571-128 11.429 1.714 22.857 2.857 34.857 2.857 16.571 0 33.143-2.286 48.571-6.286-84.571-17.143-148-91.429-148-181.143v-2.286c24.571 13.714 53.143 22.286 83.429 23.429-49.714-33.143-82.286-89.714-82.286-153.714 0-34.286 9.143-65.714 25.143-93.143 90.857 112 227.429 185.143 380.571 193.143-2.857-13.714-4.571-28-4.571-42.286 0-101.714 82.286-184.571 184.571-184.571 53.143 0 101.143 22.286 134.857 58.286 41.714-8 81.714-23.429 117.143-44.571-13.714 42.857-42.857 78.857-81.143 101.714 37.143-4 73.143-14.286 106.286-28.571z"
                  ></path>
                </svg>
              </div>
            </div>
          </div>
          <div data-thq="slider-slide" class="team12-slider-slide4 swiper-slide">
            <div class="team12-card5">
              <img
                :alt="member4Alt"
                :src="member4Src"
                class="team12-placeholder-image4 thq-img-ratio-1-1 thq-img-round"
              />
              <div class="team12-content6">
                <div class="team12-title4">
                  <span class="team12-text29 thq-body-small">
                    <span>Full name</span>
                    <slot name="member4">
                      <!--Default content for member4-->
                      <div class="team12-fragment29">
                        <span class="team12-text64">Full name</span>
                      </div>
                    </slot>
                  </span>
                  <span class="team12-text31 thq-body-small">
                    <span>Job title</span>
                    <slot name="member4Job">
                      <!--Default content for member4Job-->
                      <div class="team12-fragment17">
                        <span class="team12-text52">Job title</span>
                      </div>
                    </slot>
                  </span>
                </div>
                <span class="team12-text33 thq-body-small">
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                  Suspendisse varius enim in eros elementum tristique.
                </span>
              </div>
              <div class="team12-social-icons4">
                <svg viewBox="0 0 877.7142857142857 1024" class="thq-icon-small">
                  <path
                    d="M135.429 808h132v-396.571h-132v396.571zM276 289.143c-0.571-38.857-28.571-68.571-73.714-68.571s-74.857 29.714-74.857 68.571c0 37.714 28.571 68.571 73.143 68.571h0.571c46.286 0 74.857-30.857 74.857-68.571zM610.286 808h132v-227.429c0-121.714-65.143-178.286-152-178.286-70.857 0-102.286 39.429-119.429 66.857h1.143v-57.714h-132s1.714 37.143 0 396.571v0h132v-221.714c0-11.429 0.571-23.429 4-32 9.714-23.429 31.429-48 68-48 47.429 0 66.286 36 66.286 89.714v212zM877.714 237.714v548.571c0 90.857-73.714 164.571-164.571 164.571h-548.571c-90.857 0-164.571-73.714-164.571-164.571v-548.571c0-90.857 73.714-164.571 164.571-164.571h548.571c90.857 0 164.571 73.714 164.571 164.571z"
                  ></path></svg
                ><svg viewBox="0 0 950.8571428571428 1024" class="thq-icon-small">
                  <path
                    d="M925.714 233.143c-25.143 36.571-56.571 69.143-92.571 95.429 0.571 8 0.571 16 0.571 24 0 244-185.714 525.143-525.143 525.143-104.571 0-201.714-30.286-283.429-82.857 14.857 1.714 29.143 2.286 44.571 2.286 86.286 0 165.714-29.143 229.143-78.857-81.143-1.714-149.143-54.857-172.571-128 11.429 1.714 22.857 2.857 34.857 2.857 16.571 0 33.143-2.286 48.571-6.286-84.571-17.143-148-91.429-148-181.143v-2.286c24.571 13.714 53.143 22.286 83.429 23.429-49.714-33.143-82.286-89.714-82.286-153.714 0-34.286 9.143-65.714 25.143-93.143 90.857 112 227.429 185.143 380.571 193.143-2.857-13.714-4.571-28-4.571-42.286 0-101.714 82.286-184.571 184.571-184.571 53.143 0 101.143 22.286 134.857 58.286 41.714-8 81.714-23.429 117.143-44.571-13.714 42.857-42.857 78.857-81.143 101.714 37.143-4 73.143-14.286 106.286-28.571z"
                  ></path>
                </svg>
              </div>
            </div>
          </div>
          <div data-thq="slider-slide" class="team12-slider-slide5 swiper-slide">
            <div class="team12-card6">
              <img
                :alt="member5Alt"
                :src="member5Src"
                class="team12-placeholder-image5 thq-img-ratio-1-1 thq-img-round"
              />
              <div class="team12-content7">
                <div class="team12-title5">
                  <span class="team12-text34 thq-body-small">Full name</span>
                  <span class="team12-text35 thq-body-small">Job title</span>
                </div>
                <span class="team12-text36 thq-body-small">
                  <span>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Suspendisse varius enim in eros elementum tristique.
                  </span>
                  <slot name="member5Content">
                    <!--Default content for member5Content-->
                    <div class="team12-fragment25">
                      <span class="team12-text60">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                        Suspendisse varius enim in eros elementum tristique.
                      </span>
                    </div>
                  </slot>
                </span>
              </div>
              <div class="team12-social-icons5">
                <svg viewBox="0 0 877.7142857142857 1024" class="thq-icon-small">
                  <path
                    d="M135.429 808h132v-396.571h-132v396.571zM276 289.143c-0.571-38.857-28.571-68.571-73.714-68.571s-74.857 29.714-74.857 68.571c0 37.714 28.571 68.571 73.143 68.571h0.571c46.286 0 74.857-30.857 74.857-68.571zM610.286 808h132v-227.429c0-121.714-65.143-178.286-152-178.286-70.857 0-102.286 39.429-119.429 66.857h1.143v-57.714h-132s1.714 37.143 0 396.571v0h132v-221.714c0-11.429 0.571-23.429 4-32 9.714-23.429 31.429-48 68-48 47.429 0 66.286 36 66.286 89.714v212zM877.714 237.714v548.571c0 90.857-73.714 164.571-164.571 164.571h-548.571c-90.857 0-164.571-73.714-164.571-164.571v-548.571c0-90.857 73.714-164.571 164.571-164.571h548.571c90.857 0 164.571 73.714 164.571 164.571z"
                  ></path></svg
                ><svg viewBox="0 0 950.8571428571428 1024" class="thq-icon-small">
                  <path
                    d="M925.714 233.143c-25.143 36.571-56.571 69.143-92.571 95.429 0.571 8 0.571 16 0.571 24 0 244-185.714 525.143-525.143 525.143-104.571 0-201.714-30.286-283.429-82.857 14.857 1.714 29.143 2.286 44.571 2.286 86.286 0 165.714-29.143 229.143-78.857-81.143-1.714-149.143-54.857-172.571-128 11.429 1.714 22.857 2.857 34.857 2.857 16.571 0 33.143-2.286 48.571-6.286-84.571-17.143-148-91.429-148-181.143v-2.286c24.571 13.714 53.143 22.286 83.429 23.429-49.714-33.143-82.286-89.714-82.286-153.714 0-34.286 9.143-65.714 25.143-93.143 90.857 112 227.429 185.143 380.571 193.143-2.857-13.714-4.571-28-4.571-42.286 0-101.714 82.286-184.571 184.571-184.571 53.143 0 101.143 22.286 134.857 58.286 41.714-8 81.714-23.429 117.143-44.571-13.714 42.857-42.857 78.857-81.143 101.714 37.143-4 73.143-14.286 106.286-28.571z"
                  ></path>
                </svg>
              </div>
            </div>
          </div>
          <div data-thq="slider-slide" class="team12-slider-slide6 swiper-slide">
            <div class="team12-card7">
              <img
                :alt="member6Alt"
                :src="member6Src"
                class="team12-placeholder-image6 thq-img-ratio-1-1 thq-img-round"
              />
              <div class="team12-content8">
                <div class="team12-title6">
                  <span class="team12-text38 thq-body-small">
                    <span>Full name</span>
                    <slot name="member6">
                      <!--Default content for member6-->
                      <div class="team12-fragment18">
                        <span class="team12-text53">Full name</span>
                      </div>
                    </slot>
                  </span>
                  <span class="team12-text40 thq-body-small">Job title</span>
                </div>
                <span class="team12-text41 thq-body-small">
                  <span>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Suspendisse varius enim in eros elementum tristique.
                  </span>
                  <slot name="member6Content">
                    <!--Default content for member6Content-->
                    <div class="team12-fragment24">
                      <span class="team12-text59">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                        Suspendisse varius enim in eros elementum tristique.
                      </span>
                    </div>
                  </slot>
                </span>
              </div>
              <div class="team12-social-icons6">
                <svg viewBox="0 0 877.7142857142857 1024" class="thq-icon-small">
                  <path
                    d="M135.429 808h132v-396.571h-132v396.571zM276 289.143c-0.571-38.857-28.571-68.571-73.714-68.571s-74.857 29.714-74.857 68.571c0 37.714 28.571 68.571 73.143 68.571h0.571c46.286 0 74.857-30.857 74.857-68.571zM610.286 808h132v-227.429c0-121.714-65.143-178.286-152-178.286-70.857 0-102.286 39.429-119.429 66.857h1.143v-57.714h-132s1.714 37.143 0 396.571v0h132v-221.714c0-11.429 0.571-23.429 4-32 9.714-23.429 31.429-48 68-48 47.429 0 66.286 36 66.286 89.714v212zM877.714 237.714v548.571c0 90.857-73.714 164.571-164.571 164.571h-548.571c-90.857 0-164.571-73.714-164.571-164.571v-548.571c0-90.857 73.714-164.571 164.571-164.571h548.571c90.857 0 164.571 73.714 164.571 164.571z"
                  ></path></svg
                ><svg viewBox="0 0 950.8571428571428 1024" class="thq-icon-small">
                  <path
                    d="M925.714 233.143c-25.143 36.571-56.571 69.143-92.571 95.429 0.571 8 0.571 16 0.571 24 0 244-185.714 525.143-525.143 525.143-104.571 0-201.714-30.286-283.429-82.857 14.857 1.714 29.143 2.286 44.571 2.286 86.286 0 165.714-29.143 229.143-78.857-81.143-1.714-149.143-54.857-172.571-128 11.429 1.714 22.857 2.857 34.857 2.857 16.571 0 33.143-2.286 48.571-6.286-84.571-17.143-148-91.429-148-181.143v-2.286c24.571 13.714 53.143 22.286 83.429 23.429-49.714-33.143-82.286-89.714-82.286-153.714 0-34.286 9.143-65.714 25.143-93.143 90.857 112 227.429 185.143 380.571 193.143-2.857-13.714-4.571-28-4.571-42.286 0-101.714 82.286-184.571 184.571-184.571 53.143 0 101.143 22.286 134.857 58.286 41.714-8 81.714-23.429 117.143-44.571-13.714 42.857-42.857 78.857-81.143 101.714 37.143-4 73.143-14.286 106.286-28.571z"
                  ></path>
                </svg>
              </div>
            </div>
          </div>
        </div>
        <div
          data-thq="slider-pagination"
          class="team12-slider-pagination swiper-pagination swiper-pagination-bullets swiper-pagination-horizontal"
        >
          <div
            data-thq="slider-pagination-bullet"
            class="swiper-pagination-bullet swiper-pagination-bullet-active"
          ></div>
          <div
            data-thq="slider-pagination-bullet"
            class="swiper-pagination-bullet"
          ></div>
          <div
            data-thq="slider-pagination-bullet"
            class="swiper-pagination-bullet"
          ></div>
          <div
            data-thq="slider-pagination-bullet"
            class="swiper-pagination-bullet"
          ></div>
          <div
            data-thq="slider-pagination-bullet"
            class="swiper-pagination-bullet"
          ></div>
          <div
            data-thq="slider-pagination-bullet"
            class="swiper-pagination-bullet"
          ></div>
        </div>
        <div data-thq="slider-button-prev" class="swiper-button-prev"></div>
        <div data-thq="slider-button-next" class="swiper-button-next"></div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Team12',
  props: {
    member6Alt: {
      type: String,
      default: 'Member Alt',
    },
    member3Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1518739005966-3a39d6d87103?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNDQwMDIxNXw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    member4Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1515027037286-7da2d06130cf?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNDQwMDIxNnw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    member3Alt: {
      type: String,
      default: 'Member Alt',
    },
    member1Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1499996860823-5214fcc65f8f?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNDQwMDIxNnw&ixlib=rb-4.0.3&q=80&w=1400',
    },
    member1Alt: {
      type: String,
      default: 'Member Alt',
    },
    member4Alt: {
      type: String,
      default: 'Member Alt',
    },
    member2Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1492106087820-71f1a00d2b11?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNDQwMDIxNnw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    member5Alt: {
      type: String,
      default: 'Member Alt',
    },
    member5Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1636041247924-17cced2e0fd4?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNDQwMDIxNnw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    member2Alt: {
      type: String,
      default: 'Member Alt',
    },
    member6Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1496545087308-51ec893e6bbc?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNDQwMDIxNXw&ixlib=rb-4.0.3&q=80&w=1080',
    },
  },
  data() {
    return {
      rawqg7u: ' ',
      rawshqa: ' ',
      raw11xt: ' ',
      rawtf1x: ' ',
    }
  },
}
</script>

<style scoped>
.team12-max-width {
  gap: var(--dl-space-space-twounits);
  width: 100%;
  height: auto;
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team12-section-title {
  gap: var(--dl-space-space-unit);
  width: 100%;
  display: flex;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
}
 
.team12-content1 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
 
.team12-card1 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team12-content2 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team12-text12 {
  overflow: auto;
  max-height: var(--dl-size-size-medium);
  text-align: center;
}
 
.team12-slider {
  width: 100%;
  height: auto;
  display: none;
  position: relative;
}
 
.team12-slider-slide1 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  padding-bottom: var(--dl-space-space-threeunits);
}
 
.team12-card2 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team12-placeholder-image1 {
  width: 80%;
}
 
.team12-content3 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team12-title1 {
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team12-text13 {
  font-style: normal;
  font-weight: 600;
}
 
.team12-text15 {
  text-align: center;
}
 
.team12-text17 {
  overflow: auto;
  max-height: var(--dl-size-size-medium);
  text-align: center;
}
 
.team12-social-icons1 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
 
.team12-slider-slide2 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  padding-bottom: var(--dl-space-space-threeunits);
}
 
.team12-card3 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team12-placeholder-image2 {
  width: 80%;
}
 
.team12-content4 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team12-title2 {
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team12-text19 {
  font-style: normal;
  font-weight: 600;
}
 
.team12-text20 {
  text-align: center;
}
 
.team12-text21 {
  overflow: auto;
  max-height: var(--dl-size-size-medium);
  text-align: center;
}
 
.team12-social-icons2 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
 
.team12-slider-slide3 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  padding-bottom: var(--dl-space-space-threeunits);
}
 
.team12-card4 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team12-placeholder-image3 {
  width: 80%;
}
 
.team12-content5 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team12-title3 {
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team12-text23 {
  font-style: normal;
  font-weight: 600;
}
 
.team12-text25 {
  text-align: center;
}
 
.team12-text27 {
  overflow: auto;
  max-height: var(--dl-size-size-medium);
  text-align: center;
}
 
.team12-social-icons3 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
 
.team12-slider-slide4 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  padding-bottom: var(--dl-space-space-threeunits);
}
 
.team12-card5 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team12-placeholder-image4 {
  width: 80%;
}
 
.team12-content6 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team12-title4 {
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team12-text29 {
  font-style: normal;
  font-weight: 600;
}
 
.team12-text31 {
  text-align: center;
}
 
.team12-text33 {
  overflow: auto;
  max-height: var(--dl-size-size-medium);
  text-align: center;
}
 
.team12-social-icons4 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
 
.team12-slider-slide5 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  padding-bottom: var(--dl-space-space-threeunits);
}
 
.team12-card6 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team12-placeholder-image5 {
  width: 80%;
}
 
.team12-content7 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team12-title5 {
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team12-text34 {
  font-style: normal;
  font-weight: 600;
}
 
.team12-text35 {
  text-align: center;
}
 
.team12-text36 {
  overflow: hidden;
  max-height: var(--dl-size-size-medium);
  text-align: center;
}
 
.team12-social-icons5 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
 
.team12-slider-slide6 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  padding-bottom: var(--dl-space-space-threeunits);
}
 
.team12-card7 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team12-placeholder-image6 {
  width: 80%;
}
 
.team12-content8 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team12-title6 {
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team12-text38 {
  font-style: normal;
  font-weight: 600;
}
 
.team12-text40 {
  text-align: center;
}
 
.team12-text41 {
  overflow: auto;
  max-height: var(--dl-size-size-medium);
  text-align: center;
}
 
.team12-social-icons6 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
 
.team12-slider-pagination {
  display: block;
}
 
.team12-fragment10 {
  display: contents;
}
 
.team12-text43 {
  display: inline-block;
}
 
.team12-fragment11 {
  display: contents;
}
 
.team12-text44 {
  display: inline-block;
}
 
.team12-fragment12 {
  display: contents;
}
 
.team12-text45 {
  display: inline-block;
}
 
.team12-fragment13 {
  display: contents;
}
 
.team12-text46 {
  display: inline-block;
}
 
.team12-fragment14 {
  display: contents;
}
 
.team12-text49 {
  display: inline-block;
}
 
.team12-fragment15 {
  display: contents;
}
 
.team12-text50 {
  display: inline-block;
}
 
.team12-fragment16 {
  display: contents;
}
 
.team12-text51 {
  display: inline-block;
}
 
.team12-fragment17 {
  display: contents;
}
 
.team12-text52 {
  display: inline-block;
}
 
.team12-fragment18 {
  display: contents;
}
 
.team12-text53 {
  display: inline-block;
}
 
.team12-fragment19 {
  display: contents;
}
 
.team12-text54 {
  display: inline-block;
}
 
.team12-fragment20 {
  display: contents;
}
 
.team12-text55 {
  display: inline-block;
}
 
.team12-fragment21 {
  display: contents;
}
 
.team12-text56 {
  display: inline-block;
}
 
.team12-fragment22 {
  display: contents;
}
 
.team12-text57 {
  display: inline-block;
}
 
.team12-fragment23 {
  display: contents;
}
 
.team12-text58 {
  display: inline-block;
}
 
.team12-fragment24 {
  display: contents;
}
 
.team12-text59 {
  display: inline-block;
}
 
.team12-fragment25 {
  display: contents;
}
 
.team12-text60 {
  display: inline-block;
}
 
.team12-fragment26 {
  display: contents;
}
 
.team12-text61 {
  display: inline-block;
}
 
.team12-fragment27 {
  display: contents;
}
 
.team12-text62 {
  display: inline-block;
}
 
.team12-fragment28 {
  display: contents;
}
 
.team12-text63 {
  display: inline-block;
}
 
.team12-fragment29 {
  display: contents;
}
 
.team12-text64 {
  display: inline-block;
}
 
@media(max-width: 767px) {
  .team12-team8 {
    padding: var(--dl-space-space-threeunits);
  }
  .team12-max-width {
    padding: var(--dl-space-space-threeunits);
  }
  .team12-slider {
    display: block;
  }
}
 
@media(max-width: 479px) {
  .team12-team8 {
    padding: var(--dl-space-space-oneandhalfunits);
  }
  .team12-max-width {
    padding: var(--dl-space-space-oneandhalfunits);
  }
  .team12-text11 {
    text-align: center;
  }
  .team12-placeholder-image1 {
    width: 100%;
  }
  .team12-placeholder-image2 {
    width: 100%;
  }
  .team12-placeholder-image3 {
    width: 100%;
  }
  .team12-placeholder-image4 {
    width: 100%;
  }
  .team12-placeholder-image5 {
    width: 100%;
  }
  .team12-placeholder-image6 {
    width: 100%;
  }
}
</style>
