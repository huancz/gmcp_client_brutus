This repository is a copy of parts of aardwolfclient package, tweaked
a bit to suit BrutusMUD needs (I only removed unsupported features so
far, and renamed the files around to be a bit consistent).

Original package is avalable under the conditions of WTFPL V2
(http://sam.zoy.org/wtfpl/) from https://code.google.com/p/aardwolfclientpackage/

Same license applies to this clone.

Installation
============

1) Install MUSHclient from http://mushclient.com/downloads/dlmushclient.htm

2) Download latest version from https://github.com/huancz/gmcp_client_brutus/zipball/master
   and extract the contents of MUSHclient directory into your mushclient installation
   directory (worlds/ to worlds/, lua/ to lua/, ...) Say yes to overwrite.

3) create world, press CTRL+SHIFT+P to enter plugin menu, and add (in this order):

    support_repaint_buffer.xml
    support_miniwin_z_order_monitor.xml
    support_gmcp_handler.xml

4) rest of the plugins are optional, try them or uninstall them as you wish
