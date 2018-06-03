---
layout   : default
permalink: design/ui-style-guide/formulieren/
published: true
# Custom Page Variables
# ─────────────────────
title: Formulieren
---


<div class="container">
    <div class="row">
    <div class="col-sm-6">
<div class="container4">
  <h3 class="titel">REGISTREREN</h3>
  <form action="/action_page.php">
   <div class="form-group">
      <label for="text">Gebruikersnaam</label>
      <input type="text" class="form-control" class="text" placeholder="Typ hier je gebruikersnaam" name="text">
    </div>
    <div class="form-group">
      <label for="email">E-mailadres</label>
      <input type="email" class="form-control" class="email" placeholder="Typ hier je e-mailadres" name="email">
    </div>
    <div class="form-group">
      <label for="pwd">Wachtwoord</label>
      <input type="password" class="form-control" class="pwd2" placeholder="Typ hier je wachtwoord" name="pwd">
      <div class="form-group">
      </div>
      <label for="pwd">Herhaal wachtwoord</label>
      <input type="password" class="form-control" class="pwd2" placeholder="Herhaal hier je wachtwoord" name="pwd">
      </div>
    <button class="button2"> VERDER </button>
  </form>
</div>
</div>


<div class="col-sm-6">
<div class="container4">
  <h3 class="titel">INLOGGEN</h3>
  <form action="/action_page.php">
   <div class="form-group">
      <label for="text">Gebruikersnaam</label>
      <input type="text" class="form-control" class="text" placeholder="Typ hier je gebruikersnaam" name="text">
    </div>
    <div class="form-group">
      <label for="pwd">Wachtwoord</label>
      <input type="password" class="pwd2" placeholder="Typ hier je wachtwoord" name="pwd">
    <button class="button2"> VERDER </button>
    </div>
  </form>
</div>
</div>
</div>

 <div class="row">
    <div class="col-sm-6">
      <div class="container5">
        <h3 class="titel">MIJN ACCOUNT</h3>
        <form action="/action_page.php">
        <div class="form-group">
            <label for="text">Profielfoto</label>
        </div>
        <img src="/1718-nmd3-project-clauwers_cocquyt/assets/img/fotojongen.png" class="fotojongen" width="30%"/>
        <button class="button3"> OPSLAAN </button>
        <div class="form-group">
      <label for="text">Gebruikersnaam</label>
      <input type="text" class="form-control" class="pwd" placeholder="Typ hier je gebruikersnaam" name="text">
      <button class="button3"> OPSLAAN </button>
      </div>
    <div class="form-group">
      <label for="email">E-mailadres</label>
      </div>
      <input type="email" class="form-control" class="pwd" placeholder="Typ hier je e-mailadres" name="email">
      <button class="button3"> OPSLAAN </button>
    <div class="form-group">
      <label for="pwd">Wachtwoord</label>
      </div>
      <input type="password" class="form-control" class="pwd" placeholder="Typ hier je wachtwoord" name="pwd">
      <button class="button3"> OPSLAAN </button>
      <div class="form-group">
        <label for="pwd">Taal</label>
        </div>
        <p class="formulier"> Nederlands 
          <label class="switch">
            <input type="checkbox" checked>
            <span class="slider round"> </span>
          </label>
        Frans </p>
    </form>
  </div>
</div>
</div>
