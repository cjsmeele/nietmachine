Nietmachine
===========

Name
----

Nietmachine - Scripts to complement bspwm

Description
-----------

This repository consists of the following components:

### Barteld

Barteld is a script that feeds off of information provided by bspwm and
Moniek to display a panel with a workspace/desktop list, resource usage
information and a clock. The panel used in this setup is
[lemonbar](https://github.com/LemonBoy/bar), with
[patches](https://github.com/krypt-n/bar) applied to support Xft fonts.

### Moniek

Moniek is a utility that periodically prints CPU and memory usage
statistics, and battery / adapter status to standard output.

### Batman

Batman watches over your battery levels and will shout at you when it's
getting too low.

### Treintje

Treintje listens for bspwm `node_manage` events and automatically sets
window transparency to a certain level when it detects that a URxvt
window being spawned.

Dependencies
------------

- Perl 5.12.0 or above, with the JSON module available
- [bspwm](https://github.com/baskerville/bspwm)
- [lemonbar (xft patched)](https://github.com/krypt-n/bar)
- [xtitle](https://github.com/baskerville/xtitle)
- For Treintje: transset, xcompmgr or an equivalent

License
-------

All files in this repository are licensed under the MIT license unless
specified otherwise in the file itself.

The MIT license text can be found in [LICENSE](LICENSE).

Author
------

[Chris Smeele](https://github.com/cjsmeele)
