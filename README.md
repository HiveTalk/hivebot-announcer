# hivebot
hivetalk nostr bot - room announcer

## [Deprecated] - Existing code in this repo is deprecated. 

```
This Bot will poll the HiveTalk API every 15 min as a github action currently to do the following: 
- It will post a link to active rooms within the last hour on the nostr social media account as a kind 1 note.
- It will also append it to the log in this repository. 
- If the room has been posted in the last hour already it will not repost it so as not to spam the network.
```

## TODO -  Nostr
  Make a new nostr bot post a Nostr Kind 1 note when a live event happens. The idea is to make a simple bot to mirror when 30311 live events posted to hive relay to the hive nostr social account. See Issue for more details. 


Bot and social account now consolidated on nostr, should post to 
https://njump.me/npub1z0lcg9p2v5nzg5fycxq0k56ze6snp42clmrafzqpn5w6u74v5x9q708ldk
