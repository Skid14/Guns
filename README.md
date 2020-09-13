--Filterui guns

local ScreenGui = Instance.new("ScreenGui")
local Gunmain = Instance.new("Frame")
local Close = Instance.new("TextButton")
local tommygun = Instance.new("TextButton")
local minigun = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.CoreGui

Gunmain.Name = "Gunmain"
Gunmain.Parent = ScreenGui
Gunmain.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Gunmain.BackgroundTransparency = 0.200
Gunmain.BorderColor3 = Color3.fromRGB(0, 0, 255)
Gunmain.BorderSizePixel = 2
Gunmain.Position = UDim2.new(0.0824742243, 0, 0.0830140486, 0)
Gunmain.Size = UDim2.new(0, 250, 0, 400)

Close.Name = "Close"
Close.Parent = Gunmain
Close.BackgroundColor3 = Color3.fromRGB(89, 89, 89)
Close.BackgroundTransparency = 0.800
Close.BorderColor3 = Color3.fromRGB(0, 0, 255)
Close.BorderSizePixel = 2
Close.Position = UDim2.new(0.0985566974, 0, 0.844932914, 0)
Close.Size = UDim2.new(0, 200, 0, 50)
Close.Font = Enum.Font.Highway
Close.Text = "Close the fucking ui"
Close.TextColor3 = Color3.fromRGB(255, 0, 0)
Close.TextSize = 20.000

tommygun.Name = "tommygun"
tommygun.Parent = Gunmain
tommygun.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
tommygun.BackgroundTransparency = 0.500
tommygun.Position = UDim2.new(0.0400000028, 0, 0.0299999993, 0)
tommygun.Size = UDim2.new(0, 100, 0, 25)
tommygun.Font = Enum.Font.SourceSans
tommygun.Text = "tommygun"
tommygun.TextColor3 = Color3.fromRGB(0, 0, 255)
tommygun.TextSize = 14.000

minigun.Name = "minigun"
minigun.Parent = Gunmain
minigun.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
minigun.BackgroundTransparency = 0.500
minigun.Position = UDim2.new(0.556000054, 0, 0.0299999993, 0)
minigun.Size = UDim2.new(0, 100, 0, 25)
minigun.Font = Enum.Font.SourceSans
minigun.Text = "minigun"
minigun.TextColor3 = Color3.fromRGB(0, 0, 255)
minigun.TextSize = 14.000
