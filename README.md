# SuperSkripts
## Elevate your Minecraft server using this pack of skripts and avoid the hassle of installing bloated plugins that slow your server performance<br><br>⚠️ All scripts in this pack require [Skript](https://github.com/SkriptLang/Skript) to run.

# Scripts included in the pack:

## join.sk
### Playtime Tracker

Track and display player login times and stats using UUIDs.

**Commands:**

* `/joindate` (or `/jd`) `[<player>]`: See when you or another player first joined the server.
* `/lastjoin` (or `/lj`) `[<player>]`: See the exact time you or another player last logged in.
* `/playtime` (or `/pt`) `[<player>]`: Check total time spent on the server.

---

## tab.sk
### Custom Tablist

A clean server info tablist with an automatic AFK status manager.

**Features:**
* **Dynamic Tablist:** Displays real-time player ping, server TPS, and online player counts.
* **Auto-AFK Detection:** Automatically marks a player as AFK if they stand completely still.

**Commands:**

* `/afk`: Manually mark yourself as away and change your tablist prefix.

---

## party.sk
### Player Party System

Let players form groups, use private chat, and play together on the server.

**Features:**
* **Interactive Help Menu:** Hoverable text and clickable shortcuts make the help menu easy to use.
* **Party Chat & Toggle:** A private chat room for your group, plus a toggle (`/party chat toggle`) to automatically send all your text straight to the party.
* **Session Cleanup:** Automatically closes the party if the host logs out, and cleans up old data.

**Commands:**

* `/party` (or `/p`) `help`: Help menu.
* `/party` `create`: Start a party and become the leader.
* `/party` `invite <player>`: Invite someone to your party.
* `/party` `accept <player>`: Join a party you were invited to.
* `/party` `leave`: Leave your current party.
* `/party` `info`: See your party leader and how many members are in the group.
* `/party` `promote <player>`: Make someone else the party leader.
* `/party` `kick <player>`: Kick a player out of the party.
* `/party` `chat <message>`: Send a quick message to your party.
* `/party` `chat toggle`: Toggle whether all your regular chat messages go to the party.

---

## msg.sk
### Private Messaging

A quick and lightweight whisper and reply system.

**Features:**
* **Easy Replies:** Saves who you were talking to so you can reply quickly without typing full names over and over.
* **Safety Checks:** Stops players from trying to message themselves.

**Commands:**

* `/msg` (or `/message`) `<player> <message>`: Whisper another online player.
* `/reply` (or `/r`) `<message>`: Quickly reply to the last person who messaged you.

---

## mail.sk
### Offline Mailbox

Send messages to any player on the server, even if they are currently offline.

**Features:**
* **Hoverable Help Interface:** Helpful hovers and text shortcuts to navigate the mail commands.
* **Inbox Reminders:** Alerts players about unread messages right when they log into the server.

**Commands:**

* `/mail help`: Help menu.
* `/mail check`: See how many messages are in your inbox.
* `/mail check all`: Read your whole inbox at once.
* `/mail check <number>`: Read a single specific message.
* `/mail send <player> <message>`: Drop a message into a player's mailbox.
* `/mail clear`: Wipe your entire mailbox.
* `/mail clear <number>`: Delete one specific message.
