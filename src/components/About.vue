<template>
   <section id="about">
      <!--begin section_wrapper -->
      <div class="section_wrapper">
        <!--begin section_box -->
        <div class="section_box">
          <!--begin row -->
          <div class="row">
            <!--begin twelvecol -->
            <div class="twelvecol">
              <!--begin fivecol -->
              <div class="fivecol left_fade">
                <img :src="pic3" alt="picture" />
              </div>
              <!--end fivecol -->

              <!--begin sevencol -->
              <div class="sevencol last padding_top right_fade">
                <h2>Passionate about crafting smart design</h2>

                <p>
                  Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut
                  odit aut fugit, sed quia magni dolores eos qui ratione sequi
                  nesciunt. Neque porro quisquam est, qui ipsum quiaim netsum.
                  Consequuntur magni netsum es qui ratione sequi nesciunt. Neque
                  porro quisquat est quia.
                </p>

                <!--begin featured_dropcap -->
                <div class="featured_dropcap">
                  <span class="dropcaps_icon"
                    ><Icon icon="ri:pencil-ruler-fill" width="30" /></span>
                  <p>
                    Quis autem velis reprehenderit et quis voluptate velit esse
                    quam nihil et illum consequatur quia voluptas sit aspernatur
                    aut odit aut fugit.
                  </p>
                </div>
                <!--end featured_dropcap -->

                <!--begin featured_dropcap -->
                <div class="featured_dropcap">
                  <span class="dropcaps_icon"
                    ><Icon icon="mdi:user" width="30" /></span>
                  <p>
                    Quis autem velis reprehenderit et quis voluptate velit esse
                    quam nihil et illum consequatur quia voluptas sit aspernatur
                    aut odit aut fugit.
                  </p>
                </div>
                <!--end featured_dropcap -->

                <!--begin featured_dropcap -->
                <div class="featured_dropcap">
                  <span class="dropcaps_icon"
                    ><Icon icon="mdi:umbrella" width="30" /></span>
                  <p>
                    Quis autem velis reprehenderit et quis voluptate velit esse
                    quam nihil et illum consequatur quia voluptas sit aspernatur
                    aut odit aut fugit.
                  </p>
                </div>
                <!--end featured_dropcap -->
              </div>
              <!--end sevencol -->
            </div>
            <!--end twelvecol -->
          </div>
          <!--end row -->
        </div>
        <!--end section_box -->
      </div>
      <!--end section_wrapper -->

      <!--begin section_wrapper -->
      <div class="section_wrapper grey_border">
        <!--begin section_box -->
        <div class="section_box partners_margins">
          <!--begin row -->
          <div class="row">
            <ul class="partners up_fade">
              <li><img :src="logo7" alt="Logo" /></li>
              <li><img :src="logo1" alt="Logo" /></li>
              <li><img :src="logo5" alt="Logo" /></li>
              <li><img :src="logo2" alt="Logo" /></li>
              <li><img :src="logo3" alt="Logo" /></li>
              <li><img :src="logo0" alt="Logo" /></li>
            </ul>
          </div>
          <!--end row -->
        </div>
        <!--end section_box -->
      </div>
      <!--end section_wrapper -->
    </section>
</template>

<script setup>
import { Icon } from '@iconify/vue';
import pic3 from "../../public/img/pic3.png";
import logo0 from "../../public/img/logo0.png";
import logo1 from "../../public/img/logo1.png";
import logo2 from "../../public/img/logo2.png";
import logo3 from "../../public/img/logo3.png";
import logo5 from "../../public/img/logo5.png";
import logo7 from "../../public/img/logo7.png";
</script>

<style>

</style>