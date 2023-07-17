<template>
  <div class="info_wrapper">
    <!--begin info_box -->
    <div class="info_box">
      <h4 class="info_title">
        <span>{{ info }}</span>
      </h4>

      <p class="info_text">
        {{ infoText }}
      </p>

      <a href="#pricing" class="info_button_white scrool">{{ discover }}</a>

      <a href="#contact" class="info_button_transparent scrool">{{
        subscribe
      }}</a>
    </div>
    <!--end info_box -->
  </div>
</template>

<script setup>
const info = "Simplé, Designed With Love For Apps";
const infoText = `Sapien ligula, blandit eget dui ut, tincidunt faucibus nulla.
          Vestibulum sodales, dolor eget gravida lobortis, dolor justo viverra
          consectetur, nec luctus erat leo nectrisim neque. Cras ac scelerisque
          tellus. Suspendisse ut tortor bibendum, condimentum augue
          tinciduntims, tristique urna. Mauris consectetur eleifend augue. Cras
          pulvinar, justo ac pharetra varius, interdum.`;
const discover = "Explore Now";
const subscribe = "Subscribe Today";
</script>

<style></style>
