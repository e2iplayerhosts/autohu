E2iPlayer auto.HU host

Install:

~~~
wget --no-check-certificate https://github.com/e2iplayerhosts/autohu/archive/master.zip -q -O /tmp/autohu.zip
unzip -q -o /tmp/autohu.zip -d /tmp
cp -r -f /tmp/autohu-master/IPTVPlayer/* /usr/lib/enigma2/python/Plugins/Extensions/IPTVPlayer
rm -r -f /tmp/autohu*
~~~

restart enigma2 GUI
