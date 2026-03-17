-- [[ URIEL V1 - EXPANSÃO FF ]]

-- 1. ABA DE VISUAIS (ESP AVANÇADO)
local TabESP = Window:NewTab("Visuals (ESP)")
local SectionESP = TabESP:NewSection("Sensing Inimigos")

SectionESP:NewToggle("ESP Nomes", "Mostra o nick dos jogadores", function(state)
    _G.ESP_Names = state
    -- Lógica para desenhar o nome acima do personagem
end)

SectionESP:NewToggle("ESP Distância", "Mostra a quantos metros estão", function(state)
    _G.ESP_Distance = state
end)

SectionESP:NewToggle("Antena Cabeça", "Linha gigante no céu", function(state)
    _G.Antenna = state
end)

-- 2. ABA DE MOVIMENTAÇÃO (EXPLOITS)
local TabMov = Window:NewTab("Movimentação")
local SectionMov = TabMov:NewSection("Vantagens de Mapa")

SectionMov:NewSlider("Velocidade (Speed)", "Aumenta a corrida", 100, 16, function(s)
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s
end)

SectionMov:NewSlider("Super Pulo", "Pula mais alto", 200, 50, function(s)
    game.Players.LocalPlayer.Character.Humanoid.JumpPower = s
end)

SectionMov:NewToggle("Medkit Correndo", "Cura sem parar", function(state)
    _G.MedkitRun = state
end)

-- 3. ABA DE REGEDIT (SENSI & LOCK)
local TabReg = Window:NewTab("Regedit (Sensi)")
local SectionReg = TabReg:NewSection("Ajustes de Memória")

SectionReg:NewToggle("Aim Lock (Cabeça)", "Trava a mira no pescoço", function(state)
    _G.AimLock = state
end)

SectionReg:NewSlider("Sensi Max (DPI)", "Aumenta a sensibilidade", 1000, 100, function(s)
    _G.SensiValue = s
end)

SectionReg:NewToggle("No Recoil 100%", "Balas não espalham", function(state)
    _G.NoRecoil = state
end)

-- [[ LÓGICA DE LOOP PARA ESP E AIMLOCK ]]
game:GetService("RunService").RenderStepped:Connect(function()
    if _G.AimLock then
        -- Lógica de trava de memória (AimLock)
    end
    
    if _G.ESP_Names or _G.ESP_Distance then
        -- Lógica para atualizar os desenhos na tela
    end
end)

Uriel_capa_2026
