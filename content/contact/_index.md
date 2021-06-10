---
title: "Contact"
bg_image: "https://pixabay.com/get/g9ba704040e5c11e74dc944c2654ec15caf83477853f6363b7921b4ad64bc15e695c55d8b671e075a27cc09d25a1cd31f_1920.jpg"
# meta description
description: "This is meta description"
# save as draft
draft: false
---

<p>
Usa il modulo contatti a seguire per scrivermi di un'idea, di un suggerimento, di una proposta di collaborazione.
</p>
<p>
Oppure puoi contattarmi sui vari social che trovi linkati nel menù.
</p>

<p>
E ricordati che se hai ulteriori dubbi sono sempre felice di poter aiutare chi magari non è ancora navigato nel mare della tecnologia.
</p>

<form name="contact" method="POST" data-netlify-recaptcha="true" data-netlify="true">
<!-- Aggiunto lo style alle etichette del form per avere un font simil coerente-->
  <p style = "font-family: -apple-system, BlinkMacSystemFont, Helvetica Neue, sans-serif;">
    <label><b>Il tuo nome:</b> <input type="text" name="name" /></label>   
  </p>
  <p style = "font-family: -apple-system, BlinkMacSystemFont, Helvetica Neue, sans-serif;">
    <label><b>Il tuo indirizzo e-mail:</b> <input type="email" name="email" /></label>
  </p>

  <p style = "font-family: -apple-system, BlinkMacSystemFont, Helvetica Neue, sans-serif;">
    <label><b>Messaggio:</b> <textarea name="message"></textarea></label>
  </p>
  <!-- Captcha da centrare -->
  <div data-netlify-recaptcha="true"></div>
  <br>
  <p>
    <button style=width:100% type="submit">Invia</button>
  </p>
</form>
