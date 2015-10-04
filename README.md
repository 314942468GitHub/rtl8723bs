# rtl8723bs
Realtek SDIO Wi-Fi driver

Tested on: 
- Onda v975w
- Teclast 3G
- HP Stream 7
- Dell Venue 8 3000
- WinBook TW100 and TW700

Do verify that the device is listed under ```/sys/bus/sdio/```

Note that on all those tablets, you will need to apply a few patches because
to the BayTrail SDIO drivers:
http://thread.gmane.org/gmane.linux.kernel.mmc/25081/focus=25087
http://thread.gmane.org/gmane.linux.kernel.mmc/31583

You can also find those patches in the patches/ sub-directory.
