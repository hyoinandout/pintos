# PintOS-Team5-Project1
Operating System PintOS Project1

## How to install
1. cd ~
2. git clone https://github.com/gpgun0/PintOS-Team5-Project1.git
3. vi ~/.bashrc
```
...
export PATH="$PATH:/home/**name**/pintos/src/utils"
export PINTOSDIR="/home/**name**/PintOS-Team5-Project1"
export GDBMACROPATH="/home/**name**/PintOS-Team5-Project1/src/utils/pintos-gdb"
```
4. cd ./PintOS-Team5-Project1/src/utils
5. make clean && make
6. cd ../threads
7. make clean && make
8. pintos -q run alarm-multiple

