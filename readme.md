# wa-broadcast

## What is wa-broadcast?

wa-broadcast is simple application to send bulk whatsapp message using whatsapp-web.js

## Installation & setup

- clone this repository `git clone https://github.com/wishnupmi/wa-broadcast.git`
- `cd wa-broadcast`
- `npm install` to install dependency this application or you can execute file `install` (windows `install.bat`, linux `install.sh` you must set this file permission to executable)
- change your `path of google chrome` key in `config.json` on line 6 variable `executablePath`
- `npm run start` to run this application on your terminal / console or you can execute file `buka` (windows `buka.bat`, linux `buka.sh` you must set this file permission to executable)
- if you first run this application, you must scan qr code whatsapp to login
- if you want to send bulk message open send.html in your browser and you can drag your spreadsheet file ( message.xlsx in my example file )

## Feature

- Send attachment from local disk or internet
- Send message to personal or group without save number whatsapp

## Problem
- If happen login loop, you can remove file `session.json`, reopen this application and now you can scan barcode again
- `npm update` to update all package used in this application, this is needed if whatsapp web changed

## Lisensi

Lisensi dari wa-broadcast adalah [MIT License](LICENSE) namun proyek yang dibangun menyeseuaikan dengan kebijakan masing-masing
