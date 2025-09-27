---
layout: protected
title: "Anmeldung"
permalink: /Anmeldung
---

Hier kannst du dich für unsere Hochzeit anmelden. Bitte fülle das Formular aus und sende es ab. Alternativ kannst du auch eine E-Mail an [norabearth@hotmail.com](mailto:norabearth@hotmail.com) schicken.

<form
  action="https://formspree.io/f/xjkagewb"
  target="_top"
  method="POST"
>
  <fieldset>
    <div class="fs-field">
      <label class="fs-label" for="first-name">Vorname</label>
      <input class="fs-input" id="first-name" name="first-name" required />
    </div>
    <div class="fs-field">
      <label class="fs-label" for="last-name">Nachname</label>
      <input class="fs-input" id="last-name" name="last-name" required />
    </div>
  </fieldset>
  <fieldset>
    <div class="fs-field">
      <label class="fs-label" for="email">Email</label>
      <input class="fs-input" id="email" name="email" required />
    </div>
  </fieldset>
  <fieldset>
    <div class="fs-field">
      <label class="fs-label">
        Bitte gebe allfällige Unverträglichkeiten an
      </label>
      <div class="fs-checkbox-group">
        <div class="fs-checkbox-field">
          <div class="fs-checkbox-wrapper">
            <label class="fs-label">
                <input
                class="fs-checkbox"
                id="laktose"
                name="unvertraeglichkeiten"
                type="checkbox"
                value="Laktose"
                />
            Laktose</label>
          </div>
        </div>
        <div class="fs-checkbox-field">
          <div class="fs-checkbox-wrapper">
            <label class="fs-label">
                <input
                class="fs-checkbox"
                id="Gluten"
                name="unvertraeglichkeiten"
                type="checkbox"
                value="Gluten"
                />
            Gluten</label>
          </div>
        </div>
      </div>
    </div>
    <div class="fs-field">
      <label class="fs-label" for="menu">
        Bitte wähle ob du Fleisch oder Vegetarisch essen möchtest
      </label>
      <select class="fs-select" id="menu" name="menu">
        <option value="Fleisch">Fleisch</option>
        <option value="Vegetarisch">Vegetarisch</option>
      </select>
    </div>
  </fieldset>
  <div class="fs-button-group">
    <button class="fs-button" type="submit">Absenden</button>
  </div>
</form>