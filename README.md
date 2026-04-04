# Gemini Self Bot  
  
## usage  

**so how do i get it?**   
theres few options   
1 send it a friend request on discord (brotabrr.dev.gemini)  
2 join my [server](https://discord.gg/SG8STWeHaw) and try it out in geminis own channel  
3 use it on any server where it is in aready  
4 add it to your own server, dm it the invite link and wait for it to join! 

   
**how do i use it?**  
its very simple, DM it, Reply to its message or ping it on any server it is on and has permission to chat  
     
**thats it?**  
basically yeah!  
theres few commands tho but you likely wont need them much  
you can view them by pinging the bot and saying `mod.info` or `user.info`  
also the bot replies to every message where it got replied or pinged, aslong as it has chat permission.   
be aware of it might getting muted due to spamming if its used actively  

## FAQ  
**why is it "gemini" if it dont run whit gemini?**  
it originally ran whit gemini using playwright but it had alot errors and was very slow,  
then after some while i swapped to groq whit llama 70B,  
it got rate limited in few hours and cost 3 whole cents, after that i switched to llama 8B and added anti spam  

**does it spy on me?**  
nah, the ai dont save any messages nor sends them anywhere  
only time when its send somewhere is if you do report or suggestion command  

**why is it so dumb?**  
i honestly dont know, its very dumb considering its 8B model  
it might be cause its not designed to be on discord and its unsure of who its talking to, who replied to who and it only has context window of 7 messages.  
  
**is it free?**  
YES! its completely free for everyone whit basically infinite messages  
im thinking about adding paid tier someday tho, but its not yet! the paid tier might have better model (70B), but dont worry! it will still stay free for everyone  
tho heads-up! if it gets alot of requests and gets rate limited often i might add there message limit  
  
**what can i do whit it?**  
anything you want, but dont be too rude or do anything illegal cuz discord might not like it  
its mostly used for shit and giggles currently  
dont say it anything that you wouldnt say to FBI or your own mother!  

## trouble shooting  
**no ansawer at all**  
theres few possible reasons  
1 server is down  
--fix: wait sometime, from few minutes to few hours  
  
2 youre on channel where bot doesnt have permission to chat  
--fix: switch to channel where bot has been configured and has send message permission  
  
3 the bot has been muted by moderator
--fix: ask moderators why its muted / unmute it if youre mod

**"Sorry, Groq had an error. Try again later."**  
the api got rate limited, please dont use the bot for few minutes  
if it lasts for long time contact dev (yourlocalaipotato)  

**"You don't have permission to use mod commands." even when im mod**  
1 you might are not mod  
2 you misspelled command, make absolutely sure that its 100% correctly spelled  
<sup>this happens because of very simple if/then, if you have no permission to use or if its invalid then it thinks you have no permission</sup>  
  
**the bot wont join server**  
it takes sometime to join, and the bot may decline joining if it thinks its for personal gain, eg J4J or invite rewards  

**the bot thinks that they/someone is someone else**  
this is normal, it hapens because  its not meant for discord and past conversation is translated roughly to keep bot free and fast for everyone
