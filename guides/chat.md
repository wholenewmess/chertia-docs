# 💬 Chat

Chertia features a custom chat system. This page will help you understand how the system works.

### 🪶 Chat Modes

* **In-character (ic)** chat is the default. You can switch to it with the command `/chat mode ic`. In in-character chat, your messages will have a reach radius. By default, this radius is 30 and can be changed with `/chat radius [number of blocks]`. This means that only others within that radius will be able to receive your messages.
* **Out-of-character (ooc)** chat can be selected with `/chat mode ooc`. All messages will automatically be sent with parantheses.

At any time, you can switch between these modes per-message. By starting your message with a quotation, it will be an in-character message. By starting it with an opening parenthesis, it will be an out-of-character message.

### ＠ Modifiers

You can modify your chat using @X where X is a letter or number. A modifier can be placed anywhere in your message, but should be followed by a space if not placed at the end of a message (ex. "@50 Hello!"). Here are some examples of modifiers.

* `@50` will modify your message so only those in a 50-block radius will receive it.
* `@whisper` or `@w` will modify your message to become a "whisper", and only those in a 5-block radius will receive it.
* `@shout` or `@s` will modify your message to become a "shout", and those in a 100-block radius will receive it.
* `@transmit` or `@t` will modify your message to become a "transmission". These are in-character messages that will be received globally.
* `@global` or `@g` will modify your message to become a global out-of-character message.
