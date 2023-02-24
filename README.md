# wifipineapple-hcxdumptool

hcxdumptool module for the WiFi Pineapple to to capture packets from wlan devices and perform PMKID attacks.

## How to Install

1) Run the `./build.sh` script inside the hcxdumptool directory

2) SCP the dist/hcxdumptool directory in /pineapple/modules/ on the WiFi Pineapple. 

![SCP](https://raw.githubusercontent.com/mattlawer/wifipineapple-PMKID/master/screenshots/scp.png)

        scp -r dist/hcxdumptool root@172.16.42.1:/pineapple/modules/
    
3) Enter the the WiFi Pineapple web interface, go to Modules->hcxdumptool and have fun!

![Preview](https://raw.githubusercontent.com/lorenzoPrimi/wifipineapple-hcxdumptool/master/screenshots/module.png)
![Preview-running](https://raw.githubusercontent.com/lorenzoPrimi/wifipineapple-hcxdumptool/master/screenshots/module-running.png)

