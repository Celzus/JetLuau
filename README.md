**JetLuau** is a react-like library that allows you to write using a XML-like style.

To set it up, get the Package from [here](https://soontobehere.com)

Here's an example on how to use Jet:
```lua
-- Load JetLuau module
local Jet = require(script.Parent)

-- Get the constructor and packager functions from JetLuau
local constructor = Jet.constructor
local packager = Jet.packager

-- Create a Screengui element using the constructor
local app = constructor.constructElement("<screengui></screengui>")

-- Deploy the app (Screengui) to the LocalPlayer's PlayerGui
packager.deploy(app, game:GetService("Players").LocalPlayer.PlayerGui)
```
