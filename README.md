<h1 align='center'>BP CHARACTER</a></h1><p align='center'><b><a href='https://discord.gg/uvRdnGPNF7'>Discord</a> - <a href='https://0resmon.tebex.io/'>Website</a></b></h5>




## USE OF EXPORT

```
TriggerServerEvent('bp_character:isthisfirst')

```

#### This export control your “charksin” table in database.

![This is an image](https://i.hizliresim.com/a51u12b.PNG)

#### İf your data is empty open character create screen . İf your data is not empty load skins your ped.




------------------------------------------------------------------------------------------------------------------


### GET PLAYER CLOTHINGS

#### This export gets all the clothing information of the character

```
local skin = exports['bp_character']:characterstyleget(playerid)

```

#### This event set skin for ped

```
TriggerEvent('bp_character:insertped',ped,skin)

```

#### EXAMPLE:

#### Get informatin in server.lua and send 

![This is an image](https://i.hizliresim.com/nwb5kdw.PNG)

#### Send skin with event in client.lua

![This is an image](https://i.hizliresim.com/qvxi8ca.PNG)
