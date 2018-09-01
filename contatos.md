---
layout: page
title: "Contatos"
---

  <form class="gform pure-form pure-form-stacked" method="POST" data-email="example@email.net"
  action="https://script.google.com/macros/s/AKfycbzO2JBqXFqIX8qQc37BkZvL4Ijsz2NdwhQTESyc/exec">
    <!-- change the form action to your script url -->

    <div class="form-elements">
      <fieldset class="pure-group">
        <label for="name">Name: </label>
        <input id="name" name="name" placeholder="What your Mom calls you" />
      </fieldset>

      <fieldset class="pure-group">
        <label for="message">Message: </label>
        <textarea id="message" name="message" rows="10"
        placeholder="Tell us what's on your mind..."></textarea>
      </fieldset>

      <fieldset class="pure-group">
        <label for="email"><em>Your</em> Email Address:</label>
        <input id="email" name="email" type="email" value=""
        required placeholder="your.name@email.com"/>
        <span class="email-invalid" style="display:none">
          Must be a valid email address</span>
      </fieldset>

      <fieldset class="pure-group">
        <label for="color">Favourite Color: </label>
        <input id="color" name="color" placeholder="green" />
      </fieldset>

      <button class="button-success pure-button button-xlarge">
        <i class="fa fa-paper-plane"></i>&nbsp;Send</button>
    </div>

    <!-- Customise the Thankyou Message People See when they submit the form: -->
    <div class="thankyou_message" style="display:none;">
      <h2><em>Thanks</em> for contacting us!
        We will get back to you soon!</h2>
    </div>

  </form>

  <!-- Submit the Form to Google Using "AJAX" -->
  <script data-cfasync="false" type="text/javascript"
  src="form-submission-handler.js"></script>
<!-- END -->
