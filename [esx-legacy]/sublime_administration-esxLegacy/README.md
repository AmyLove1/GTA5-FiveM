# sublime_administration

- __dependency__ : ``es_extended LEGACY``

- __library__ : ``RageUI v2.1.7``

- __conso cpu@client__ : ``0.00ms - 0.01ms``

[require] :

> https://github.com/esx-framework/esx-legacy
-
> https://github.com/brouznouf/fivem-mysql-async
or 
> https://github.com/overextended/oxmysql

#


# preview

> https://www.youtube.com/watch?v=Zb7TNJ-2jSw

:fr:

# configuration
Tout ce passe dans le fichier "Shared" !

# exports !

Voici les functions disponibles sous exports : 

```lua
-- Return si le menu est ouvert
exports['sublime_administration']:isAdminPanelOpened()

-- Return si le player et utilise le noclip
exports['sublime_administration']:isAdminNoClip()

-- Return la météo actuelle
exports['sublime_administration']:getCurrentWeather()

-- Envoie un logs discord
exports['sublime_administration']:sendLogs("message")
```
