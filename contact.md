---
title: Contact
permalink: /contact/
image: https://img.vakantievibes.be/pexels-amber-faust-3006103.jpg
---

<div class="contact-page">
    <div class="lead">
        <p>Feedback? Foutje ontdekt? Suggesties voor een nieuw artikel? Laat het ons zeker weten!</p>
        <p>Samenwerken? We kijken er alvast naar uit om uw product te leren kennen en de mogelijkheden samen te bekijken.</p>
        <p>Je kan ons contacteren via <em>info@vakantievibes.be</em> of gebruik volgend contactformulier:</p>
    </div>
    <p class="success hidden"><strong>Success!</strong> Uw bericht werd verzonden. Ik contacteer u zo vlug mogelijk.</p>
    <form action="#" name="form" method="post" class="contact-form">
        <p class="error"></p>
        <p class="contact-form-author">
            <input type="text" name="name" placeholder="Naam" required="required" />
        </p>
        <p class="contact-form-phone">
            <input type="tel" name="telephone" placeholder="Telefoon" />
        </p>
        <p class="contact-form-email">
            <input type="email" name="email" placeholder="Email" required="required" />
        </p>
        <p class="contact-form-message">
            <textarea name="message" rows="4" placeholder="Bericht"></textarea>
        </p>
        <p class="contact-form-captcha">
            <img src="/system/captcha.php" alt="" class="captcha" width="200" height="40" /><br />
            <input type="text" name="captcha" id="contact-captcha-input" placeholder="Typ de tekens uit de afbeelding" required="required" />
        </p>
        <p class="contact-form-submit">
            <input type="submit" value="Verstuur" />
        </p>
    </form>
</div>
