# 08/04/26  
<sup><sup>yesterday i could now add anything due to re-ordering project files and rewriting prompts, bot should be quicker, smarter and more efficient<sup><sup>  

ive been working... alot  
ive made websearch test better (moved from ddgs to compound-mini)  
ive been adding prompts and adding functionality to change personalities,   
ive made modular personalities  
ive made more dev cmds (give/remove premium, remove mute, see mutes persons...)  
ive fixed like dozen bugs caused by yesterdays reorder  

# 06/04/26  
added dev.test commands, used for testing possible future features    
added dev.del cmd that deletes message sent by bot, usually used on testing  
added user.regen cmd that regenerates bot message  
added blackjack, you can use it by saying bj in dm or channel where bot is  
now if you type `//` on front of a message it is completely ingored by bot always  
fixed bug #0007

# 05/04/26  
added filters cause they are clearly required  
added remote mute and remote kick that only developer can do incase if there are clear repeating offenses  
created changelog  
fixed bugs #0003, #0004, #0005 and #0006  
added dev.test command, this is used by developers for testing, it can logs what is send to groq on current channel/dm ONLY and expires after 5 minutes, and can be used to make bot say anything for testing filters  
added remote mute, allowing to mute specific userid for specified amounth of seconds  

# 04/04/26  
i added logs, and refined personality  
*logs do not save any senstive useless information, such as usernames, messages or invite links*  
also added github page for it and added dev commands, mod commands and user commands  
added welcome message  
and added anti spam   

# 03/04/26  
created the bot
it first used pywright and gemini on browser  
later i moved it to cloud and groq  llama70B  
it got rate limited and i switched to 8B  and reduced context from 50 msg to 7 msg for privacy and model heavyness reasons
