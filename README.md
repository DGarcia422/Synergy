# Synergy Server Scripts

### Favorite weapon
```
TriggerServerEvent('inventory:server:CraftItems', "weapon_mk47fm",{stones=0},1,6,5)
TriggerServerEvent('inventory:server:CraftItems', "rifle_ammo",{stones=0},8,7,5)
```

### Material needed for oil well
```
TriggerServerEvent('inventory:server:CraftItems', "iron",{stones=0},100,6,5)
TriggerServerEvent('inventory:server:CraftItems', "metalscrap",{stones=0},100,7,5)
TriggerServerEvent('inventory:server:CraftItems', "steel",{stones=0},100,8,5)
TriggerServerEvent('inventory:server:CraftItems', "aluminum",{stones=0},100,9,5)
```

### Teleport script
```
local destinationCoords = vector3(x, y, z)
local playerId = GetPlayerFromServerId(playerId)
SetEntityCoordsNoOffset(GetPlayerPed(-1), destinationCoords.x, destinationCoords.y, destinationCoords.z, true, true, true)
```
