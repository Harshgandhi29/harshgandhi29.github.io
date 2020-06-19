---
layout: page
---
##<ins>Projects<ins>
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
  <h3 style="text-align:center;"><u>Translating/Alerting Mail Bot</u></h3>
  <div class="grid-container">
    <div class="grid-item">This is a bot which runs using pyFirmat,email and the google api IMAP. It is designed to send a signal to an arduino everytime an unseen email is detected. Using pyfirmata, it initializes the pin and the import through which it the arduino is connected and sends a 0,5 volt which can be translated to (0,1/off,on), that turns on an LED light. To ensure the user's safety a txt file was created which stores the password (an environment can also be used but would require some modification). It connects to the gmail server with the correct ssl port. There are also some features which have been added including an interface using tkinter(widgets) and specific alerts from specific email addresses which are important to the user.<br>

  It also has the option of reading the emails outloud, if the user is busy eg. driving and can translate the email into several languages. This interface allows for people with limited computer knowledge to read emails in different language and outloud.
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



