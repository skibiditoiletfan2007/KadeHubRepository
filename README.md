
# KadeHub Public
## What is KadeHub?
- #### KadeHub is a script solely developed for the ROBLOX game [The Strongest Battlegrounds](https://www.roblox.com/games/10449761463/The-Strongest-Battlegrounds?AssetId=10449761463).
- #### KadeHub is named the way it is because one of my past usernames was "Kade".


# KadeHub Loadstring
```lua
getgenv().AutoReport = true
if getgenv().KadeHubLoaded ~= true then
    getgenv().KadeHubLoaded = true
   loadstring(game:HttpGet("https://raw.githubusercontent.com/skibiditoiletfan2007/KadeHubRepository/main/Latest.lua"))()
else
    game.StarterGui:SetCore("SendNotification",  {
        Title = "KadeHub";
        Text = "KadeHub is already executed!";
        Icon = "rbxassetid://17893547380";
        Duration = 15;
    })
end
```
## Feedback / Reports / Discord Server

Have any bug reports or feedback or just wanna generally join the discord server? Head on down to the [KadeHub Discord Server](https://discord.gg/V6ETjQ76bP)


## Acknowledgements / Credits

 - dudemonarchy - The Owner, Coded mostly everything
 - ATrain - Anti Garou & Death Blow functions, Instant Dash, Invisibility, Custom Animations 
 - Reap - Having most animation IDs logged on standby, Lock On Function
 - King Dream - Some functions found in KadeHub
 - Tariviste - Bonuis disguise features and finding fixes for Invisibility
 - Dawid - Fluent UI Library
 - Nameless Admin - Walkfling Code
 - Infinite Yield - Camera fixing code
 - Infinite Yield Reborn - Being an awesome side script

