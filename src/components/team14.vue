<template>
  <div class="thq-section-padding">
    <div class="team14-max-width thq-section-max-width">
      <div class="team14-section-title">
        <span class="thq-body-small team14-text10">
          <slot name="content1">
            <!--Default content for content1-->
            <div class="team14-fragment26">
              <span class="team14-text86">
                Our team consists of dedicated professionals with diverse
                expertise in supporting disabled children and their families.
              </span>
            </div>
          </slot>
        </span>
        <button class="team14-button thq-button-filled">
          <span class="thq-body-small">
            <slot name="actionContent">
              <!--Default content for actionContent-->
              <div class="team14-fragment25">
                <span class="team14-text85">Open positions</span>
              </div>
            </slot>
          </span>
        </button>
        <div class="team14-content10">
          <h2 class="thq-heading-2">
            <slot name="heading1">
              <!--Default content for heading1-->
              <div class="team14-fragment20">
                <span class="team14-text80">Meet Our Team</span>
              </div>
            </slot>
          </h2>
          <p class="thq-body-large team14-text13">
            <slot name="content2">
              <!--Default content for content2-->
              <div class="team14-fragment13">
                <span class="team14-text71">
                  <span>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    <span v-html="rawlz17"></span>
                  </span>
                  <span><span v-html="raw9w07"></span></span>
                </span>
              </div>
            </slot>
          </p>
        </div>
      </div>
      <div
        data-thq="slider"
        data-loop="true"
        data-autoplay="true"
        data-navigation="true"
        data-pagination="true"
        class="team14-slider1 swiper"
      >
        <div data-thq="slider-wrapper" class="swiper-wrapper">
          <div data-thq="slider-slide" class="team14-slider-slide10 swiper-slide">
            <div class="team14-card10">
              <img
                :alt="member1Alt"
                :src="member1Src"
                class="thq-img-ratio-1-1"
              />
              <div class="team14-content11">
                <div class="team14-title10">
                  <span class="team14-text14 thq-body-small">
                    <slot name="member1">
                      <!--Default content for member1-->
                      <div><span>John Doe</span></div>
                    </slot>
                  </span>
                  <span class="team14-text15 thq-body-small">
                    <slot name="member1Job">
                      <!--Default content for member1Job-->
                      <div><span>Lead Consultant</span></div>
                    </slot>
                  </span>
                </div>
                <span class="team14-text16 thq-body-small">
                  <slot name="member1Content">
                    <!--Default content for member1Content-->
                    <div>
                      <span>
                        John is a highly experienced consultant with a background
                        in special education and child development.
                      </span>
                    </div>
                  </slot>
                </span>
              </div>
              <div class="team14-social-icons10">
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
            <div class="team14-card11">
              <img
                :alt="member2Alt"
                :src="member2Src"
                class="thq-img-ratio-1-1"
              />
              <div class="team14-content12">
                <div class="team14-title11">
                  <span class="team14-text17 thq-body-small">
                    <slot name="member2">
                      <!--Default content for member2-->
                      <div class="team14-fragment31">
                        <span class="team14-text91">Jane Smith</span>
                      </div>
                    </slot>
                  </span>
                  <span class="team14-text18 thq-body-small">
                    <slot name="member2Job">
                      <!--Default content for member2Job-->
                      <div><span>Family Support Specialist</span></div>
                    </slot>
                  </span>
                </div>
                <span class="team14-text19 thq-body-small">
                  <slot name="member2Content">
                    <!--Default content for member2Content-->
                    <div>
                      <span>
                        Jane specializes in providing support to families of
                        disabled children, offering guidance and resources.
                      </span>
                    </div>
                  </slot>
                </span>
              </div>
              <div class="team14-social-icons11">
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
            <div class="team14-card12">
              <img
                :alt="member3Alt"
                :src="member3Src"
                class="thq-img-ratio-1-1"
              />
              <div class="team14-content13">
                <div class="team14-title12">
                  <span class="team14-text20 thq-body-small">
                    <slot name="member3">
                      <!--Default content for member3-->
                      <div><span>David Johnson</span></div>
                    </slot>
                  </span>
                  <span class="team14-text21 thq-body-small">
                    <slot name="member3Job">
                      <!--Default content for member3Job-->
                      <div><span>Behavioral Therapist</span></div>
                    </slot>
                  </span>
                </div>
                <span class="team14-text22 thq-body-small">
                  <slot name="member3Content">
                    <!--Default content for member3Content-->
                    <div>
                      <span>
                        David focuses on behavioral interventions and strategies
                        to help children with disabilities thrive.
                      </span>
                    </div>
                  </slot>
                </span>
              </div>
              <div class="team14-social-icons12">
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
            <div class="team14-card13">
              <img
                :alt="member4Alt"
                :src="member4Src"
                class="thq-img-ratio-1-1"
              />
              <div class="team14-content14">
                <div class="team14-title13">
                  <span class="team14-text23 thq-body-small">
                    <slot name="member4">
                      <!--Default content for member4-->
                      <div><span>Sarah Brown</span></div>
                    </slot>
                  </span>
                  <span class="team14-text24 thq-body-small">
                    <slot name="member4Job">
                      <!--Default content for member4Job-->
                      <div><span>Speech Therapist</span></div>
                    </slot>
                  </span>
                </div>
                <span class="team14-text25 thq-body-small">
                  <slot name="member4Content">
                    <!--Default content for member4Content-->
                    <div>
                      <span>
                        Sarah is a speech therapist who works with children to
                        improve their communication skills.
                      </span>
                    </div>
                  </slot>
                </span>
              </div>
              <div class="team14-social-icons13">
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
          <div data-thq="slider-slide" class="team14-slider-slide11 swiper-slide">
            <div class="team14-card14">
              <img
                :alt="member5Alt"
                :src="member5Src"
                class="thq-img-ratio-1-1"
              />
              <div class="team14-content15">
                <div class="team14-title14">
                  <span class="team14-text26 thq-body-small">Full name</span>
                  <span class="team14-text27 thq-body-small">
                    <span>Job title</span>
                    <slot name="member5Job">
                      <!--Default content for member5Job-->
                      <div><span>Occupational Therapist</span></div>
                    </slot>
                  </span>
                </div>
                <span class="team14-text29 thq-body-small">
                  <span>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Suspendisse varius enim in eros elementum tristique.
                  </span>
                  <slot name="member5Content">
                    <!--Default content for member5Content-->
                    <div>
                      <span>
                        Michael specializes in occupational therapy techniques to
                        support children in their daily activities.
                      </span>
                    </div>
                  </slot>
                </span>
              </div>
              <div class="team14-social-icons14">
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
            <div class="team14-card15">
              <img
                :alt="member6Alt"
                :src="member6Src"
                class="thq-img-ratio-1-1"
              />
              <div class="team14-content16">
                <div class="team14-title15">
                  <span class="team14-text31 thq-body-small">
                    <span>Full name</span>
                    <slot name="member6">
                      <!--Default content for member6-->
                      <div><span>Emily Wilson</span></div>
                    </slot>
                  </span>
                  <span class="team14-text33 thq-body-small">Job title</span>
                </div>
                <span class="team14-text34 thq-body-small">
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                  Suspendisse varius enim in eros elementum tristique.
                </span>
              </div>
              <div class="team14-social-icons15">
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
            <div class="team14-card16">
              <img
                :alt="member7Alt"
                :src="member7Src"
                class="thq-img-ratio-1-1"
              />
              <div class="team14-content17">
                <div class="team14-title16">
                  <span class="team14-text35 thq-body-small">
                    <span>Full name</span>
                    <slot name="member7">
                      <!--Default content for member7-->
                      <div><span>Alexandra Garcia</span></div>
                    </slot>
                  </span>
                  <span class="team14-text37 thq-body-small">Job title</span>
                </div>
                <span class="team14-text38 thq-body-small">
                  <span>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Suspendisse varius enim in eros elementum tristique.
                  </span>
                  <slot name="member7Content">
                    <!--Default content for member7Content-->
                    <div>
                      <span>
                        Alexandra provides nutritional guidance and support to
                        ensure children with disabilities have a balanced diet.
                      </span>
                    </div>
                  </slot>
                </span>
              </div>
              <div class="team14-social-icons16">
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
            <div class="team14-card17">
              <img
                :alt="member8Alt"
                :src="member8Src"
                class="thq-img-ratio-1-1"
              />
              <div class="team14-content18">
                <div class="team14-title17">
                  <span class="team14-text40 thq-body-small">
                    <slot name="member8">
                      <!--Default content for member8-->
                      <div><span>Daniel Martinez</span></div>
                    </slot>
                  </span>
                  <span class="team14-text41 thq-body-small">Job title</span>
                </div>
                <span class="team14-text42 thq-body-small">
                  <slot name="member8Content">
                    <!--Default content for member8Content-->
                    <div>
                      <span>
                        Daniel specializes in educational assessments and
                        interventions to support the learning needs of disabled
                        children.
                      </span>
                    </div>
                  </slot>
                </span>
              </div>
              <div class="team14-social-icons17">
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
          class="team14-slider-pagination1 swiper-pagination swiper-pagination-bullets swiper-pagination-horizontal"
        >
          <div
            data-thq="slider-pagination-bullet"
            class="swiper-pagination-bullet swiper-pagination-bullet-active"
          ></div>
          <div
            data-thq="slider-pagination-bullet"
            class="swiper-pagination-bullet"
          ></div>
        </div>
        <div data-thq="slider-button-prev" class="swiper-button-prev"></div>
        <div data-thq="slider-button-next" class="swiper-button-next"></div>
      </div>
      <div
        data-thq="slider"
        data-navigation="true"
        data-pagination="true"
        class="team14-slider2 swiper"
      >
        <div data-thq="slider-wrapper" class="swiper-wrapper">
          <div data-thq="slider-slide" class="team14-slider-slide12 swiper-slide">
            <div class="team14-card18">
              <img
                :alt="member1Alt"
                :src="member1Src"
                class="thq-img-ratio-1-1"
              />
              <div class="team14-content19">
                <div class="team14-title18">
                  <span class="team14-text43 thq-body-small">
                    <span>Full name</span>
                    <slot name="member1">
                      <!--Default content for member1-->
                      <div class="team14-fragment27">
                        <span class="team14-text87">John Doe</span>
                      </div>
                    </slot>
                  </span>
                  <span class="team14-text45 thq-body-small">
                    <slot name="member1Job">
                      <!--Default content for member1Job-->
                      <div class="team14-fragment16">
                        <span class="team14-text76">Lead Consultant</span>
                      </div>
                    </slot>
                  </span>
                </div>
                <span class="team14-text46 thq-body-small">
                  <slot name="member1Content">
                    <!--Default content for member1Content-->
                    <div class="team14-fragment17">
                      <span class="team14-text77">
                        John is a highly experienced consultant with a background
                        in special education and child development.
                      </span>
                    </div>
                  </slot>
                </span>
              </div>
              <div class="team14-social-icons18">
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
          <div data-thq="slider-slide" class="team14-slider-slide13 swiper-slide">
            <div class="team14-card19">
              <img
                :alt="member2Alt"
                :src="member2Src"
                class="thq-img-ratio-1-1"
              />
              <div class="team14-content20">
                <div class="team14-title19">
                  <span class="team14-text47 thq-body-small">Full name</span>
                  <span class="team14-text48 thq-body-small">
                    <slot name="member2Job">
                      <!--Default content for member2Job-->
                      <div class="team14-fragment19">
                        <span class="team14-text79">
                          Family Support Specialist
                        </span>
                      </div>
                    </slot>
                  </span>
                </div>
                <span class="team14-text49 thq-body-small">
                  <slot name="member2Content">
                    <!--Default content for member2Content-->
                    <div class="team14-fragment21">
                      <span class="team14-text81">
                        Jane specializes in providing support to families of
                        disabled children, offering guidance and resources.
                      </span>
                    </div>
                  </slot>
                </span>
              </div>
              <div class="team14-social-icons19">
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
          <div data-thq="slider-slide" class="team14-slider-slide14 swiper-slide">
            <div class="team14-card20">
              <img
                :alt="member3Alt"
                :src="member3Src"
                class="thq-img-ratio-1-1"
              />
              <div class="team14-content21">
                <div class="team14-title20">
                  <span class="team14-text50 thq-body-small">
                    <slot name="member3">
                      <!--Default content for member3-->
                      <div class="team14-fragment11">
                        <span class="team14-text69">David Johnson</span>
                      </div>
                    </slot>
                  </span>
                  <span class="team14-text51 thq-body-small">
                    <slot name="member3Job">
                      <!--Default content for member3Job-->
                      <div class="team14-fragment14">
                        <span class="team14-text74">Behavioral Therapist</span>
                      </div>
                    </slot>
                  </span>
                </div>
                <span class="team14-text52 thq-body-small">
                  <slot name="member3Content">
                    <!--Default content for member3Content-->
                    <div class="team14-fragment15">
                      <span class="team14-text75">
                        David focuses on behavioral interventions and strategies
                        to help children with disabilities thrive.
                      </span>
                    </div>
                  </slot>
                </span>
              </div>
              <div class="team14-social-icons20">
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
          <div data-thq="slider-slide" class="team14-slider-slide15 swiper-slide">
            <div class="team14-card21">
              <img
                :alt="member4Alt"
                :src="member4Src"
                class="thq-img-ratio-1-1"
              />
              <div class="team14-content22">
                <div class="team14-title21">
                  <span class="team14-text53 thq-body-small">
                    <slot name="member4">
                      <!--Default content for member4-->
                      <div class="team14-fragment28">
                        <span class="team14-text88">Sarah Brown</span>
                      </div>
                    </slot>
                  </span>
                  <span class="team14-text54 thq-body-small">
                    <slot name="member4Job">
                      <!--Default content for member4Job-->
                      <div class="team14-fragment29">
                        <span class="team14-text89">Speech Therapist</span>
                      </div>
                    </slot>
                  </span>
                </div>
                <span class="team14-text55 thq-body-small">
                  <slot name="member4Content">
                    <!--Default content for member4Content-->
                    <div class="team14-fragment33">
                      <span class="team14-text93">
                        Sarah is a speech therapist who works with children to
                        improve their communication skills.
                      </span>
                    </div>
                  </slot>
                </span>
              </div>
              <div class="team14-social-icons21">
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
          <div data-thq="slider-slide" class="team14-slider-slide16 swiper-slide">
            <div class="team14-card22">
              <img
                :alt="member5Alt"
                :src="member5Src"
                class="thq-img-ratio-1-1"
              />
              <div class="team14-content23">
                <div class="team14-title22">
                  <span class="team14-text56 thq-body-small">
                    <slot name="member5">
                      <!--Default content for member5-->
                      <div class="team14-fragment37">
                        <span class="team14-text97">Michael Lee</span>
                      </div>
                    </slot>
                  </span>
                  <span class="team14-text57 thq-body-small">
                    <slot name="member5Job">
                      <!--Default content for member5Job-->
                      <div class="team14-fragment22">
                        <span class="team14-text82">Occupational Therapist</span>
                      </div>
                    </slot>
                  </span>
                </div>
                <span class="team14-text58 thq-body-small">
                  <slot name="member5Content">
                    <!--Default content for member5Content-->
                    <div class="team14-fragment18">
                      <span class="team14-text78">
                        Michael specializes in occupational therapy techniques to
                        support children in their daily activities.
                      </span>
                    </div>
                  </slot>
                </span>
              </div>
              <div class="team14-social-icons22">
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
          <div data-thq="slider-slide" class="team14-slider-slide17 swiper-slide">
            <div class="team14-card23">
              <img
                :alt="member6Alt"
                :src="member6Src"
                class="thq-img-ratio-1-1"
              />
              <div class="team14-content24">
                <div class="team14-title23">
                  <span class="team14-text59 thq-body-small">
                    <slot name="member6">
                      <!--Default content for member6-->
                      <div class="team14-fragment32">
                        <span class="team14-text92">Emily Wilson</span>
                      </div>
                    </slot>
                  </span>
                  <span class="team14-text60 thq-body-small">
                    <slot name="member6Job">
                      <!--Default content for member6Job-->
                      <div class="team14-fragment12">
                        <span class="team14-text70">Physical Therapist</span>
                      </div>
                    </slot>
                  </span>
                </div>
                <span class="team14-text61 thq-body-small">
                  <slot name="member6Content">
                    <!--Default content for member6Content-->
                    <div class="team14-fragment34">
                      <span class="team14-text94">
                        Emily helps children improve their physical abilities and
                        motor skills through therapy sessions.
                      </span>
                    </div>
                  </slot>
                </span>
              </div>
              <div class="team14-social-icons23">
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
          <div data-thq="slider-slide" class="team14-slider-slide18 swiper-slide">
            <div class="team14-card24">
              <img
                :alt="member7Alt"
                :src="member7Src"
                class="thq-img-ratio-1-1"
              />
              <div class="team14-content25">
                <div class="team14-title24">
                  <span class="team14-text62 thq-body-small">
                    <slot name="member7">
                      <!--Default content for member7-->
                      <div class="team14-fragment23">
                        <span class="team14-text83">Alexandra Garcia</span>
                      </div>
                    </slot>
                  </span>
                  <span class="team14-text63 thq-body-small">Job title</span>
                </div>
                <span class="team14-text64 thq-body-small">
                  <slot name="member7Content">
                    <!--Default content for member7Content-->
                    <div class="team14-fragment10">
                      <span class="team14-text68">
                        Alexandra provides nutritional guidance and support to
                        ensure children with disabilities have a balanced diet.
                      </span>
                    </div>
                  </slot>
                </span>
              </div>
              <div class="team14-social-icons24">
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
          <div data-thq="slider-slide" class="team14-slider-slide19 swiper-slide">
            <div class="team14-card25">
              <img
                :alt="member8Alt"
                :src="member8Src"
                class="thq-img-ratio-1-1"
              />
              <div class="team14-content26">
                <div class="team14-title25">
                  <span class="team14-text65 thq-body-small">
                    <slot name="member8">
                      <!--Default content for member8-->
                      <div class="team14-fragment36">
                        <span class="team14-text96">Daniel Martinez</span>
                      </div>
                    </slot>
                  </span>
                  <span class="team14-text66 thq-body-small">
                    <slot name="member8Job">
                      <!--Default content for member8Job-->
                      <div class="team14-fragment24">
                        <span class="team14-text84">
                          Educational Psychologist
                        </span>
                      </div>
                    </slot>
                  </span>
                </div>
                <span class="team14-text67 thq-body-small">
                  <slot name="member8Content">
                    <!--Default content for member8Content-->
                    <div class="team14-fragment35">
                      <span class="team14-text95">
                        Daniel specializes in educational assessments and
                        interventions to support the learning needs of disabled
                        children.
                      </span>
                    </div>
                  </slot>
                </span>
              </div>
              <div class="team14-social-icons25">
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
          class="team14-slider-pagination2 swiper-pagination swiper-pagination-bullets swiper-pagination-horizontal"
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
  name: 'Team14',
  props: {
    member5Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1712685884811-5f1cf73e3d32?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNDQwMDE2N3w&ixlib=rb-4.0.3&q=80&w=1080',
    },
    member2Alt: {
      type: String,
      default: 'Image of Jane Smith',
    },
    member1Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1501196354995-cbb51c65aaea?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNDQwMDE2N3w&ixlib=rb-4.0.3&q=80&w=1080',
    },
    member4Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1460794418188-1bb7dba2720d?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNDQwMDE2OHw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    member7Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1691233123155-27bf011dc33f?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNDQwMDE2OHw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    member6Alt: {
      type: String,
      default: 'Image of Emily Wilson',
    },
    member2Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1479767574301-a01c78234a0c?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNDQwMDE2N3w&ixlib=rb-4.0.3&q=80&w=1080',
    },
    member3Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1508185140592-283327020902?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNDQwMDE2OHw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    member1Alt: {
      type: String,
      default: 'Image of John Doe',
    },
    member8Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1580489944761-15a19d654956?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNDQwMDE2N3w&ixlib=rb-4.0.3&q=80&w=1080',
    },
    member6Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1518739005966-3a39d6d87103?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNDQwMDE2N3w&ixlib=rb-4.0.3&q=80&w=1080',
    },
    member5Alt: {
      type: String,
      default: 'Image of Michael Lee',
    },
    member8Alt: {
      type: String,
      default: 'Image of Daniel Martinez',
    },
    member3Alt: {
      type: String,
      default: 'Image of David Johnson',
    },
    member4Alt: {
      type: String,
      default: 'Image of Sarah Brown',
    },
    member7Alt: {
      type: String,
      default: 'Image of Alexandra Garcia',
    },
  },
  data() {
    return {
      raw41v8: ' ',
      rawlhbx: ' ',
      rawlz17: ' ',
      raw9w07: ' ',
    }
  },
}
</script>

<style scoped>
.team14-max-width {
  gap: var(--dl-space-space-twounits);
  height: auto;
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team14-section-title {
  gap: var(--dl-space-space-unit);
  width: 100%;
  display: flex;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
}
 
.team14-button {
  width: 100%;
  max-width: 300px;
}
 
.team14-content10 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team14-slider1 {
  width: 100%;
  height: auto;
  display: inline-block;
  position: relative;
  align-self: center;
}
 
.team14-slider-slide10 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  padding-bottom: var(--dl-space-space-threeunits);
}
 
.team14-card10 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team14-content11 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team14-title10 {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team14-text14 {
  font-style: normal;
  font-weight: 600;
}
 
.team14-text15 {
  text-align: center;
}
 
.team14-text16 {
  overflow: auto;
  max-height: var(--dl-size-size-medium);
  text-align: center;
}
 
.team14-social-icons10 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
 
.team14-card11 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team14-content12 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team14-title11 {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team14-text17 {
  font-style: normal;
  font-weight: 600;
}
 
.team14-text18 {
  text-align: center;
}
 
.team14-text19 {
  overflow: auto;
  max-height: var(--dl-size-size-large);
  text-align: left;
}
 
.team14-social-icons11 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
 
.team14-card12 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team14-content13 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team14-title12 {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team14-text20 {
  font-style: normal;
  font-weight: 600;
}
 
.team14-text21 {
  text-align: center;
}
 
.team14-text22 {
  overflow: auto;
  max-height: var(--dl-size-size-large);
  text-align: left;
}
 
.team14-social-icons12 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
 
.team14-card13 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team14-content14 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team14-title13 {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team14-text23 {
  font-style: normal;
  font-weight: 600;
}
 
.team14-text24 {
  text-align: center;
}
 
.team14-text25 {
  overflow: auto;
  max-height: var(--dl-size-size-large);
  text-align: left;
}
 
.team14-social-icons13 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
 
.team14-slider-slide11 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  padding-bottom: var(--dl-space-space-threeunits);
}
 
.team14-card14 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team14-content15 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team14-title14 {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team14-text26 {
  font-style: normal;
  font-weight: 600;
}
 
.team14-text27 {
  text-align: center;
}
 
.team14-text29 {
  overflow: hidden;
  max-height: var(--dl-size-size-medium);
  text-align: center;
}
 
.team14-social-icons14 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
 
.team14-card15 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team14-content16 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team14-title15 {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team14-text31 {
  font-style: normal;
  font-weight: 600;
}
 
.team14-text33 {
  text-align: center;
}
 
.team14-text34 {
  overflow: auto;
  max-height: var(--dl-size-size-medium);
  text-align: center;
}
 
.team14-social-icons15 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
 
.team14-card16 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team14-content17 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team14-title16 {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team14-text35 {
  font-style: normal;
  font-weight: 600;
}
 
.team14-text37 {
  text-align: center;
}
 
.team14-text38 {
  overflow: auto;
  max-height: var(--dl-size-size-medium);
  text-align: center;
}
 
.team14-social-icons16 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
 
.team14-card17 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team14-content18 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team14-title17 {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team14-text40 {
  font-style: normal;
  font-weight: 600;
}
 
.team14-text41 {
  text-align: center;
}
 
.team14-text42 {
  overflow: auto;
  max-height: var(--dl-size-size-medium);
  text-align: center;
}
 
.team14-social-icons17 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
 
.team14-slider-pagination1 {
  display: block;
}
 
.team14-slider2 {
  width: 100%;
  height: auto;
  display: none;
  position: relative;
}
 
.team14-slider-slide12 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  padding-bottom: var(--dl-space-space-threeunits);
}
 
.team14-card18 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team14-content19 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team14-title18 {
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team14-text43 {
  font-style: normal;
  font-weight: 600;
}
 
.team14-text45 {
  text-align: center;
}
 
.team14-text46 {
  overflow: auto;
  max-height: var(--dl-size-size-medium);
  text-align: center;
}
 
.team14-social-icons18 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
 
.team14-slider-slide13 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  padding-bottom: var(--dl-space-space-threeunits);
}
 
.team14-card19 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team14-content20 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team14-title19 {
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team14-text47 {
  font-style: normal;
  font-weight: 600;
}
 
.team14-text48 {
  text-align: center;
}
 
.team14-text49 {
  overflow: auto;
  max-height: var(--dl-size-size-large);
  text-align: left;
}
 
.team14-social-icons19 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
 
.team14-slider-slide14 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  padding-bottom: var(--dl-space-space-threeunits);
}
 
.team14-card20 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team14-content21 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team14-title20 {
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team14-text50 {
  font-style: normal;
  font-weight: 600;
}
 
.team14-text51 {
  text-align: center;
}
 
.team14-text52 {
  overflow: auto;
  max-height: var(--dl-size-size-large);
  text-align: left;
}
 
.team14-social-icons20 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
 
.team14-slider-slide15 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  padding-bottom: var(--dl-space-space-threeunits);
}
 
.team14-card21 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team14-content22 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team14-title21 {
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team14-text53 {
  font-style: normal;
  font-weight: 600;
}
 
.team14-text54 {
  text-align: center;
}
 
.team14-text55 {
  overflow: auto;
  max-height: var(--dl-size-size-large);
  text-align: left;
}
 
.team14-social-icons21 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
 
.team14-slider-slide16 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  padding-bottom: var(--dl-space-space-threeunits);
}
 
.team14-card22 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team14-content23 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team14-title22 {
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team14-text56 {
  font-style: normal;
  font-weight: 600;
}
 
.team14-text57 {
  text-align: center;
}
 
.team14-text58 {
  overflow: hidden;
  max-height: var(--dl-size-size-medium);
  text-align: center;
}
 
.team14-social-icons22 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
 
.team14-slider-slide17 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  padding-bottom: var(--dl-space-space-threeunits);
}
 
.team14-card23 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team14-content24 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team14-title23 {
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team14-text59 {
  font-style: normal;
  font-weight: 600;
}
 
.team14-text60 {
  text-align: center;
}
 
.team14-text61 {
  overflow: auto;
  max-height: var(--dl-size-size-medium);
  text-align: center;
}
 
.team14-social-icons23 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
 
.team14-slider-slide18 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  padding-bottom: var(--dl-space-space-threeunits);
}
 
.team14-card24 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team14-content25 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team14-title24 {
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team14-text62 {
  font-style: normal;
  font-weight: 600;
}
 
.team14-text63 {
  text-align: center;
}
 
.team14-text64 {
  overflow: auto;
  max-height: var(--dl-size-size-medium);
  text-align: center;
}
 
.team14-social-icons24 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
 
.team14-slider-slide19 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  padding-bottom: var(--dl-space-space-threeunits);
}
 
.team14-card25 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team14-content26 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team14-title25 {
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team14-text65 {
  font-style: normal;
  font-weight: 600;
}
 
.team14-text66 {
  text-align: center;
}
 
.team14-text67 {
  overflow: auto;
  max-height: var(--dl-size-size-medium);
  text-align: center;
}
 
.team14-social-icons25 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
 
.team14-slider-pagination2 {
  display: block;
}
 
.team14-fragment10 {
  display: contents;
}
 
.team14-text68 {
  display: inline-block;
}
 
.team14-fragment11 {
  display: contents;
}
 
.team14-text69 {
  display: inline-block;
}
 
.team14-fragment12 {
  display: contents;
}
 
.team14-text70 {
  display: inline-block;
}
 
.team14-fragment13 {
  display: contents;
}
 
.team14-text71 {
  display: inline-block;
}
 
.team14-fragment14 {
  display: contents;
}
 
.team14-text74 {
  display: inline-block;
}
 
.team14-fragment15 {
  display: contents;
}
 
.team14-text75 {
  display: inline-block;
}
 
.team14-fragment16 {
  display: contents;
}
 
.team14-text76 {
  display: inline-block;
}
 
.team14-fragment17 {
  display: contents;
}
 
.team14-text77 {
  display: inline-block;
}
 
.team14-fragment18 {
  display: contents;
}
 
.team14-text78 {
  display: inline-block;
}
 
.team14-fragment19 {
  display: contents;
}
 
.team14-text79 {
  display: inline-block;
}
 
.team14-fragment20 {
  display: contents;
}
 
.team14-text80 {
  display: inline-block;
}
 
.team14-fragment21 {
  display: contents;
}
 
.team14-text81 {
  display: inline-block;
}
 
.team14-fragment22 {
  display: contents;
}
 
.team14-text82 {
  display: inline-block;
}
 
.team14-fragment23 {
  display: contents;
}
 
.team14-text83 {
  display: inline-block;
}
 
.team14-fragment24 {
  display: contents;
}
 
.team14-text84 {
  display: inline-block;
}
 
.team14-fragment25 {
  display: contents;
}
 
.team14-text85 {
  display: inline-block;
}
 
.team14-fragment26 {
  display: contents;
}
 
.team14-text86 {
  display: inline-block;
}
 
.team14-fragment27 {
  display: contents;
}
 
.team14-text87 {
  display: inline-block;
}
 
.team14-fragment28 {
  display: contents;
}
 
.team14-text88 {
  display: inline-block;
}
 
.team14-fragment29 {
  display: contents;
}
 
.team14-text89 {
  display: inline-block;
}
 
.team14-fragment30 {
  display: contents;
}
 
.team14-text90 {
  display: inline-block;
}
 
.team14-fragment31 {
  display: contents;
}
 
.team14-text91 {
  display: inline-block;
}
 
.team14-fragment32 {
  display: contents;
}
 
.team14-text92 {
  display: inline-block;
}
 
.team14-fragment33 {
  display: contents;
}
 
.team14-text93 {
  display: inline-block;
}
 
.team14-fragment34 {
  display: contents;
}
 
.team14-text94 {
  display: inline-block;
}
 
.team14-fragment35 {
  display: contents;
}
 
.team14-text95 {
  display: inline-block;
}
 
.team14-fragment36 {
  display: contents;
}
 
.team14-text96 {
  display: inline-block;
}
 
.team14-fragment37 {
  display: contents;
}
 
.team14-text97 {
  display: inline-block;
}
 
@media(max-width: 767px) {
  .team14-max-width {
    padding: var(--dl-space-space-threeunits);
  }
  .team14-slider1 {
    display: none;
  }
  .team14-slider2 {
    display: block;
  }
}
 
@media(max-width: 479px) {
  .team14-max-width {
    padding: var(--dl-space-space-oneandhalfunits);
  }
  .team14-text10 {
    text-align: center;
  }
  .team14-button {
    width: 100%;
  }
  .team14-text13 {
    text-align: center;
  }
}
</style>
