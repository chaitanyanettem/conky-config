This conkyrc was hacked together from two other configurations: 

1. The Conky Lua configuration created by Despot77(many thanks!) and 
2. A basic conkyrc created using conkycolors(conky-colors --cpu=2 --ubuntu --network --calendar)

Though Despot77's configuration was beautiful, there was something missing. It was just a little difficult to get the information i wanted from a single glance. Even the beautiful clock had that problem. A similar problem plagued the conkyrc from conkycolors. The text was just too small. So I combined them into something i liked.

NOTES: 

1. The time is being fetched using the strftime(3) from time.h. See its man page for more.
2. When adding conky as a startup application, it should start after the desktop starts as illustrated in setup.sh
3. setup.sh can be set to run at startup by adding it in /etc/rc.local or by going to "System>Preferences>Startup Applications"
4. It is assumed that the .conkyrc file and the .lua folder will be placed immediately within the home directory. 
5. If .conkyrc is not in Home directory of user then conky has to be called with -c option specifying its location. If the lua script is not at the assumed location then suitable changes have to be made to .conkyrc(the script's address has to be changed right before TEXT starts in conkyrc).
