<template>
  <section id="contact">
      <!--begin call_to_action_dark_wrapper -->
      <div class="call_to_action_dark_wrapper">
        <!--begin call_to_action_dark -->
        <div class="call_to_action_dark">
          <h3 class="left_fade">Get In Touch</h3>
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
        <!--end call_to_action_dark -->
      </div>
      <!--end call_to_action_dark_wrapper -->

      <!--begin section_wrapper -->
      <div class="section_wrapper dark_bg">
        <!--begin section_box -->
        <div class="section_box align_center">
          <!--begin row -->
          <div class="row bounce_fade">
            <!--begin success message -->
            <p class="contact_success_box" style="display: none">
              We received your message and you'll hear from us soon. Thank You!
            </p>
            <!--end success message -->

            <!--begin contact form -->
            <form
              id="contact-form"
              class="contact"
              action="contact.php"
              method="post"
            >
              <input
                class="contact-input white-input"
                type="text"
                required=""
                name="contact_names"
                placeholder="Full Name*"
              />
              <input
                class="contact-input white-input"
                type="email"
                required=""
                name="contact_email"
                placeholder="Email Adress*"
              />
              <textarea
                class="contact-commnent white-input"
                rows="2"
                cols="20"
                name="contact_message"
                placeholder="Your Message..."
              ></textarea>
              <input
                type="submit"
                value="Send Message"
                id="submit-button"
                class="contact-submit"
              />
            </form>
            <!--end contact form -->
          </div>
          <!--end row -->
        </div>
        <!--end section_box -->
      </div>
      <!--end section_wrapper -->
    </section>
</template>

<script>
export default {

}
</script>

<style>

</style>