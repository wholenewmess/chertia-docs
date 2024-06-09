---
coverY: 0
---

# 💬 Chat System

Chertia features a custom chat system. This page will help you understand how the system works.

### 🪶 Chat Modes

* **In-character (ic)** chat is the default. You can switch to it with the command `/chat mode ic`. In in-character chat, your messages will have a reach radius. By default, this radius is 30 and can be changed with `/chat radius [number of blocks]`. This means that only others within that radius will be able to receive your messages.
* **Out-of-character (ooc)** chat can be selected with `/chat mode ooc`. All messages will automatically be sent with parantheses. Additionally, these OOC messages will default to being global.
* **Local-only** mode can be set regardless of ic or ooc chat mode. Use `/chat local-only true/false` to change it. In this mode, you will only receive local chat. Be aware that you can still send global chat messages in this mode.

At any time, you can switch between these modes per-message. By starting your message with a quotation, it will be an in-character message. By starting it with an opening parenthesis, it will be an out-of-character message.

### ⬆️ Responding & Messaging

You can click on a player/character's name in chat to message them. By clicking on the content of the message itself, you can directly respond to it. After clicking, type your response to the message and hit send, and others will see an arrow in your message. Hovering over the arrow will reveal the contents of the original message.

### ＠ Modifiers

You can modify your chat using @X where X is a letter or number. A modifier can be placed anywhere in your message, but should be followed by a space if not placed at the end of a message (ex. "@50 Hello!"). Here are some examples of modifiers.

* `@50` will modify your message so only those in a 50-block radius will receive it. You can put any number between 1 and 100 in as the radius.
* `@whisper` or `@w` will modify your message to become a "whisper", and only those in a 5-block radius will receive it.
* `@shout` or `@s` will modify your message to become a "shout", and those in a 100-block radius will receive it.
* `@transmit` or `@t` will modify your message to become a "transmission". These are in-character messages that will be received globally.
* `@global` or `@g` will modify your message to become a global out-of-character message.

### Examples

Here are a few examples of how these modifiers work:

```
Person A and B are RP-ing, in IC mode.
What they write:                   What appears in Chat:
A: Yeah, like that!                A: Yeah, like that! (30)
B: (lmao)                          B: (lmao) (30)
A: @g come see B do handstands     A: (come see B do handstands)
B: @shout I'm doing it!!           B: I'm doing it!! (100)
C: @t Someone help at x y z!!      C: [⚡] Someone help at x y z!!
```

```
Person A is in OOC mode, near Person B.
What they write:                   What appears in Chat:
A: wb                              A: (wb)
A: hey B can you get me a log @30  A: (hey B can you get me a log) (30)
```
