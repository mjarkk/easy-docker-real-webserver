# My docker lemp config
My full docker LEMP stack (Linux, Nginx, MySQL, PHP)  
This is a fully working lemp server with all the PHP extensions you might need  
This also has some other programs installed like [FFMPEG](https://www.ffmpeg.org/), [graphicsmagick](http://www.graphicsmagick.org/), [MailDev](https://github.com/djfarrelly/MailDev) and a view others programs that a PHP server just needs  

## Install
- Install [docker](https://docs.docker.com/install/) and [docker-compose](https://docs.docker.com/compose/install/)
- Clone this repo and open a terminal inside the cloned folder
- `./rebuild.sh`

## BUGS
- This docker config will not work on windows
- PHP scripts does sometimes not have the write to exsecute, create, remove. **Fix**: `chmod 777 html -R`
