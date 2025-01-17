# Prime Affliction Bot

The official bot for [Prime Affliction](https://www.discord.gg/primeaffliction) discord server.

-----
  <a href="ignore/PrimeBanner.png" >
    <img src="ignore/PrimeBanner.png">
  </a>

-----
### Table of Content

* [Command List](#command-list)
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

  <a href="ignore/RecruitEmbed.png" >
    <img src="ignore/RecruitEmbed.png">
  </a>


### ServerInfo
  - ❓ Displays various information about the discord server
  `Member+ Use Only`
  ```bash
  /serverinfo
  ```
  
  <a href="ignore/ServerInfoEmbed.png" >
    <img src="ignore/ServerInfoEmbed.png">
  </a>

### Whois
  - 🔍 Get various information on a member of the discord server
  `Member+ Use Only`
  ```bash
  /whois {@member}
  ```
   
  <a href="ignore/UserInfoEmbed.png" >
    <img src="ignore/UserInfoEmbed.png">
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
  
  <a href="ignore/TimeStampEmbed.png">
    <img src="ignore/TimeStampEmbed.png">
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
### Author

  <a href="ignore/VolakPFP.png" >
    <img src="ignore/VolakPFP.png" width="200" height="200">
  </a>

ㅤㅤㅤㅤㅤ[**Volak**](https://github.com/Volak)

---
### License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/Volak/PrimeAfflictionBot/blob/main/LICENSE) file for details.


