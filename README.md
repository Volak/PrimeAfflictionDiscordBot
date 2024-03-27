# Prime Affliction Bot

The official bot for [Prime Affliction](https://www.discord.gg/primeaffliction) discord server.

-----
  <a href="https://cdn.discordapp.com/attachments/1028380505923670096/1045961502135439400/WebsiteBannerMini.png?ex=6610f70f&is=65fe820f&hm=f12f88d36bf119f4fddc0c39a813b16f70cc2399af6e1d337be120b34321c221&" >
    <img src="https://cdn.discordapp.com/attachments/1028380505923670096/1045961502135439400/WebsiteBannerMini.png?ex=6610f70f&is=65fe820f&hm=f12f88d36bf119f4fddc0c39a813b16f70cc2399af6e1d337be120b34321c221&">
  </a>

-----
### Table of Content

* [Command List](#command-list)
* [Work in Progress (WIP)](#work-in-progress)
* [Author](#author)
* [License](#license)

-----
### Command List

<sub> 〰️ Admin Commands 〰️ </sub>
* [Addrole](#addrole)
* [Removerole](#removerole)
* [Setrank](#setrank)

<sub> 〰️ Rank Managemenmt 〰️ </sub>
* [Promote](#promote)
* [Demote](#demote)
* [Recruit](#recruit)

<sub> 〰️ Miscellaneous 〰️ </sub>
* [Server Info](#serverinfo)
* [Whois](#whois)
* [Nickname](#nickname)
* [Purge](#purge)
* [Say](#say)
* [TimeStamp Generator](#timestamp)
* [Dice Roll](#roll)
* [Coin Flip](#coinflip)
* [Ping](#ping)

## Commands
> Note: the repository uses Discord slash commands

### AddRole 
  - ➕ Add any existing role to any member in the discord
  `Admin Use Only`
  ```bash 
  /addrole {@member} {@role}
  ```


### RemoveRole
  - ➖ Remove any existing role from any member in the discord
  `Admin Use Only`
  ```bash 
  /removerole {@member} {@role}
  ```


### SetRank
  - ✖️ Set member rank
  `Admin Use Only`
  ```bash 
  /setrank {@member} {@rank}
  ```


### Promote
   - ✅ Promote member to next increment rank
   `Officers can only promote up to Tier 1 Operator`
   ```bash 
   /promote {@member} {@role}
   ```
   

### Demote
  - ❎ Demote member to next increment rank
  `Officers can only demote down to Tier 2 Observer`
  ```bash
  /demote {@member} {@role}
  ```


### Recruit
  - 💯 Recruit a member to recruit status. User will be sent a recruit guide
  `Member+ Use Only`
  ```bash
  /recruit {@member}
  ```

  <a href="https://cdn.discordapp.com/attachments/1028380505923670096/1061621583879352420/image.png?ex=661290a5&is=66001ba5&hm=df7ec8145e7b73c51a3456800c25a875961a04f787b698aa22531be98b982efd&" >
    <img src="https://cdn.discordapp.com/attachments/1028380505923670096/1061621583879352420/image.png?ex=661290a5&is=66001ba5&hm=df7ec8145e7b73c51a3456800c25a875961a04f787b698aa22531be98b982efd&">
  </a>


### ServerInfo
  - ❓ Displays various information about the discord server
  `Member+ Use Only`
  ```bash
  /serverinfo
  ```
  
  <a href="https://cdn.discordapp.com/attachments/1028380505923670096/1052404923733651536/image.png?ex=6615f2f6&is=66037df6&hm=4d667172d453b805e76f5c450adddf63efe29fc2e40af51cda9738b0162c4fed&" >
    <img src="https://cdn.discordapp.com/attachments/1028380505923670096/1052404923733651536/image.png?ex=6615f2f6&is=66037df6&hm=4d667172d453b805e76f5c450adddf63efe29fc2e40af51cda9738b0162c4fed&">
  </a>

### Whois
  - 🔍 Get various information on a member of the discord server
  `Member+ Use Only`
  ```bash
  /whois {@member}
  ```
   
  <a href="https://cdn.discordapp.com/attachments/1028380505923670096/1052405193783914506/image.png?ex=6615f336&is=66037e36&hm=80ac6d0618bccd276a3a3e3e24d8694762e80bef86b0cb25997d373b5cfd2ddb&" >
    <img src="https://cdn.discordapp.com/attachments/1028380505923670096/1052405193783914506/image.png?ex=6615f336&is=66037e36&hm=80ac6d0618bccd276a3a3e3e24d8694762e80bef86b0cb25997d373b5cfd2ddb&">
  </a>

### Nickname
  - ✎ Change member's nickname
  `Admin Use Only`
  ```bash
  /nickname {@member} {nickname}
  ```


### Purge
> Plans to Upgrade to have more specific options when deleting messages
  - 🎤 Delete certain amount of messages within channel
  `Officers+ Use Only`
  ```bash
  /purge {number of messages to delete}
  ```
  
  
### Say
  - ❗️ Get the bot to say anything on your behalf.
  `Admin Use Only`
  ```bash
  /say {message}[Alternate]
  ```
  
  
### Timestamp
  - 🕒 Formats and shows all the TimeStamp styles with side-by-side copy&paste and result
  `Member+ Use Only`
  ```bash
  /timestamp {date}{time}
  ```
  
  <a href="https://cdn.discordapp.com/attachments/1028380505923670096/1064101582066700288/image.png?ex=66125bd3&is=65ffe6d3&hm=38edc9b641c4d4775d688dffe06045f7bb8ba4ff86c7c5c795d1fec36147899f&">
    <img src="https://cdn.discordapp.com/attachments/1028380505923670096/1064101582066700288/image.png?ex=66125bd3&is=65ffe6d3&hm=38edc9b641c4d4775d688dffe06045f7bb8ba4ff86c7c5c795d1fec36147899f&">
  </a>
  
  
  ### Roll
  - 🎲 Roll a die that has a range of 1 and [sides]
  `Friends+`
  ```bash
  /role {sides}
  ```
  
  
  ### Coin Flip
  - 🟡 Flip a coin (Heads, Tails)
  `Friends+`
  ```bash
  /coinflip
  ```
  
  
  ### Ping
  - ❗️ Pongs back (with visible latency) to verify bot is working
  `Officers+ Use Only`
  ```bash
  /ping
  ```


---
### Work in Progress

  - Purge Specification
  
    〰️ Optional Specifications 〰️
    
    ‣ Messages coming from specific member
    
    ‣ Messages containing certain word
    
    ‣ Messages containing certain member mention
    
    ‣ Messages containing certain role mention
  
  - PartyStart
  
    〰️ Description 〰️
    
    ‣ Start a party that will @mention the people you want for the activity
  
    ‣ A display embed will be shown, updates as members join/leave
  - Help Panel
  
    〰️ Description 〰️
    
    ‣ A clean panel describing each command and their use
    
---
### Author

  <a href="https://cdn.discordapp.com/attachments/1028380505923670096/1064095140999856168/BlueEyes.png?ex=661255d3&is=65ffe0d3&hm=85e758da9eb68ce199a96d7fdfed20601b64a36a838067c1bdbe635e8e0e6ae5&" >
    <img src="https://cdn.discordapp.com/attachments/1028380505923670096/1064095140999856168/BlueEyes.png?ex=661255d3&is=65ffe0d3&hm=85e758da9eb68ce199a96d7fdfed20601b64a36a838067c1bdbe635e8e0e6ae5&" width="200" height="200">
  </a>

ㅤㅤㅤㅤㅤ[**Volak**](https://github.com/Volak)

---
### License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/Volak/PrimeAfflictionBot/blob/main/LICENSE) file for details.


