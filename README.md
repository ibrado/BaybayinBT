Baybayin BT
===========

A simple modification of the Big Time watch using Baybayin, the ancient Philippine script. The character mapped to a digit is usually the first or second syllable of the corresponding Filipino/Tagalog number, as follows:

1 - Sa
2 - Da
3 - Ta
4 - Pa
5 - Li
6 - Ni
7 - Pi
8 - Wa
9 - Si
0 - Pu (only as a second digit, else blank)

Cheatsheet: https://raw.github.com/ibrado/BaybayinBT/master/cheatsheet.png

This mapping (and watchface) is for fun only and does not depict the way time is actually said in Filipino.

If midnight, it just shows the "sun with Ka" flag symbol.

Screenshot says Sa DaLi = 1:25 [ It's also how "sandali" (moment) is written classically :) ]

00:14 = SaPa (on second row)
04:38 = Pa TaWa
10:53 = SaPu LiTa
12:03 = SaDa Ta
21:00 = DaSa (on first row)

The font used is Tagalog Stylized by Paul Morrow.

Wikipedia: http://en.wikipedia.org/wiki/Baybayin
Tagalog Stylized font: http://www.mts.net/~pmorrow/fonts.htm#style

To compile, install Pebble SDK in e.g. pebble-dev then 

cd pebble-dev/Pebble/watches
git clone http://github.com/ibrado/BaybayinBT

~/pebble-dev/Pebble/tools/create_pebble_project.py --symlink-only ~/pebble-dev/Pebble/sdk/BaybayinBT

cd BaybayinBT
./waf configure
./waf build

Watchface is build/BaybayinBT.pbw

Enjoy,

Alex Ibrado <alex@ibrado.org>
