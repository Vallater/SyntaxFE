-- Gui to Lua
-- Version: 3.2

-- Instances:

local Intro = Instance.new("ScreenGui")
local Filter = Instance.new("Frame")
local Config = Instance.new("Configuration")
local Background = Instance.new("Frame")
local Content = Instance.new("Frame")
local TextButton1 = Instance.new("TextButton")
local TextButton1_2 = Instance.new("TextButton")
local TextButton1_3 = Instance.new("TextButton")
local TextButton1_4 = Instance.new("TextButton")
local TextButton1_5 = Instance.new("TextButton")
local TextButton1_6 = Instance.new("TextButton")
local TextButton1_7 = Instance.new("TextButton")
local TextButton1_8 = Instance.new("TextButton")

--Properties:

Intro.Name = "Intro"
Intro.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

Filter.Name = "Filter"
Filter.Parent = Intro
Filter.BackgroundColor3 = Color3.fromRGB(51, 204, 204)
Filter.BorderColor3 = Color3.fromRGB(0, 0, 0)
Filter.BorderSizePixel = 0
Filter.Position = UDim2.new(-0.25, 0, -0.25, 0)
Filter.Size = UDim2.new(1.5, 0, 1.5, 0)
Filter.Visible = false
Filter.ZIndex = 10

Config.Name = "Config"
Config.Parent = Intro

Background.Name = "Background"
Background.Parent = Intro
Background.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Background.BorderColor3 = Color3.fromRGB(0, 204, 255)
Background.BorderSizePixel = 0
Background.Position = UDim2.new(-0.25, 0, -0.25, 0)
Background.Size = UDim2.new(1.5, 0, 1.5, 0)

Content.Name = "Content"
Content.Parent = Intro
Content.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Content.BackgroundTransparency = 1.000
Content.BorderColor3 = Color3.fromRGB(0, 0, 0)
Content.BorderSizePixel = 0
Content.Size = UDim2.new(1, 0, 1, 0)

TextButton1.Name = "TextButton1"
TextButton1.Parent = Content
TextButton1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton1.BackgroundTransparency = 1.000
TextButton1.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton1.Position = UDim2.new(0.182432443, 0, 0.101013109, 0)
TextButton1.Size = UDim2.new(0.5, 0, 0.5, 0)
TextButton1.Font = Enum.Font.ArialBold
TextButton1.Text = "SYNTAX V3 IT'S A SHIT"
TextButton1.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton1.TextSize = 48.000
TextButton1.TextStrokeTransparency = 0.300

TextButton1_2.Name = "TextButton1"
TextButton1_2.Parent = Content
TextButton1_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton1_2.BackgroundTransparency = 1.000
TextButton1_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton1_2.Position = UDim2.new(0.288610041, 0, 0.179678202, 0)
TextButton1_2.Size = UDim2.new(0.5, 0, 0.5, 0)
TextButton1_2.Font = Enum.Font.ArialBold
TextButton1_2.Text = "JOIN SYNTAX V4 SERVER RIGHT NOWW!!!"
TextButton1_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton1_2.TextSize = 48.000
TextButton1_2.TextStrokeTransparency = 0.300

TextButton1_3.Name = "TextButton1"
TextButton1_3.Parent = Content
TextButton1_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton1_3.BackgroundTransparency = 1.000
TextButton1_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton1_3.Position = UDim2.new(0.273166031, 0, 0.294100136, 0)
TextButton1_3.Size = UDim2.new(0.5, 0, 0.5, 0)
TextButton1_3.Font = Enum.Font.ArialBold
TextButton1_3.Text = "https://discord.gg/syntax-v4"
TextButton1_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton1_3.TextSize = 48.000
TextButton1_3.TextStrokeTransparency = 0.300

TextButton1_4.Name = "TextButton1"
TextButton1_4.Parent = Content
TextButton1_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton1_4.BackgroundTransparency = 1.000
TextButton1_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton1_4.Position = UDim2.new(0.273166031, 0, 0.356078684, 0)
TextButton1_4.Size = UDim2.new(0.5, 0, 0.5, 0)
TextButton1_4.Font = Enum.Font.ArialBold
TextButton1_4.Text = "https://discord.gg/syntax-v4"
TextButton1_4.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton1_4.TextSize = 48.000
TextButton1_4.TextStrokeTransparency = 0.300

TextButton1_5.Name = "TextButton1"
TextButton1_5.Parent = Content
TextButton1_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton1_5.BackgroundTransparency = 1.000
TextButton1_5.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton1_5.Position = UDim2.new(0.273166031, 0, 0.409713954, 0)
TextButton1_5.Size = UDim2.new(0.5, 0, 0.5, 0)
TextButton1_5.Font = Enum.Font.ArialBold
TextButton1_5.Text = "https://discord.gg/syntax-v4"
TextButton1_5.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton1_5.TextSize = 48.000
TextButton1_5.TextStrokeTransparency = 0.300

TextButton1_6.Name = "TextButton1"
TextButton1_6.Parent = Content
TextButton1_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton1_6.BackgroundTransparency = 1.000
TextButton1_6.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton1_6.Position = UDim2.new(0.273166031, 0, 0.472884387, 0)
TextButton1_6.Size = UDim2.new(0.5, 0, 0.5, 0)
TextButton1_6.Font = Enum.Font.ArialBold
TextButton1_6.Text = "https://discord.gg/syntax-v4"
TextButton1_6.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton1_6.TextSize = 48.000
TextButton1_6.TextStrokeTransparency = 0.300

TextButton1_7.Name = "TextButton1"
TextButton1_7.Parent = Content
TextButton1_7.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton1_7.BackgroundTransparency = 1.000
TextButton1_7.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton1_7.Position = UDim2.new(0.42567569, 0, -0.15524435, 0)
TextButton1_7.Size = UDim2.new(0.5, 0, 0.5, 0)
TextButton1_7.Font = Enum.Font.ArialBold
TextButton1_7.Text = "Vall big pro and owner syntax"
TextButton1_7.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton1_7.TextSize = 48.000
TextButton1_7.TextStrokeTransparency = 0.300

TextButton1_8.Name = "TextButton1"
TextButton1_8.Parent = Content
TextButton1_8.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton1_8.BackgroundTransparency = 1.000
TextButton1_8.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton1_8.Position = UDim2.new(0.128378391, 0, -0.0396305136, 0)
TextButton1_8.Size = UDim2.new(0.5, 0, 0.5, 0)
TextButton1_8.Font = Enum.Font.ArialBold
TextButton1_8.Text = "JOIN V4 NEW SERVER THERE LINK"
TextButton1_8.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton1_8.TextSize = 48.000
TextButton1_8.TextStrokeTransparency = 0.300
