# 22/06/26 
- refined ui even more
- fixed bug where if you pinged bot before saying command, it did not register as command
- - bot now should be able to use text based commands no matter do you ping or not, and where you ping

# 21/06/26
- refined ui
- added memory
- increased bot context history
- - 7 past messages -> 100 past messages
- - 4096 input tokens -> 16384 input tokens
- - 512 output tokens -> 2048 output tokens

# 30/05/26
- made dumfack a real [bot](https://discord.com/oauth2/authorize?client_id=1510277216242766084)  
- remade old dumfack selfbot to dumfack lite
- switched from Gemini 3.1 Flash Lite multi modal image description llama-4-scout-17b-16e-instruct
- made bot send multiple messages at once to feel more human
- added slash commands
- added typing animation and realistic humane stops
- removed number and hard-coded word filters

# 27/05/26 (possibly wrong date)  
- done some prompt engineering to dumfack (it now can help with commands and knows info about its dev)  
- done lots of testing  

# 26/05/26 (possibly wrong date)  
- tested dumfack with gemini model  
- made dumfack temporalily use Gemini 3.1 Flash Lite for testing  

# 30/04/26
- basically rewrote entire [website](https://dumfack.brotabrr.workers.dev/)...  
- updated ui... alot  
- - now has outline on personalities, color depends from status (premium, free, dev). 
- - chats now show latest message
- - added branching stuff
- - added settings
- - added alot of animations
- added experiements, these are toggles you can switch to try possible future features  
- - these include chat formatting, edit msg, images, msg tree and temp slider  
- - (theres lots of bugs still, some are either permanently on or off. sorry)  
- added settings... yay
- - you can now recover deleted chats, change cooldown between letters that ai sends, toggle experiements 
- added chat branching, you can now go to anywhere on chat you want, every time you regen, edit, or somehow manipualate chat it makes new timeline
- - IF YOU CANNOT ACCESS YOUR OLD CHATS, THEY ARE NOT DELETED, JUST UNAVAILABLE TEMPORALLY!! WILL BE FIXED SOON
- basically rewrote half of ui and code...

# 27/04/26
- added regen button to [website](https://dumfack.brotabrr.workers.dev/) 
- added personality configurations to [website](https://dumfack.brotabrr.workers.dev/) 
- added dev test for 70B model
- more coming soon...

# 22/04/26
im sorry, no updates for nearly 2 weeks, this is cause of multiple reasons:  
- i worked few days on [website](https://dumfack.brotabrr.workers.dev/)  
- i got school  
- my family got very sick recently
- i kinda lost motivation cuz no one really used my bot and it was just quick niche (if it gets usage i will update it tho)

# 10/04/26
finished re-ordering and rewriting prompts   
bots prompts now use ~15% less tokens  
made personalities free for everyone and some premium  
fixed multiple bugs, both old and ones made during developement builds (i did not keep track of dev bugs)  
added dev test for TTS and picture recognition   
added premium test, premium users now can send images and have extra personalities  

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
