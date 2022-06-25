-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScriptHubGui = Instance.new("ScreenGui")
local ScriptHub = Instance.new("Frame")
local Frame = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local LOL = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")
local CreditsO = Instance.new("TextButton")
local GeneralUseScriptO = Instance.new("TextButton")
local GameO = Instance.new("TextButton")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local TextLabel_3 = Instance.new("TextLabel")
local CreditsM = Instance.new("Frame")
local UICorner_3 = Instance.new("UICorner")
local TextLabel_4 = Instance.new("TextLabel")
local CloseButton = Instance.new("TextButton")
local GeneralUseScriptM = Instance.new("Frame")
local UICorner_4 = Instance.new("UICorner")
local InfiniteYield = Instance.new("TextButton")
local AntiAfk = Instance.new("TextButton")
local Esp = Instance.new("TextButton")
local CloseButton_2 = Instance.new("TextButton")
local GameM = Instance.new("ScrollingFrame")
local TextLabel_5 = Instance.new("TextLabel")
local dfNotifier = Instance.new("TextButton")
local RiverHUB = Instance.new("TextButton")
local TextLabel_6 = Instance.new("TextLabel")
local GreyGui = Instance.new("TextButton")
local TextLabel_7 = Instance.new("TextLabel")
local DXH = Instance.new("TextButton")
local Proxo = Instance.new("TextButton")
local CloseButton_3 = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local TextButton = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local KeyFrame = Instance.new("Frame")
local Login = Instance.new("TextLabel")
local UICorner_7 = Instance.new("UICorner")
local Check = Instance.new("TextBox")
local UICorner_8 = Instance.new("UICorner")
local Enter = Instance.new("TextButton")
local UICorner_9 = Instance.new("UICorner")
local GetKey = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")
local UICorner_11 = Instance.new("UICorner")

--Properties:

ScriptHubGui.Parent = game.CoreGui

ScriptHubGui.Name = "ScriptHubGui"
ScriptHubGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScriptHubGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

ScriptHub.Name = "ScriptHub"
ScriptHub.Parent = ScriptHubGui
ScriptHub.BackgroundColor3 = Color3.fromRGB(89, 89, 89)
ScriptHub.Position = UDim2.new(0.26556778, 0, 0.211864412, 0)
ScriptHub.Size = UDim2.new(0, 550, 0, 272)
ScriptHub.Visible = false
ScriptHub.Active = true
ScriptHub.Draggable = true

Frame.Parent = ScriptHub
Frame.BackgroundColor3 = Color3.fromRGB(49, 49, 49)
Frame.Position = UDim2.new(0.0231660232, 0, 0, 0)
Frame.Size = UDim2.new(0, 115, 0, 272)

UICorner.Parent = Frame

LOL.Name = "LOL"
LOL.Parent = ScriptHub
LOL.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
LOL.Size = UDim2.new(0, 115, 0, 272)

UICorner_2.Parent = LOL

CreditsO.Name = "CreditsO"
CreditsO.Parent = LOL
CreditsO.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
CreditsO.BackgroundTransparency = 1.000
CreditsO.Position = UDim2.new(0.269565225, 0, 0.283088237, 0)
CreditsO.Size = UDim2.new(0, 84, 0, 39)
CreditsO.Font = Enum.Font.GothamBlack
CreditsO.Text = "Credits"
CreditsO.TextColor3 = Color3.fromRGB(255, 255, 255)
CreditsO.TextScaled = true
CreditsO.TextSize = 14.000
CreditsO.TextWrapped = true

GeneralUseScriptO.Name = "GeneralUseScriptO"
GeneralUseScriptO.Parent = LOL
GeneralUseScriptO.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
GeneralUseScriptO.BackgroundTransparency = 1.000
GeneralUseScriptO.Position = UDim2.new(0.269565225, 0, 0.426470578, 0)
GeneralUseScriptO.Size = UDim2.new(0, 84, 0, 39)
GeneralUseScriptO.Font = Enum.Font.GothamBlack
GeneralUseScriptO.Text = "General Use Script"
GeneralUseScriptO.TextColor3 = Color3.fromRGB(255, 255, 255)
GeneralUseScriptO.TextScaled = true
GeneralUseScriptO.TextSize = 14.000
GeneralUseScriptO.TextWrapped = true

GameO.Name = "GameO"
GameO.Parent = LOL
GameO.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
GameO.BackgroundTransparency = 1.000
GameO.Position = UDim2.new(0.269565225, 0, 0.569852948, 0)
GameO.Size = UDim2.new(0, 84, 0, 39)
GameO.Font = Enum.Font.GothamBlack
GameO.Text = "Game"
GameO.TextColor3 = Color3.fromRGB(255, 255, 255)
GameO.TextScaled = true
GameO.TextSize = 14.000
GameO.TextWrapped = true

TextLabel.Parent = LOL
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Position = UDim2.new(0, 0, 0.283088237, 0)
TextLabel.Size = UDim2.new(0, 31, 0, 34)
TextLabel.Font = Enum.Font.GothamBlack
TextLabel.Text = "#"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

TextLabel_2.Parent = LOL
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.Position = UDim2.new(0, 0, 0.426470578, 0)
TextLabel_2.Size = UDim2.new(0, 31, 0, 34)
TextLabel_2.Font = Enum.Font.GothamBlack
TextLabel_2.Text = "#"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 14.000
TextLabel_2.TextWrapped = true

TextLabel_3.Parent = LOL
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.Position = UDim2.new(0, 0, 0.569852948, 0)
TextLabel_3.Size = UDim2.new(0, 31, 0, 34)
TextLabel_3.Font = Enum.Font.GothamBlack
TextLabel_3.Text = "#"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.TextScaled = true
TextLabel_3.TextSize = 14.000
TextLabel_3.TextWrapped = true

CreditsM.Name = "CreditsM"
CreditsM.Parent = ScriptHub
CreditsM.BackgroundColor3 = Color3.fromRGB(89, 89, 89)
CreditsM.Position = UDim2.new(0.245173782, 0, 0, 0)
CreditsM.Size = UDim2.new(0, 415, 0, 272)
CreditsM.Visible = false

UICorner_3.Parent = CreditsM

TextLabel_4.Parent = CreditsM
TextLabel_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.BackgroundTransparency = 1.000
TextLabel_4.Position = UDim2.new(0.271099746, 0, 0.0992647037, 0)
TextLabel_4.Size = UDim2.new(0, 179, 0, 50)
TextLabel_4.Font = Enum.Font.GothamBlack
TextLabel_4.Text = "Script Hub Made by Pou#0766"
TextLabel_4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.TextScaled = true
TextLabel_4.TextSize = 14.000
TextLabel_4.TextWrapped = true

CloseButton.Name = "CloseButton"
CloseButton.Parent = CreditsM
CloseButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
CloseButton.BackgroundTransparency = 1.000
CloseButton.Position = UDim2.new(0.877108455, 0, 0, 0)
CloseButton.Size = UDim2.new(0, 51, 0, 50)
CloseButton.Font = Enum.Font.GothamBlack
CloseButton.Text = "Close"
CloseButton.TextColor3 = Color3.fromRGB(255, 255, 255)
CloseButton.TextScaled = true
CloseButton.TextSize = 14.000
CloseButton.TextWrapped = true

GeneralUseScriptM.Name = "GeneralUseScriptM"
GeneralUseScriptM.Parent = ScriptHub
GeneralUseScriptM.BackgroundColor3 = Color3.fromRGB(89, 89, 89)
GeneralUseScriptM.Position = UDim2.new(0.230909094, 0, 0, 0)
GeneralUseScriptM.Size = UDim2.new(0, 423, 0, 272)
GeneralUseScriptM.Visible = false

UICorner_4.Parent = GeneralUseScriptM

InfiniteYield.Name = "Infinite Yield"
InfiniteYield.Parent = GeneralUseScriptM
InfiniteYield.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
InfiniteYield.BackgroundTransparency = 1.000
InfiniteYield.Position = UDim2.new(0.262411356, 0, 0.0992647037, 0)
InfiniteYield.Size = UDim2.new(0, 200, 0, 50)
InfiniteYield.Font = Enum.Font.GothamBlack
InfiniteYield.Text = "Infinite Yield"
InfiniteYield.TextColor3 = Color3.fromRGB(255, 255, 255)
InfiniteYield.TextScaled = true
InfiniteYield.TextSize = 14.000
InfiniteYield.TextWrapped = true
InfiniteYield.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)

AntiAfk.Name = "Anti Afk"
AntiAfk.Parent = GeneralUseScriptM
AntiAfk.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
AntiAfk.BackgroundTransparency = 1.000
AntiAfk.Position = UDim2.new(0.262411356, 0, 0.283088237, 0)
AntiAfk.Size = UDim2.new(0, 200, 0, 50)
AntiAfk.Font = Enum.Font.GothamBlack
AntiAfk.Text = "Anti Afk"
AntiAfk.TextColor3 = Color3.fromRGB(255, 255, 255)
AntiAfk.TextScaled = true
AntiAfk.TextSize = 14.000
AntiAfk.TextWrapped = true
AntiAfk.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/2dgeneralspam1/scripts-and-stuff/master/scripts/LoadstringypVvhJBq4QNz", true))()
end)

Esp.Name = "Esp"
Esp.Parent = GeneralUseScriptM
Esp.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Esp.BackgroundTransparency = 1.000
Esp.Position = UDim2.new(0.262411356, 0, 0.511029422, 0)
Esp.Size = UDim2.new(0, 200, 0, 50)
Esp.Font = Enum.Font.GothamBlack
Esp.Text = "Esp"
Esp.TextColor3 = Color3.fromRGB(255, 255, 255)
Esp.TextScaled = true
Esp.TextSize = 14.000
Esp.TextWrapped = true
Esp.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/ic3w0lf22/Unnamed-ESP/master/UnnamedESP.lua',true))()
end)

CloseButton_2.Name = "CloseButton"
CloseButton_2.Parent = GeneralUseScriptM
CloseButton_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
CloseButton_2.BackgroundTransparency = 1.000
CloseButton_2.Position = UDim2.new(0.877108455, 0, 0, 0)
CloseButton_2.Size = UDim2.new(0, 51, 0, 50)
CloseButton_2.Font = Enum.Font.GothamBlack
CloseButton_2.Text = "Close"
CloseButton_2.TextColor3 = Color3.fromRGB(255, 255, 255)
CloseButton_2.TextScaled = true
CloseButton_2.TextSize = 14.000
CloseButton_2.TextWrapped = true

GameM.Name = "GameM"
GameM.Parent = ScriptHub
GameM.Active = true
GameM.BackgroundColor3 = Color3.fromRGB(89, 89, 89)
GameM.Position = UDim2.new(0.230909094, 0, 0, 0)
GameM.Size = UDim2.new(0, 423, 0, 272)
GameM.Visible = false
GameM.CanvasSize = UDim2.new(0, 0, 20, 0)

TextLabel_5.Parent = GameM
TextLabel_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_5.BackgroundTransparency = 1.000
TextLabel_5.Position = UDim2.new(0.262411356, 0, 0.00496323546, 0)
TextLabel_5.Size = UDim2.new(0, 200, 0, 50)
TextLabel_5.Font = Enum.Font.GothamBlack
TextLabel_5.Text = "GPO"
TextLabel_5.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_5.TextScaled = true
TextLabel_5.TextSize = 14.000
TextLabel_5.TextWrapped = true

dfNotifier.Name = "df Notifier"
dfNotifier.Parent = TextLabel_5
dfNotifier.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
dfNotifier.BackgroundTransparency = 1.000
dfNotifier.Position = UDim2.new(-0.409999996, 0, 1, 0)
dfNotifier.Size = UDim2.new(0, 157, 0, 50)
dfNotifier.Font = Enum.Font.GothamBlack
dfNotifier.Text = "df Notifier"
dfNotifier.TextColor3 = Color3.fromRGB(255, 255, 255)
dfNotifier.TextScaled = true
dfNotifier.TextSize = 14.000
dfNotifier.TextWrapped = true
dfNotifier.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/ArponAG/Scripts/main/gpo.lua', true))()
end)

RiverHUB.Name = "RiverHUB"
RiverHUB.Parent = TextLabel_5
RiverHUB.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
RiverHUB.BackgroundTransparency = 1.000
RiverHUB.Position = UDim2.new(0.61500001, 0, 1, 0)
RiverHUB.Size = UDim2.new(0, 157, 0, 50)
RiverHUB.Font = Enum.Font.GothamBlack
RiverHUB.Text = "RiverHub"
RiverHUB.TextColor3 = Color3.fromRGB(255, 255, 255)
RiverHUB.TextScaled = true
RiverHUB.TextSize = 14.000
RiverHUB.TextWrapped = true
RiverHUB.MouseButton1Down:Connect(function()
	pcall(function()
		loadstring(game:HttpGet("http://riverhub.xyz/" .. tostring(game.PlaceId) .. ".lua"))()
	end)
end)

TextLabel_6.Parent = GameM
TextLabel_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_6.BackgroundTransparency = 1.000
TextLabel_6.Position = UDim2.new(0.262411356, 0, 0.02132353, 0)
TextLabel_6.Size = UDim2.new(0, 200, 0, 50)
TextLabel_6.Font = Enum.Font.GothamBlack
TextLabel_6.Text = "Mining Simulator 2"
TextLabel_6.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_6.TextScaled = true
TextLabel_6.TextSize = 14.000
TextLabel_6.TextWrapped = true

GreyGui.Name = "GreyGui"
GreyGui.Parent = TextLabel_6
GreyGui.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
GreyGui.BackgroundTransparency = 1.000
GreyGui.Position = UDim2.new(0.109999985, 0, 1, 0)
GreyGui.Size = UDim2.new(0, 157, 0, 50)
GreyGui.Font = Enum.Font.GothamBlack
GreyGui.Text = "GreyGui"
GreyGui.TextColor3 = Color3.fromRGB(255, 255, 255)
GreyGui.TextScaled = true
GreyGui.TextSize = 14.000
GreyGui.TextWrapped = true
GreyGui.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet('https://robloxscripts.co.uk/keysystem.lua'))('zNmJsacD')
end)

TextLabel_7.Parent = GameM
TextLabel_7.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_7.BackgroundTransparency = 1.000
TextLabel_7.Position = UDim2.new(0.262411356, 0, 0.0408088267, 0)
TextLabel_7.Size = UDim2.new(0, 200, 0, 50)
TextLabel_7.Font = Enum.Font.GothamBlack
TextLabel_7.Text = "PSX"
TextLabel_7.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_7.TextScaled = true
TextLabel_7.TextSize = 14.000
TextLabel_7.TextWrapped = true

DXH.Name = "DXH"
DXH.Parent = TextLabel_7
DXH.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
DXH.BackgroundTransparency = 1.000
DXH.Position = UDim2.new(-0.409999996, 0, 1, 0)
DXH.Size = UDim2.new(0, 157, 0, 50)
DXH.Font = Enum.Font.GothamBlack
DXH.Text = "DXH"
DXH.TextColor3 = Color3.fromRGB(255, 255, 255)
DXH.TextScaled = true
DXH.TextSize = 14.000
DXH.TextWrapped = true
DXH.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/Pojken123/psxx/main/p"))()
end)

Proxo.Name = "Proxo"
Proxo.Parent = TextLabel_7
Proxo.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Proxo.BackgroundTransparency = 1.000
Proxo.Position = UDim2.new(0.61500001, 0, 1, 0)
Proxo.Size = UDim2.new(0, 157, 0, 50)
Proxo.Font = Enum.Font.GothamBlack
Proxo.Text = "Proxo"
Proxo.TextColor3 = Color3.fromRGB(255, 255, 255)
Proxo.TextScaled = true
Proxo.TextSize = 14.000
Proxo.TextWrapped = true
Proxo.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet('https://pastebinp.com/raw/95HthyJq',true))()
end)

CloseButton_3.Name = "CloseButton"
CloseButton_3.Parent = GameM
CloseButton_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
CloseButton_3.BackgroundTransparency = 1.000
CloseButton_3.Position = UDim2.new(0.877108455, 0, 0, 0)
CloseButton_3.Size = UDim2.new(0, 51, 0, 50)
CloseButton_3.Font = Enum.Font.GothamBlack
CloseButton_3.Text = "Close"
CloseButton_3.TextColor3 = Color3.fromRGB(255, 255, 255)
CloseButton_3.TextScaled = true
CloseButton_3.TextSize = 14.000
CloseButton_3.TextWrapped = true

UICorner_5.Parent = ScriptHub

TextButton.Parent = ScriptHub
TextButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton.BackgroundTransparency = 1.000
TextButton.Position = UDim2.new(0.956363678, 0, -0.0919117704, 0)
TextButton.Size = UDim2.new(0, 54, 0, 50)
TextButton.Font = Enum.Font.GothamBlack
TextButton.Text = "Close"
TextButton.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton.TextScaled = true
TextButton.TextSize = 14.000
TextButton.TextWrapped = true

UICorner_6.Parent = TextButton

KeyFrame.Name = "KeyFrame"
KeyFrame.Parent = ScriptHubGui
KeyFrame.BackgroundColor3 = Color3.fromRGB(125, 125, 125)
KeyFrame.Position = UDim2.new(0.407509178, 0, 0.22457628, 0)
KeyFrame.Size = UDim2.new(0, 201, 0, 260)
KeyFrame.Visible = true

Login.Name = "Login"
Login.Parent = KeyFrame
Login.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Login.Size = UDim2.new(0, 200, 0, 50)
Login.Font = Enum.Font.GothamBlack
Login.Text = "Login"
Login.TextColor3 = Color3.fromRGB(0, 0, 0)
Login.TextScaled = true
Login.TextSize = 14.000
Login.TextWrapped = true

UICorner_7.Parent = Login

Check.Name = "Check"
Check.Parent = KeyFrame
Check.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Check.Position = UDim2.new(0.109452739, 0, 0.27692306, 0)
Check.Size = UDim2.new(0, 157, 0, 49)
Check.Font = Enum.Font.GothamBlack
Check.Text = "Put Key Here"
Check.TextColor3 = Color3.fromRGB(0, 0, 0)
Check.TextScaled = true
Check.TextSize = 14.000
Check.TextWrapped = true

UICorner_8.Parent = Check

Enter.Name = "Enter"
Enter.Parent = KeyFrame
Enter.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Enter.Position = UDim2.new(0.184079587, 0, 0.503846169, 0)
Enter.Size = UDim2.new(0, 126, 0, 42)
Enter.Font = Enum.Font.GothamBlack
Enter.Text = "Enter"
Enter.TextColor3 = Color3.fromRGB(0, 0, 0)
Enter.TextScaled = true
Enter.TextSize = 14.000
Enter.TextWrapped = true
Enter.MouseButton1Click:Connect(function()
	if Check.Text == "BenIsSus" then
		KeyFrame.Visible = false
		wait(1)
		ScriptHub.Visible = true
	end
end)

UICorner_9.Parent = Enter

GetKey.Name = "GetKey"
GetKey.Parent = KeyFrame
GetKey.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
GetKey.Position = UDim2.new(0.149253726, 0, 0.742307663, 0)
GetKey.Size = UDim2.new(0, 142, 0, 47)
GetKey.Font = Enum.Font.GothamBlack
GetKey.Text = "Get Key"
GetKey.TextColor3 = Color3.fromRGB(0, 0, 0)
GetKey.TextScaled = true
GetKey.TextSize = 14.000
GetKey.TextWrapped = true
GetKey.MouseButton1Click:Connect(function()
	game.StarterGui:SetCore("SendNotification", {Title = "Copied!", Text = "Link was succeesfully copied!", Icon = "", Duration = 4})
	wait(1)
	setclipboard("https://linkvertise.com/463868/s/1")
end)

UICorner_10.Parent = GetKey

UICorner_11.Parent = KeyFrame

-- Scripts:

local function DFKT_fake_script() -- CreditsO.Script 
	local script = Instance.new('Script', CreditsO)

	script.Parent.MouseButton1Click:Connect(function()
	
		script.Parent.Parent.Parent.CreditsM.Visible = true
	
	end)
end
coroutine.wrap(DFKT_fake_script)()
local function QJJGXCQ_fake_script() -- GeneralUseScriptO.Script 
	local script = Instance.new('Script', GeneralUseScriptO)

	script.Parent.MouseButton1Click:Connect(function()
		
		script.Parent.Parent.Parent.GeneralUseScriptM.Visible = true
	
	end)
end
coroutine.wrap(QJJGXCQ_fake_script)()
local function AAAKD_fake_script() -- GameO.Script 
	local script = Instance.new('Script', GameO)

	script.Parent.MouseButton1Click:Connect(function()
	
		script.Parent.Parent.Parent.GameM.Visible = true
	
	end)
end
coroutine.wrap(AAAKD_fake_script)()
local function DDMUT_fake_script() -- CloseButton.Script 
	local script = Instance.new('Script', CloseButton)

	local GeneralUseScriptO = script.Parent.Parent
	
	script.Parent.MouseButton1Click:Connect(function()
		GeneralUseScriptO.Visible = false
	end)
end
coroutine.wrap(DDMUT_fake_script)()
local function KOAT_fake_script() -- CloseButton_2.Script 
	local script = Instance.new('Script', CloseButton_2)

	local GeneralUseScriptO = script.Parent.Parent
	
	script.Parent.MouseButton1Click:Connect(function()
		GeneralUseScriptO.Visible = false
	end)
end
coroutine.wrap(KOAT_fake_script)()
local function ITGM_fake_script() -- CloseButton_3.Script 
	local script = Instance.new('Script', CloseButton_3)

	local GeneralUseScriptO = script.Parent.Parent
	
	script.Parent.MouseButton1Click:Connect(function()
		GeneralUseScriptO.Visible = false
	end)
end
coroutine.wrap(ITGM_fake_script)()
local function XWBQAG_fake_script() -- TextButton.Script 
	local script = Instance.new('Script', TextButton)

	local GeneralUseScriptO = script.Parent.Parent
	
	script.Parent.MouseButton1Click:Connect(function()
		GeneralUseScriptO.Visible = false
	end)
end
coroutine.wrap(XWBQAG_fake_script)()
