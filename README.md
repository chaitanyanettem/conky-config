This conkyrc was hacked together from two other configurations: 

1. The Conky Lua configuration created by Despot77(many thanks!) and 
2. A basic conkyrc created using conkycolors

Though Despot77's configuration was beautiful, there was something missing. It was just a little difficult to get the information i wanted from a single glance. Even the beautiful clock had that problem. A similar problem plagued the conkyrc from conkycolors. The text was just too small. So I combined them into something i liked.

NOTES: 

1. The time is being fetched using the strftime(3) from time.h. See its man page for more.
2. When adding conky as a startup application, it should start after the desktop starts as illustrated in setup.sh

