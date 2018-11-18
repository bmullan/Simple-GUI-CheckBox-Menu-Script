### Simple GUI Menu script.

Simple GUI Bash Script using YAD to launch scripts/apps 

I had the need to create a nice GUI based menu for end-users that they could just select 
via a Check-Box method which applications they they would want to have installed in an LXD
container for their use with the CIAB Remote Desktop system.

The applications will all be web based but because they will each reside in their own LXD container
on the same 10.x.x.x subnet as the CIAB Remote Desktop containers (ciab-guac, cn1).

Because of this those Web applications will be reachable by those CIAB remote desktop users **but not** 
from the *Internet*.

The only users of the Web Applications will be CIAB Remote Desktop Users that access their LXD remote
desktop containers via Guacamole/Tomcat/MySQL/NGINX which are all running in another LXD container named
ciab-guac.

However, this script can be used for many use-cases beside mine so I thought I'd publish it here.



