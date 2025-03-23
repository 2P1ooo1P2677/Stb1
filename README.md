local _0xA1B2C3 = Instance.new("ScreenGui")
local _0xD4E5F6 = Instance.new("Frame")
local _0xA7B8C9 = Instance.new("TextLabel")
local _0xB1C2D3 = Instance.new("TextLabel")
local _0xE4F5A6 = Instance.new("TextBox")
local _0xD7E8F9 = Instance.new("TextButton")
local _0xA9B0C1 = Instance.new("TextButton")
local _0xC2D3E4 = Instance.new("TextButton")
local _0xF5A6B7 = Instance.new("TextLabel")

_0xA1B2C3.Parent = game:GetService("CoreGui")
_0xD4E5F6.Parent = _0xA1B2C3
_0xD4E5F6.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
_0xD4E5F6.Size = UDim2.new(0, 300, 0, 300)
_0xD4E5F6.Position = UDim2.new(0.35, 0, 0.35, 0)
_0xD4E5F6.Active = true
_0xD4E5F6.Draggable = true

_0xA7B8C9.Parent = _0xD4E5F6
_0xA7B8C9.Text = "Strongest Battleground Script"
_0xA7B8C9.Size = UDim2.new(0, 300, 0, 40)
_0xA7B8C9.Position = UDim2.new(0, 0, 0, 0)
_0xA7B8C9.TextColor3 = Color3.fromRGB(255, 255, 255)
_0xA7B8C9.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
_0xA7B8C9.Font = Enum.Font.SourceSansBold
_0xA7B8C9.TextSize = 18

_0xB1C2D3.Parent = _0xD4E5F6
_0xB1C2D3.Text = "Speed:"
_0xB1C2D3.Size = UDim2.new(0, 60, 0, 30)
_0xB1C2D3.Position = UDim2.new(0.05, 0, 0.2, 0)
_0xB1C2D3.TextColor3 = Color3.fromRGB(255, 255, 255)
_0xB1C2D3.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
_0xB1C2D3.Font = Enum.Font.SourceSansBold
_0xB1C2D3.TextSize = 16

_0xE4F5A6.Parent = _0xD4E5F6
_0xE4F5A6.Size = UDim2.new(0, 120, 0, 30)
_0xE4F5A6.Position = UDim2.new(0.4, 0, 0.2, 0)
_0xE4F5A6.BackgroundColor3 = Color3.fromRGB(0, 170, 255)
_0xE4F5A6.TextColor3 = Color3.fromRGB(255, 255, 255)
_0xE4F5A6.Font = Enum.Font.SourceSansBold
_0xE4F5A6.TextSize = 16
_0xE4F5A6.Text = "3"

_0xD7E8F9.Parent = _0xD4E5F6
_0xD7E8F9.Text = "Start"
_0xD7E8F9.Size = UDim2.new(0, 120, 0, 40)
_0xD7E8F9.Position = UDim2.new(0.1, 0, 0.4, 0)
_0xD7E8F9.BackgroundColor3 = Color3.fromRGB(0, 170, 0)
_0xD7E8F9.TextColor3 = Color3.fromRGB(255, 255, 255)

_0xA9B0C1.Parent = _0xD4E5F6
_0xA9B0C1.Text = "Stop"
_0xA9B0C1.Size = UDim2.new(0, 120, 0, 40)
_0xA9B0C1.Position = UDim2.new(0.55, 0, 0.4, 0)
_0xA9B0C1.BackgroundColor3 = Color3.fromRGB(170, 0, 0)
_0xA9B0C1.TextColor3 = Color3.fromRGB(255, 255, 255)

_0xC2D3E4.Parent = _0xD4E5F6
_0xC2D3E4.Text = "Subscribe on YouTube"
_0xC2D3E4.Size = UDim2.new(0, 250, 0, 40)
_0xC2D3E4.Position = UDim2.new(0.08, 0, 0.6, 0)
_0xC2D3E4.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
_0xC2D3E4.TextColor3 = Color3.fromRGB(255, 255, 255)
_0xC2D3E4.Font = Enum.Font.SourceSansBold
_0xC2D3E4.TextSize = 16

_0xF5A6B7.Parent = _0xD4E5F6
_0xF5A6B7.Text = "Script created by 2P1ooo1P2"
_0xF5A6B7.Size = UDim2.new(0, 300, 0, 30)
_0xF5A6B7.Position = UDim2.new(0, 0, 0.85, 0)
_0xF5A6B7.TextColor3 = Color3.fromRGB(255, 215, 0)
_0xF5A6B7.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
_0xF5A6B7.Font = Enum.Font.SourceSansBold
_0xF5A6B7.TextSize = 16

local _0xA0B1C2 = game:GetService("RunService").Heartbeat
local _0xD4E5F6 = false
local _0xA1B2C3 = game:GetService("Players")
local _0xF3A4B5 = _0xA1B2C3.LocalPlayer
local _0xF2A3B4, _0xD5E6F7

local function _0xB7A8C9()
    _0xF2A3B4 = _0xF3A4B5.Character or _0xF3A4B5.CharacterAdded:Wait()
    _0xD5E6F7 = _0xF2A3B4:WaitForChild("Humanoid")
end

_0xB7A8C9()

_0xF3A4B5.CharacterAdded:Connect(_0xB7A8C9)

function _0xF8A9B0(_0xE6F7D8)
    return tonumber(_0xE6F7D8) ~= nil or _0xE6F7D8 == 'inf'
end

local function _0xD7F8E9()
    _0xD4E5F6 = true
    while _0xD4E5F6 and _0xA0B1C2:Wait() and _0xF2A3B4 and _0xD5E6F7 and _0xD5E6F7.Parent do
        local _0xD2F3A4 = tonumber(_0xE4F5A6.Text) or 3
        if _0xD5E6F7.MoveDirection.Magnitude > 0 then
            _0xF2A3B4:TranslateBy(_0xD5E6F7.MoveDirection * _0xD2F3A4)
        end
    end
end

local function _0xF1A2B3()
    _0xD4E5F6 = false
end

_0xE4F5A6.FocusLost:Connect(function(_0xE7F8D9)
    if not _0xE7F8D9 then
        local _0xD2F3A4 = tonumber(_0xE4F5A6.Text) or 3
        _0xB1C2D3.Text = "Speed: " .. _0xD2F3A4
    end
end)

_0xD7E8F9.MouseButton1Click:Connect(_0xD7F8E9)
_0xA9B0C1.MouseButton1Click:Connect(_0xF1A2B3)

_0xC2D3E4.MouseButton1Click:Connect(function()
    local _0xE1F2A3 = "https://youtube.com/@scriptbox-r6y?si=NBDaQ67omCaX58x-"

    local _0xD9F1E0, _0xB8A9C1 = pcall(function()
        setclipboard(_0xE1F2A3)
    end)

    if _0xD9F1E0 then
        game.StarterGui:SetCore("SendNotification", {
            Title = "Link Copied!",
            Text = "The YouTube link has been copied to your clipboard.",
            Duration = 3
        })
    else
        game.StarterGui:SetCore("SendNotification", {
            Title = "Error",
            Text = "Unable to copy link. Exploit or environment doesn't support clipboard access.",
            Duration = 5
        })
    end
end)

game.StarterGui:SetCore("SendNotification", {
    Title = "Strongest Battleground Script Loaded";
    Text = "Script created by 2P1ooo1P2";
    Duration = 15;
})
