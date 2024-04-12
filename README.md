# ina260_logfile_micropython

![picture](https://github.com/charkster/ina260_logfile_micropython/blob/main/ina260_qt_py_rp2040_wiring.jpg)

**INA260 logging to screen and logfile**, implemented in **MicroPython** (using Adafruit QT PY RP2040).

This is a re-write on my [Python script](https://github.com/charkster/INA260) which runs on full-size Raspberry Pi. It is cheaper and boots much faster.

I open this script in [Thonny](https://thonny.org/) and have it run in the REPL. Current and voltage are sampled once per second, and displayed in REPL. A CSV logfile is also created on the MCU, which can be accessed using Thonny. 
A QT PY RP2040 was used as it has a 2Mbyte flash to store the CSV logfile. 
