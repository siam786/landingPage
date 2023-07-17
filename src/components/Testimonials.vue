<template>
  <div class="testimonials_wrapper">
      <!--begin testimonials_box -->
      <div class="testimonials_box">
        <ul class="rslides" id="slider4">
          <li>
            <!--begin row -->
            <div class="row">
              <!--begin twelvecol -->
              <div class="twelvecol">
                <!--begin fivecol -->
                <div class="fivecol">
                  <!--begin testimonials_info -->
                  <div class="testimonials_info">
                    <img
                      :src="testimonials1"
                      alt="John Doe"
                      class="testimonials_picture"
                    />

                    <p class="testimonials_name">
                      Natasha Kiplings<br /><span>Writter Simple Design</span>
                    </p>
                  </div>
                  <!--end testimonials_info -->
                </div>
                <!--end fivecol -->

                <!--begin sevencol -->
                <div class="sevencol last">
                  <!--begin testimonials_text -->
                  <p class="testimonials_text">
                    "Your time is limited, so don't waste it living someone
                    else's life. Don't be trapped by dogma - which is living
                    with the results of other people's thinking."
                  </p>
                  <!--end testimonials_text -->
                </div>
                <!--end sevencol -->
              </div>
              <!--end twelvecol -->
            </div>
            <!--end row -->
          </li>

          <li>
            <!--begin row -->
            <div class="row">
              <!--begin twelvecol -->
              <div class="twelvecol">
                <!--begin fivecol -->
                <div class="fivecol">
                  <!--begin testimonials_info -->
                  <div class="testimonials_info">
                    <img
                      :src="testimonials1"
                      alt="John Doe"
                      class="testimonials_picture"
                    />

                    <p class="testimonials_name">
                      Johnnatan Smiths<br /><span
                        >Fashion Designer - Ellas</span
                      >
                    </p>
                  </div>
                  <!--end testimonials_info -->
                </div>
                <!--end fivecol -->

                <!--begin sevencol -->
                <div class="sevencol last">
                  <!--begin testimonials_text -->
                  <p class="testimonials_text">
                    "I'm an optimist in the sense that I believe humans are
                    noble and honorable, and some of them are really smart. I
                    have a very optimistic view of individuals.
                  </p>
                  <!--end testimonials_text -->
                </div>
                <!--end sevencol -->
              </div>
              <!--end twelvecol -->
            </div>
            <!--end row -->
          </li>
        </ul>
      </div>
      <!--end testimonials_box -->
    </div>
</template>

<script setup>
import testimonials1 from "../../public/img/testimonials1.jpg";
</script>

<style>

</style>