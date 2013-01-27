Awesome-Laptop
==============

PLEASE NOTE THESE CONFIGS DONOT WORK WITH 3.5 AND WILL NO LONGER BE UPDATED PLEASE SEE [Awesome-Laptop-3.5][8] FOR A WORKING 3.5 CONFIG
--------------------------------------------------------------------------------------------------------------------------------------

Awesome Config's Redesigned for Laptop Usage

http://awesome.naquadah.org/wiki/Main_Page
https://github.com/setkeh/Awesome

Depends on: git [luasocket][1] - [luainotify][2] - [oocairo][7]

Optional:  [Widget-Notify][4]

INSTALL Awesome Window Manager
------------------------------

`Ubuntu/Debian:`

    # apt-get install awesome

`Archlinux:`

    # pacman -S awesome

`Gentoo:`

    # emerge -av awesome

`Fedora:`

    # su -c 'wget -nd -P /etc/yum.repos.d http://repos.fedorapeople.org/repos/thm/awesome/fedora-awesome.repo'
    # su -c 'yum install awesome'

NOTES
-----

`Wallpapers:`
 
    Due to not owning the licesnces for any of the wallpapers displayed in screenshots they will be 
    removed from the File tree. To Combat the nessesity to Manually edit the lua theme i have created
    a wallaper changer to the configs it will list your wallpapers and aplly the wallpaper and restart
    awesome automaticly for you.
    How to use this function:
    mkdir ~/.config/awesome/wallpaper
    Fill this directory with Wallpapers and select the wall paper you want from the Awesome Menu
    (NOTE Awesome Soft restart maybe required if you cans see your images in the menu.)

`Scripts:`

    Please Keep in mind if you download these configs and scripts they are currently in beta what works for 
    me may not work for you nessisarily you are ofcourse welcome to open up issues and please makesure you 
    give detailed log output and explinations for the issues. Currently Most of the Scripts are designed 
    for working with Archlinux (i.e Pacman and Aur Updates) but im working on making it more distro indipendant. 
    Enjoy :) 

`Screenshots`

    If you would like to share your screenshot of these configs please contact setkeh via email or 
    join #linuxdistrocommunity on freenode :)

SUPPORT
-------

[The Linux Distro Community][5]

[setkeh][6]

What I Changed
--------------

I may forget to update this bit :)

Converted Widgets to BlingBling For sexy graphs :)

Fixed some Small Issues in blingbling code

Just remember if you use latest bling bling it may have errors if yu clone bling bling please do not post issues on my awesome configs 

TODO
----

1. Clean Up rc.conf
2. Add More comments to rc.lua
3. Open For Suggestions :)

Contributing
------------

1. Fork it.
2. Create a branch (`git checkout -b Awesome`)
3. Commit your changes (`git commit -am "Added foo and bar"`)
4. Push to the branch (`git push origin Awesome`)
5. Create an [Issue][6] with a link to your branch
6. Join the Linux Distro Community IRC or Mumble! :D

SHARE AND ENJOY!
----------------

[1]: http://w3.impa.br/~diego/software/luasocket
[2]: http://www3.telus.net/taj_khattra/luainotify.html
[3]: https://wiki.archlinux.org/index.php/Mpd
[4]: https://github.com/setkeh/Awesome-Widget-Notify 
[5]: http://www.linuxdistrocommunity.com
[6]: https://github.com/setkeh/Awesome/issues
[7]: http://oocairo.naquadah.org
[8]: https://github.com/setkeh/Awesome-Laptop-3.5
