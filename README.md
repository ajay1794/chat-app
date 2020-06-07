# chat-app
Specifications required:
#all libraries can be installed through PIP
1. Django 3.0.3
2. channels 2.4.0
3.channels-redis 2.4.2
#you need to manually download redis server(version3.0+) and open it to make this work:

link: https://github.com/microsoftarchive/redis/releases

download latest version (prefer zip file) and open redis-server.exe
then open the Project

NOTE: after running the "py manage.py runserver" command go to http://127.0.0.1:8000/chat to choose chat room

* enter any name of chatroom you want  and open another browser window and open the same link there and type exact same name of chat room there.
* Now type anything in the sendbox and press enter. It will appear in both windows.
Hurrah! Chat room is working!
