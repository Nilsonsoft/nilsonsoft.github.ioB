---
layout: page
title: "Contato"
---
<!-- START HERE -->
   <link rel="stylesheet" href="https://unpkg.com/purecss@1.0.0/build/pure-min.css">
   <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css">
   <!-- Style The Contact Form How Ever You Prefer -->
 
  <form class="gform pure-form pure-form-stacked" method="POST" data-email="example@email.net"
  action="https://script.google.com/macros/s/AKfycbzO2JBqXFqIX8qQc37BkZvL4Ijsz2NdwhQTESyc/exec">
    <!-- change the form action to your script url -->

    <div class="form-elements">
      <fieldset class="pure-group">
        <label for="name">Nome: </label>
        <input id="name" name="name" placeholder="What your Mom calls you" />
      </fieldset>

      <fieldset class="pure-group">
        <label for="message">Menssagem: </label>
        <textarea id="message" name="message" rows="10"
        placeholder="Tell us what's on your mind..."></textarea>
      </fieldset>

      <fieldset class="pure-group">
        <label for="email"><em>Seu</em> Email:</label>
        <input id="email" name="email" type="email" value=""
        required placeholder="your.name@email.com"/>
        <span class="email-invalid" style="display:none">
          Insira um email válido</span>
      </fieldset>

      <fieldset class="pure-group">
        <label for="assunto">Assunto: </label>
        <input id="assunto" name="assunto" placeholder="Assunto" />
      </fieldset>

      <button class="button-success pure-button button-xlarge">
        <i class="fa fa-paper-plane"></i>&nbsp;Send</button>
    </div>

    <!-- Customise the Thankyou Message People See when they submit the form: -->
    <div class="thankyou_message" style="display:none;">
      <h2><em>Obrigado</em> pelo contato!
        Sua menssagem foi enviada com sucesso!</h2>
    </div>

  </form>

  <!-- Submit the Form to Google Using "AJAX" -->
  <script data-cfasync="false" type="text/javascript"
  src="/assets/js/form-submission-handler.js"></script>
<!-- END -->
