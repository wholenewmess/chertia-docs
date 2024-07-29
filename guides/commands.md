---
cover: ../.gitbook/assets/2024-05-28_22.01.55.png
coverY: 0
---

# 💻 Commands

This page will provide you with an overview of various commands on the server.

### 🗣️ Chat

For detailed information on the chat system, go [<mark style="color:blue;">here</mark>](chat.md).

* `/msg [player] [text]` - Send someone a private message.
* `/r [text]` - Reply to your last received message.
* `/me [text]` - Sends a message in chat with the format of your character performing an action. For example, "`/me jumps around`",
* `/radius <number>` - Sets the default chat radius for your messages when In Character.
* `/ic` or `/ooc` - Sets your chat mode to either In-Character or Out-Of-Character.
* `/afk` - Puts you in AFK mode. Moving will disable AFK mode.

### **🧙** Characters

* `/character create [name]` - Start the character creation process.
* `/character edit [element] [value]` - Edit an element of your character. Just doing `/character edit` will open the interactive editor.
  * Other elements include: `race`, `name`, `nickname`, `height`, `age`, `pronouns`.
  * Supporters can change the colour of their character card using `/character edit colour [hex code]`.
* `/character view [player]` - View someone's character card.
* `/character reset` - Reset your character. Staff member approval is required.

### 👕 Skins

* `/s add [name] [url]` - Adds a skin to your list of skins. Use Imgur for the URL of the image source.
* `/s remove [name]` - Removes a skin from your list of skins.
* `/s set [name]` - Changes your current skin.
* `/s reset` - Resets your skin to your normal Minecraft skin.

### 💵 Economy & Trading

* `/bal` - View your balance.
* `/pay [player] [amount]` - Sends crowns to another player.
* `/crowns top` - View the top 5 balances.
* `/trade [player]` - Starts a trade request with another player.
* `/lockdrop` - Toggles your ability to drop items.
* `/giveitem` - After running this, the next player you click on will receive your held item (the whole stack).

### 👥 Event-Only

* `/sw` - Teleport to the event location.
* `/home` - Teleport home.
* `/tpa [player]` - Send a teleport request to another player.

### 📝 Miscellaneous

* `/note add [name] [text]` - Creates a note with the provided name and text.
* `/note view [name]` - View a specific notes.
* `/note delete [name]` - Delete a specific note.
* `/notes` - View an overview of all your notes.
* `/report [text]` - Sends a message to the staff team with your username, location, and provided description. Report bugs or rule violations using this command.
* `/submit-farm [text]` - Forwards your current location and the text to staff so they can review and approve the concept / prototype of your farm.
