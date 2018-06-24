# About

## Introduction

GmodHQ project focuses on professionalism which is lacking in the Garry's Mod community. 
Our vision is to create a server network with staff that are actually helpful and fair. 
There's way too many abusive and selfish server owners out there.

Our end goal is to be running a server for all of the most popular gamemodes on Garry's Mod. 
We're starting off with Sandbox, DarkRP, GoFish and Stronghold servers. Donor and staff ranks are synced between all of the servers. 
Buy one rank, get perks on all of the current and future GmodHQ servers. 
We don't believe having pay to win perks is a good idea, you will never see us sell staff ranks (like some servers do) or any other perks with huge advantages over other players. 
Our priority is server stability and staff quality before anything else. Custom content will be developed once we have control over those both priorities first. 
However, we're starting off with custom pages for user profiles, leaderboards and donations which can be found at GmodHQ.com.

## But why?
This may seem like another generic gmod server out in the wild, which it partly is with a big focus on server stability and staff quality. 
It's easy finding a gmod server to play on. Finding a server with quality staff is next to impossible. Corruption among staff is always going to be there no matter what. 
The amount of work put into reducing it is what matters the most. The majority of servers punish their users for every little thing, punishing should be the last resort. 
Owners should design their servers in a way users aren't able to break rules in the first place. There's no perfect way of doing that, but most server owners don't even try.

## Technical details
Each GmodHQ game server and service is running inside of docker containers. Services include things such as nginx, reverse proxies, forums, jenkins, git, mysql and so on. 
All of the game server files are located on git so every change is being tracked. Big changes are always tested on dev branch before being merged to master. 
Once a change is made, jenkins is triggered to build and replace server container with the new one automatically.

This kind of setup is very flexible and compatible with most dedicated or virtual servers no matter OS. 
GmodHQ backs up all of our server data daily, backups are encrypted before leaving the dedi to be stored on the cloud. 
A week's worth of backups are always kept on server locally. Backups are also downloaded to offline hard drives from time to time. 
Our next step is making our setup compatible with kubernetes, but that's in the far future. The setup is a overkill for Garry's Mod servers, but it has its benefits in the long run.

## Personal background
I feel like knowing the owner a bit more tells more about the server than any generic server description. I have been running servers since I was around 14 years old (currently 22). 
My first ever dedicated server was GoFish on gmod, it actually peaked at 30/30 players. From there I moved on to minecraft, which exploded and peaked at 1200 players online. 
That server is actually still running on CowCraft.net for mostly nostalgic purposes. It's long dead with few dedicated players still playing. 
I have made many mistakes and bad decisions, I only mentioned successful projects. There were countless servers before them. The most important part is to learn from mistakes and do better next time.

One of the biggest reasons why I am launching GmodHQ is passion and nostalgia for Garry's Mod. As long as donations cover server and developer costs, I'm happy. 
I hate servers with abusive staff and pay to win perks with only goal of making as much money as possible. But that's the current state of the majority of gmod servers.