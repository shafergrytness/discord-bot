# Discord-Bot-for-Twitch
Also includes our website files. This project uses [PandaScore](https://developers.pandascore.co/) and [Discord's API](https://discordapp.com/developers/docs/intro) to post stream statuses and notifications for Twitch.tv as well as upcoming tournament matches in Discord. 

Notifications are set to check every 5 minutes by default (edit this delay in Notification.cs) and you may want to create a separate text channel in Discord if streams.txt becomes long.

## Command List

### !echo (string)
repeats anything user inputs
### !live (streamname)
checks twitch if user-input streamer is online and returns a link to that stream
### !upcoming (lol / ow / dota2)
returns 4 upcoming matches for input game
### !notification (enable)
sends a notification whenever a stream goes live*

*Edit the list of streams using streams.txt

## Screenshots

Bot usage

![alt text](https://github.com/shafergrytness/Discord-Bot-for-Twitch/blob/master/Screenshots/07-large.jpg "Notification command")

![alt text](https://github.com/shafergrytness/Discord-Bot-for-Twitch/blob/master/Screenshots/05-large.jpg "Upcoming command")

![alt text](https://github.com/shafergrytness/Discord-Bot-for-Twitch/blob/master/Screenshots/03-large.jpg "Live command")

Website

![alt text](https://github.com/shafergrytness/Discord-Bot-for-Twitch/blob/master/Screenshots/website.png "Website")
