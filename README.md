# jmpanti
jump and anti

_G.BlizexJumpableAnti= true

    game.RunService.Heartbeat:Connect(function()
        if _G.BlizexJumpableAntithen    
        local CurrentVelocity = game.Players.LocalPlayer.Character.HumanoidRootPart.Velocity
        game.Players.LocalPlayer.Character.HumanoidRootPart.Velocity = Vector3.new(1000,1000,1000)
        game.RunService.RenderStepped:Wait()
        game.Players.LocalPlayer.Character.HumanoidRootPart.Velocity = CurrentVelocity
        end    
    end)
﻿
