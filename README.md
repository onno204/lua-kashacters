# KASHacters - ESX Multi Characters

## Introduction

> I've seen a lot of request to have ESX Multi Character, while working on my own framework I've made it multiple times and wanted to try it out with ESX. I tried to edit as less possible to the core of essentialmode or es_extended and it worked well :) PS. just don't mind the name...

## Code Samples

> You can edit it all you want, this release is not my main priority for coding so support for this will be limited but if you have any questions just send a message to **KASH#0205** on Discord (you  might need to add me first).

## Installation

> First of all to get this working you need to comment out the `NetworkIsSessionStarted()` Citizen.CreateThread() in *essentialmode\client\main.lua* on line *6 - 16*

>Second you need to upload the SQL file to your database **BEFORE** you start the resource.

>At last you will put the resource (*esx_kashacters*) in your resource folder.

>In the *esx_kashacters\server\main.lua* you can edit the tables where an identifier is needed as such:
```
local IdentifierTables = {
    {table = "users", column = "identifier"},
    {table = "owned_vehicles", column = "owner"},
    {table = "user_accounts", column = "identifier"},
}
```

## Credits

> ESX Framework and **KASH** for creating the resource. You can do whatever the f with it what you want but it is nice to give the main man credits ;)

- LOVE KASH (Discord: KASH#0205)
