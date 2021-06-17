This is an open source OS. I don't have a purpose for this right now, but I just really wanted to do it. Learning experience.

##TODO Checklist:
--------------------
*Bootloader*  
*Kernel*  
*Commands*  
*GUI*  

##Compiling and running with QEMU:
---------------------
First, make sure you have the latest version of nasm and qemu.
```
sudo apt install nasm
sudo apt isntall qemu
```
There already is a .bin file in the build folder so you can just skip ahead to running to it in qemu.
```
nasm -f bin bootloader.asm -o osname.bin
qemu-system-x86_64 osname.bin
```

