# kcst
KotCzarny's Slackware tool

Please note: php4static is a php4 binary for 32bit linux with openssl and curl compiled in. It's included mainly for my private use and not required for kcst to run, but might be handy when system is badly damaged (to the point that wget fails).

What it can do for you? Let me explain by pasting cmdline help:
```
kcst-0.9.6 - KotCzarny's Slackware Tool
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
  news - get and display changelog.txt
  fixlibs [paths] - try to autoinstall missing libs
  slist|start|stop|restart|reload|graceful string - control system services (/etc/rc.d/rc.string)
  sbu - slackbuilds update list
  sbs string - slackbuilds search
  sbd string - slackbuilds download
  sbb string - slackbuilds download and build
  sbg[et] string - slackbuilds download, build and install
  rnm from to [-d] [-h] [-r] [-w] [-x] - regexp based batch rename, pass -h for help
  cf [path] - count files at path (or . if no path given)
  gf regexp [path1..] - recursively find files/dirs matching regexp in paths (or . if no path given)
```
