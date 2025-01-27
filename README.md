# hivebot
hivetalk nostr bot - room announcer

[Deprecated] This Bot will poll the HiveTalk API every 15 min as a github action currently to do the following: 
- It will post a link to active rooms within the last hour on the nostr social media account as a kind 1 note.
- It will also append it to the log in this repository. 
- If the room has been posted in the last hour already it will not repost it so as not to spam the network.

## TODO -  Nostr
- Make a Kind 1 note should be revised and posted as live event, mirroring when 30311 live event is posted to hive relay
- This means: bot should poll hive relay fro 30311 live events and repost the start of event using the social account.
- optional: post that event has ended.



Bot and social account now consolidated on nostr, should post to 
https://njump.me/npub1z0lcg9p2v5nzg5fycxq0k56ze6snp42clmrafzqpn5w6u74v5x9q708ldk
