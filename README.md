# ESP32-router-process-csn150

## Name of prjoect 
ESP32 NAT Router

## Purpose
creating a ESP32 Router Scanner

## Equipment 
+ [ESP32 CAM](https://www.amazon.com/ESP32-CAM-MB-Aideepen-ESP32-CAM-Bluetooth-Arduino/dp/B0948ZFTQZ/ref=sr_1_1_sspa?keywords=esp32+cam&qid=1678904348&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUEyWDQyMkxLUUJWSFQxJmVuY3J5cHRlZElkPUEwOTk4NjQ1TllJUURNRzcxWEZJJmVuY3J5cHRlZEFkSWQ9QTA1NDcwNDczNkVVTEZMMDZWUzZSJndpZGdldE5hbWU9c3BfYXRmJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ==)
+ [usb micro data cable](https://www.amazon.com/AmazonBasics-Male-Micro-Cable-Black/dp/B0711PVX6Z/ref=sr_1_1_ffob_sspa?crid=16W1ZVGK5RSBL&keywords=usb+micro+data+cable&qid=1678905952&sprefix=usb+micro+data+%2Caps%2C123&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUExUllNUjBONzVaQjc1JmVuY3J5cHRlZElkPUEwOTM3MTg3NjU4RzJRWkM3UTRaJmVuY3J5cHRlZEFkSWQ9QTAxODUxNTUyMFlHTjZHVks1NTNQJndpZGdldE5hbWU9c3BfYXRmJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ==)
+ [micro memory chip](https://www.amazon.com/Amazon-Basics-microSDXC-Memory-Adapter/dp/B08TJRVWV1/ref=sr_1_1_ffob_sspa?crid=23O8LCMK14S72&keywords=micro+sd+card&qid=1678906000&sprefix=micro+sd+%2Caps%2C423&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUE4NFM3RzNPTTU2SlQmZW5jcnlwdGVkSWQ9QTA1MDcyMDkyNjRFR0JDUVFQMjA2JmVuY3J5cHRlZEFkSWQ9QTA2Njg3NDYzM1dDMk5KQ0QyMEJZJndpZGdldE5hbWU9c3BfYXRmJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ==)

## Link for documentation
+  [Martin Ger Program](https://github.com/martin-ger/esp32_nat_router)
+ [Esp32 Flash Dowload Tool](https://www.espressif.com/en/support/download/other-tools)
 
+ #### Walkthrough video


<a href="http://www.youtube.com/watch?feature=player_embedded&v=41Lymi6rXA8&list=PLLikBZAto8K7zrkQQYOfoY9404SBhXeQr
" target="_blank"><img src="https://github.com/samlora704/ESP32-router-process-csn150/blob/main/Martin%20Ger%20youtube.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

## Steps I followed
+ download folder from link above titled "link for  documentation"
+ extract all for both downloaded folders
+ go through "downloads"folder and look for "flash_Download_tool" open it 
+ double click on the flash_download_tool application ( a black screen will pop up dont be afraid)
+ when a small message window with pop up for chipset select "ESP32c2"
+ loadmode select "USB"
+ change the "chiptype" to ## "ESP32" # (if that happens to be the chiptype you have purchased) for some strange reason you the USB selection isnt there 
+ select ok
+ hover over the "..." your file expolorer will open and look for the "esp32 nat router master" folder double click on the folder titled "ESP32", then the  "buildfolder"  
+ in this order you will select each file the builder folder -"bootloader.bin" "partition.bin" "firmware.bin"
+ on the right side of the "@" type for each on the .bin '1000' for the bootloader.bin, '8000' for the partitions.bin '10000'for firmware.bin
+ leave all other selection as is 
+ plug in your ESP32 device 
+ for 'com' select the com that pops up (varies)
+ for 'BAUD' select 115200
### + hold down the rest button whilst you select start once the device syncs with firmware download the program by pressing start again
+ 


## Problems
