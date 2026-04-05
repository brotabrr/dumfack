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
