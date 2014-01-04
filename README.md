Requirements:
-------------------------
Generic:
* Bitcoin >=0.6.4
* Python
* Twisted
* python-argparse (for Python <=2.6)

Linux:
* sudo apt-get install python-zope.interface python-twisted python-twisted-web
* sudo apt-get install python-argparse # if on Python 2.6 or older

Windows:
* Install Python 2.7: http://www.python.org/getit/
* Install Twisted: http://twistedmatrix.com/trac/wiki/Downloads
* Install Zope.Interface: http://pypi.python.org/pypi/zope.interface/3.8.0
* Install python win32 api: http://sourceforge.net/projects/pywin32/files/pywin32/Build%20218/
* Install python win32 api wmi wrapper: https://pypi.python.org/pypi/WMI/#downloads
* Unzip the files into C:\Python27\Lib\site-packages

Running P2Pool:
-------------------------
Run P2Pool with the "--net dvachcoin" option.

Then run your miner program, connecting to 127.0.0.1 on port 8372 with any
username and password.

If you are behind a NAT, you should enable TCP port forwarding on your
router. Forward port 8376 to the host running P2Pool.

Run for additional options.

    python run_p2pool.py --help

Donations towards further development:
-------------------------
2CHCOIN:    2Q4wAwe9a4bqX96dWjRgU5kv7PPjGNUFhx
DOGE:       DDCjGwqBxx87W6wKWCBTRfvsdBjFWirzwM

Official wiki :
-------------------------
https://en.bitcoin.it/wiki/P2Pool


