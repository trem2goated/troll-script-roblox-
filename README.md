--im cool right?

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local flin = Instance.new("TextButton")
local punc = Instance.new("TextButton")
local iy = Instance.new("TextButton")
local wal = Instance.new("TextButton")
local jum = Instance.new("TextButton")
local walkk = Instance.new("TextBox")
local jumpp = Instance.new("TextBox")
local TextLabel = Instance.new("TextLabel")
local X = Instance.new("TextButton")
local Openfram = Instance.new("Frame")
local Open = Instance.new("TextButton")



ScreenGui.Parent = game.CoreGui

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(255, 0, 209)
Frame.BorderColor3 = Color3.fromRGB(0, 194, 253)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.601145029, 0, 0.398406386, 0)
Frame.Size = UDim2.new(0, 330, 0, 195)
Frame.Visible = false
Frame.Style = Enum.FrameStyle.DropShadow
Frame.Active = true
Frame.Draggable = true

flin.Name = "flin"
flin.Parent = Frame
flin.BackgroundColor3 = Color3.fromRGB(6, 6, 59)
flin.BorderSizePixel = 0
flin.Position = UDim2.new(0.069222562, 0, 0.227487266, 0)
flin.Size = UDim2.new(0, 77, 0, 31)
flin.Font = Enum.Font.SourceSans
flin.Text = "Fling"
flin.TextColor3 = Color3.fromRGB(79, 79, 79)
flin.TextScaled = true
flin.TextSize = 14.000
flin.TextWrapped = true
flin.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/zHxNWgY7", true))()
end)

punc.Name = "punc"
punc.Parent = Frame
punc.BackgroundColor3 = Color3.fromRGB(6, 6, 59)
punc.BorderSizePixel = 0
punc.Position = UDim2.new(0.672252834, 0, 0.227487266, 0)
punc.Size = UDim2.new(0, 77, 0, 31)
punc.Font = Enum.Font.SourceSans
punc.Text = "Punch"
punc.TextColor3 = Color3.fromRGB(79, 79, 79)
punc.TextScaled = true
punc.TextSize = 14.000
punc.TextWrapped = true
punc.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/VgwGU1kr", true))()
end)


iy.Name = "iy"
iy.Parent = Frame
iy.BackgroundColor3 = Color3.fromRGB(6, 6, 59)
iy.BorderSizePixel = 0
iy.Position = UDim2.new(0.0661922097, 0, 0.591589808, 0)
iy.Size = UDim2.new(0, 77, 0, 31)
iy.Font = Enum.Font.SourceSans
iy.Text = "Infinite Yield"
iy.TextColor3 = Color3.fromRGB(79, 79, 79)
iy.TextScaled = true
iy.TextSize = 14.000
iy.TextWrapped = true
iy.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)


wal.Name = "wal"
wal.Parent = Frame
wal.BackgroundColor3 = Color3.fromRGB(6, 6, 59)
wal.BorderSizePixel = 0
wal.Position = UDim2.new(0.672252774, 0, 0.591589808, 0)
wal.Size = UDim2.new(0, 77, 0, 31)
wal.Font = Enum.Font.SourceSans
wal.Text = "WalkSpeed"
wal.TextColor3 = Color3.fromRGB(79, 79, 79)
wal.TextScaled = true
wal.TextSize = 14.000
wal.TextWrapped = true
wal.MouseButton1Down:Connect(function()
	game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = walkk.Text
end)

jum.Name = "jum"
jum.Parent = Frame
jum.BackgroundColor3 = Color3.fromRGB(6, 6, 59)
jum.BorderSizePixel = 0
jum.Position = UDim2.new(0.672252774, 0, 0.801846206, 0)
jum.Size = UDim2.new(0, 77, 0, 31)
jum.Font = Enum.Font.SourceSans
jum.Text = "JumpPower"
jum.TextColor3 = Color3.fromRGB(79, 79, 79)
jum.TextScaled = true
jum.TextSize = 14.000
jum.TextWrapped = true
jum.MouseButton1Down:Connect(function()
	game.Players.LocalPlayer.Character.Humanoid.JumpPower = jumpp.Text
end)

walkk.Name = "walkk"
walkk.Parent = Frame
walkk.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
walkk.Position = UDim2.new(0.332746685, 0, 0.637168825, 0)
walkk.Size = UDim2.new(0, 104, 0, 15)
walkk.Font = Enum.Font.SourceSans
walkk.ShowNativeInput = false
walkk.Text = ""
walkk.TextColor3 = Color3.fromRGB(0, 0, 0)
walkk.TextSize = 14.000

jumpp.Name = "jumpp"
jumpp.Parent = Frame
jumpp.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
jumpp.Position = UDim2.new(0.332746685, 0, 0.826912403, 0)
jumpp.Size = UDim2.new(0, 104, 0, 15)
jumpp.Font = Enum.Font.SourceSans
jumpp.ShowNativeInput = false
jumpp.Text = ""
jumpp.TextColor3 = Color3.fromRGB(0, 0, 0)
jumpp.TextSize = 14.000

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Position = UDim2.new(0.26060605, 0, -4.65661287e-10, 0)
TextLabel.Size = UDim2.new(0, 140, 0, 31)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Trolling GUI"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

X.Name = "X"
X.Parent = Frame
X.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
X.BackgroundTransparency = 1.000
X.BorderSizePixel = 0
X.Position = UDim2.new(0.91026634, 0, -0.043287307, 0)
X.Size = UDim2.new(0, 29, 0, 29)
X.Font = Enum.Font.SciFi
X.Text = "X"
X.TextColor3 = Color3.fromRGB(255, 0, 0)
X.TextScaled = true
X.TextSize = 14.000
X.TextWrapped = true
X.MouseButton1Down:Connect(function()
	Openfram.Visible = true
	Frame.Visible = false
end)

Openfram.Name = "Openfram"
Openfram.Parent = ScreenGui
Openfram.BackgroundColor3 = Color3.fromRGB(38, 255, 14)
Openfram.BorderSizePixel = 0
Openfram.Position = UDim2.new(0.0133587793, 0, 0.836653352, 0)
Openfram.Size = UDim2.new(0, 160, 0, 34)

Open.Name = "Open"
Open.Parent = Openfram
Open.BackgroundColor3 = Color3.fromRGB(79, 255, 76)
Open.BorderSizePixel = 0
Open.Position = UDim2.new(0.075000003, 0, 0.176470593, 0)
Open.Size = UDim2.new(0, 135, 0, 22)
Open.Font = Enum.Font.SourceSans
Open.TextColor3 = Color3.fromRGB(0, 0, 0)
Open.TextSize = 14.000
Open.Text = "Open"
Open.MouseButton1Down:connect(function()
	Frame.Visible = true
	Openfram.Visible = false
end)
