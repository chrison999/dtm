Dragon's Tale Casino Monitor
============================

This program run's alongside eGenesis' Dragon's Tale Casino 
(<http://www.dragons.tl/>) it allows you to keep track of the 
in-game chat, your private messages, system info, et cetera with
some added features that aren't in present in the game client.

This utility was heavily inspirited by Umuri's program for 
Microsoft Windows.  Unlike Umuri's utility, this program uses GTK
and runs on GNU/Linux (and other systems which have python and GTK 
available).


Usage
-----

To use the program, you'll need to turn on "log game chat to 
egenesis.bug" in your in-game settings.  Then provide the location of that 
file as an argument to dtm.

For example:

    $ ./dtm ~/eClient/egenesis.bug

Note that the file `games.json` is used to pretty-print some info in the 
system messages and jackpots window.  Future versions will use this to create
hyperlinks to pages on the wiki 
(<http://www.dragons.tl/mediawiki-1.16.5/index.php/Main_Page>).  Currently,
it's expected that this file exists in the same directory that you call dtm
from.

There are currently two configuration options:
  * PM Notify: rings the system bell when you receive a private message
  * Autoscroll chat: scrolls the chatwindow down as new messages arrive

You can save your preferences for these options in a file called `.dtmrc` 
placed in your $HOME directory.  For example, to have the program autostart
with both options activated your `.dtmrc` file would look like this:

    pm_notify=ON
    autoscroll=ON


Feedback/Donations
-------------------

Like this program?  Found it useful?  Talk to me in-game `tspacepilot`.  
Really like it?  Send me a little btc:

    1HuSTn525oA7QUGdLdv9TPHen4k8sXVGok

Or invite me to a drink at your favorite in-game bar!
