

This kind of works except the Serial pins    are too long causing some issues with the serial connection

see https://github.com/arduino/ArduinoCore-mbed/issues/74#issuecomment-1120703328

```
if the board keeps running the sketch and just the communication is not functional it's probably due to the long stubs on high density USB0 pins (J1 25-27, which are shared with the ones in the USB-C connector).
Cutting the traces close to the HD connector looks like a no go in your PCB but maybe it's worth trying 🙃
```
I havn't figured out which line is causing the issue.
