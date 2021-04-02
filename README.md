


![Build Status](https://travis-ci.com/Saiprasad16/discord-bot.png?branch=master)



```shell
docker image build -t ubuntu:dbot .
```

## Example manual build
``` shell
docker image build -t bradmorg/ubuntu:dbot /home/pi/discord-bot
docker push bradmorg/ubuntu:dbot 
docker stop discordbot 
docker rm discordbot
docker run --name discordbot --restart always -d -e TOKEN=$TOKEN bradmorg/ubuntu:dbot
```
