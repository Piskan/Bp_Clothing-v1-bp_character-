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
local skin = exports['bp_character']:characterstyleget(playerid)  ---  playerid = xPlayer.identifier or Player.PlayerData.citizenid

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


------------------------------------------------------------------------------------------------------------------


### DELETE AND TATTO EXPORTS

#### This export delete all character infos like ( character skin, character tattoo , character dress )

```
exports['bp_character']:playerdeleteforcharacter(xPlayer.idenitifer or Player.PlayerData.citizenid)

```

#### This export get player tattoo

```
exports['bp_character']:charactertattoget(playerid)

```


------------------------------------------------------------------------------------------------------------------

### GIVE SKIN MENU FOR ADMINS

#### This command give players skin menus ( barber shop, clothing shop , or operation)

```
/skinmenu playerid (barber,clothing,operation)  --- 3 option 

```

## ESX LEGACY IDENTITY SETTINGS AND INFOS


[![Watch the video](https://kcdn-dfbd.kxcdn.com/wp-content/uploads/2014/02/Click-Here-to-Play-Video.jpg)](https://youtu.be/Q1YL5fnzIG8)



------------------------------------------------------------------------------------------------------------------


## CONFIG SETTINGS

#### This settings for base type

```
Config.framework = 'ESX' -- FRAMEWORK! , "ESX", "QBCORE"

```

#### This settings for sql type

```
Config.Mysql = 'mysql-async' -- "ghmattisql", "mysql-async", "oxmysql"

```

#### This settings for open esx:playerload or qb:onplayerload events

```
Config.useplayerload = false 

```

#### This settings for pedmenu permission with steam hex id


```
Config.pedmenulist = {
    ["steam"] = "steam:11000010e15e4d1"
}

```

------------------------------------------------------------------------------------------------------------------

## ESX MULTICHARACTER

#### ESX MULTICHARACTER 

####Support is not given because all settings are made for esx_skin. I'm just throwing a version that you can use without installing peds

#### Do not miss open bp_character > config > Config.useplayerload = true

### LINK :  [MULTICHARACTER](https://easyupload.io/eb4hu1).

------------------------------------------------------------------------------------------------------------------

## QB MULTICHARACTER INFOS

### LINK :  [QB-MULTICHARACTER-EXAMPLE](https://easyupload.io/8zo7ep).

#### QB MULTICHARACTER - CLIENT PART

![This is an image](https://i.hizliresim.com/78rubl3.PNG)

#### QB MULTICHARACTER - SERVER PART

![This is an image](https://i.hizliresim.com/ri94qkf.PNG)


