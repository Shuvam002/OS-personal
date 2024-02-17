# OS-personal

Hello guys, this is my personal grand project and probably my last one..

Here, I'm building an OS from scratch.

To run this, you need to have a bash shell whether actual OS, VM or even a shell; it doesn't matter.

# Tools Needed

For now you need to have qemu-kvm

install it using:

`apt install qemu-kvm`

after that run:

`make && qemu-system-i386 -fda build/main_floppy.img`