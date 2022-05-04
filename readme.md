# Udev Rules

| File name                      | Description                              |
|--------------------------------|------------------------------------------|
| 51-gcadapter.rules             | To allow access to Gamecube Adapter      |
| 52-dolphin.rules               | To passthough bluetooth adatper          |
| 53-switchProController.rules   | To allow access to Switch Pro Controller |
| 60-dualsense-controllers.rules | To allow access to Duelsense Controller  |


To apply rules copy rules to `/etc/udev/rules.d`, than run `sudo udevadm control --reload-rules` and reboot.
