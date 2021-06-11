# DevOpsAssignment  
DevOps Assignment with reference to KeYule Repo;   
Credits to: https://github.com/keyule/Telegram-Bot-for-Bots  (https://t.me/BotsSGBot)  

In this case, I will be using a chatbot that saves and return inputs.  

https://t.me/nusprojectbot

![SS](https://user-images.githubusercontent.com/75791753/121622155-145ab880-caa0-11eb-8abd-745bd3bac432.png)

Overview

Idea is to create a simple telegram bot that saves and returns inputs. Applications for the bot can be to save notes, or a simple to-do list.  

Process includes  

-Creating a Telegram bot using t.me/botfather  

-Using web browser to check activity of Bot  
  Basic Info of Bot: https://api.telegram.org/botXXX/getme  
  Retrieve msg to sent to Bot: https://api.telegram.org/botXXX>/getUpdate  
  Sending msg from Bot: https://api.telegram.org/botXXX/sendMessage?chat_id=<chat-id>&text=TestReply  
  
-Set up Python  
  Install libraries: pip3 install request  
  To check pip verison: pip --version  
  List of pip functions: pip help  
 
 -Python code (Base): Echo function  
 -Import libraries to include emoticons:  
    -import urllib  
    
