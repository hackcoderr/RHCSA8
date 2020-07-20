## Linux Basic Command

---

1. Linux Provides a CLI (Command Line Interface) to Communicate with the OS.
   2.CLI is better for tasks which cannot be performed with the GUI.

---

**This cmd will open program which you want to open.**

> \$ programname

e.g

    $ firefox

**To find the path of your program.**

> \$ which programname

e.g

    $ which firefox

**To see the code of your program in detail.**

> \$ gedit path_of_program

e.g
  
 \$ gedit /usr/bin/firefox

**To see date.**

> \$ date

**Create a continuous digital clock in Linux terminal**

    $ watch -t -n 1 date +%T

    $ while [ 1 ] ; do echo -en "$(date +%T)\r" ; sleep 1; done

**To see the current month calender.**

> \$ cal

**To see the calender of desired year**

> \$ cal year

e.g
  
    $ cal 2019

**To see the calender of desired month with year**

> \$ cal month year

e.g

    $ cal 4 2018

**To print something**

> \$ echo which_you_want_print

e.g  
  
    $ echo hello

**To speak something through your system speaker using cmd**

> \$ espeak-ng which_you_want_to_listen

e.g

    $ espeak-ng hello

    $ date | espeak-ng

