# CatDueller

A glorified duckdueller skid

![1](/images/gui.png)

## Usage

- Download the release ending in "-clean.jar" and put it into your mods folder
- Open GUI with right control
- Start the bot with semicolon

## Description

A skid of hypixel duels bot [duckdueller](https://github.com/HumanDuck23/DuckDuellerKT) made by randoms who know fuck all about minecraft modding or programming in general and yet ask $30 for it.
The release is not even obfuscated, most of the project is just untouched duckdueller and not to mention it has laughable auth. So laughable in fact that a toddler could remove it.
Have fun using the clean version if you are a weirdo who bots hypixel duels in 2026.

## Tracking users

**(everything listed below has been removed from the clean version for obvious reasons)**

When I was removing whatever auth this dogshit had I stumbled upon this funny scene

![1](/images/tracking.png)

For some reason whoever the fuck made this shit decided that the $30 you give for it is not enough, and they also want to track your games.

And it would not surprise anyone that this (now down) webhook belongs to a private channel in the devs discord server called "duels-logs-1".

````json
{
  "application_id": null,
  "avatar": null,
  "channel_id": "1455786095806513344",
  "guild_id": "1359887726157238532",
  "id": "1455787210220634258",
  "name": "duels-logs-1",
  "type": 1,
  "token": "9ucoU6rTXrVC_pRZ9xy0Ty99vS2B9TDOj8aBF5gz_8nP9RPuUnGhfgEcDNQxqsJoKJpY",
  "url": "https://discord.com/api/webhooks/1455787210220634258/9ucoU6rTXrVC_pRZ9xy0Ty99vS2B9TDOj8aBF5gz_8nP9RPuUnGhfgEcDNQxqsJoKJpY"
}
````

Though it is weird that in this case they use a webhook message to log your wins/losses but does not mean they are not also using their irc for tracking.
There is a setting toggled on by default that sends all your queues to their websocket for dodging other users, but it could also be used to spy on your queues as well.