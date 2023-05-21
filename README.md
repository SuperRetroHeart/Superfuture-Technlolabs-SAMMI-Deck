# Superfuture Technolabs SAMMI Examples
This is a collection of buttons and automations for [SAMMI](https://github.com/SAMMISolutions/SAMMI-Official/releases) named (loosely) after the theming of my livestreams. Most buttons are geared towards Twitch specifically, though many of them can be adapted to work with YouTube via adjusting the triggers in SAMMI. Most are designed for automation, such as when you get a new follower.

## Importing a Button Into SAMMI
It's a two-step process:

1.) Copy the raw text from JSON for a given button, including the opening and closing {curly braces}.
2.) Open a deck in SAMMI, right click on an open space, and select "Import From JSON".

## Twitch Buttons (API / SAMMI)
[Due to Twitch depreciating slash commands via IRC in February 2023](https://discuss.dev.twitch.tv/t/deprecation-of-chat-commands-through-irc/40486), there may be buttons that use API calls. While SAMMI has covered most API implimentations via built-in commands (such as the **Twitch: Send Announcement** command), some buttons may include API calls for added flexibility or for features that haven't been replicated in built-in SAMMI commands.

### Alerts
While these examples were built with Twitch in mind and in turn use Twitch commands and triggers, they can be converted to YouTube alerts by changing certain commands and trigger types in SAMMI. Alerts and other notifications are fun ways to kit out your stream regardless of what platform you stream to. Keep in mind that these are primarily meant to be inspiration for you to make your own alerts, not "out of the box" solutions. You can drop your own sources in to get a feel for how they work, but it's more how the cookies are made rather than the cookies themselves.
Now, did I ever tell you about how I started making my own alerts because all the info I could find in SAMMI about displaying a random image was about twerking Thanos GIFs wait where are you going come back

### Misc
Various bits and pieces that don't fit elsewhere, like tracking a specific number or subscriber goals and other fun things you can do.

### Moderation
Various tools, mostly automatons, to help with moderating Twitch chat. That includes issuing automatic bans for specific phrases.

### Toolkit
Buttons that don't do anything on their own, but are useful building blocks to create other kinds of buttons. Weighted arrays, dice rollers, data pulls, and the like.

### Twitch
Twitch-specific automations and buttons, typically related to Twitch chat or Twitch-exclusive features.

## Extra Notes
### "Bot" accounts and "Join chat under this name" in SAMMI
Buttons with a Twitch API include mention of a "bot" account. There are a couple of different ways bots can work on Twitch; in SAMMI's case, this is a separate account that you've previously set up and connected to SAMMI that you're sending instructons to. I **strongly recommend** that you run API commands via your own account unless you already have an account set up for this purpose.

Buttons using SAMMI commands, in turn, will send messages and announcements based on which account is set as "Join chat under this name" in Twitch Connections. This is selectable at the bottom of the SAMMI Core window. These should be fine for the majority of folks who need automations That Just Work without too much fuss.

## Twitch Decks
There aren't any here yet, but when I do add them, they'll be for more complex actions that can't be contained in a single button.
