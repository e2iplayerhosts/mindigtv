E2iPlayer https://mytv.telenor.hu/ host

Install:

~~~
wget --no-check-certificate https://github.com/e2iplayerhosts/mindigtv/archive/master.zip -q -O /tmp/mindigtv.zip
unzip -q -o /tmp/mindigtv.zip -d /tmp
cp -r -f /tmp/mindigtv-master/IPTVPlayer/* /usr/lib/enigma2/python/Plugins/Extensions/IPTVPlayer
rm -r -f /tmp/mindigtv*
~~~

restart enigma2 GUI
