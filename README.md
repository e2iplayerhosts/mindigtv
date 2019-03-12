E2iPlayer https://www.mindigtv.hu/ host

Install:

~~~
wget --no-check-certificate https://github.com/e2iplayerhosts/mindigtv/archive/master.zip -q -O /tmp/mindigtv.zip
unzip -q -o /tmp/mindigtv.zip -d /tmp
cp -r -f /tmp/mindigtv-master/IPTVPlayer/* /usr/lib/enigma2/python/Plugins/Extensions/IPTVPlayer
rm -r -f /tmp/mindigtv*
~~~

restart enigma2 GUI

![mindigtv1](https://user-images.githubusercontent.com/6920933/54215261-efa1c000-44e7-11e9-8bd0-7732d453105a.jpg)
