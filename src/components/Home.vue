<template>
  <section id="home_wrapper">
      <!--begin home_box -->
      <div class="home_box">
        <h2 class="home_title">
          innovative &amp; modern template, designed with love for apps.
        </h2>

        <h3 class="home_subtitle">
          Design is not just what it looks like. Design is how it works.
        </h3>

        <!--begin success_box -->
        <p class="newsletter_success_box" style="display: none">
          We received your message and you'll hear from us soon. Thank You!
        </p>
        <!--end success_box -->

        <!--begin newsletter_form_wrapper -->
        <div class="newsletter_form_wrapper">
          <!--begin newsletter_form_box -->
          <div class="newsletter_form_box">
            <!--begin success_box -->
            <p class="newsletter_success_box" style="display: none">
              We received your message and you'll hear from us soon. Thank You!
            </p>
            <!--end success_box -->

            <!--begin newsletter-form -->
            <form
              id="newsletter-form"
              class="newsletter_form"
              action="newsletter.php"
              method="post"
            >
              <input
                id="email_newsletter"
                type="email"
                name="nf_email"
                placeholder="Enter Your Email Address"
              />
              <input
                type="submit"
                value="GET STARTED!"
                id="submit-button-newsletter"
              />
            </form>
            <!--end newsletter-form -->
          </div>
          <!--end newsletter_form_box -->
        </div>
        <!--end newsletter_form_wrapper -->
      </div>
      <!--end home_box -->
    </section>
</template>

<script>
export default {

}
</script>

<style>

</style>