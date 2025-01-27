<template>
  <div class="thq-section-padding team13-team8">
    <div class="team13-max-width thq-section-max-width">
      <div class="team13-section-title">
        <span class="thq-body-small team13-text10">
          <slot name="content1">
            <!--Default content for content1-->
            <div class="team13-fragment15">
              <span class="team13-text66">
                Join our team and make a difference in your career!
              </span>
            </div>
          </slot>
        </span>
        <button class="team13-button thq-button-filled">
          <span class="thq-body-small">
            <slot name="actionContent">
              <!--Default content for actionContent-->
              <div class="team13-fragment13">
                <span class="team13-text64">Open positions</span>
              </div>
            </slot>
          </span>
        </button>
        <div class="team13-content10">
          <h2 class="thq-heading-2">
            <slot name="heading1">
              <!--Default content for heading1-->
              <div class="team13-fragment21">
                <span class="team13-text72">Meet our team</span>
              </div>
            </slot>
          </h2>
          <p class="thq-body-large team13-text13">
            <slot name="content2">
              <!--Default content for content2-->
              <div class="team13-fragment26">
                <span class="team13-text77">
                  <span>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    <span v-html="rawzas0"></span>
                  </span>
                  <span><span v-html="rawd1zi"></span></span>
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
        class="team13-slider1 swiper"
      >
        <div data-thq="slider-wrapper" class="swiper-wrapper">
          <div data-thq="slider-slide" class="team13-slider-slide1 swiper-slide">
            <div class="team13-card10">
              <img
                :alt="member1Alt"
                :src="member1Src"
                class="thq-img-ratio-1-1"
              />
              <div class="team13-content11">
                <div class="team13-title10">
                  <span class="team13-text14 thq-body-small">
                    <slot name="member1">
                      <!--Default content for member1-->
                      <div><span>John Doe</span></div>
                    </slot>
                  </span>
                  <span class="team13-text15 thq-body-small">
                    <slot name="member1Job">
                      <!--Default content for member1Job-->
                      <div><span>Lead Consultant</span></div>
                    </slot>
                  </span>
                </div>
                <span class="team13-text16 thq-body-small">
                  <slot name="member1Content">
                    <!--Default content for member1Content-->
                    <div class="team13-fragment12">
                      <span class="team13-text63">
                        John is a highly experienced consultant with a background
                        in special education and child development. He is
                        dedicated to providing personalized support to help
                        children reach their full potential.
                      </span>
                    </div>
                  </slot>
                </span>
              </div>
              <div class="team13-social-icons10">
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
            <div class="team13-card11">
              <img
                :alt="member2Alt"
                :src="member2Src"
                class="thq-img-ratio-1-1"
              />
              <div class="team13-content12">
                <div class="team13-title11">
                  <span class="team13-text17 thq-body-small">
                    <slot name="member2">
                      <!--Default content for member2-->
                      <div class="team13-fragment25">
                        <span class="team13-text76">Jane Smith</span>
                      </div>
                    </slot>
                  </span>
                  <span class="team13-text18 thq-body-small">
                    <slot name="member2Job">
                      <!--Default content for member2Job-->
                      <div class="team13-fragment29">
                        <span class="team13-text82">
                          Family Support Specialist
                        </span>
                      </div>
                    </slot>
                  </span>
                </div>
                <span class="team13-text19 thq-body-small">
                  <slot name="member2Content">
                    <!--Default content for member2Content-->
                    <div>
                      <span>
                        Jane specializes in providing emotional and practical
                        support to families of disabled children. Her
                        compassionate approach helps families navigate challenges
                        and access necessary resources.
                      </span>
                    </div>
                  </slot>
                </span>
              </div>
              <div class="team13-social-icons11">
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
            <div class="team13-card12">
              <img
                :alt="member3Alt"
                :src="member3Src"
                class="thq-img-ratio-1-1"
              />
              <div class="team13-content13">
                <div class="team13-title12">
                  <span class="team13-text20 thq-body-small">
                    <slot name="member3">
                      <!--Default content for member3-->
                      <div><span>Michael Johnson</span></div>
                    </slot>
                  </span>
                  <span class="team13-text21 thq-body-small">
                    <slot name="member3Job">
                      <!--Default content for member3Job-->
                      <div><span>Behavioral Therapist</span></div>
                    </slot>
                  </span>
                </div>
                <span class="team13-text22 thq-body-small">
                  <slot name="member3Content">
                    <!--Default content for member3Content-->
                    <div>
                      <span>
                        Michael has expertise in behavioral therapy techniques
                        tailored for children with disabilities. He works closely
                        with families to develop effective strategies for managing
                        behavior.
                      </span>
                    </div>
                  </slot>
                </span>
              </div>
              <div class="team13-social-icons12">
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
          <div data-thq="slider-slide" class="team13-slider-slide2 swiper-slide">
            <div class="team13-card13">
              <img
                :alt="member4Alt"
                :src="member4Src"
                class="thq-img-ratio-1-1"
              />
              <div class="team13-content14">
                <div class="team13-title13">
                  <span class="team13-text23 thq-body-small">
                    <slot name="member4">
                      <!--Default content for member4-->
                      <div class="team13-fragment22">
                        <span class="team13-text73">Sarah Lee</span>
                      </div>
                    </slot>
                  </span>
                  <span class="team13-text24 thq-body-small">
                    <slot name="member4Job">
                      <!--Default content for member4Job-->
                      <div><span>Speech Therapist</span></div>
                    </slot>
                  </span>
                </div>
                <span class="team13-text25 thq-body-small">
                  <slot name="member4Content">
                    <!--Default content for member4Content-->
                    <div class="team13-fragment16">
                      <span class="team13-text67">
                        Sarah is a licensed speech therapist who specializes in
                        communication disorders in children. She provides
                        individualized therapy sessions to improve speech and
                        language skills.
                      </span>
                    </div>
                  </slot>
                </span>
              </div>
              <div class="team13-social-icons13">
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
            <div class="team13-card14">
              <img
                :alt="member5Alt"
                :src="member5Src"
                class="thq-img-ratio-1-1"
              />
              <div class="team13-content15">
                <div class="team13-title14">
                  <span class="team13-text26 thq-body-small">
                    <slot name="member5">
                      <!--Default content for member5-->
                      <div class="team13-fragment24">
                        <span class="team13-text75">David Brown</span>
                      </div>
                    </slot>
                  </span>
                  <span class="team13-text27 thq-body-small">
                    <slot name="member5Job">
                      <!--Default content for member5Job-->
                      <div class="team13-fragment10">
                        <span class="team13-text61">Educational Specialist</span>
                      </div>
                    </slot>
                  </span>
                </div>
                <span class="team13-text28 thq-body-small">
                  <slot name="member5Content">
                    <!--Default content for member5Content-->
                    <div>
                      <span>
                        David has a background in special education and curriculum
                        development. He supports children with disabilities in
                        academic settings, ensuring they receive appropriate
                        educational support.
                      </span>
                    </div>
                  </slot>
                </span>
              </div>
              <div class="team13-social-icons14">
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
            <div class="team13-card15">
              <img
                :alt="member6Alt"
                :src="member6Src"
                class="thq-img-ratio-1-1"
              />
              <div class="team13-content16">
                <div class="team13-title15">
                  <span class="team13-text29 thq-body-small">
                    <slot name="member6">
                      <!--Default content for member6-->
                      <div><span>Emily Wilson</span></div>
                    </slot>
                  </span>
                  <span class="team13-text30 thq-body-small">
                    <slot name="member6Job">
                      <!--Default content for member6Job-->
                      <div><span>Occupational Therapist</span></div>
                    </slot>
                  </span>
                </div>
                <span class="team13-text31 thq-body-small">
                  <slot name="member6Content">
                    <!--Default content for member6Content-->
                    <div>
                      <span>
                        Emily is an occupational therapist specializing in sensory
                        integration and fine motor skills development. She works
                        with children to improve their independence and daily
                        living skills.
                      </span>
                    </div>
                  </slot>
                </span>
              </div>
              <div class="team13-social-icons15">
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
          class="team13-slider-pagination1 swiper-pagination swiper-pagination-bullets swiper-pagination-horizontal"
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
        class="team13-slider2 swiper"
      >
        <div data-thq="slider-wrapper" class="swiper-wrapper">
          <div data-thq="slider-slide" class="team13-slider-slide3 swiper-slide">
            <div class="team13-card16">
              <img
                :alt="member1Alt"
                :src="member1Src"
                class="thq-img-ratio-1-1"
              />
              <div class="team13-content17">
                <div class="team13-title16">
                  <span class="team13-text32 thq-body-small">
                    <span>Full name</span>
                    <slot name="member1">
                      <!--Default content for member1-->
                      <div class="team13-fragment27">
                        <span class="team13-text80">John Doe</span>
                      </div>
                    </slot>
                  </span>
                  <span class="team13-text34 thq-body-small">
                    <span>Job title</span>
                    <slot name="member1Job">
                      <!--Default content for member1Job-->
                      <div class="team13-fragment11">
                        <span class="team13-text62">Lead Consultant</span>
                      </div>
                    </slot>
                  </span>
                </div>
                <span class="team13-text36 thq-body-small">
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                  Suspendisse varius enim in eros elementum tristique.
                </span>
              </div>
              <div class="team13-social-icons16">
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
          <div data-thq="slider-slide" class="team13-slider-slide4 swiper-slide">
            <div class="team13-card17">
              <img
                :alt="member2Alt"
                :src="member2Src"
                class="thq-img-ratio-1-1"
              />
              <div class="team13-content18">
                <div class="team13-title17">
                  <span class="team13-text37 thq-body-small">Full name</span>
                  <span class="team13-text38 thq-body-small">Job title</span>
                </div>
                <span class="team13-text39 thq-body-small">
                  <span>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Suspendisse varius enim in eros elementum tristique.
                  </span>
                  <slot name="member2Content">
                    <!--Default content for member2Content-->
                    <div class="team13-fragment28">
                      <span class="team13-text81">
                        Jane specializes in providing emotional and practical
                        support to families of disabled children. Her
                        compassionate approach helps families navigate challenges
                        and access necessary resources.
                      </span>
                    </div>
                  </slot>
                </span>
              </div>
              <div class="team13-social-icons17">
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
          <div data-thq="slider-slide" class="team13-slider-slide5 swiper-slide">
            <div class="team13-card18">
              <img
                :alt="member3Alt"
                :src="member3Src"
                class="thq-img-ratio-1-1"
              />
              <div class="team13-content19">
                <div class="team13-title18">
                  <span class="team13-text41 thq-body-small">
                    <span>Full name</span>
                    <slot name="member3">
                      <!--Default content for member3-->
                      <div class="team13-fragment14">
                        <span class="team13-text65">Michael Johnson</span>
                      </div>
                    </slot>
                  </span>
                  <span class="team13-text43 thq-body-small">
                    <span>Job title</span>
                    <slot name="member3Job">
                      <!--Default content for member3Job-->
                      <div class="team13-fragment31">
                        <span class="team13-text84">Behavioral Therapist</span>
                      </div>
                    </slot>
                  </span>
                </div>
                <span class="team13-text45 thq-body-small">
                  <span>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Suspendisse varius enim in eros elementum tristique.
                  </span>
                  <slot name="member3Content">
                    <!--Default content for member3Content-->
                    <div class="team13-fragment19">
                      <span class="team13-text70">
                        Michael has expertise in behavioral therapy techniques
                        tailored for children with disabilities. He works closely
                        with families to develop effective strategies for managing
                        behavior.
                      </span>
                    </div>
                  </slot>
                </span>
              </div>
              <div class="team13-social-icons18">
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
          <div data-thq="slider-slide" class="team13-slider-slide6 swiper-slide">
            <div class="team13-card19">
              <img
                :alt="member4Alt"
                :src="member4Src"
                class="thq-img-ratio-1-1"
              />
              <div class="team13-content20">
                <div class="team13-title19">
                  <span class="team13-text47 thq-body-small">Full name</span>
                  <span class="team13-text48 thq-body-small">
                    <span>Job title</span>
                    <slot name="member4Job">
                      <!--Default content for member4Job-->
                      <div class="team13-fragment20">
                        <span class="team13-text71">Speech Therapist</span>
                      </div>
                    </slot>
                  </span>
                </div>
                <span class="team13-text50 thq-body-small">
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                  Suspendisse varius enim in eros elementum tristique.
                </span>
              </div>
              <div class="team13-social-icons19">
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
          <div data-thq="slider-slide" class="team13-slider-slide7 swiper-slide">
            <div class="team13-card20">
              <img
                :alt="member5Alt"
                :src="member5Src"
                class="thq-img-ratio-1-1"
              />
              <div class="team13-content21">
                <div class="team13-title20">
                  <span class="team13-text51 thq-body-small">Full name</span>
                  <span class="team13-text52 thq-body-small">Job title</span>
                </div>
                <span class="team13-text53 thq-body-small">
                  <span>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Suspendisse varius enim in eros elementum tristique.
                  </span>
                  <slot name="member5Content">
                    <!--Default content for member5Content-->
                    <div class="team13-fragment30">
                      <span class="team13-text83">
                        David has a background in special education and curriculum
                        development. He supports children with disabilities in
                        academic settings, ensuring they receive appropriate
                        educational support.
                      </span>
                    </div>
                  </slot>
                </span>
              </div>
              <div class="team13-social-icons20">
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
          <div data-thq="slider-slide" class="team13-slider-slide8 swiper-slide">
            <div class="team13-card21">
              <img
                :alt="member6Alt"
                :src="member6Src"
                class="thq-img-ratio-1-1"
              />
              <div class="team13-content22">
                <div class="team13-title21">
                  <span class="team13-text55 thq-body-small">
                    <span>Full name</span>
                    <slot name="member6">
                      <!--Default content for member6-->
                      <div class="team13-fragment23">
                        <span class="team13-text74">Emily Wilson</span>
                      </div>
                    </slot>
                  </span>
                  <span class="team13-text57 thq-body-small">
                    <span>Job title</span>
                    <slot name="member6Job">
                      <!--Default content for member6Job-->
                      <div class="team13-fragment18">
                        <span class="team13-text69">Occupational Therapist</span>
                      </div>
                    </slot>
                  </span>
                </div>
                <span class="team13-text59 thq-body-small">
                  <span>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Suspendisse varius enim in eros elementum tristique.
                  </span>
                  <slot name="member6Content">
                    <!--Default content for member6Content-->
                    <div class="team13-fragment17">
                      <span class="team13-text68">
                        Emily is an occupational therapist specializing in sensory
                        integration and fine motor skills development. She works
                        with children to improve their independence and daily
                        living skills.
                      </span>
                    </div>
                  </slot>
                </span>
              </div>
              <div class="team13-social-icons21">
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
          class="team13-slider-pagination2 swiper-pagination swiper-pagination-bullets swiper-pagination-horizontal"
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
  name: 'Team13',
  props: {
    member2Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1702482527875-e16d07f0d91b?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNDQwMDE3Mnw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    member1Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1502768040783-423da5fd5fa0?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNDQwMDE3MXw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    member6Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1413847394921-b259543f4872?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNDQwMDE3MXw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    member4Alt: {
      type: String,
      default: 'Image of Sarah Lee',
    },
    member5Alt: {
      type: String,
      default: 'Image of David Brown',
    },
    member5Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1527203561188-dae1bc1a417f?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNDQwMDE3M3w&ixlib=rb-4.0.3&q=80&w=1080',
    },
    member4Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1519058082700-08a0b56da9b4?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNDQwMDE3MXw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    member3Alt: {
      type: String,
      default: 'Image of Michael Johnson',
    },
    member6Alt: {
      type: String,
      default: 'Image of Emily Wilson',
    },
    member3Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1532074205216-d0e1f4b87368?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNDQwMDE3MXw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    member2Alt: {
      type: String,
      default: 'Image of Jane Smith',
    },
    member1Alt: {
      type: String,
      default: 'Image of John Doe',
    },
  },
  data() {
    return {
      raw3ibq: ' ',
      rawpcbo: ' ',
      rawzas0: ' ',
      rawd1zi: ' ',
    }
  },
}
</script>

<style scoped>
.team13-max-width {
  gap: var(--dl-space-space-twounits);
  height: auto;
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team13-section-title {
  gap: var(--dl-space-space-unit);
  width: 100%;
  display: flex;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
}
 
.team13-button {
  width: 100%;
  max-width: 300px;
}
 
.team13-content10 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team13-slider1 {
  width: 100%;
  height: auto;
  display: inline-block;
  position: relative;
}
 
.team13-slider-slide1 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  padding-bottom: var(--dl-space-space-threeunits);
}
 
.team13-card10 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team13-content11 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team13-title10 {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team13-text14 {
  font-style: normal;
  font-weight: 600;
}
 
.team13-text15 {
  text-align: center;
}
 
.team13-text16 {
  overflow: auto;
  max-height: var(--dl-size-size-medium);
  text-align: left;
}
 
.team13-social-icons10 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
 
.team13-card11 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team13-content12 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team13-title11 {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team13-text17 {
  font-style: normal;
  font-weight: 600;
}
 
.team13-text18 {
  text-align: center;
}
 
.team13-text19 {
  overflow: auto;
  max-height: var(--dl-size-size-medium);
  text-align: left;
}
 
.team13-social-icons11 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
 
.team13-card12 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team13-content13 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team13-title12 {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team13-text20 {
  font-style: normal;
  font-weight: 600;
}
 
.team13-text21 {
  text-align: center;
}
 
.team13-text22 {
  overflow: auto;
  max-height: var(--dl-size-size-medium);
  text-align: left;
}
 
.team13-social-icons12 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
 
.team13-slider-slide2 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  padding-bottom: var(--dl-space-space-threeunits);
}
 
.team13-card13 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team13-content14 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team13-title13 {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team13-text23 {
  font-style: normal;
  font-weight: 600;
}
 
.team13-text24 {
  text-align: center;
}
 
.team13-text25 {
  overflow: auto;
  max-height: var(--dl-size-size-medium);
  text-align: center;
}
 
.team13-social-icons13 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
 
.team13-card14 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team13-content15 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team13-title14 {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team13-text26 {
  font-style: normal;
  font-weight: 600;
}
 
.team13-text27 {
  text-align: center;
}
 
.team13-text28 {
  overflow: auto;
  max-height: var(--dl-size-size-medium);
  text-align: left;
}
 
.team13-social-icons14 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
 
.team13-card15 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team13-content16 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team13-title15 {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.team13-text29 {
  font-style: normal;
  font-weight: 600;
}
 
.team13-text30 {
  text-align: center;
}
 
.team13-text31 {
  overflow: auto;
  max-height: var(--dl-size-size-medium);
  text-align: center;
}
 
.team13-social-icons15 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
 
.team13-slider-pagination1 {
  display: block;
}
 
.team13-slider2 {
  width: 100%;
  height: auto;
  display: none;
  position: relative;
}
 
.team13-slider-slide3 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  padding-bottom: var(--dl-space-space-threeunits);
}
 
.team13-card16 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team13-content17 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team13-title16 {
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team13-text32 {
  font-style: normal;
  font-weight: 600;
}
 
.team13-text34 {
  text-align: center;
}
 
.team13-text36 {
  overflow: auto;
  max-height: var(--dl-size-size-medium);
  text-align: left;
}
 
.team13-social-icons16 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
 
.team13-slider-slide4 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  padding-bottom: var(--dl-space-space-threeunits);
}
 
.team13-card17 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team13-content18 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team13-title17 {
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team13-text37 {
  font-style: normal;
  font-weight: 600;
}
 
.team13-text38 {
  text-align: center;
}
 
.team13-text39 {
  overflow: auto;
  max-height: var(--dl-size-size-medium);
  text-align: left;
}
 
.team13-social-icons17 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
 
.team13-slider-slide5 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  padding-bottom: var(--dl-space-space-threeunits);
}
 
.team13-card18 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team13-content19 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team13-title18 {
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team13-text41 {
  font-style: normal;
  font-weight: 600;
}
 
.team13-text43 {
  text-align: center;
}
 
.team13-text45 {
  overflow: auto;
  max-height: var(--dl-size-size-medium);
  text-align: left;
}
 
.team13-social-icons18 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
 
.team13-slider-slide6 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  padding-bottom: var(--dl-space-space-threeunits);
}
 
.team13-card19 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team13-content20 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team13-title19 {
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team13-text47 {
  font-style: normal;
  font-weight: 600;
}
 
.team13-text48 {
  text-align: center;
}
 
.team13-text50 {
  overflow: auto;
  max-height: var(--dl-size-size-medium);
  text-align: center;
}
 
.team13-social-icons19 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
 
.team13-slider-slide7 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  padding-bottom: var(--dl-space-space-threeunits);
}
 
.team13-card20 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team13-content21 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team13-title20 {
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team13-text51 {
  font-style: normal;
  font-weight: 600;
}
 
.team13-text52 {
  text-align: center;
}
 
.team13-text53 {
  overflow: auto;
  max-height: var(--dl-size-size-medium);
  text-align: left;
}
 
.team13-social-icons20 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
 
.team13-slider-slide8 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  padding-bottom: var(--dl-space-space-threeunits);
}
 
.team13-card21 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team13-content22 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team13-title21 {
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.team13-text55 {
  font-style: normal;
  font-weight: 600;
}
 
.team13-text57 {
  text-align: center;
}
 
.team13-text59 {
  overflow: auto;
  max-height: var(--dl-size-size-medium);
  text-align: center;
}
 
.team13-social-icons21 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
 
.team13-slider-pagination2 {
  display: block;
}
 
.team13-fragment10 {
  display: contents;
}
 
.team13-text61 {
  display: inline-block;
}
 
.team13-fragment11 {
  display: contents;
}
 
.team13-text62 {
  display: inline-block;
}
 
.team13-fragment12 {
  display: contents;
}
 
.team13-text63 {
  display: inline-block;
}
 
.team13-fragment13 {
  display: contents;
}
 
.team13-text64 {
  display: inline-block;
}
 
.team13-fragment14 {
  display: contents;
}
 
.team13-text65 {
  display: inline-block;
}
 
.team13-fragment15 {
  display: contents;
}
 
.team13-text66 {
  display: inline-block;
}
 
.team13-fragment16 {
  display: contents;
}
 
.team13-text67 {
  display: inline-block;
}
 
.team13-fragment17 {
  display: contents;
}
 
.team13-text68 {
  display: inline-block;
}
 
.team13-fragment18 {
  display: contents;
}
 
.team13-text69 {
  display: inline-block;
}
 
.team13-fragment19 {
  display: contents;
}
 
.team13-text70 {
  display: inline-block;
}
 
.team13-fragment20 {
  display: contents;
}
 
.team13-text71 {
  display: inline-block;
}
 
.team13-fragment21 {
  display: contents;
}
 
.team13-text72 {
  display: inline-block;
}
 
.team13-fragment22 {
  display: contents;
}
 
.team13-text73 {
  display: inline-block;
}
 
.team13-fragment23 {
  display: contents;
}
 
.team13-text74 {
  display: inline-block;
}
 
.team13-fragment24 {
  display: contents;
}
 
.team13-text75 {
  display: inline-block;
}
 
.team13-fragment25 {
  display: contents;
}
 
.team13-text76 {
  display: inline-block;
}
 
.team13-fragment26 {
  display: contents;
}
 
.team13-text77 {
  display: inline-block;
}
 
.team13-fragment27 {
  display: contents;
}
 
.team13-text80 {
  display: inline-block;
}
 
.team13-fragment28 {
  display: contents;
}
 
.team13-text81 {
  display: inline-block;
}
 
.team13-fragment29 {
  display: contents;
}
 
.team13-text82 {
  display: inline-block;
}
 
.team13-fragment30 {
  display: contents;
}
 
.team13-text83 {
  display: inline-block;
}
 
.team13-fragment31 {
  display: contents;
}
 
.team13-text84 {
  display: inline-block;
}
 
@media(max-width: 767px) {
  .team13-team8 {
    padding: var(--dl-space-space-threeunits);
  }
  .team13-max-width {
    padding: var(--dl-space-space-threeunits);
  }
  .team13-slider1 {
    display: none;
  }
  .team13-slider2 {
    display: block;
  }
}
 
@media(max-width: 479px) {
  .team13-team8 {
    padding: var(--dl-space-space-oneandhalfunits);
  }
  .team13-max-width {
    padding: var(--dl-space-space-oneandhalfunits);
  }
  .team13-text10 {
    text-align: center;
  }
  .team13-button {
    width: 100%;
  }
  .team13-text13 {
    text-align: center;
  }
}
</style>
