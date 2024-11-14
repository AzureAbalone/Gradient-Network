# 🤖Gradient Network Bot🤖

<div align="center">
  <img src="./images/console.png" alt="Gradient Bot Console" width="951"/>
</div>

# 🥇 Overview 🥇

_Gradient Bot is the next generation software automation made for registering and farming accounts on Gradient Network. It has many intuitive functions and a nice interface, which eases the overall user experience in an effort to increase platform efficiency._

**💰Price💰 : 80$ USDT**

[Contact _ Telegram](https://t.me/dellcontontai) : **https://t.me/dellcontontai**

[Video_demo](https://youtu.be/V4W5QVaF6MQ) : **https://youtu.be/V4W5QVaF6MQ**

## 🏕️ Features

✅	Automatic account registration

📧	Automatic Re-verify Account 

🚜	Automated farming 1 account – 1 proxy 

💯	**SPECIAL** : **_Automated farming with multi-account mode (each account runs multiple proxies)_**

🔐	Captcha solving 

🤝	Invite code binding 

📤	Export statistics to CSV 

📑	Auto-export unverified/unregistered accounts 

## 💻 Requirements

•	Windows operating system

•	Internet connection

•	Valid email accounts for registration (for ex : _rambler.ru_ ...)


•	Valid proxies (_Static Residential Proxy - IPV4_)



## 🛠️ Configuration - settings.yaml

This file contains general settings for the bot 
```yaml

threads: 3 # Number of threads for registration and export stats (min 1) 

invite_code: " DLZFHM" 

capsolver_api_key: "CAP-xxxx" # Your CapSolver API key 

delay_before_start: 

  min: 5 # Minimum delay before starting registration (in seconds) 

  max: 10 # Maximum delay before starting registration (in seconds) 

imap_settings: # IMAP settings for email providers 

  rambler.ru: imap.rambler.ru

  hotmail.com: imap-mail.outlook.com

  outlook.com: imap-mail.outlook.com

  mail.ru: imap.mail.ru

  gmail.com: imap.gmail.com

  gmx.com: imap.gmx.com

  yahoo.com: imap.mail.yahoo.com

  gmx.net: imap.gmx.net

  gmx.de: imap.gmx.net
```

## ⚙️ Other Configuration Files
- 📄 **_farm.txt_**

Contains accounts for farming. 

_Format:_
```
email:password
email:password
...
```
- 📄 **register.txt** 

Contains accounts to register

_Format:_
```
email:password
email:password
...
```
- 📄 **verify.txt**

Contains accounts to re-verify. 

_Format:_
```
email:password
email:password
...
```
- 📄 **multiple_proxies.txt**

Contains proxies to run **_multi-account mode (each account runs multiple proxies)_** 

✳️✳️✳️ **_The number of proxies will be evenly distributed among the accounts in farm.txt. For example, if there are 10 proxies and 3 accounts, account 1 will use proxies from 1 to 4, account 2 will use proxies from 5 to 7, account 3 will use proxies from 7 to 10._**

_Format:_
```
http://user:pass@ip:port
http://user:pass@ip:port
...
```
- 📄 **proxies.txt**

Contains proxies for farming 01 account – 01 proxy   

_Format:_
```
http://user:pass@ip:port
http://user:pass@ip:port
...
```
