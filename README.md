local DrRayLibrary = loadstring(game:HttpGet("https://raw.githubusercontent.com/AZYsGithub/DrRay-UI-Library/main/DrRay.lua"))()

local window = DrRayLibrary:Load("Workers menu", "Default")


local tab = DrRayLibrary.newTab("farmar", "ImageIdHere")


local laap = falss
tab.newToggle("auto rebirth", "Da rebirth automático ", false, function(valuri)
 laap = valuri
    if laap then
    while laap do
    if laap then
    wait()
    local multiplicador = 2


local args = {
    [1] = game:GetService("Players").LocalPlayer
}


for i = 1, multiplicador - 1 do
    table.insert(args, game:GetService("Players").LocalPlayer)
end


game:GetService("ReplicatedStorage").Functions.Rebirth:InvokeServer(unpack(args))
         end
      end
    end
end)

local loop = false
tab.newToggle("auto fighters30", "farma os fighters 30", false, function(value)
  loop = value
    if loop then
        while loop do
          if loop then
            wait()
            if loop then
            local player = game.Players.LocalPlayer
    local char = player.Character

    char.HumanoidRootPart.CFrame = CFrame.new(-1067, 12, -1307)
            end
            
    wait(5)
if loop then
    fireclickdetector(workspace.Interactive.NPCQUEST.NpcTalk.ClickDetector)
end
    wait(7)

    local player = game.Players.LocalPlayer
    local character = player.Character or player.CharacterAdded:Wait()
    local Humanoid = character:FindFirstChildOfClass("Humanoid")
    local HumanoidRootPart = character:FindFirstChild("HumanoidRootPart")

    local pasta = workspace:WaitForChild("Npcs")
    local subpasta = pasta:WaitForChild("Fighters3")
    for _, npc in pairs(subpasta:GetChildren()) do
        local humanoidRootPart = npc:FindFirstChild("HumanoidRootPart")
        local humanoid = npc:FindFirstChildOfClass("Humanoid")

        if humanoidRootPart and humanoid  and loop then
            wait(0.5)
            local npcPosition = humanoidRootPart.Position
            print(npcPosition) 

            
            local direction = (HumanoidRootPart.Position - npcPosition).Unit 
            local newPosition = npcPosition + direction * 3 

            
            HumanoidRootPart.CFrame = CFrame.lookAt(newPosition, npcPosition)

            wait(0.2)

            
         if loop then   
local player = game.Players.LocalPlayer
local backpack = player:WaitForChild("Backpack")
local character = player.Character or player.CharacterAdded:Wait()

local function equipCombat()
    local tool = backpack:FindFirstChild("Combat")
    if tool then
        character.Humanoid:EquipTool(tool)
    else
        print("Item 'Combat' não encontrado na mochila.")
    end
end

equipCombat()
         end     
            
if loop then
humanoid.Health = humanoid.Health -1
      wait(0.2)
            humanoid.Health = 0 
end
local function checarnpc()
while true do 
wait(0.1)
local pasta = workspace:WaitForChild("Npcs")
    local subpasta = pasta:WaitForChild("Fighters3")
    for _, npc in pairs(subpasta:GetChildren()) do
        local humanoidRootPart = npc:FindFirstChild("HumanoidRootPart")
        local humanoid = npc:FindFirstChildOfClass("Humanoid")

    
        
    if  not humanoid or not humanoidRootPart then
        wait(0.4)
        
        print("sem npcs")
              end
         end
     end
end
            
            coroutine.wrap(checarnpc)()
            wait(0.5)
          if loop then
            local args = {
                [1] = game:GetService("Players").LocalPlayer
            }

            game:GetService("ReplicatedStorage").Events.boxing:FireServer(unpack(args))
          end
            wait(0.5)
            
            
local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

local function unequipCombat()
    local tool = character:FindFirstChild("Combat")
    if tool then
        tool.Parent = player:WaitForChild("Backpack")
    else
        print("Item 'Combat' não está equipado.")
    end
end

unequipCombat()

            
            humanoid.Health = 100
            humanoid.Health = 900
Humanoid.Health = Humanoid.Health + 1
        end
end
            
          end
        end
    end
end)
