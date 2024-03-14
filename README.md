#### junior MD WHATSAPP BOT
Junior-md - Simple whatsapp Multi Device whatsapp bot.

***

### SETUP

1. Scan the QR and copy it
    <br>
<a href='https://hermit.adithyan.xyz/qr' target="_blank"><img alt='SCAN QR' src='https://img.shields.io/badge/Scan_qr-100000?style=for-the-badge&logo=scan&logoColor=white&labelColor=black&color=black'/></a>

#### DEPLOY TO HEROKU 

1. If You don't have a account in Heroku. Create a account.
    <br>
<a href='https://signup.heroku.com/' target="_blank"><img alt='Heroku' src='https://img.shields.io/badge/-Create-black?style=for-the-badge&logo=heroku&logoColor=white'/></a>

3. Now Deploy
    <br>
<a href='https://dashboard.heroku.com/new?template=https://github.com/cheekydavy/junior-MD' target="_blank"><img alt='DEPLOY' src='https://img.shields.io/badge/-DEPLOY-black?style=for-the-badge&logo=heroku&logoColor=white'/></a>

#### RUN ON VPS/UBUNTU/WINDOWS

1. Install NodeJs,ffmpeg
2. Installation
   ```
   $ npm i -global pm2
   $ git clone https://github.com/cheekydavy/junior-md.git
   $ cd junior-md
   $ npm install
   ```
3. Configuration
   ```
   $ echo "VPS = true
     SESSION_ID = null
     AUTH_FILE = session
     SUDO = null
     PREFIX = .
     MODE = private
     LOG_MSG = true" > config.env
   ```
- Start
  ```
  $ npm start
  ```
- Stop
  ```
  $ pm2 delete hermit-md
  ```
<br>

For help visit [Github wiki](https://github.com/cheekydavy/junior-md/wiki)

***
