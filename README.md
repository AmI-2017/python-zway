# REST operation of Lights in Python #

The modules provided in this repository show how lights can be operated (i.e., turned on or off) on Z-Wave networks using REST APIs (through the [Z-Way server](http://razberry.z-wave.me)).

* The `rest.py` module provides a really basic API for easily calling REST services
* The `zway.py` shows how to turn on every "switch" device (i.e., lamps) connected to a Z-Wave network. Lamps are turned on and, after 10s, they are turned off.

_Please be aware that this module only works on machines running the [Z-Way server](http://razberry.z-wave.me)._
