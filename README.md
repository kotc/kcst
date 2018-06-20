# kcst
KotCzarny's Slackware tool

What it can do for you? Let me explain by pasting cmdline help:
```
kcst-0.9.1 - KotCzarny's Slackware Tool.
Usage: kcst command [args]

Commands:
  u[pgrade] - auto-upgrade pkgs (warning: doesnt check dependencies!)
  update - update PACKAGES.TXT
  g[et] name1 [name2..] - download and install pkgs
  r[emove] name1 [name2..] - remove pkgs
  d[ownload] name1 [name2..] - download pkgs
  l[ist] [string] - list installed pkgs (with optional filtering)
  s[earch] string - search pkgs (string is a regexp)
  sf string - search MANIFEST for file path fragment
  fixlibs [paths] - try to autoinstall missing libs
  ru - remove unneeded files (mostly docs and locales, don't use if system is not set to english)
  slist|start|stop|restart|reload|graceful string - control system services (/etc/rc.d/rc.string)
  mconf [help|mmx|p3|pm|c7] - run ./configure
  mmake - run make
  mpkg - run makepkg
  sbu - slackbuilds update list
  sbs string - slackbuilds search
  sbd string - slackbuilds download
  sbb string - slackbuilds download and build
  sbg[et] string - slackbuilds download, build and install
```
