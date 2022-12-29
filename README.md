# Xtream UI for Ubuntu 20.04 install
This is an installation mirror for xtream ui software on Ubuntu 20.04.
Includes NGINX 1.19.2 and PHP 7.3.25.



### Update 08/12/2020: ###
- bumped php version from 7.2 to 7.3 following 7.2 obsolence
- fixed user_watcher.php disconnect users every minute because of wrong pid check.

Note: HLS activity is wrongly reported. You should use mpegts ouput and not hls while it's unfixed

### THANKS ###

Thanks to GTA for xtream-ui admin original interface
Thanks to emre1393 for being the wisdom of xui community

### Installation: ###

Update your ubuntu first, then install panel:
``` 
sudo apt update && sudo apt full-upgrade -y;  
wget https://raw.githubusercontent.com/NeySlim/xtreamui_mirror/master/install.py; 
sudo python install.py  
```
  
If you want a whole NEW installation, choose MAIN and then UPDATE.  
If you want to install load balance on additional servers, add a server to panel in manage servers page, then run script and proceed with LB option.  
If you want to update admin panel, select UPDATE.

### Video tutorials : ###

[Xtream-UI Tutorials](https://www.youtube.com/playlist?list=PLJB51brdC_w7dTDxi1MPqiuk3JH5U2ekn "Xtream-UI Tutorials")



