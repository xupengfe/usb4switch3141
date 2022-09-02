# usb4switch3141
It's for usb4switch3141 control and auotmation.

It's for usb4switch3141: https://mcci.com/usb/dev-tools/model-3141/
And you could use it to do some automation as you want.

You just only make sure your Linux os has installed the minicom tool.
Use "minicom" cmd to check if it works.

# ./usb4switch.sh -h
  usage: ./usb4switch.sh  [1|2|off|s|h|*]
  1    Connect host port to port 1 with super speed
  2    Connect host port to port 2 with super speed
  off  Disconned all ports with host port
  s    Check current status
  hot  One round port 1, 2 and disconnect test
  h|*  Show this and show status
