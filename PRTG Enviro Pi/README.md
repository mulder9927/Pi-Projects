Environment monitor uses the enviroweb service to piggyback info from please make sure you install the enviropiweb app from here 

https://github.com/nophead/EnviroPlusWeb

once that is done place the file Enviro+prtg.py into the EnviropiWeb folder in /etc and put the service file in /etc/systemd/system and run sudo asystemctl enable prtgenviro.service then run the service and boom should work. 