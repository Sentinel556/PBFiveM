# PBFiveM

Over complicated FiveM Panic Button Script

# Functionality

An Officer may press `Ctrl + H` to activate the Panic Button, which will display a blip on the map, display a short notification and play a short sound.

![Image 1](https://cdn.discordapp.com/attachments/547812834491498496/570666551007510528/unknown.png)
![Image 2](https://cdn.discordapp.com/attachments/547812834491498496/570668805689442342/unknown.png)

# Installation

Although getting it to work couldn't be easier here you go.
First drop PB (the file inside, not the master branch),
then start the resource in your server.cfg

```lua
start mapmanager
start chat
start spawnmanager
start sessionmanager
start fivem
start hardcap
start rconlog
start scoreboard
start playernames
start PB
```
Woho, you are done. It should work now!

# Known Issues

* Player is unable to activate two Panic Buttons at the same time (Semi Intentional)

* The notification will sometimes display the wrong streetname.
