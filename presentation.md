%title: Linux terminal intro. Plask 2020
%auth: Lars Aaberg

```
 _     _                    _                      _             _
| |   (_)_ __  _   ___  __ | |_ ___ _ __ _ __ ___ (_)_ __   __ _| |
| |   | | '_ \| | | \ \/ / | __/ _ \ '__| '_ ` _ \| | '_ \ / _` | |
| |___| | | | | |_| |>  <  | ||  __/ |  | | | | | | | | | | (_| | |
|_____|_|_| |_|\__,_/_/\_\  \__\___|_|  |_| |_| |_|_|_| |_|\__,_|_|

 _       _                 _            _   _
(_)_ __ | |_ _ __ ___   __| |_   _  ___| |_(_) ___  _ __
| | '_ \| __| '__/ _ \ / _` | | | |/ __| __| |/ _ \| '_ \   
| | | | | |_| | | (_) | (_| | |_| | (__| |_| | (_) | | | |
|_|_| |_|\__|_|  \___/ \__,_|\__,_|\___|\__|_|\___/|_| |_|

 ____  _           _      ____   ___ ____   ___
|  _ \| | __ _ ___| | __ |___ \ / _ \___ \ / _ \ 
| |_) | |/ _` / __| |/ /   __) | | | |__) | | | | 
|  __/| | (_| \__ \   <   / __/| |_| / __/| |_| | 
|_|   |_|\__,_|___/_|\_\ |_____|\___/_____|\___/ 

```

--------------------------------------------

-> apt install <-

*lars@spv:~$*

--------------------------------------------

-> apt install <-

*lars@spv:~$* cowsay "Plask 2020. Awesome!"

--------------------------------------------

-> apt install <-

*lars@spv:~$* cowsay "Plask 2020. Awesome!"

Command 'cowsay' not found, but can be installed with:

sudo apt install cowsay
*lars@spv:~$*

--------------------------------------------

-> apt install <-

*lars@spv:~$* cowsay "Plask 2020. Awesome!"

Command 'cowsay' not found, but can be installed with:

sudo apt install cowsay
*lars@spv:~$* sudo apt -y install cowsay

--------------------------------------------

-> apt install <-

*lars@spv:~$* cowsay "Plask 2020. Awesome!"

Command 'cowsay' not found, but can be installed with:

sudo apt install cowsay
*lars@spv:~$* sudo apt -y install cowsay
[sudo] password for lars:

--------------------------------------------

-> apt install <-

*lars@spv:~$* cowsay "Plask 2020. Awesome!"

Command 'cowsay' not found, but can be installed with:

sudo apt install cowsay
*lars@spv:~$* sudo apt -y install cowsay
[sudo] password for lars:
Reading package lists... Done
Building dependency tree
Reading state information... Done
Suggested packages:
  filters cowsay-off
The following NEW packages will be installed:
  cowsay
0 upgraded, 1 newly installed, 0 to remove and 0 not upgraded.
Need to get 17.7 kB of archives.
After this operation, 89.1 kB of additional disk space will be used.
Get:1 http://archive.ubuntu.com/ubuntu bionic/universe amd64 cowsay all 3.03+dfsg2-4 [17.7 kB]
Fetched 17.7 kB in 1s (23.0 kB/s)
Selecting previously unselected package cowsay.
(Reading database ... 60612 files and directories currently installed.)
Preparing to unpack .../cowsay_3.03+dfsg2-4_all.deb ...
Unpacking cowsay (3.03+dfsg2-4) ...
Setting up cowsay (3.03+dfsg2-4) ...
Processing triggers for man-db (2.8.3-2ubuntu0.1) ...
*lars@spv:~$*

--------------------------------------------

-> apt install <-

*lars@spv:~$* cowsay "Plask 2020. Awesome!"

Command 'cowsay' not found, but can be installed with:

sudo apt install cowsay
*lars@spv:~$* sudo apt -y install cowsay
[sudo] password for lars:
Reading package lists... Done
Building dependency tree
Reading state information... Done
Suggested packages:
  filters cowsay-off
The following NEW packages will be installed:
  cowsay
0 upgraded, 1 newly installed, 0 to remove and 0 not upgraded.
Need to get 17.7 kB of archives.
After this operation, 89.1 kB of additional disk space will be used.
Get:1 http://archive.ubuntu.com/ubuntu bionic/universe amd64 cowsay all 3.03+dfsg2-4 [17.7 kB]
Fetched 17.7 kB in 1s (23.0 kB/s)
Selecting previously unselected package cowsay.
(Reading database ... 60612 files and directories currently installed.)
Preparing to unpack .../cowsay_3.03+dfsg2-4_all.deb ...
Unpacking cowsay (3.03+dfsg2-4) ...
Setting up cowsay (3.03+dfsg2-4) ...
Processing triggers for man-db (2.8.3-2ubuntu0.1) ...
*lars@spv:~$* clear

--------------------------------------------

-> apt install <-

*lars@spv:~$*

--------------------------------------------

-> apt install <-

*lars@spv:~$* cowsay "Plask 2020. Awesome!"

--------------------------------------------

-> apt install <-

*lars@spv:~$* cowsay "Plask 2020. Awesome!"
| ______________________
|< Plask 2020. Awesome! >
| ----------------------
|        \\   ^__^
|         \\  (oo)\\_______
|            (__)\\       )\\/\\
|                ||----w |
|                ||     ||
*lars@spv:~$* 

--------------------------------------------

-> apt install <-

*lars@spv:~$* cowsay "Plask 2020. Awesome!"
| ______________________
|< Plask 2020. Awesome! >
| ----------------------
|        \\   ^__^
|         \\  (oo)\\_______
|            (__)\\       )\\/\\
|                ||----w |
|                ||     ||
*lars@spv:~$* clear

--------------------------------------------

-> terminal <-

*lars@spv:~$*

--------------------------------------------

-> terminal <-

*lars@spv:~$* curl https://www.metaweather.com/api/location/search/?query=ber

--------------------------------------------

-> terminal <-

*lars@spv:~$* curl https://www.metaweather.com/api/location/search/?query=ber
[{"title":"Berlin","location_type":"City","woeid":638242,"latt_long":"52.516071,13.376980"},{"title":"Nuremberg","location_type":"City","wo
eid":680564,"latt_long":"49.454342,11.07349"},{"title":"Aberdeen","location_type":"City","woeid":10243,"latt_long":"57.153820,-2.106790"}]
*lars@spv:~$*

--------------------------------------------

-> terminal <-

*lars@spv:~$* curl https://www.metaweather.com/api/location/search/?query=ber
[{"title":"Berlin","location_type":"City","woeid":638242,"latt_long":"52.516071,13.376980"},{"title":"Nuremberg","location_type":"City","wo
eid":680564,"latt_long":"49.454342,11.07349"},{"title":"Aberdeen","location_type":"City","woeid":10243,"latt_long":"57.153820,-2.106790"}]
*lars@spv:~$* curl https://www.metaweather.com/api/location/search/?query=ber | jq

--------------------------------------------

-> terminal <-

*lars@spv:~$* curl https://www.metaweather.com/api/location/search/?query=ber
[{"title":"Berlin","location_type":"City","woeid":638242,"latt_long":"52.516071,13.376980"},{"title":"Nuremberg","location_type":"City","wo
eid":680564,"latt_long":"49.454342,11.07349"},{"title":"Aberdeen","location_type":"City","woeid":10243,"latt_long":"57.153820,-2.106790"}]
*lars@spv:~$* curl https://www.metaweather.com/api/location/search/?query=ber | jq
```
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100   277  100   277    0     0    992      0 --:--:-- --:--:-- --:--:--   992
[
  {
    "title": "Berlin",
    "location_type": "City",
    "woeid": 638242,
    "latt_long": "52.516071,13.376980"
  },
  {
    "title": "Nuremberg",
    "location_type": "City",
    "woeid": 680564,
    "latt_long": "49.454342,11.07349"
  },
  {
    "title": "Aberdeen",
    "location_type": "City",
    "woeid": 10243,
    "latt_long": "57.153820,-2.106790"
  }
]
```

--------------------------------------------