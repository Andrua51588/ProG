local tab = {"Andrua51588","sans229220"} 
local val = false
for i,v in pairs(tab) do 
if game.Players.LocalPlayer.Name == v then 
print("g")
val = true 
end end 
if val == false then 
game.Players.LocalPlayer:Kick("Free Hacker")
end 
Title = game.Players.LocalPlayer.Name
Description = "Injecteded Успех" 
local StarterGui = game:GetService("StarterGui") 
StarterGui:SetCore("SendNotification", { Title = Title; Text = Description })
