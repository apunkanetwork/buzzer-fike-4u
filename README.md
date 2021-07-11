# File-sharing-Bot

<p align="center">
  <a href="https://www.python.org">
    <img src="http://ForTheBadge.com/images/badges/made-with-python.svg" width ="250">
  </a>
  <a href="https://t.me/Central_Links">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQYUFC_daQBVwH6D5ibRoYy-ba4VgLkUyYpcA&usqp=CAU" width="150">
  </a><br>
  <a href="https://t.me/Central_Links">
    &nbsp;<img src="https://img.shields.io/badge/Channel-blue?style=flat-square&logo=telegram" width="130" height="18">&nbsp;
  </a>
  <a href="https://t.me/central_request">
    &nbsp;<img src="https://img.shields.io/badge/Group-blue?style=flat-square&logo=telegram" width="130" height="18">&nbsp;
  </a>
  <br>
  <a href="https://github.com/Thiyaku17/File-Sharing-Bot/stargazers">
    <img src="https://img.shields.io/github/stars/Thiyaku17/File-Sharing-Bot?style=social">
  </a>
  <a href="https://github.com/Thiyaku17/File-Sharing-Bot/fork">
    <img src="https://img.shields.io/github/forks/Thiyaku17/File-Sharing-Bot?label=Fork&style=social">
  </a>  
</p>


Telegram Bot to store Posts and Documents and it can Access by Special Links.
I Guess This Will Be Usefull For Many People.....😇. 

##

**If you need any more modes in repo or If you find out any bugs, mention in [@centralcontactbot](https://www.telegram.dog/centralcontactbot)**

### Features
- Fully customisable.
- Customisable welcome messages.
- More than one Posts in One Link.
- Can be deployed on heroku directly.
- Broadcast Support

### Setup

- Add the bot to Database Channel with all permission
- Add bot to ForceSub channel as Admin with Invite Users via Link Permission if you enabled ForceSub 
- Add MangoDB Url

##
### Installation
#### Deploy on Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)</br>
<a href="https://youtu.be/LCrkRTMkmzE">
  <img src="https://img.shields.io/badge/How%20to-Deploy-red?logo=youtube" width="147">
</a><br>
**Check This Tutorial Video on YouTube for any Help**<br>
**Thanks to [Thiyaku](https://t.me/Thiyaku_17) and his [Request](https://t.me/Central_Request) for this Video**

#### Deploy in your VPS
````bash
git clone https://github.com/Thiyaku17/File-Sharing-Bot
cd File-Sharing-Bot
pip3 install -r requirements.txt
# <Create config.py appropriately>
python3 main.py
````

### Admin Commands

```
/start - start the bot or get posts

/batch - create link for more than one posts

/genlink - create link for one post

/subscribers - To Know The Count Of the Person Using the bot (Owner Only)

/send - To Send A Broadcast Message (Owner Only)

```

### Variables

* `API_HASH` Your API Hash from my.telegram.org
* `API_ID` Your API ID from my.telegram.org
* `TG_BOT_TOKEN` Your bot token from @BotFather
* `OWNER_ID` Must enter Your Telegram Id
* `CHANNEL_ID` Your Channel ID eg:- -100xxxxxxxx
* `ADMINS` Optional: A space separated list of user_ids of Admins, they can only create links
* `START_MESSAGE` Optional: start message of bot, use HTML and <a href='https://github.com/shahsad-klr/File-Sharing-Bot/blob/main/README.md#start_message'>fillings</a>
* `FORCE_SUB_CHANNEL` Optional: ForceSub Channel ID, leave 0 if you want disable force sub
* `DB_URI` Create a postgre database if you deploy the locally | In heroku do nothing

### Extra Variables

* `CUSTOM_CAPTION` put your Custom caption text if you want Setup Custom Caption, you can use HTML and <a href='https://github.com/shahsad-klr/File-Sharing-Bot/blob/main/README.md#custom_caption'>fillings</a> for formatting (only for documents)
* `DISABLE_CHANNEL_BUTTON` Put True to Disable Channel Share Button, Default if False

### Fillings
#### START_MESSAGE

* `{first}` - User first name
* `{last}` - User last name
* `{id}` - User ID
* `{mention}` - Mention the user
* `{username}` - Username

#### CUSTOM_CAPTION

* `{filename}` - file name of the Document
* `{previouscaption}` - Original Caption


## Support   
Join Our [Telegram Channel](https://www.telegram.dog/Central_Links) For Support/Assistance And Our [Channel](https://www.telegram.dog/central_links) For Updates.   
   
Report Bugs, Give Feature Requests There..   

### Credits

- Thanks To Dan For His Awsome [Libary](https://github.com/pyrogram/pyrogram)
- Our Support Group Members

### Licence
[![GNU GPLv3 Image](https://www.gnu.org/graphics/gplv3-127x51.png)](http://www.gnu.org/licenses/gpl-3.0.en.html)  

[FILE-SHARING-BOT](https://github.com/Thiyaku17/File-Sharing-Bot/) is Free Software: You can use, study share and improve it at your
will. Specifically you can redistribute and/or modify it under the terms of the
[GNU General Public License](https://www.gnu.org/licenses/gpl.html) as
published by the Free Software Foundation, either version 3 of the License, or
(at your option) any later version. 

##

   **Star this Repo if you Liked it ⭐⭐⭐**
