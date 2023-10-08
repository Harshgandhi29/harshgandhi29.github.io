---
layout: page
title: Projects
---
<head>
<meta charset="utf-8">
<!--<link rel="stylesheet" href="styles.css">-->
<style>
.grid-container {
  /*display: grid;
  grid-template-columns: 50% 50%;*/
  padding: 20px;
  }
.grid-item{
  text-align: justify;
  text-align-last: center;
}
  
</style>
</head>
<body>
  <h3 style="text-align:center;">
    <a href="https://github.com/Harshgandhi29/Mail-Bot"> 
    <u>Translating/Alerting Mail Bot</u>
    </a>
  </h3>
  <div class="grid-container">
    <div class="grid-item">This is an automated bot that runs using pyFirmat, email and the Google API IMAP. It is designed to send a signal to an LED powered by an Arduino when an unseen email is detected. Using Pyfirmata, it initializes the pin and the import through which the Arduino is connected and sends a 0,5 volt which can be translated to (0,1/off, on), that turns on an LED light. To ensure the user's safety a text file was created that stores the password (an environment can also be used but would require some modification). It connects to the Gmail server with the correct SSL port. There are also some features which have been added including an interface using Tkinter(widgets) and specific alerts from specific email addresses which are important to the user.<br>

  It also has the option of reading the emails out loud, if the user is busy eg. driving and can translate the email into several languages. This interface allows people with limited computer knowledge to read emails in different languages and out loud.
      <br>
      <br>
  </div>

   <div class="grid-item">
      <a href="https://github.com/Harshgandhi29/Mail-Bot"> 
        <img src="Gmail-logo.png" alt="Pie:)" style="width:400px;height:200px;">
      </a>
   </div>
  </div>
</body>



