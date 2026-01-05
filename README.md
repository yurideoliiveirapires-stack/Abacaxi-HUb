

local screenGui = Instance.new("ScreenGui")
screenGui.Name = "AvisoAtualizacao"
screenGui.ResetOnSpawn = false
screenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")


local fundo = Instance.new("Frame")
fundo.Size = UDim2.new(1, 0, 1, 0) -- ocupa toda a tela
fundo.Position = UDim2.new(0, 0, 0, 0)
fundo.BackgroundColor3 = Color3.fromRGB(0, 0, 0) -- preto
fundo.BorderSizePixel = 0
fundo.Parent = screenGui


local aviso = Instance.new("TextLabel")
aviso.Size = UDim2.new(0.8, 0, 0.3, 0) -- ocupa boa parte da tela
aviso.Position = UDim2.new(0.1, 0, 0.35, 0) -- centralizado verticalmente
aviso.BackgroundTransparency = 1
aviso.TextColor3 = Color3.fromRGB(255, 255, 255) -- branco
aviso.TextScaled = true
aviso.Font = Enum.Font.GothamBold
aviso.TextWrapped = true
aviso.Text = "Script desativado temporariamente.\nMotivo: O script será atualizado com todas as melhorias e correções de bugs em uma única atualização.\nAgradecemos a compreensão."
aviso.Parent = fundo
