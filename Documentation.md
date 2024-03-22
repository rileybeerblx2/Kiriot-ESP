# Kiriot ESP
This documentation is for Kiriot ESP Credit To Kiriot

## Booting the Kiriot ESP Loadstring
```lua
-- loadstring
local ESP = loadstring(game:HttpGet("https://kiriot22.com/releases/ESP.lua"))()
```




## Creating The ESP Config
```lua
-- config
ESP.Tracers = true
ESP.Players = true
ESP.Boxes = true
ESP.Names = true
ESP:Toggle(true)
```

## Creating The ESP Config (Without Tracers)
```lua
-- config
ESP.Players = true
ESP.Boxes = true
ESP.Names = true
ESP:Toggle(true)
```

## Creating The ESP Object
```lua
-- object
ESP:AddObjectListener(Workspace, { -- Object Path, For example: Workspace.ThisFolder
    Name = "", --Object name inside of the path, for example: Workspace.ThisFolder.Item_1
    CustomName = "", -- Name you want to be displayed
    Color = Color3.fromRGB(0, 0, 0), -- Color
    IsEnabled = "whatever" -- Any name, has to be the same as the last line: ESP.TheNameYouWant
})
ESP.whatever = true
```
