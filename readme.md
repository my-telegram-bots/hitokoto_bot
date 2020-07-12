# hitokoto_bot (cloudflare workers version)

This bot is an attempt to run on cloudflare workers, you can edit the function domessage and doinline to easily create your own bot.  

So workers.js can't use in nodejs directly because without web server, fetch function and need some edit)

![demo](/img/demo-1.jpeg)

# Tutorial
1. You must have a domain hosted in the cloudflare
(Telegtam bot's server can't request xxx.xxx.workers.dev url)  
2. Go to ask t.me/botfather that he can tell you some infomation about your bot(token)
3. Create a worker in cloudflare and paste workers.js
4. Use the information above to edit the first 3 lines
5. Set workers route like this ![image](/img/workers_setup_custon_domain.jpeg)
6. set your bot's webhook (browser or curl)
    
    https://api.telegram.org/bot[token]/setwebhook?url=[step3_3]
7. Enjoy yourself and do some magic edit to build you own bot ~


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