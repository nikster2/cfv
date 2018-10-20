# cfv 2.x

© 2000–2009 Matthew Mueller [donut AT dakotacom DOT net](donut@dakotacom.net)

## Requirements

Python ≥ 2.4 <https://www.python.org/>

### Optional

* Python Imaging Library <http://www.pythonware.com/products/pil/>
  (only needed if you want to create the dimensions column of .crc files)
* python-fchksum <http://code.fluffytapeworm.com/projects>
  (may speed up checksumming speed a bit, especially if your python wasn’t built with the mmap module.)

## Install

### Unix

1. make install (which just runs `python setup.py install --prefix=/usr/local`)
2. read man page, `cfv -h`, etc. have fun
3. optional: run tests to verify correct operation: `cd test; ./test.py`

### Windows

1. maybe `python setup.py install` will do something useful? At least it should stick the libraries in the right place
2. move `cfv.bat` to somewhere in the path
3. edit the `cfv.bat` file if your Python is installed somewhere other than `C:\python24`

## Copying

This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation; either version 2 of the License, or (at your option) any later version. See the file `COPYING` for more information.

I would appreciate it if you make modifications if you would send them to me for possible inclusion in the main source.

You can get the latest version at:

* <https://www.ibiblio.org/pub/Linux/utils/file/>
* <http://cfv.sourceforge.net/>
