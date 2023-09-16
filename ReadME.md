# Unofficial Documentary Of Fluxlib
sadly colorpicker don't work for mobile and the slider
# Getting the Loadstring
needed to make your script work
```lua
local Flux = loadstring(game:HttpGet"https://raw.githubusercontent.com/ExploitCoder7/123/main/fluxlib.txt")()
```

## Creating a Window
```lua
local win = Flux:Window(" ", " ", Color3.fromRGB(0,0,0), Enum.KeyCode.LeftControl)
--[[
first arg is the name
second arg is the description
third is Color
]]
```

## Notifying the User
```lua
Flux:Notification("", "Button")
--[[
First arg is the text
second arg is buttons
```

## Creating Tabs
```lua
local TabNameHere = win:Tab("Tab 1", "http://www.roblox.com/asset/?id=6023426915")
--[[
first arg is Name
second arg is Icon
]]
```

## Creating Labels
Sadly there's no section...
```lua
tabname:Label("This is just a label.")
--[[
first arg is the label text
]]
```

## Creating Lines
```lua
tabname:Line()
```

## Creating Textboxes
```lua
tab:Textbox("TextBox", "Description", true, function(Value) 
 print("Value") 
 end)
--[[
first arg is Name
second arg is Description
third is idfk
]]
```
