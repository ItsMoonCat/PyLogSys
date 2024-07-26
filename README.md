# PyLogSys
A small logsystem on python, what use a basic print, but a have a little bit more information

How to use:
```py
# how to import
from PyLogSys import log
# debug mode, optional
import PyLogSys
PyLogSys.debug = bool # if True, all messages will be displayed despite the type
# message
log(MessageType: str, Message: str, Priority: bool)
```
Allowed message types:

i - Info, e - Error, w - Warning

Message - just message, may be string & f-string

Priority - bool, priority of message, if True: message will be displayed despite the debug mode, and the type.
