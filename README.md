# pyNoEarHurtingVolume
Screw you earrape (This python script kills ear hurting volumes before it has time to shoot your eardrums and kill them)

How to use:

1: Download and run the .py file. It will make a configuration file at `/tmp/.%USERNAME%-pyNoEarHurtingVolume.cfg`, edit it and paste in the below config and edit it to how you like. Also you might want to keep the max-allowed-as-safe number above 100, so that regular voice doesn't get cancelled:
```ini
[DEFAULT]
maxvol = 50
lowvol = 25

[AutochangeVolume]
notearraped = 1  
max-allowed-as-safe = 166
```
