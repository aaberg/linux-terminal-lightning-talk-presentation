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







-> # Installation of new cli tools <-

-> *apt* <-

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$*

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* cowsay "Plask 2020. Awesome!"

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* cowsay "Plask 2020. Awesome!"

Command 'cowsay' not found, but can be installed with:

sudo apt install cowsay
*lars@sonat:~$*

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* cowsay "Plask 2020. Awesome!"

Command 'cowsay' not found, but can be installed with:

sudo apt install cowsay
*lars@sonat:~$* sudo apt -y install cowsay

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* cowsay "Plask 2020. Awesome!"

Command 'cowsay' not found, but can be installed with:

sudo apt install cowsay
*lars@sonat:~$* sudo apt -y install cowsay
[sudo] password for lars:

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* cowsay "Plask 2020. Awesome!"

Command 'cowsay' not found, but can be installed with:

sudo apt install cowsay
*lars@sonat:~$* sudo apt -y install cowsay
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
*lars@sonat:~$*

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* cowsay "Plask 2020. Awesome!"

Command 'cowsay' not found, but can be installed with:

sudo apt install cowsay
*lars@sonat:~$* sudo apt -y install cowsay
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
*lars@sonat:~$* clear

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$*

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* cowsay "Plask 2020. Awesome!"

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* cowsay "Plask 2020. Awesome!"
| ______________________
|< Plask 2020. Awesome! >
| ----------------------
|        \\   ^__^
|         \\  (oo)\\_______
|            (__)\\       )\\/\\
|                ||----w |
|                ||     ||
*lars@sonat:~$* 

--------------------------------------------

-> Linux terminal <-






|                    *Linux streams*

```
        
                     ---------------
                    |               |
                    |               | 
         stdin ---> |    Program    | ---> stdout (1)
                    |               | 
                    |               |
                     ---------------
                            |
                            |
                             ----> stderr (2)
                            
```

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$*

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* echo

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* echo Plask 2020

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* echo Plask 2020
Plask 2020
*lars@sonat:~$*

--------------------------------------------

-> Linux terminal <-






-> # Redirect stdout to file <-

-> ( \> ) operator <-

-> Demonstrert med *echo*, *curl* og og *cat* <-

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$*

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* echo Plash 2020 > plask.txt

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* echo Plash 2020 > plask.txt
*lars@sonat:~$*

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* echo Plash 2020 > plask.txt
*lars@sonat:~$* cat plask.txt

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* echo Plash 2020 > plask.txt
*lars@sonat:~$* cat plask.txt
Plask 2020
*lars@sonat:~$*

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* echo Plash 2020 > plask.txt
*lars@sonat:~$* cat plask.txt
Plask 2020
*lars@sonat:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* echo Plash 2020 > plask.txt
*lars@sonat:~$* cat plask.txt
Plask 2020
*lars@sonat:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber
[{"title":"Berlin","location_type":"City","woeid":638242,"latt_long":"52.516071,13.376980"},{"title":"Nuremberg","location_type":"City","wo
eid":680564,"latt_long":"49.454342,11.07349"},{"title":"Aberdeen","location_type":"City","woeid":10243,"latt_long":"57.153820,-2.106790"}]
*lars@sonat:~$*

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* echo Plash 2020 > plask.txt
*lars@sonat:~$* cat plask.txt
Plask 2020
*lars@sonat:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber
[{"title":"Berlin","location_type":"City","woeid":638242,"latt_long":"52.516071,13.376980"},{"title":"Nuremberg","location_type":"City","wo
eid":680564,"latt_long":"49.454342,11.07349"},{"title":"Aberdeen","location_type":"City","woeid":10243,"latt_long":"57.153820,-2.106790"}]
*lars@sonat:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber > data.json

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* echo Plash 2020 > plask.txt
*lars@sonat:~$* cat plask.txt
Plask 2020
*lars@sonat:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber
[{"title":"Berlin","location_type":"City","woeid":638242,"latt_long":"52.516071,13.376980"},{"title":"Nuremberg","location_type":"City","wo
eid":680564,"latt_long":"49.454342,11.07349"},{"title":"Aberdeen","location_type":"City","woeid":10243,"latt_long":"57.153820,-2.106790"}]
*lars@sonat:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber > data.json
*lars@sonat:~$*

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* echo Plash 2020 > plask.txt
*lars@sonat:~$* cat plask.txt
Plask 2020
*lars@sonat:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber
[{"title":"Berlin","location_type":"City","woeid":638242,"latt_long":"52.516071,13.376980"},{"title":"Nuremberg","location_type":"City","wo
eid":680564,"latt_long":"49.454342,11.07349"},{"title":"Aberdeen","location_type":"City","woeid":10243,"latt_long":"57.153820,-2.106790"}]
*lars@sonat:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber > data.json
*lars@sonat:~$* cat data.json

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* echo Plash 2020 > plask.txt
*lars@sonat:~$* cat plask.txt
Plask 2020
*lars@sonat:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber
[{"title":"Berlin","location_type":"City","woeid":638242,"latt_long":"52.516071,13.376980"},{"title":"Nuremberg","location_type":"City","wo
eid":680564,"latt_long":"49.454342,11.07349"},{"title":"Aberdeen","location_type":"City","woeid":10243,"latt_long":"57.153820,-2.106790"}]
*lars@sonat:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber > data.json
*lars@sonat:~$* cat data.json
[{"title":"Berlin","location_type":"City","woeid":638242,"latt_long":"52.516071,13.376980"},{"title":"Nuremberg","location_type":"City","wo
eid":680564,"latt_long":"49.454342,11.07349"},{"title":"Aberdeen","location_type":"City","woeid":10243,"latt_long":"57.153820,-2.106790"}]
*lars@sonat:~$*

--------------------------------------------

-> Linux terminal <-






-> # Redirect from file to stdin <-

-> ( < ) operator <-

-> Demonstrert med wc, *curl*, *cat* og *jq* <-

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$*

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* curl -s http://metaphorpsum.com/paragraphs/20 > lorem.txt

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* curl -s http://metaphorpsum.com/paragraphs/20 > lorem.txt
*lars@sonat:~$*

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* curl -s http://metaphorpsum.com/paragraphs/20 > lorem.txt
*lars@sonat:~$* cat lorem.txt

--------------------------------------------

-> Linux terminal <-

A mask sees an indonesia as a blameful shear. The whilom party comes from a picked pound. 
A march of the feather is assumed to be a teeny mimosa.


Some assert that a car is a griefless address. A format is a persian from the right perspe
ctive. A missive story is an action of the mind.


However, few can name a dreggy chicory that isn't a looser regret. Those batteries are not
hing more than jackets. It's an undeniable fact, really; the tergal bus comes from a salta
nt Santa. A watchmaker can hardly be considered a sincere step-son without also being a drop.


A tuba can hardly be considered a tarmac smile without also being a gallon. What we don't 
know for sure is whether or not the unstuck stem comes from a lightish visitor. A yogurt 
of the white is assumed to be a hydric design. Unfortunately, that is wrong; on the contr
ary, the eels could be said to resemble daylong tornadoes.

Some assert that a car is a griefless address. A format is a persian from the right perspe
ctive. A missive story is an action of the mind.


However, few can name a dreggy chicory that isn't a looser regret. Those batteries are not
hing more than jackets. It's an undeniable fact, really; the tergal bus comes from a salta
nt Santa. A watchmaker can hardly be considered a sincere step-son without also being a drop.
*lars@sonat:~$*

--------------------------------------------

-> Linux terminal <-

A mask sees an indonesia as a blameful shear. The whilom party comes from a picked pound. 
A march of the feather is assumed to be a teeny mimosa.


Some assert that a car is a griefless address. A format is a persian from the right perspe
ctive. A missive story is an action of the mind.


However, few can name a dreggy chicory that isn't a looser regret. Those batteries are not
hing more than jackets. It's an undeniable fact, really; the tergal bus comes from a salta
nt Santa. A watchmaker can hardly be considered a sincere step-son without also being a drop.


A tuba can hardly be considered a tarmac smile without also being a gallon. What we don't 
know for sure is whether or not the unstuck stem comes from a lightish visitor. A yogurt 
of the white is assumed to be a hydric design. Unfortunately, that is wrong; on the contr
ary, the eels could be said to resemble daylong tornadoes.

Some assert that a car is a griefless address. A format is a persian from the right perspe
ctive. A missive story is an action of the mind.


However, few can name a dreggy chicory that isn't a looser regret. Those batteries are not
hing more than jackets. It's an undeniable fact, really; the tergal bus comes from a salta
nt Santa. A watchmaker can hardly be considered a sincere step-son without also being a drop.
*lars@sonat:~$* clear

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* 

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* wc -w < lorem.txt

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* wc -w < lorem.txt
937
*lars@sonat:~$*

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* wc -w < lorem.txt
937
*lars@sonat:~$* cat data.json

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* wc -w < lorem.txt
937
*lars@sonat:~$* cat data.json
\[{"title":"Berlin","location_type":"City","woeid":638242,"latt_long":"52.516071,13.376980"},{"title":"Nuremberg","location_type":"City","wo
eid":680564,"latt_long":"49.454342,11.07349"},{"title":"Aberdeen","location_type":"City","woeid":10243,"latt_long":"57.153820,-2.106790"}]
*lars@sonat:~$*

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* wc -w < lorem.txt
937
*lars@sonat:~$* cat data.json
\[{"title":"Berlin","location_type":"City","woeid":638242,"latt_long":"52.516071,13.376980"},{"title":"Nuremberg","location_type":"City","wo
eid":680564,"latt_long":"49.454342,11.07349"},{"title":"Aberdeen","location_type":"City","woeid":10243,"latt_long":"57.153820,-2.106790"}]
*lars@sonat:~$* jq < data.json

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* wc -w < lorem.txt
937
*lars@sonat:~$* cat data.json
\[{"title":"Berlin","location_type":"City","woeid":638242,"latt_long":"52.516071,13.376980"},{"title":"Nuremberg","location_type":"City","wo
eid":680564,"latt_long":"49.454342,11.07349"},{"title":"Aberdeen","location_type":"City","woeid":10243,"latt_long":"57.153820,-2.106790"}]
*lars@sonat:~$* jq < data.json
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
*lars@sonat:~$*


--------------------------------------------

-> Linux terminal <-






-> # Piping <-

-> ( | ) operator <-

-> Demonstrert med *curl*, *jq* og *cat* <-

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$*

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber
[{"title":"Berlin","location_type":"City","woeid":638242,"latt_long":"52.516071,13.376980"},{"title":"Nuremberg","location_type":"City","wo
eid":680564,"latt_long":"49.454342,11.07349"},{"title":"Aberdeen","location_type":"City","woeid":10243,"latt_long":"57.153820,-2.106790"}]
*lars@sonat:~$*

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber
[{"title":"Berlin","location_type":"City","woeid":638242,"latt_long":"52.516071,13.376980"},{"title":"Nuremberg","location_type":"City","wo
eid":680564,"latt_long":"49.454342,11.07349"},{"title":"Aberdeen","location_type":"City","woeid":10243,"latt_long":"57.153820,-2.106790"}]
*lars@sonat:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber | jq

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber
[{"title":"Berlin","location_type":"City","woeid":638242,"latt_long":"52.516071,13.376980"},{"title":"Nuremberg","location_type":"City","wo
eid":680564,"latt_long":"49.454342,11.07349"},{"title":"Aberdeen","location_type":"City","woeid":10243,"latt_long":"57.153820,-2.106790"}]
*lars@sonat:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber | jq
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
*lars@sonat:~$*

--------------------------------------------

-> Linux terminal <-






-> Scripting og annet gøy <-

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$*

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber | jq

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber | jq
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
*lars@sonat:~$*

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber | jq
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
*lars@sonat:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber | jq '.[0].title'

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber | jq
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
*lars@sonat:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber | jq '.[0].title'
"Berlin"
*lars@sonat:~$*

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber | jq
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
*lars@sonat:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber | jq '.[0].title'
"Berlin"
*lars@sonat:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber | jq '.[0].title' -r

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber | jq
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
*lars@sonat:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber | jq '.[0].title'
"Berlin"
*lars@sonat:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber | jq '.[0].title' -r
Berlin
*lars@sonat:~$*

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber | jq
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
*lars@sonat:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber | jq '.[0].title'
"Berlin"
*lars@sonat:~$* curl -s https://www.metaweather.com/api/location/search/?query=ber | jq '.[0].title' -r
Berlin
*lars@sonat:~$* clear

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$*

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* mkdir numbers

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* mkdir numbers
*lars@sonat:~$*

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* mkdir numbers
*lars@sonat:~$* cd numbers

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* mkdir numbers
*lars@sonat:~$* cd numbers
*lars@sonat:~/numbers$*

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~$* mkdir numbers
*lars@sonat:~$* cd numbers
*lars@sonat:~/numbers$* clear

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~/numbers$*

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~/numbers$* curl -s http://numbersapi.com/42

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~/numbers$* curl -s http://numbersapi.com/42
42 is the number of kilometers in a marathon.
*lars@sonat:~/numbers$*

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~/numbers$* curl -s http://numbersapi.com/42
42 is the number of kilometers in a marathon.
*lars@sonat:~/numbers$* for i in {1..100}; do curl -s http://numbersapi.com/${i} >> numbers.txt; echo >> numbers.txt ; done

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~/numbers$* curl -s http://numbersapi.com/42
42 is the number of kilometers in a marathon.
*lars@sonat:~/numbers$* for i in {1..100}; do curl -s http://numbersapi.com/${i} >> numbers.txt; echo >> numbers.txt ; done
*lars@sonat:~/numbers$*

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~/numbers$* curl -s http://numbersapi.com/42
42 is the number of kilometers in a marathon.
*lars@sonat:~/numbers$* for i in {1..100}; do curl -s http://numbersapi.com/${i} >> numbers.txt; echo >> numbers.txt ; done
*lars@sonat:~/numbers$* cat numbers.txt

--------------------------------------------

-> Linux terminal <-

75 is the age limit for Canadian senators.
76 is the atomic number of osmium.
77 is the atomic number of iridium.
78 is the number of lines that make up Metatron's Cube.
79 is the record for cumulative weeks at #1 on the Billboard charts, held by Elvis Presley.
80 is the standard TCP/IP port number used for HTTP connections.
81 is the number of squares on a shogi playing board.
82 is the number of games in an NBA or NHL regular season.
83 is the atomic number of bismuth.
84 is the code for international direct dial phone calls to Vietnam.
85 is the IQ and nickname of Aaron in Alien 3.
86 is the device number for a lockout relay function in electrical circuit protection schemes.
87 is the number of tools in the Wenger Swiss Army Knife version XXL, listed in the Guinness Book of World Records as the world's most multi-functional penknife.
88 is the pounds of oxygen that the adult human body requires daily.
89 is the number of units of each colour in the board game Blokus.
90 is the number of minutes in a football (soccer) match.
91 is the atomic number of protactinium.
92 is the number of stories in the Xujiahui Tower proposed to be built in Shanghai, China.
93 is the atomic number of neptunium.
94 is the atomic number of plutonium.
95 is the percentage confidence interval that is considered satisfactory for most purposes in statistics.
96 is the rating of Skyrim on metacritic.com.
97 is the number of minutes it takes the Hubble space telescope to complete an orbit around the Earth.
98 is the temperature (F) of the normal body.
99 is the highest jersey number allowed in most major league sports.
100 is the record number of points scored in one NBA game by a single player, set by Wilt Chamberlain of the Philadelphia Warriors on March 2, 1962 I.
*lars@sonat:~/numbers$*

--------------------------------------------

-> Linux terminal <-

75 is the age limit for Canadian senators.
76 is the atomic number of osmium.
77 is the atomic number of iridium.
78 is the number of lines that make up Metatron's Cube.
79 is the record for cumulative weeks at #1 on the Billboard charts, held by Elvis Presley.
80 is the standard TCP/IP port number used for HTTP connections.
81 is the number of squares on a shogi playing board.
82 is the number of games in an NBA or NHL regular season.
83 is the atomic number of bismuth.
84 is the code for international direct dial phone calls to Vietnam.
85 is the IQ and nickname of Aaron in Alien 3.
86 is the device number for a lockout relay function in electrical circuit protection schemes.
87 is the number of tools in the Wenger Swiss Army Knife version XXL, listed in the Guinness Book of World Records as the world's most multi-functional penknife.
88 is the pounds of oxygen that the adult human body requires daily.
89 is the number of units of each colour in the board game Blokus.
90 is the number of minutes in a football (soccer) match.
91 is the atomic number of protactinium.
92 is the number of stories in the Xujiahui Tower proposed to be built in Shanghai, China.
93 is the atomic number of neptunium.
94 is the atomic number of plutonium.
95 is the percentage confidence interval that is considered satisfactory for most purposes in statistics.
96 is the rating of Skyrim on metacritic.com.
97 is the number of minutes it takes the Hubble space telescope to complete an orbit around the Earth.
98 is the temperature (F) of the normal body.
99 is the highest jersey number allowed in most major league sports.
100 is the record number of points scored in one NBA game by a single player, set by Wilt Chamberlain of the Philadelphia Warriors on March 2, 1962 I.
*lars@sonat:~/numbers$* clear

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~/numbers$*

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~/numbers$* cat numbers.txt | grep atomic

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~/numbers$* cat numbers.txt | grep atomic
51 is the *atomic* number of antimony.
62 is the *atomic* number of samarium.
71 is the *atomic* number of lutetium.
76 is the *atomic* number of osmium.
77 is the *atomic* number of iridium.
83 is the *atomic* number of bismuth.
91 is the *atomic* number of protactinium.
93 is the *atomic* number of neptunium.
94 is the *atomic* number of plutonium.
*lars@sonat:~/numbers$*

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~/numbers$* cat numbers.txt | grep atomic
51 is the *atomic* number of antimony.
62 is the *atomic* number of samarium.
71 is the *atomic* number of lutetium.
76 is the *atomic* number of osmium.
77 is the *atomic* number of iridium.
83 is the *atomic* number of bismuth.
91 is the *atomic* number of protactinium.
93 is the *atomic* number of neptunium.
94 is the *atomic* number of plutonium.
*lars@sonat:~/numbers$* clear

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~/numbers$*

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~/numbers$* cat numbers.txt | tail -10

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~/numbers$* cat numbers.txt | tail -10
91 is the atomic number of protactinium.
92 is the number of stories in the Xujiahui Tower proposed to be built in Shanghai, China.
93 is the atomic number of neptunium.
94 is the atomic number of plutonium.
95 is the percentage confidence interval that is considered satisfactory for most purposes in statistics.
96 is the rating of Skyrim on metacritic.com.
97 is the number of minutes it takes the Hubble space telescope to complete an orbit around the Earth.
98 is the temperature (F) of the normal body.
99 is the highest jersey number allowed in most major league sports.
100 is the record number of points scored in one NBA game by a single player, set by Wilt Chamberlain of the Philadelphia Warriors on March 2, 1962 I.
*lars@sonat:~/numbers$*

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~/numbers$* cat numbers.txt | tail -10
91 is the atomic number of protactinium.
92 is the number of stories in the Xujiahui Tower proposed to be built in Shanghai, China.
93 is the atomic number of neptunium.
94 is the atomic number of plutonium.
95 is the percentage confidence interval that is considered satisfactory for most purposes in statistics.
96 is the rating of Skyrim on metacritic.com.
97 is the number of minutes it takes the Hubble space telescope to complete an orbit around the Earth.
98 is the temperature (F) of the normal body.
99 is the highest jersey number allowed in most major league sports.
100 is the record number of points scored in one NBA game by a single player, set by Wilt Chamberlain of the Philadelphia Warriors on March 2, 1962 I.
*lars@sonat:~/numbers$* cat numbers.txt | tail -10 | grep atomic

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~/numbers$* cat numbers.txt | tail -10
91 is the atomic number of protactinium.
92 is the number of stories in the Xujiahui Tower proposed to be built in Shanghai, China.
93 is the atomic number of neptunium.
94 is the atomic number of plutonium.
95 is the percentage confidence interval that is considered satisfactory for most purposes in statistics.
96 is the rating of Skyrim on metacritic.com.
97 is the number of minutes it takes the Hubble space telescope to complete an orbit around the Earth.
98 is the temperature (F) of the normal body.
99 is the highest jersey number allowed in most major league sports.
100 is the record number of points scored in one NBA game by a single player, set by Wilt Chamberlain of the Philadelphia Warriors on March 2, 1962 I.
*lars@sonat:~/numbers$* cat numbers.txt | tail -10 | grep atomic
91 is the atomic *number* of protactinium.
93 is the atomic *number* of neptunium.
94 is the atomic *number* of plutonium.
*lars@sonat:~/numbers$*

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~/numbers$* cat numbers.txt | tail -10
91 is the atomic number of protactinium.
92 is the number of stories in the Xujiahui Tower proposed to be built in Shanghai, China.
93 is the atomic number of neptunium.
94 is the atomic number of plutonium.
95 is the percentage confidence interval that is considered satisfactory for most purposes in statistics.
96 is the rating of Skyrim on metacritic.com.
97 is the number of minutes it takes the Hubble space telescope to complete an orbit around the Earth.
98 is the temperature (F) of the normal body.
99 is the highest jersey number allowed in most major league sports.
100 is the record number of points scored in one NBA game by a single player, set by Wilt Chamberlain of the Philadelphia Warriors on March 2, 1962 I.
*lars@sonat:~/numbers$* cat numbers.txt | tail -10 | grep atomic
91 is the atomic *number* of protactinium.
93 is the atomic *number* of neptunium.
94 is the atomic *number* of plutonium.
*lars@sonat:~/numbers$* clear

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~/numbers$*

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~/numbers$* figlet "The end!"

--------------------------------------------

-> Linux terminal <-

*lars@sonat:~/numbers$* figlet "The end!"
```
 _____ _                           _ _
|_   _| |__   ___    ___ _ __   __| | |
  | | | '_ \ / _ \  / _ \ '_ \ / _` | |
  | | | | | |  __/ |  __/ | | | (_| |_|
  |_| |_| |_|\___|  \___|_| |_|\__,_(_)
```
*lars@sonat:~/numbers$*

--------------------------------------------
