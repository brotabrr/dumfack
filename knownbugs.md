## High Priority 
### if there are any major High Priority bugs the bot might stay down until they are fixed, usually takes hours - day     
---  
~~**#0006 bot can swear if you make your name something offensive and it replies to you**~~
- example: naming yourself N-Word and replying to bot makes it say your display name (N-Word)
- first noticed: 05/04/26  
- fixed: 05/04/26  
- workaround: Do not use offensive names  
- why: likely because the bot does only filter messages, not usernames. likely caused by rushed filtering, im sorry  

~~**#0005 filters check every message for anything offensive, even if it was not pinged**~~
- example: someone sends gif on server, bot says "*Sorry, I can't talk about or use any numbers right now.*"
- first noticed: 05/04/26
- fixed: 05/04/26
- workaround: avoid saying anything offensive in server at all, currently this bypasses mod.config and is nearly impossible to avoid, only fix would be to make bot only be able to chat in specific channels with roles
- why: this is likely because of rushed filters, im sorry

## Medium Priority  
### Medium Priority bugs are fixed if there is nothing else to add/fix, fixing might take few days to week  
---
**#0007 bot responds in every channel despite configurations**
- example: self explanatory
- first noticed: 05/04/26
- fixed: NaN
- workaround: NaN
- why: i honestly have no idea, i guess it might be cause of new logic made to allow bot seeing own messages in dm

~~**#0004 bot says "*Sorry, I can't talk about or use any numbers right now.*" even if theres no clear numbers**~~  
- example: user sends a tenor gif, and bot replies whit   "*Sorry, I can't talk about or use any numbers right now.*"  
- first noticed: 04/04/26  
- fixed: 05/04/26  
- workaround: avoid sending any gifs or any custom emojis/stickers or mentioning anyone  
- why: every tenor gif link has number at end of it, the bot does not see the gif but insteat the link. and every custom emoji and sticker has ID that contains numbers  

~~**#0003 bots own messages do not get sent as context in dm**~~
- example: user says something (eg "*hey how are you doing*"), bot replies and asks question (eg "*...do you want to see my dog?*"), user replies like if bot can read own messages (eg "*yeah sure!*"), bot replies whitout seeing own message about dog (eg "*hey im doing well...*")  
- first noticed: 04/04/26
- fixed: 05/04/26
- workaround: Always give your own context from bot message, (eg :"*i would love to see your dog...*")   
- why: i dont know, but i think its caused by dm logic, where you do not have to ping the bot to talk whit it  

## Low Priority  
### Low Priority bugs are usually not fixed for while, from weeks to few months, Low Priority bugs usually do not cause any harm or annoyance or are very easy to avoid   
---
**#0002 if you misspell bot command it says you dont have permission to use commands**  
- example: you say `dumfack mod.setup #general` insteat of `dumfack mod.setup.add #general`  
- first noticed: 04/04/26  
- fixed: NaN
- workaround: check did you spell correctly, you can see correct spelling by mentioning/replying bot and saying `mod.info`
- why: this is because of very simple if/then on code, if for any reason the command cannot be done it says "*You don't have permission to use mod commands.*"  

**#0001 bot replies to other bots dms**  
- example: bot gets warning from server, Dyno dms the bot, bot ansawers whit "*hey whats up XD*"  
- first noticed: 03/04/26  
- fixed: NaN  
- workaround: NaN  
- why: because bot does not distinguish bot from user   
