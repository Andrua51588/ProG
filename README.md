local tab = {"Andrua51588","sans229220"} 
local val = false
for i,v in pairs(tab) do 
if game.Players.LocalPlayer.Name == v then 
val = true 
end end 
if val == false then 
game.Players.LocalPlayer:Kick("Free Hacker")
end 
local userId = game.Players.LocalPlayer.UserId 
local thumbType = Enum.ThumbnailType.HeadShot 
local thumbSize = Enum.ThumbnailSize.Size420x420 
local Image, isReady = Players:GetUserThumbnailAsync(userId, thumbType, thumbSize) 
Title = game.Players.LocalPlayer.Name.."; 
Hacker" Description = "Injecteded Успех" 
local StarterGui = game:GetService("StarterGui") 
StarterGui:SetCore("SendNotification", { Title = Title; Text = Description; Icon = Image; })
