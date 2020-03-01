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

-> Linux terminal <-

*lars@spv:~$*

--------------------------------------------

-> Linux terminal <-

*lars@spv:~$* cowsay "Plask 2020. Awesome!"

--------------------------------------------

-> Linux terminal <-

*lars@spv:~$* cowsay "Plask 2020. Awesome!"

Command 'cowsay' not found, but can be installed with:

sudo apt install cowsay
*lars@spv:~$*

--------------------------------------------

-> Linux terminal <-

*lars@spv:~$* cowsay "Plask 2020. Awesome!"

Command 'cowsay' not found, but can be installed with:

sudo apt install cowsay
*lars@spv:~$* sudo apt -y install cowsay

--------------------------------------------

-> Linux terminal <-

*lars@spv:~$* cowsay "Plask 2020. Awesome!"

Command 'cowsay' not found, but can be installed with:

sudo apt install cowsay
*lars@spv:~$* sudo apt -y install cowsay
[sudo] password for lars:

--------------------------------------------

-> Linux terminal <-

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

-> Linux terminal <-

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

-> Linux terminal <-

*lars@spv:~$*

--------------------------------------------

-> Linux terminal <-

*lars@spv:~$* cowsay "Plask 2020. Awesome!"

--------------------------------------------

-> Linux terminal <-

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

-> Linux terminal <-

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

-> Linux terminal <-

*lars@spv:~$*

--------------------------------------------

-> Linux terminal <-

*lars@spv:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber

--------------------------------------------

-> Linux terminal <-

*lars@spv:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber
[{"title":"Berlin","location_type":"City","woeid":638242,"latt_long":"52.516071,13.376980"},{"title":"Nuremberg","location_type":"City","wo
eid":680564,"latt_long":"49.454342,11.07349"},{"title":"Aberdeen","location_type":"City","woeid":10243,"latt_long":"57.153820,-2.106790"}]
*lars@spv:~$*

--------------------------------------------

-> Linux terminal <-

*lars@spv:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber
[{"title":"Berlin","location_type":"City","woeid":638242,"latt_long":"52.516071,13.376980"},{"title":"Nuremberg","location_type":"City","wo
eid":680564,"latt_long":"49.454342,11.07349"},{"title":"Aberdeen","location_type":"City","woeid":10243,"latt_long":"57.153820,-2.106790"}]
*lars@spv:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber | jq

--------------------------------------------

-> Linux terminal <-

*lars@spv:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber
[{"title":"Berlin","location_type":"City","woeid":638242,"latt_long":"52.516071,13.376980"},{"title":"Nuremberg","location_type":"City","wo
eid":680564,"latt_long":"49.454342,11.07349"},{"title":"Aberdeen","location_type":"City","woeid":10243,"latt_long":"57.153820,-2.106790"}]
*lars@spv:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber | jq
```
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
*lars@spv:~$*

--------------------------------------------

-> Linux terminal <-

*lars@spv:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber
[{"title":"Berlin","location_type":"City","woeid":638242,"latt_long":"52.516071,13.376980"},{"title":"Nuremberg","location_type":"City","wo
eid":680564,"latt_long":"49.454342,11.07349"},{"title":"Aberdeen","location_type":"City","woeid":10243,"latt_long":"57.153820,-2.106790"}]
*lars@spv:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber | jq
```
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
*lars@spv:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber | jq '.[0].title'

--------------------------------------------

-> Linux terminal <-

*lars@spv:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber
[{"title":"Berlin","location_type":"City","woeid":638242,"latt_long":"52.516071,13.376980"},{"title":"Nuremberg","location_type":"City","wo
eid":680564,"latt_long":"49.454342,11.07349"},{"title":"Aberdeen","location_type":"City","woeid":10243,"latt_long":"57.153820,-2.106790"}]
*lars@spv:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber | jq
```
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
*lars@spv:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber | jq '.[0].title'
"Berlin"
*lars@spv:~$*

--------------------------------------------

-> Linux terminal <-

*lars@spv:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber
[{"title":"Berlin","location_type":"City","woeid":638242,"latt_long":"52.516071,13.376980"},{"title":"Nuremberg","location_type":"City","wo
eid":680564,"latt_long":"49.454342,11.07349"},{"title":"Aberdeen","location_type":"City","woeid":10243,"latt_long":"57.153820,-2.106790"}]
*lars@spv:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber | jq
```
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
*lars@spv:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber | jq '.[0].title'
"Berlin"
*lars@spv:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber | jq '.[0].title' -r

--------------------------------------------

-> Linux terminal <-

*lars@spv:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber
[{"title":"Berlin","location_type":"City","woeid":638242,"latt_long":"52.516071,13.376980"},{"title":"Nuremberg","location_type":"City","wo
eid":680564,"latt_long":"49.454342,11.07349"},{"title":"Aberdeen","location_type":"City","woeid":10243,"latt_long":"57.153820,-2.106790"}]
*lars@spv:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber | jq
```
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
*lars@spv:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber | jq '.[0].title'
"Berlin"
*lars@spv:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber | jq '.[0].title' -r
Berlin
*lars@spv:~$*

--------------------------------------------

-> Linux terminal <-

*lars@spv:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber
[{"title":"Berlin","location_type":"City","woeid":638242,"latt_long":"52.516071,13.376980"},{"title":"Nuremberg","location_type":"City","wo
eid":680564,"latt_long":"49.454342,11.07349"},{"title":"Aberdeen","location_type":"City","woeid":10243,"latt_long":"57.153820,-2.106790"}]
*lars@spv:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber | jq
```
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
*lars@spv:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber | jq '.[0].title'
"Berlin"
*lars@spv:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber | jq '.[0].title' -r
Berlin
*lars@spv:~$* clear

--------------------------------------------

-> Linux terminal <-

*lars@spv:~$*

--------------------------------------------

-> Linux terminal <-

*lars@spv:~$* mkdir weather

--------------------------------------------

-> Linux terminal <-

*lars@spv:~$* mkdir weather
*lars@spv:~$*

--------------------------------------------

-> Linux terminal <-

*lars@spv:~$* mkdir weather
*lars@spv:~$* cd weather

--------------------------------------------

-> Linux terminal <-

*lars@spv:~$* mkdir weather
*lars@spv:~$* cd weather
*lars@spv:~/weather$*

--------------------------------------------

-> Linux terminal <-

*lars@spv:~$* mkdir weather
*lars@spv:~$* cd weather
*lars@spv:~/weather$* curl -s https://www.metaweather.com/api/location/search/?query=ber > locations.json

--------------------------------------------

-> Linux terminal <-

*lars@spv:~$* mkdir weather
*lars@spv:~$* cd weather
*lars@spv:~/weather$* curl -s https://www.metaweather.com/api/location/search/?query=ber > locations.json
*lars@spv:~/weather$*

--------------------------------------------

-> Linux terminal <-

*lars@spv:~$* mkdir weather
*lars@spv:~$* cd weather
*lars@spv:~/weather$* curl -s https://www.metaweather.com/api/location/search/?query=ber > locations.json
*lars@spv:~/weather$* ls

--------------------------------------------

-> Linux terminal <-

*lars@spv:~$* mkdir weather
*lars@spv:~$* cd weather
*lars@spv:~/weather$* curl -s https://www.metaweather.com/api/location/search/?query=ber > locations.json
*lars@spv:~/weather$* ls
locations.json
*lars@spv:~/weather$*

--------------------------------------------

-> Linux terminal <-

*lars@spv:~$* mkdir weather
*lars@spv:~$* cd weather
*lars@spv:~/weather$* curl -s https://www.metaweather.com/api/location/search/?query=ber > locations.json
*lars@spv:~/weather$* ls
locations.json
*lars@spv:~/weather$* cat locations.json

--------------------------------------------

-> Linux terminal <-

*lars@spv:~$* mkdir weather
*lars@spv:~$* cd weather
*lars@spv:~/weather$* curl -s https://www.metaweather.com/api/location/search/?query=ber > locations.json
*lars@spv:~/weather$* ls
locations.json
*lars@spv:~/weather$* cat locations.json
[{"title":"Berlin","location_type":"City","woeid":638242,"latt_long":"52.516071,13.376980"},{"title":"Nuremberg","location_type":"City","wo
eid":680564,"latt_long":"49.454342,11.07349"},{"title":"Aberdeen","location_type":"City","woeid":10243,"latt_long":"57.153820,-2.106790"}]
*lars@spv:~/weather$*

--------------------------------------------

-> Linux terminal <-

*lars@spv:~$* mkdir weather
*lars@spv:~$* cd weather
*lars@spv:~/weather$* curl -s https://www.metaweather.com/api/location/search/?query=ber > locations.json
*lars@spv:~/weather$* ls
locations.json
*lars@spv:~/weather$* cat locations.json
[{"title":"Berlin","location_type":"City","woeid":638242,"latt_long":"52.516071,13.376980"},{"title":"Nuremberg","location_type":"City","wo
eid":680564,"latt_long":"49.454342,11.07349"},{"title":"Aberdeen","location_type":"City","woeid":10243,"latt_long":"57.153820,-2.106790"}]
*lars@spv:~/weather$* cat locations.json | jq

--------------------------------------------

-> Linux terminal <-

*lars@spv:~$* mkdir weather
*lars@spv:~$* cd weather
*lars@spv:~/weather$* curl -s https://www.metaweather.com/api/location/search/?query=ber > locations.json
*lars@spv:~/weather$* ls
locations.json
*lars@spv:~/weather$* cat locations.json
[{"title":"Berlin","location_type":"City","woeid":638242,"latt_long":"52.516071,13.376980"},{"title":"Nuremberg","location_type":"City","wo
eid":680564,"latt_long":"49.454342,11.07349"},{"title":"Aberdeen","location_type":"City","woeid":10243,"latt_long":"57.153820,-2.106790"}]
*lars@spv:~/weather$* cat locations.json | jq
```
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
*lars@spv:~/weather$*

--------------------------------------------

-> Linux terminal <-

*lars@spv:~$* mkdir weather
*lars@spv:~$* cd weather
*lars@spv:~/weather$* curl -s https://www.metaweather.com/api/location/search/?query=ber > weather.json
*lars@spv:~/weather$* ls
locations.json
*lars@spv:~/weather$* cat locations.json
[{"title":"Berlin","location_type":"City","woeid":638242,"latt_long":"52.516071,13.376980"},{"title":"Nuremberg","location_type":"City","wo
eid":680564,"latt_long":"49.454342,11.07349"},{"title":"Aberdeen","location_type":"City","woeid":10243,"latt_long":"57.153820,-2.106790"}]
*lars@spv:~/weather$* cat locations.json | jq
```
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
*lars@spv:~/weather$* clear

--------------------------------------------

-> Linux terminal <-

*lars@spv:~/weather$*

--------------------------------------------

-> Linux terminal <-

*lars@spv:~/weather$*  cd ~/numbers

--------------------------------------------

-> Linux terminal <-

*lars@spv:~/numbers$*

--------------------------------------------

-> Linux terminal <-

*lars@spv:~/numbers$* curl -s http://numbersapi.com/42

--------------------------------------------

-> Linux terminal <-

*lars@spv:~/numbers$* curl -s http://numbersapi.com/42
42 is the number of kilometers in a marathon.
*lars@spv:~/numbers$*

--------------------------------------------

-> Linux terminal <-

*lars@spv:~/numbers$* curl -s http://numbersapi.com/42
42 is the number of kilometers in a marathon.
*lars@spv:~/numbers$* for i in {1..100}; do curl -s http://numbersapi.com/${i} >> numbers.txt; echo >> numbers.txt ; done

--------------------------------------------

-> Linux terminal <-

*lars@spv:~/numbers$* curl -s http://numbersapi.com/42
42 is the number of kilometers in a marathon.
*lars@spv:~/numbers$* for i in {1..100}; do curl -s http://numbersapi.com/${i} >> numbers.txt; echo >> numbers.txt ; done
*lars@spv:~/numbers$*

--------------------------------------------

-> Linux terminal <-

*lars@spv:~/numbers$* curl -s http://numbersapi.com/42
42 is the number of kilometers in a marathon.
*lars@spv:~/numbers$* for i in {1..100}; do curl -s http://numbersapi.com/${i} >> numbers.txt; echo >> numbers.txt ; done
*lars@spv:~/numbers$* cat numbers.txt

--------------------------------------------

-> Linux terminal <-

63 is the number of chromosomes found in the offspring of a donkey and a horse.
64 is number of golden disks in the myth of the Tower of Hanoi.
65 is the minimum grade required to pass an exam, or class, in many areas.
66 is the number of years of the longest hiccups on record by an American pig farmer from 1922 to 1987.
67 is the number of counties in Florida.
68 is the number of sectors on one cylinder of MFM hard disks with 4 heads and 17 sectors per track.
69 is the atomic number of thulium, a lanthanide.
70 is the distance (meter) from archer to targets in Olympic Archery.
71 is the number of different characters that can be used with a standard English Keyboard, excluding uppercase letters.
72 is the number of names of God, according to Kabbalah.
73 is the percentage of girls in Bangladesh that are married by age 18.
74 is the atomic number of tungsten.
75 is the age in years that the Saguaro Cactus, found in southwestern US, must be to grow branches.
76 is the atomic number of osmium.
77 is the atomic number of iridium.
78 is the atomic number of platinum.
79 is the record for cumulative weeks at #1 on the Billboard charts, held by Elvis Presley.
80 is a common limit for the characters per line in computing (derived from the number of columns in IBM cards).
81 is the number of squares on a shogi playing board.
82 is the number of games in an NBA or NHL regular season.
83 is the highest UHF channel on older televisions made before the late 1970s.
84 is the atomic number of polonium.
85 is the IQ and nickname of Aaron in Alien 3.
86 is the device number for a lockout relay function in electrical circuit protection schemes.
87 is the number of tools in the Wenger Swiss Army Knife version XXL, listed in the Guinness Book of World Records as the world's most multi-functional penknife.
88 is the number of keys on a piano (36 black and 52 white).
89 is the atomic number of actinium.
90 is the latitude of the North Pole and the South Pole.
91 is the atomic number of protactinium.
92 is the number of stories in the Xujiahui Tower proposed to be built in Shanghai, China.
93 is the atomic number of neptunium.
94 is the length of an NBA court in feet.
95 is the NBA record for Most Assists in a 7-game playoff series (by Magic Johnson of the Los Angeles Lakers in 1984).
96 is the rating of Skyrim on metacritic.com.
97 is the number of different characters that can be used with a standard English Keyboard.
98 is the highest jersey number allowed in the National Hockey League (as 99 was retired by the entire league to honor Wayne Gretzky).
99 is the number of names of Allah, the names or attributes of God in the Qur'an.
100 is the number of pounds in an American short hundredweight.
*lars@spv:~/numbers$*

--------------------------------------------

-> Linux terminal <-

63 is the number of chromosomes found in the offspring of a donkey and a horse.
64 is number of golden disks in the myth of the Tower of Hanoi.
65 is the minimum grade required to pass an exam, or class, in many areas.
66 is the number of years of the longest hiccups on record by an American pig farmer from 1922 to 1987.
67 is the number of counties in Florida.
68 is the number of sectors on one cylinder of MFM hard disks with 4 heads and 17 sectors per track.
69 is the atomic number of thulium, a lanthanide.
70 is the distance (meter) from archer to targets in Olympic Archery.
71 is the number of different characters that can be used with a standard English Keyboard, excluding uppercase letters.
72 is the number of names of God, according to Kabbalah.
73 is the percentage of girls in Bangladesh that are married by age 18.
74 is the atomic number of tungsten.
75 is the age in years that the Saguaro Cactus, found in southwestern US, must be to grow branches.
76 is the atomic number of osmium.
77 is the atomic number of iridium.
78 is the atomic number of platinum.
79 is the record for cumulative weeks at #1 on the Billboard charts, held by Elvis Presley.
80 is a common limit for the characters per line in computing (derived from the number of columns in IBM cards).
81 is the number of squares on a shogi playing board.
82 is the number of games in an NBA or NHL regular season.
83 is the highest UHF channel on older televisions made before the late 1970s.
84 is the atomic number of polonium.
85 is the IQ and nickname of Aaron in Alien 3.
86 is the device number for a lockout relay function in electrical circuit protection schemes.
87 is the number of tools in the Wenger Swiss Army Knife version XXL, listed in the Guinness Book of World Records as the world's most multi-functional penknife.
88 is the number of keys on a piano (36 black and 52 white).
89 is the atomic number of actinium.
90 is the latitude of the North Pole and the South Pole.
91 is the atomic number of protactinium.
92 is the number of stories in the Xujiahui Tower proposed to be built in Shanghai, China.
93 is the atomic number of neptunium.
94 is the length of an NBA court in feet.
95 is the NBA record for Most Assists in a 7-game playoff series (by Magic Johnson of the Los Angeles Lakers in 1984).
96 is the rating of Skyrim on metacritic.com.
97 is the number of different characters that can be used with a standard English Keyboard.
98 is the highest jersey number allowed in the National Hockey League (as 99 was retired by the entire league to honor Wayne Gretzky).
99 is the number of names of Allah, the names or attributes of God in the Qur'an.
100 is the number of pounds in an American short hundredweight.
*lars@spv:~/numbers$* clear

--------------------------------------------

-> Linux terminal <-

*lars@spv:~/numbers$*

--------------------------------------------

-> Linux terminal <-

*lars@spv:~/numbers$* cat numbers.txt | grep atomic

--------------------------------------------

-> Linux terminal <-

*lars@spv:~/numbers$* cat numbers.txt | grep atomic
51 is the *atomic* number of antimony.
69 is the *atomic* number of thulium, a lanthanide.
74 is the *atomic* number of tungsten.
76 is the *atomic* number of osmium.
77 is the *atomic* number of iridium.
78 is the *atomic* number of platinum.
84 is the *atomic* number of polonium.
89 is the *atomic* number of actinium.
91 is the *atomic* number of protactinium.
93 is the *atomic* number of neptunium.
*lars@spv:~/numbers$*

--------------------------------------------

-> Linux terminal <-

*lars@spv:~/numbers$* cat numbers.txt | grep atomic
51 is the *atomic* number of antimony.
69 is the *atomic* number of thulium, a lanthanide.
74 is the *atomic* number of tungsten.
76 is the *atomic* number of osmium.
77 is the *atomic* number of iridium.
78 is the *atomic* number of platinum.
84 is the *atomic* number of polonium.
89 is the *atomic* number of actinium.
91 is the *atomic* number of protactinium.
93 is the *atomic* number of neptunium.
*lars@spv:~/numbers$* clear

--------------------------------------------

-> Linux terminal <-

*lars@spv:~/numbers$*

--------------------------------------------

-> Linux terminal <-

*lars@spv:~/numbers$* figlet "The end!"

--------------------------------------------

-> Linux terminal <-

*lars@spv:~/numbers$* figlet "The end!"
```
 _____ _                           _ _
|_   _| |__   ___    ___ _ __   __| | |
  | | | '_ \ / _ \  / _ \ '_ \ / _` | |
  | | | | | |  __/ |  __/ | | | (_| |_|
  |_| |_| |_|\___|  \___|_| |_|\__,_(_)
```
*lars@spv:~/numbers$*

--------------------------------------------
