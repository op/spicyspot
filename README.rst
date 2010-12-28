spicyspot
=========

Script to make it possible to control access to a chillispot from a command
line interface.

In Thailand, many hotels and hostels offers wifi through a company called
Cyberpoint. Some drawbacks of the architecture they offer is;

- you're forced to login using a web browser
- they use javascript things to resize your browser window
- you can not use "restore my tabs" features in browsers

I wrote this very quickly on my vacation. Feel free to extend and improve.

Future improvements
-------------------

- Make it work in foreground mode (eg. when closed, automatically logoff)
- Save state between runs (this to remove the hardcoded url used today)
