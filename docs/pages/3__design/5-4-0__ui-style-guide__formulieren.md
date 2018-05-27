---
layout   : default
permalink: design/ui-style-guide/formulieren/
published: true
# Custom Page Variables
# ─────────────────────
title: Formulieren
---

<div class="container4">
  <h3>REGISTREREN</h3>
  <form action="/action_page.php">
   <div class="form-group">
      <label for="text">Gebruikersnaam:</label>
      <input type="text" class="form-control" id="text" placeholder="Typ hier je gebruikersnaam" name="text">
    </div>
    <div class="form-group">
      <label for="email">E-mailadres:</label>
      <input type="email" class="form-control" id="email" placeholder="Typ hier je e-mailadres" name="email">
    </div>
    <div class="form-group">
      <label for="pwd">Wachtwoord:</label>
      <input type="password" class="form-control" id="pwd" placeholder="Typ hier je wachtwoord" name="pwd">
    </div>
      <div class="form-group">
      <label for="pwd">Herhaal wachtwoord:</label>
      <input type="password" class="form-control" id="pwd" placeholder="Herhaal hier je wachtwoord" name="pwd">
    </div>
    <button type="submit" class="btn btn-default">VERDER</button>
  </form>
</div>