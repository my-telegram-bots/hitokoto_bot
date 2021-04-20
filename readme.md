important alert: Cloudflare workers free plan only run script 10ms, So only simple message handling functions can be done.


# hitokoto_bot (cloudflare workers version)
This bot is an attempt to run on cloudflare workers, you can edit the function handlemessage and handleinline to easily create your own bot.   
You can use `starter.js` to create the bot you own quickly.  


![demo](/img/demo-1.jpeg)

# Tutorial
1. Go to ask t.me/botfather that he can tell you some infomation about your bot(token)
2. Create a worker in cloudflare and paste hitokoto_bot.js
3. Use the information above to edit the first 3 lines
4. set your bot's webhook (browser or curl)
    
    curl https://api.telegram.org/bot[token]/setwebhook?url=[workersurl]
    workersurl: ![webhook_url.jpg](/img/webhook_url.jpg)
5. Enjoy yourself and do some magic edit to build you own bot ~
If you still have problems you can create a issue, I can help you.

# Docments
1. [Cloudflare workers](https://developers.cloudflare.com/workers/)
2. [Telegram bots](https://core.telegram.org/bots/api)

# Thanks
1. hitokoto local data https://github.com/kokororin/hitokoto
2. seed-shuffle https://github.com/yixizhang/seed-shuffle/
3. cloudflare
## License
MIT
## Made with ♥