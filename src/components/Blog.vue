<template>
  <section id="blog">
    <!--begin call_to_action_grey_wrapper -->
    <div class="call_to_action_grey_wrapper">
      <!--begin call_to_action_white -->
      <div class="call_to_action_grey">
        <h3 class="left_fade">{{ newsTitle }}</h3>
        <div class="separator_wrapper bounce_fade">
          <div class="separator_first_circle">
            <div class="separator_second_circle"></div>
          </div>
        </div>
        <h4 class="right_fade">
          {{ newsSubTitle }}
        </h4>
      </div>
      <!--end call_to_action_white -->
    </div>
    <!--end call_to_action_grey_wrapper -->

    <!--begin section_wrapper -->
    <div class="section_wrapper grey_bg">
      <!--begin section_box -->
      <div class="section_box small_margins">
        <div v-for="item in blogItems" :key="item.id" class="row up_fade">
          <div v-for="blog in item.blogs" :key="blog.id" class="fourcol">
            <div class="blog_item">
              <div class="zoom_photo">
                <div class="view view-first">
                  <a :href="blog.imageUrl" class="prettyPhoto[gallery1]">
                    <img :src="blog.imageUrl" :alt="blog.title" />
                    <span class="mask">
                      <span class="zoom"></span>
                    </span>
                  </a>
                </div>
              </div>
              <div class="blog_item_inner">
                <h3 class="blog_title">
                  <a :href="blog.link">{{ blog.title }}</a>
                </h3>
                <a href="#" class="blog_icons">
                  <Icon :icon="blog.authorIcon" width="20" /> {{ blog.author }}
                </a>
                <a href="#" class="blog_icons last">
                  <Icon :icon="blog.categoryIcon" width="20" />
                  {{ blog.category }}
                </a>
                <p>{{ blog.description }}</p>
                <a href="#" class="button_grey">Read More</a>
                <a href="#" class="blog_comments_icon">
                  <Icon icon="bi:chat" width="15" /> {{ blog.comments }}</a
                >
              </div>
            </div>
          </div>
        </div>
      </div>
      <!--end section_box -->
    </div>
    <!--end section_wrapper -->
  </section>
</template>

<script setup>
import { Icon } from "@iconify/vue";
import blog1Image from "../../public/img/blog1.jpg";
import blog2Image from "../../public/img/blog2.jpg";
import blog3Image from "../../public/img/blog3.jpg";
import blog4Image from "../../public/img/blog4.jpg";
import blog5Image from "../../public/img/blog5.jpg";
import blog6Image from "../../public/img/blog6.jpg";

const blogItems = [
  {
    id: 1,
    blogs: [
      {
        id: 1,
        imageUrl: blog1Image,
        title: "Lorem ipsum sit netsum amet.",
        authorIcon: "material-symbols:man",
        author: "John Doe",
        categoryIcon: "icon-park-outline:stapler",
        category: "Marketing, Design",
        description:
        "Prepare to be captivated by the ethereal symphony of emotions in Quis Autem Velis. This introspective exploration of voluptas and nihil will challenge your perceptions, leaving you with a renewed understanding of the human experience.",
        comments: 8,
      },
    ],
  },
  {
    id: 2,
    blogs: [
      {
        id: 2,
        imageUrl: blog2Image,
        title: "Unveiling the Secrets of Lorem Ipsum",
        authorIcon: "material-symbols:man",
        author: "John Doe",
        categoryIcon: "icon-park-outline:stapler",
        category: "Marketing, Design",
        description:
        "Quaestis Voluptate is a mesmerizing odyssey that explores the transformative power of self-reflection. Delve into the enigma of sedit and aspernatura, and discover the profound beauty that lies within the depths of your being.",
        comments: 4,
      },
    ],
  },
  {
    id: 3,
    blogs: [
      {
        id: 3,
        imageUrl: blog3Image,
        title: "Exploring the Depths of Netsum Amet",
        authorIcon: "material-symbols:man",
        author: "John Doe",
        categoryIcon: "icon-park-outline:stapler",
        category: "Marketing, Design",
        description:
        "Immerse yourself in the enigmatic world of Quis Autem Velis and witness the poetic dance between illum and consequatur. This introspective journey will unravel the mysteries of reprehenderit, leaving you in awe of the boundless potential within.",
        comments: 5,
      },
    ],
  },
  {
    id: 4,
    blogs: [
      {
        id: 4,
        imageUrl: blog4Image,
        title: "The Journey of Lorem Ipsum: From Words to Meaning",
        authorIcon: "material-symbols:man",
        author: "John Doe",
        categoryIcon: "icon-park-outline:stapler",
        category: "Marketing, Design",
        description:
        "Step into the realm of illuminated consciousness and embark on a profound quest to understand the interplay between nihil and sedit. Quis Autem Velis is a riveting tale that will challenge your perceptions and ignite your soul.",
        comments: 8,
      },
    ],
  },
  {
    id: 5,
    blogs: [
      {
        id: 5,
        imageUrl: blog5Image,
        title: "Unlocking the Power of Sit Netsum Amet",
        authorIcon: "material-symbols:man",
        author: "John Doe",
        categoryIcon: "icon-park-outline:stapler",
        category: "Marketing, Design",
        description:
        "Unlock the secrets of etims and quiste in this thought-provoking exploration of personal growth and fulfillment. Discover the true essence of voluptas and immerse yourself in a world of endless possibilities.",
        comments: 4,
      },
    ],
  },
  {
    id: 6,
    blogs: [
      {
        id: 6,
        imageUrl: blog6Image,

        title: "Mastering the Essence: Lorem Ipsum and Beyond",
        authorIcon: "material-symbols:man",
        author: "John Doe",
        categoryIcon: "icon-park-outline:stapler",
        category: "Marketing, Design",
        description:
        "Experience the captivating journey of self-discovery as you delve into the depths of Quis Autem Velis, a world where reprehenderit and voluptate intertwine to create a mesmerizing tapestry of emotions.",
        comments: 5,
      },
    ],
  },
];
const newsTitle = "News & Announcements";
const newsSubTitle = `There are many variations of passages of Lorem Ipsum available, but
  the majority have suffered alteration, by injected humour, or new
  randomised words which don't look believable.`;
</script>

<style scoped>
.section_box {
  display: grid;
  grid-gap: 10px;
}
@media (min-width: 1200px) {
  /* Large screen styles */
  .section_box {
    grid-template-columns: repeat(3, 1fr);
  }
}

@media (max-width: 1199px) and (min-width: 768px) {
  /* Tablet screen styles */
  .section_box {
    grid-template-columns: repeat(2, 1fr);
  }
}

@media (max-width: 767px) {
  /* Mobile screen styles */
  .section_box {
    grid-template-columns: repeat(1, 1fr);
  }
}
.row .fourcol {
  width: 100%;
}
.blog_item_inner {
    
    min-height: 343px;
}
</style>
