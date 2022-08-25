# Aura-alert
## How to set up a bot for Aura Node

1 step. 
api token (you can use @FatherBot in telegram)
chat id (@getmyid_bot)

2 step. 
```
curl -s https://raw.githubusercontent.com/goto5k/Aura-alert/main/setup.sh > setup.sh && chmod +x setup.sh && ./setup.sh
```
3 step. 

```
*/1 * * * *  /bin/bash $HOME/alerts/tg-bot.sh
```
