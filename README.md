# Fiberhome-AN5506-04-FG

This repository is about a GPON ONU device. Someone from service provider scheduled to pick it up as I was not a subscriber anymore. They stopped by and don't found me on first time. Fact is there was never a second time and the device was getting dust on my desk.

So I decided to investigate how to put it to a better use. A long time ago I have heard about DD-WRT, then payed their website a visit and searched for compatible devices but no lucky. Facing the long list of supported devices I got intrigued why mine wasn't.

Next step was discover with which hardware I was dealing. Opening the device doesn't gave me too much clues since I'm a more software guy. Additionaly I found a firmware and tryed to reverse engineer it. I started with binwalk (it reported that image uses JFFS2 filesystem and code was for a big endian platform) and moved on with ghidra.

https://wikidevi.wi-cat.ru/ lists BCM68380 in xPON as MIPS74k architecture

https://www.tripleoxygen.net/

https://www.mxic.com.tw/

SoC: BCM68380 - Broadcom - MIPS74k 600MHz 2cores - GbE PHYs, USB, SLAC, SIM card controller EPON/GPON GE Processor

RAM: H5TQ2G63GFR - SK Hynix 2 Gbit (256 MB) DDR3 SDRAM

Flash: MX30LF1G18AC - Macronix 1 Gbit (128 MB) NAND
