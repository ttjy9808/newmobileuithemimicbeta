local Lib = loadstring(game:HttpGet("https://raw.githubusercontent.com/Hosvile/Refinement/main/InfinitiveUI",true))()
local Win = Lib:CreateWindow("TTJY X POOM HUB X CAT SUS X KTOLLT X XVAS BETA",1,nil,nil)

local jigoku = Win:CreateTab("Jigoku",function() end)

jigoku:CreateButton("Teleport To Red guy",function()
if workspace:FindFirstChild("IdleNPC") then
        game.StarterGui:SetCore("SendNotification",{
        Title = "Error 00";
        Text = "Found";
    })
        for i, v in pairs(Workspace:GetDescendants()) do
        if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart")  then
        game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(310.32,3.23,323.65)
            wait(0.3)
            fireproximityprompt(v)
        end
    end
    else
    game.StarterGui:SetCore("SendNotification",{
        Title = "Error 00";
        Text = "Not Found";
    })
        end
end)
jigoku:CreateButton("Auto Win",function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(607.54,11.91,1080)
    game.StarterGui:SetCore("SendNotification",{
        Title = "Error 00";
        Text = "Set time 11";
    })
    task.wait(11)
for i, v in pairs(Workspace:GetDescendants()) do
if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart")  then
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
    wait(0.3)
    fireproximityprompt(v)
end
end
end)

local b1c1 = Win:CreateTab("Chapter 1",function() end)
local b1c2 = Win:CreateTab("Chapter 2",function() end)
local b1c3 = Win:CreateTab("Chapter 3",function() end)
local b1c4 = Win:CreateTab("Chapter 4",function() end)
local b2c1 = Win:CreateTab("Book 2 Chapter 1",function() end)
local b2c2 = Win:CreateTab("Book 2 Chapter 2",function() end)
local b2c3 = Win:CreateTab("Book 2 Chapter 3",function() end)
local b2c4 = Win:CreateTab("Book 2 Chapter 4",function() end)
local b2c5 = Win:CreateTab("Book 2 Chapter 5",function() end)
