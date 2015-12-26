# python-ping
A pure python ICMP ping implementation using raw sockets.

A pure python ping implementation using raw sockets.

Note that ICMP messages can only be sent from processes running as root (in Windows, you must run this script as ‘Administrator’).

Original Version from [Matthew Dixon Cowles](ftp://ftp.visi.com/users/mdc/ping.py)

copyleft 1989-2011 by the python-ping team, see [AUTHORS](https://github.com/jedie/python-ping/blob/master/AUTHORS) for more details.
license: GNU GPL v2, see [LICENSE](https://github.com/jedie/python-ping/blob/master/LICENSE) for more details.

#usage

  ~/python-ping$ sudo ./ping.py google.com

  PYTHON-PING google.com (209.85.148.99): 55 data bytes
  64 bytes from google.com (209.85.148.99): icmp_seq=0 ttl=54 time=56.2 ms
  64 bytes from google.com (209.85.148.99): icmp_seq=1 ttl=54 time=55.7 ms
  64 bytes from google.com (209.85.148.99): icmp_seq=2 ttl=54 time=55.5 ms
  
  ----google.com PYTHON PING Statistics----
  3 packets transmitted, 3 packets received, 0.0% packet loss
  round-trip (ms)  min/avg/max = 55.468/55.795/56.232

Source: [https://pypi.python.org/pypi/python-ping]
