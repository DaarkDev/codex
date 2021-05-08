# CoDeX
(*Use at your own risk!*)
The description text can be found [here](https://github.com/DaarkDev/filelink/tree/CoDeX).

Dependencies:
- Lua (Should work with most if not all versions, use 5.1 for best experience)
- [luafilesystem](https://keplerproject.github.io/luafilesystem/)

Tested and Maintained For:
- [x] Manjaro i3 (21.0.2 Ornara)
- [x] Latest Raspian Release

*It may work on other linux distributions, it is just only tested on these.*

How to install from terminal:
(Make sure you are in `/usr/local/bin` and that the echo arguments of command 3
are in seperate lines, use vim or GNU nano to seperate them if they aren't)
```sh
sudo git clone https://github.com/DaarkDev/codex/ codex_fold
sudo -i
sudo echo 'cd /usr/local/bin/codex_fold/codex/src/ sudo lua main.lua' > codex
sudo chmod +x codex
```
If everything went successfully, you will now be able to run it via typing in `codex`
to the terminal.
