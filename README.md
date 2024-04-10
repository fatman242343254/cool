-- Gui to Lua
-- Version: 3.6

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local Prisonlifegui = Instance.new("TextLabel")
local Aimbot = Instance.new("TextButton")
local UICorner = Instance.new("UICorner")
local Esp = Instance.new("TextButton")
local UICorner_2 = Instance.new("UICorner")
local ModM9 = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local Fly = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local KillAll = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local Noclip = Instance.new("TextButton")
local Getshotgun = Instance.new("TextButton")
local Misc = Instance.new("TextButton")

-- Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(97, 97, 97)
Frame.BackgroundTransparency = 0.300
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.356729388, 0, 0.188566327, 0)
Frame.Size = UDim2.new(0, 360, 0, 360)
Frame.Active
Frame.Draggable

Prisonlifegui.Name = "Prison life gui"
Prisonlifegui.Parent = Frame
Prisonlifegui.BackgroundColor3 = Color3.fromRGB(85, 85, 85)
Prisonlifegui.BackgroundTransparency = 0.250
Prisonlifegui.BorderColor3 = Color3.fromRGB(0, 0, 0)
Prisonlifegui.BorderSizePixel = 0
Prisonlifegui.Position = UDim2.new(0.247222215, 0, 0, 0)
Prisonlifegui.Size = UDim2.new(0, 200, 0, 50)
Prisonlifegui.Font = Enum.Font.SourceSans
Prisonlifegui.Text = "Prison life gui"
Prisonlifegui.TextColor3 = Color3.fromRGB(0, 0, 0)
Prisonlifegui.TextSize = 30.000

Aimbot.Name = "Aimbot"
Aimbot.Parent = Frame
Aimbot.BackgroundColor3 = Color3.fromRGB(85, 85, 85)
Aimbot.BackgroundTransparency = 0.250
Aimbot.BorderColor3 = Color3.fromRGB(0, 0, 0)
Aimbot.BorderSizePixel = 0
Aimbot.Position = UDim2.new(0.0444444455, 0, 0.194444448, 0)
Aimbot.Size = UDim2.new(0, 100, 0, 50)
Aimbot.Font = Enum.Font.SourceSans
Aimbot.Text = "Aimbot"
Aimbot.TextColor3 = Color3.fromRGB(0, 0, 0)
Aimbot.TextSize = 30.000

UICorner.CornerRadius = UDim.new(0.100000001, 0)
UICorner.Parent = Aimbot

Esp.Name = "Esp"
Esp.Parent = Frame
Esp.BackgroundColor3 = Color3.fromRGB(85, 85, 85)
Esp.BackgroundTransparency = 0.250
Esp.BorderColor3 = Color3.fromRGB(0, 0, 0)
Esp.BorderSizePixel = 0
Esp.Position = UDim2.new(0.358333319, 0, 0.194444448, 0)
Esp.Size = UDim2.new(0, 100, 0, 50)
Esp.Font = Enum.Font.SourceSans
Esp.Text = "Esp"
Esp.TextColor3 = Color3.fromRGB(0, 0, 0)
Esp.TextSize = 30.000

UICorner_2.CornerRadius = UDim.new(0.174999997, 0)
UICorner_2.Parent = Esp

ModM9.Name = "Mod M9"
ModM9.Parent = Frame
ModM9.BackgroundColor3 = Color3.fromRGB(85, 85, 85)
ModM9.BackgroundTransparency = 0.250
ModM9.BorderColor3 = Color3.fromRGB(0, 0, 0)
ModM9.BorderSizePixel = 0
ModM9.Position = UDim2.new(0.688888907, 0, 0.194444448, 0)
ModM9.Size = UDim2.new(0, 100, 0, 50)
ModM9.Font = Enum.Font.SourceSans
ModM9.Text = "Mod M9"
ModM9.TextColor3 = Color3.fromRGB(0, 0, 0)
ModM9.TextSize = 30.000

UICorner_3.CornerRadius = UDim.new(0.075000003, 0)
UICorner_3.Parent = ModM9

Fly.Name = "Fly"
Fly.Parent = Frame
Fly.BackgroundColor3 = Color3.fromRGB(85, 85, 85)
Fly.BackgroundTransparency = 0.250
Fly.BorderColor3 = Color3.fromRGB(0, 0, 0)
Fly.BorderSizePixel = 0
Fly.Position = UDim2.new(0.0444444455, 0, 0.352777779, 0)
Fly.Size = UDim2.new(0, 100, 0, 50)
Fly.Font = Enum.Font.SourceSans
Fly.Text = "Fly"
Fly.TextColor3 = Color3.fromRGB(0, 0, 0)
Fly.TextSize = 30.000

UICorner_4.CornerRadius = UDim.new(0.200000003, 0)
UICorner_4.Parent = Fly

KillAll.Name = "Kill All"
KillAll.Parent = Frame
KillAll.BackgroundColor3 = Color3.fromRGB(85, 85, 85)
KillAll.BackgroundTransparency = 0.250
KillAll.BorderColor3 = Color3.fromRGB(0, 0, 0)
KillAll.BorderSizePixel = 0
KillAll.Position = UDim2.new(0.358333319, 0, 0.352777779, 0)
KillAll.Size = UDim2.new(0, 100, 0, 50)
KillAll.Font = Enum.Font.SourceSans
KillAll.Text = "Kill all"
KillAll.TextColor3 = Color3.fromRGB(0, 0, 0)
KillAll.TextSize = 30.000

UICorner_5.CornerRadius = UDim.new(0, 10)
UICorner_5.Parent = KillAll

Noclip.Name = "Noclip"
Noclip.Parent = Frame
Noclip.BackgroundColor3 = Color3.fromRGB(85, 85, 85)
Noclip.BackgroundTransparency = 0.250
Noclip.BorderColor3 = Color3.fromRGB(0, 0, 0)
Noclip.BorderSizePixel = 0
Noclip.Position = UDim2.new(0.0916666687, 0, 0.469444454, 0)
Noclip.Size = UDim2.new(0, 65, 0, 37)
Noclip.Font = Enum.Font.SourceSans
Noclip.Text = "Noclip"
Noclip.TextColor3 = Color3.fromRGB(0, 0, 0)
Noclip.TextSize = 16.000

Getshotgun.Name = "Get shotgun"
Getshotgun.Parent = Frame
Getshotgun.BackgroundColor3 = Color3.fromRGB(85, 85, 85)
Getshotgun.BackgroundTransparency = 0.250
Getshotgun.BorderColor3 = Color3.fromRGB(0, 0, 0)
Getshotgun.BorderSizePixel = 0
Getshotgun.Position = UDim2.new(0.688888907, 0, 0.352777779, 0)
Getshotgun.Size = UDim2.new(0, 100, 0, 50)
Getshotgun.Font = Enum.Font.SourceSans
Getshotgun.Text = "Get shotgun "
Getshotgun.TextColor3 = Color3.fromRGB(0, 0, 0)
Getshotgun.TextSize = 15.000

Misc.Name = "Misc"
Misc.Parent = Frame
Misc.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Misc.BorderColor3 = Color3.fromRGB(0, 0, 0)
Misc.BorderSizePixel = 0
Misc.Position = UDim2.new(0.0444444455, 0, 0.597222209, 0)
Misc.Size = UDim2.new(0, 100, 0, 50)
Misc.Font = Enum.Font.SourceSans
Misc.Text = "Misc"
Misc.TextColor3 = Color3.fromRGB(0, 0, 0)
Misc.TextSize = 20.000
--22
Fly.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/rFpi04KR"))()
end)

Esp.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/fatman242343254/wdasd/main/README.md"))()
end)

KillAll.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/fatman242343254/WDWADAS/main/README.md"))()
end)

ModM9.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/fatman242343254/wadzsd/main/README.md"))()
end)

Aimbot.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/fatman242343254/Script2231231/main/README.md"))()
end)

Noclip.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/fatman242343254/wadzsd/main/README.md"))()
end)

Misc.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/fatman242343254/wadzsd/main/README.md"))()
end)
