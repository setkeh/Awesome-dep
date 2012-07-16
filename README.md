Awesome
=======

Awesome Window Manager Configs

http://awesome.naquadah.org/wiki/Main_Page
https://github.com/setkeh/Awesome

Depends on: git [luasocket][1] - [luainotify][2]
Optional:   [mpd][3] - [Bashets][4]

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
	removed from the File tree so you will be required to make some changes to the ./themes/default/theme.lua

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

TODO
----

1. Clean Up rc.conf
2. Add More comments to rc.lua
3. Open For Suggestions :)

HISTORY
-------

* 2012-07-09: Version 0.0.1
      
   - Initial commit
   - Imported awesompd
   - Imported launchbar
   - Imported diskusage
   - Minor enhancement: default tags, tag names and layout
   - Minor enhancement: bottom bar widgets (Bashets, Pacman Updates, AUR Updates,  uptime, load, cpu, memory, date)
   - Version enhancement: new configuration variables
   - Version enhancement: theme tweaks
   - Version enhancement: configuration tweaks

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
[4]: http://awesome.naquadah.org/wiki/Bashets
[5]: http://www.linuxdistrocommunity.com
[6]: https://github.com/setkeh/Awesome/issues
