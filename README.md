# YTBot
![Logo](https://github.com/borgej/YTBot/blob/master/github_docs/ytb_logo2.png "Logo")


Twitch bot C# MVC project based on TwitchLib https://github.com/TwitchLib/TwitchLib

This started out as a "fun" little project to try to make myself a Twitch.tv Chatbot.
It has now getting some serious functionality ;)

The plan is to finish "basis" functionality and host it for free for everyone that wants to use this.

Ps. 
* If anyone wants to join in on the project, please do! I'd love to get more heads in on this.
* Please dont snag my ClientId =P

## TODO's
* Optimize database calls
* Publish "giveaways closing" to chat
* Add items to Dashboard
* Style Chat Stat
* Add StreamLabs API functionality


## Requirements 
* .Net Framework 4.6.1
* Microsoft SQL Server Standard (64-bit) (Tested on version 13.0.1742.0)
* IIS (Tested on version 10.0.14393.0)

## Some screenshots
### Login
![Login screen](https://github.com/borgej/YTBot/blob/master/github_docs/login.PNG "Login screen")

### Logged in
![Logged in](https://github.com/borgej/YTBot/blob/master/github_docs/loggedin.PNG "Logged in")

### Dashboard
![Dashboard](https://github.com/borgej/YTBot/blob/master/github_docs/dashboard.PNG "Dashboard")

### Stream info
![Stream info](https://github.com/borgej/YTBot/blob/master/github_docs/streaminfo.PNG "Stream info")

### Songrequests
![Songrequests](https://github.com/borgej/YTBot/blob/master/github_docs/songrequests.png "Songrequests")

### Timers
![Timers](https://github.com/borgej/YTBot/blob/master/github_docs/timers.PNG "Timers")

### System triggers
![System triggers](https://github.com/borgej/YTBot/blob/master/github_docs/systemtriggers.PNG "System triggers")

## Functionality
1. Triggers
* User triggers with mod/subscriber/follower/viewer restrictions
2. Built in triggers containing:
* Games (Roulette, gamble, russian(roulette))
* Clip (Create a stream clip directly from chat)
* Loyalty points checking
* Channel stats (followers, subs)
* How long has user been a follower or sub
* Uptime (how long has the channel been streaming)
3. Loyalty points system
4. Dashboard
5. Stream info
* Set your title and game
6. Chat stats
* Most used commands
* Most active users
* Channel chat options (still not done)
* Channel chat log
* Timeout users using words in "bad-words"-list

7. Giveaway system
8. Songrequest system
* Adding and removing songs from YouTube either by link or name of video (search will enter first search hit)
* Mods can control play/stop/volume/next/prev if allowed.
9. Polls
10. Timers
* User timers that go off at given intervals.

