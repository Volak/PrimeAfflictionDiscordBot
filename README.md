# Prime Affliction Bot

The official bot for [Prime Affliction](https://www.discord.gg/primeaffliction) discord server.

-----

  <a href="https://cdn.discordapp.com/attachments/1028380505923670096/1045961502135439400/WebsiteBannerMini.png" >
    <img src="https://cdn.discordapp.com/attachments/1028380505923670096/1045961502135439400/WebsiteBannerMini.png">
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

  <a href="https://cdn.discordapp.com/attachments/1028380505923670096/1061621583879352420/image.png" >
    <img src="https://cdn.discordapp.com/attachments/1028380505923670096/1061621583879352420/image.png">
  </a>


### ServerInfo
  - ❓ Displays various information about the discord server
  `Member+ Use Only`
  ```bash
  /serverinfo
  ```
  
  <a href="https://cdn.discordapp.com/attachments/1028380505923670096/1052404923733651536/image.png" >
    <img src="https://cdn.discordapp.com/attachments/1028380505923670096/1052404923733651536/image.png">
  </a>

### Whois
  - 🔍 Get various information on a member of the discord server
  `Member+ Use Only`
  ```bash
  /whois {@member}
  ```
   
  <a href="https://cdn.discordapp.com/attachments/1028380505923670096/1052405193783914506/image.png" >
    <img src="https://cdn.discordapp.com/attachments/1028380505923670096/1052405193783914506/image.png">
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
  - ❗️ Get the bot to say anything on your behave.
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
  
  <a href="https://cdn.discordapp.com/attachments/1028380505923670096/1064101582066700288/image.png">
    <img src="https://cdn.discordapp.com/attachments/1028380505923670096/1064101582066700288/image.png">
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

  <a href="https://cdn.discordapp.com/attachments/1028380505923670096/1064095140999856168/BlueEyes.png" >
    <img src="https://cdn.discordapp.com/attachments/1028380505923670096/1064095140999856168/BlueEyes.png" width="200" height="200">
  </a>

ㅤㅤㅤㅤㅤ[**Volak**](https://github.com/Volak)

---
### License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/Volak/PrimeAfflictionBot/blob/main/LICENSE) file for details.


