---
cover: ../.gitbook/assets/2026-02-03_17.51.02.png
coverY: 279.30306505421186
---

# 💻 Commands

Chertia Requiem features custom commands that aim to improve roleplay and survival features. Here is an overview of player commands.

### 🧍 Characters

* `/create_character` - This command will put you in the character creator. You will be prompted to enter the details that you wrote in your approved character sheet.

### 💬 Chat & Communication

* `/chat` - This command is used to control various chat settings. The settings are as follows:
  * `/chat scope [gobal/local]` - adjust your default chat scope (global chat vs. local chat).
  * `/chat default_radius [number]` - adjust your default radius for local chat.
  * `/chat shout_radius [number]` - adjust your radius for shouting.
  * `/chat whisper_radius [number]` - adjust your radius for whispering.
  * `/chat localonly` - toggle only receiving local chat messages.
* `/afk` - This command is used to toggle your AFK (away-from-keyboard) status. The command sends a chat message notifying other players that you are currently AFK, but has no other functionality. Moving or sending a message will disable your AFK status. For longer periods of being AFK, please log out of the server.

### 🛡️ Survival

* `/giveitem` (alias `/gi`) - Entering this command and then right clicking another player will transfer your held item to the clicked player. It can be disabled by re-entering the command. This is an alternative to Minecraft's default method of 'throwing' items at another player.
* `/trade [player]` - Entering this command will request a trade with another player. You can then select items from your inventory and agree upon a fair trade. This works across distances and dimensions, and is an easy way to transfer & trade items between players.
* `/sit` - Entering this command will allow you to sit on any solid block. You can also sit on certain blocks (like stairs and slabs) by right-clicking them using an empty hand.
* `/crowns` - This command is used to interact with the server's virtual economy system.&#x20;
  * `/crowns balance` - view your current balance of Crowns.
  * `/crowns send [player] [number]` - send Crowns to another player.
  * /`crowns top` - view the Crowns leaderboard.
* `/submit-farm [description]` - Submit a farm for staff to review for approval.

### 🪶 Other

* `/skins` (alias `/s`) - This command is used to change your skin in-game. This is typically used to add different outfits or appearances for your character that you can change on-the-fly. Players are able to add 3 different skins; supporters can add 6.
  * `/skins add [name] [URL]` - add a skin to your available skins. Provide a short name to help you identify the skin, and a direct link to the skin image (.png).&#x20;
  * `/skins remove [name]` - remove a skin from your available skins.
  * `/skins set [name]` - set your skin to one of your saved skins.
  * `/skins reset` - reset your skin to your actual Minecraft skin.
* `/ping` - Entering this command will display your current ping to the server and the server's current performance levels. Higher ping means that there is more latency between you and the server and you may notice lag.
* `/cweather [clear/rain/thunder/reset]` - Change your client-side weather. Resets on join.
* `/note [list/view/add/remove/delete/edit]` - Interact with the notes system, which allows you to create and store personal notes. Only you can see these.
* `/fix-stacking` - If any items in your inventory will not stack together, use this command.
