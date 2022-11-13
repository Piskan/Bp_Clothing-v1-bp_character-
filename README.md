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

#### Config Add job menus 



```
{
        ["job"] = "ems",             -------- job name from database
        ["jobcoords"] = vector3(309.79,-602.11,43.28),    -------- location
        ["joblabel"] = "[E] Job Clothing",
        ["jobclothings"] = {
            {
                ["jobsubname"] = "ems_1",   -------- clothing uniq id
                ["jobsublabel"] = "Ems",       -------- clothing name
                male = {
                    ['tshirt_1'] = 59, ['tshirt_2'] = 1,
                    ['torso_1'] = 80, ['torso_2'] = 0,
                    ['decals_1'] = 0, ['decals_2'] = 0,
                    ['arms'] = 41,
                    ['pants_1'] = 15, ['pants_2'] = 2,
                    ['shoes_1'] = 25, ['shoes_2'] = 0,
                    ['helmet_1'] = 46, ['helmet_2'] = 0,
                    ['chain_1'] = 0, ['chain_2'] = 0,
                    ['ears_1'] = 2, ['ears_2'] = 0
                },
                female = {
                    ['tshirt_1'] = 36, ['tshirt_2'] = 1,
                    ['torso_1'] = 48, ['torso_2'] = 0,
                    ['decals_1'] = 0, ['decals_2'] = 0,
                    ['arms'] = 44,
                    ['pants_1'] = 34, ['pants_2'] = 0,
                    ['shoes_1'] = 27, ['shoes_2'] = 0,
                    ['helmet_1'] = 45, ['helmet_2'] = 0,
                    ['chain_1'] = 0, ['chain_2'] = 0,
                    ['ears_1'] = 2, ['ears_2'] = 0
                }
         
           },
           {
            ["jobsubname"] = "ems_2",
            ["jobsublabel"] = "Ems2",
            male = {
                ['tshirt_1'] = 59, ['tshirt_2'] = 1,
                ['torso_1'] = 80, ['torso_2'] = 0,
                ['decals_1'] = 0, ['decals_2'] = 0,
                ['arms'] = 41,
                ['pants_1'] = 15, ['pants_2'] = 2,
                ['shoes_1'] = 25, ['shoes_2'] = 0,
                ['helmet_1'] = 46, ['helmet_2'] = 0,
                ['chain_1'] = 0, ['chain_2'] = 0,
                ['ears_1'] = 2, ['ears_2'] = 0
            },
            female = {
                ['tshirt_1'] = 36, ['tshirt_2'] = 1,
                ['torso_1'] = 48, ['torso_2'] = 0,
                ['decals_1'] = 0, ['decals_2'] = 0,
                ['arms'] = 44,
                ['pants_1'] = 34, ['pants_2'] = 0,
                ['shoes_1'] = 27, ['shoes_2'] = 0,
                ['helmet_1'] = 45, ['helmet_2'] = 0,
                ['chain_1'] = 0, ['chain_2'] = 0,
                ['ears_1'] = 2, ['ears_2'] = 0
            }
     
       }

         
        }
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


