# cRACk v1.0
"_**c**lient for **RAC** **k**ettles_"\
cRACk is TUI client for [RAC](https://github.com/The-Stratosphere-Solutions/RAC-Hub), written on Python.


## features
- supports [RAC v1.99.2](https://github.com/The-Stratosphere-Solutions/RAC-Hub/blob/main/RACv1.99.md) ([RAC v2](https://github.com/The-Stratosphere-Solutions/RAC-Hub/blob/main/RACv2.md) and [WRAC v2](https://github.com/The-Stratosphere-Solutions/RAC-Hub/blob/main/WRAC.md) support soon)
- shitcoded with love!

## how to run
### for Windows
use .exe binary from [latest release](https://github.com/pansangg/cRACk/releases),\
or run `main.py` with python interpreter.

### for Linux
run `main.py` with python interpreter.

### for MacOS
run `main.py` with python interpreter.
> note: not tested yet

## building from source
1) install python

https://www.python.org/downloads

2) download clone this repo using git
```
git clone https://github.com/pansangg/cRACk.git
```
3) install pyinstaller 
```
pip install pyinstaller
```
4) in the same directory where the main.py is located run
```
python -m PyInstaller --onefile main.py
```
5) done. check /dist folder

## TODO
- [x] fix ctrl+c exit
- [ ] add user-agents support
- [ ] add first-time config
- [ ] add MOTDs
- [ ] add support for [RAC v2](https://github.com/The-Stratosphere-Solutions/RAC-Hub/blob/main/RACv2.md)
- [ ] add support for [WRAC v2](https://github.com/The-Stratosphere-Solutions/RAC-Hub/blob/main/WRAC.md)
- [ ] fix "lower than before 0x00 result" bug
- [ ] add ANSI filter

## license
this project is licensed under GPL-3.0 license.

## see also
- [RAC-Hub](https://github.com/The-Stratosphere-Solutions/RAC-Hub)
- [about RAC (v1.99)](https://github.com/The-Stratosphere-Solutions/RAC-Hub/blob/main/RACv1.99.md)
- [about RAC (v2)](https://github.com/The-Stratosphere-Solutions/RAC-Hub/blob/main/RACv2.md)
- [about WRAC (v2)](https://github.com/The-Stratosphere-Solutions/RAC-Hub/blob/main/WRAC.md)
- [bRAC - better RAC client](https://github.com/The-Stratosphere-Solutions/RAC-Hub/blob/main/RACv2.md)
- [Mefedroniy - TUI RAC client](https://github.com/OctoBanon-Main/mefedroniy-client)

[^1]: [RAC](https://github.com/The-Stratosphere-Solutions/RAC-Hub)
[^2]: [RAC (v1.99)](https://github.com/The-Stratosphere-Solutions/RAC-Hub/blob/main/RACv1.99.md)
[^3]: [RAC (v2)](https://github.com/The-Stratosphere-Solutions/RAC-Hub/blob/main/RACv2.md)
[^4]: [WRAC (v2)](https://github.com/The-Stratosphere-Solutions/RAC-Hub/blob/main/RACv2.md)
