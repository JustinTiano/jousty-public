---
title: Jousty
---

# Jousty ⚔️

**The Discord bot for [The Joust](https://store.steampowered.com/app/4744160/The_Joust/?utm_source=jousty&utm_medium=web&utm_campaign=landing-page).**
Bring The Joust's lobbies, leaderboards, patch notes and social posts into your server.

## [➕ Add Jousty to your server](https://discord.com/oauth2/authorize?client_id=1513354263214952599&permissions=2251800082205696&integration_type=0&scope=bot+applications.commands)

## What it does

- **Looking for group:** when a player shares a public lobby from The Joust, Jousty posts it in
  your LFG channel with a **Join game** button and pings the members who opted in. The post
  disappears when the invite expires.
- **Live leaderboards:** one big board that stays put, a picture per game mode with every
  leaderboard's top 5 for today and yesterday's champion, updated live, with an alert when
  someone takes #1 and a champions post after the 8 PM reset.
- **Game updates:** The Joust's news and patch notes from Steam, posted in the channel you pick,
  with an optional role ping.
- **Socials:** The Joust's new YouTube videos and Shorts, and the posts its team shares from
  Instagram, X and TikTok, in the channel you pick, with an optional role ping.
- **Opt-in pings:** a 🔔 button lets members choose whether they get pinged for lobbies and #1s.
  Nobody is pinged unless they opted in.

## Setting it up

1. Add Jousty with the link above.
2. Run `/lfg-setup` and pick the channel for lobbies (Jousty creates the ping role and the 🔔
   panel).
3. Run `/leaderboard-setup` and pick the channel for the leaderboard, and optionally a separate
   channel for #1 alerts.
4. Run `/announce-setup` and pick the channel for The Joust's patch notes and Jousty's own update
   notes, and optionally a role to ping. The latest patch notes show up right away. `steam:False`
   or `jousty:False` leaves one out, and `/announce-setup off:True` stops them.
5. Run `/social-setup` and pick the channel for The Joust's social posts, and optionally a role to
   ping. The latest one shows up right away. `/social-setup off:True` stops them.

The setup commands are for people with **Manage Server**. Anyone can use `/leaderboard` to see a
board's top 10, privately.

## Help

Questions or problems: [join the Jousty support server](https://discord.gg/d4Bsa4Qkb).

[Terms of Service](terms) · [Privacy Policy](privacy)

<small>Emoji on the leaderboard pictures: [Twemoji](https://github.com/jdecked/twemoji), CC-BY 4.0.</small>
