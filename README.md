If you need driver for wi-fi dongle Realtek RTL8188FTV for Linux

First, check kernel version. You need a kernel: >= 6.4.

Then,
1. Download rtl8188fufw.bin 
2. Copy it in the system: sudo cp rtl8188fufw.bin /usr/lib/firmware/rtlwifi/

*Maybe you don't have /usr/lib/firmware/rtlwifi/ folder path, so you need to create those folders.

That's all. Restart and you have wifi!
