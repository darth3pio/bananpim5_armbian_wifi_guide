# Banana Pi M5: Armbian WiFi Setup Guide
As the internet resources are few and far between I tinkered around until I had something working and would like to leave somewhere more centralised that I can share my successes without having to sign up for a forum membership.
  
**We start with the driver overlays and where they're stored in Armbian**  
------------------------  
![overlay Directory](./assets/images/overlay_directory.png)
------------------------  
**Doing a directory listing we see the** ***meson-sm1-bananapi-m5-rtl8822cs.dtbo***
------------------------  
![overlay Listing](./assets/images/overlay_ls.png)
------------------------
**Starting with modifying armbianEnv.txt to add in the overlay we have to make sure to factor in the overlay_prefix into our dtbo**  
------------------------  
![armbianEnv Directory](./assets/images/armbianEnv_directory.png)
![armbianEnv Overlays](./assets/images/armbianEnv_overlays.png)
![modules Directory](./assets/images/modules_directory.png)
![modules rtl88x2cs](./assets/images/modules_rtl88x2cs.png)
