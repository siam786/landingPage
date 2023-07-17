<template>
  <section id="features">
      <!--begin call_to_action_dark_wrapper -->
      <div class="call_to_action_dark_wrapper">
        <!--begin call_to_action_grey -->
        <div class="call_to_action_dark">
          <h3 class="left_fade">Amazing Features</h3>
          <div class="separator_wrapper bounce_fade">
            <div class="separator_first_circle">
              <div class="separator_second_circle_grey"></div>
            </div>
          </div>
          <h4 class="right_fade">
            There are many variations of passages of Lorem Ipsum available, but
            the majority have suffered alteration, by injected humour, or new
            randomised words which don't look believable.
          </h4>
        </div>
        <!--end call_to_action_grey -->
      </div>
      <!--end call_to_action_dark_wrapper -->

      <!--begin section_wrapper -->
      <div class="section_wrapper dark_bg">
        <!--begin section_box -->
        <div class="section_features">
          <!--begin layerslider2 -->
          <div
            id="layerslider2"
            style="margin: 0 auto; width: 1140px; height: 635px"
          >
            <!--begin slide -->
            <div
              class="ls-slide"
              data-ls="slidedelay: 4000; transition2d: 2,7,9;"
            >
              <!-- image layer -->
              <img
                :src="graphic"
                class="ls-l"
                data-ls="parallaxlevel: 5;"
                alt="Image layer"
              />

              <!-- text layers -->
              <p
                class="ls-l"
                data-ls="parallaxlevel: -1;"
                style="
                  top: 14%;
                  left: 11%;
                  color: #fff;
                  font-size: 18px;
                  font-weight: 300;
                  font-style: italic;
                "
              >
                E-mail Marketing
              </p>

              <img
                class="ls-l"
                data-ls="parallaxlevel: -1;"
                style="top: 17%; left: 22%; white-space: nowrap"
                :src="arrow2"
                alt="Arrow"
              />

              <p
                class="ls-l"
                data-ls="parallaxlevel: -1;"
                style="
                  top: 69%;
                  left: 21%;
                  color: #fff;
                  font-size: 18px;
                  font-weight: 300;
                  font-style: italic;
                "
              >
                Marketing Campaign / Analysis
              </p>

              <img
                class="ls-l"
                data-ls="parallaxlevel: -1;"
                style="top: 67%; left: 36%; white-space: nowrap"
                :src="arrow3"
                alt="Arrow"
              />

              <p
                class="ls-l"
                data-ls="parallaxlevel: -1;"
                style="
                  top: 4%;
                  left: 60%;
                  color: #fff;
                  font-size: 18px;
                  font-weight: 300;
                  font-style: italic;
                "
              >
                New Media Center
              </p>

              <img
                class="ls-l"
                data-ls="parallaxlevel: -1;"
                style="top: 7%; left: 49%; white-space: nowrap"
                :src="arrow1"
                alt="Arrow"
              />

              <p
                class="ls-l"
                data-ls="parallaxlevel: -1;"
                style="
                  top: 16%;
                  left: 76%;
                  color: #fff;
                  font-size: 18px;
                  font-weight: 300;
                  font-style: italic;
                "
              >
                Web Design & Development
              </p>

              <img
                class="ls-l"
                data-ls="parallaxlevel: -1;"
                style="top: 19%; left: 62%; white-space: nowrap"
                :src="arrow1"
                alt="Arrow"
              />

              <p
                class="ls-l"
                data-ls="parallaxlevel: -1;"
                style="
                  top: 29%;
                  left: 87%;
                  color: #fff;
                  font-size: 18px;
                  font-weight: 300;
                  font-style: italic;
                "
              >
                SEO Infographics
              </p>

              <img
                class="ls-l"
                data-ls="parallaxlevel: -1;"
                style="top: 32%; left: 76%; white-space: nowrap"
                :src="arrow1"
                alt="Arrow"
              />

              <p
                class="ls-l"
                data-ls="parallaxlevel: -1;"
                style="
                  top: 70%;
                  left: 91%;
                  color: #fff;
                  font-size: 18px;
                  font-weight: 300;
                  font-style: italic;
                "
              >
                Logo Design
              </p>

              <img
                class="ls-l"
                data-ls="parallaxlevel: -1;"
                style="top: 68%; left: 82%; white-space: nowrap"
                :src="arrow4"
                alt="Arrow"
              />
            </div>
            <!--end slide -->
          </div>
          <!--end layerslider2 -->
        </div>
        <!--end section_box -->
      </div>
      <!--end section_wrapper -->
    </section>
</template>

<script setup>

import graphic from "../../public/img/graphic.png";
import arrow1 from "../../public/img/arrow1.png";
import arrow2 from "../../public/img/arrow2.png";
import arrow3 from "../../public/img/arrow3.png";
import arrow4 from "../../public/img/arrow4.png";
</script>

<style>

</style>