---
layout: page
header: false
breadcrumb: true
categories:
    - services
title:  "Contactez Nous"
description: "Formulaire de contact Perspectives Jardin."
permalink: /contact.htm    
---
<form action="//formspree.io/contact@perspectivesjardin.fr" method="POST">
 <fieldset>
 <label for="name">Votre Nom</label><br>
 <input type="text" name="name" placeholder="Nom" id="name" required>
 </fieldset>
 <fieldset>
 <label for="_replyto">Votre e-mail</label><br>
 <input type="email" name="_replyto" placeholder="Email" id="_replyto" required>
 </fieldset>
 <fieldset>
 <label for="message">Votre Message</label><br>
 <textarea name="message" rows="1" placeholder="Message" id="message" required></textarea>
 </fieldset>
 <input class="hidden" type="text" name="_gotcha" style="display:none">
 <input class="hidden" type="hidden" name="_subject" value="Message via http://domain.com">
<input class="button submit" type="submit" value="Envoyer">
</form>
