local uistest = game:GetService("UserInputService")
local creamorbtest = false
local playertest = game.Players.LocalPlayer
local rstoragetest = game:GetService("ReplicatedStorage")
local mystand = nil
local movetest = false
local mousetest = playertest:GetMouse()
local humtest = playertest.Character.Humanoid
local chartest = playertest.Character
local hrptest = chartest.HumanoidRootPart
local humtest = playertest.Character.Humanoid
local blockingtest = false
local vanillaiceisangrytest = 0
local dogdeval = 0
local customcreammodetest = false
local customcreammodelegittest = true
local rservicetest = game:GetService("RunService")
rstoragetest.Menacing:FireServer(true)

for i,v in pairs(game:GetService("Lighting"):GetChildren())do
    for i,v2 in pairs(game:GetService("Players").LocalPlayer.Character:GetChildren())do
        if v:IsA("LocalScript") and v2:IsA("LocalScript") then
            if v.Name == v2.Name then
                mystand = v2.Name
            end
        end
    end
end
game.Players.LocalPlayer.Character[mystand]:Destroy()

coroutine.resume(coroutine.create(function()
while rservicetest.Stepped:Wait() do
print("working")
    for i,v in pairs(chartest.HumanoidRootPart:GetChildren()) do
        print("found something")
        if v:IsA("BodyVelocity") or v:IsA("BodyPosition")then
            print(v.Name)
            v:Destroy()
        end
    end
end
end))
    
function nanhptest()
    game:GetService("ReplicatedStorage").Block:FireServer(true)
    game:GetService("ReplicatedStorage").BurnDamage:FireServer(humtest, CFrame.new(0, -50, 0), -math.huge, 0, Vector3.new(0, 0, 0), "rbxassetid://241837157", 0, Color3.new(255, 255, 255), "rbxassetid://260430079", 0, 0)
    wait()
    game:GetService("ReplicatedStorage").BurnDamage:FireServer(humtest, CFrame.new(0, -50, 0), math.huge, 0, Vector3.new(0, 0, 0), "rbxassetid://241837157", 0, Color3.new(255, 255, 255), "rbxassetid://260430079", 0, 0)
    wait(0.5)
    rstoragetest.Doppio2KCEpitaph:FireServer()
    playertest.Character.Deflect:Destroy()
    playertest.Character.Virus:Destroy()
    playertest.Character.BlockReduction:Destroy()
    playertest.Character.Block:Destroy()
    playertest.Character.Disabled:Destroy()
    playertest.Character.Vaccine:Destroy()
end
nanhptest()
rstoragetest.Doppio2KCEpitaph:FireServer()

function assettest(Id)
    return "rbxassetid://"..Id
end

function creamtdamagetest()
    for i,v in pairs(game.Workspace.Entities:GetChildren()) do
        if v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Name ~= game.Players.LocalPlayer.Name then
            if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v.HumanoidRootPart.Position).Magnitude < 15 then
                game.ReplicatedStorage.HamonSword:FireServer(v.Humanoid, 1e-320, math.huge, Vector3.new(-1e7, -1e7, 0))
                game.ReplicatedStorage.Damage12:FireServer(v.Humanoid, v.HumanoidRootPart.CFrame, 99, 0, Vector3.new(0, 0, 0), 0.01, "rbxassetid://4513955975", 1, 20)
                game.ReplicatedStorage.Damage12Sans:FireServer(v.Humanoid, v.HumanoidRootPart.CFrame, 99, 0, Vector3.new(0, 0, 0), 0.01, "rbxassetid://4513955975", 1, 20)
				game.ReplicatedStorage.Damage12Enderman:FireServer(v.Humanoid, v.HumanoidRootPart.CFrame, 99, 0, Vector3.new(0, 0, 0), 0.01, "rbxassetid://4513955975", 1, 20)
                game.ReplicatedStorage.Damage3:FireServer(v.Humanoid, v.HumanoidRootPart.CFrame, 99, 10, Vector3.new(9e999,9e999,0), 0.01, "rbxassetid://4513955975", 1, 20)
            end
        end
    end
end

function CRASHTEST()
    for i,v in pairs(game.Workspace.Entities:GetChildren()) do
        if v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Name ~= game.Players.LocalPlayer.Name then
            if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v.HumanoidRootPart.Position).Magnitude < 10000000 then
                game.ReplicatedStorage.HamonSword:FireServer(v.Humanoid, 1e-320, math.huge, Vector3.new(-1e7, -1e7, 0))
                game.ReplicatedStorage.HamonSword:FireServer(v.Humanoid, 1e-320, math.huge, Vector3.new(0, -1e7, -1e7))
                game.ReplicatedStorage.Damage12:FireServer(v.Humanoid, v.HumanoidRootPart.CFrame, 99, 0, Vector3.new(0, 0, 0), 0.01, "rbxassetid://4513955975", 1, 20)
                game.ReplicatedStorage.Damage12Sans:FireServer(v.Humanoid, v.HumanoidRootPart.CFrame, 99, 0, Vector3.new(0, 0, 0), 0.01, "rbxassetid://4513955975", 1, 20)
				game.ReplicatedStorage.Damage12Enderman:FireServer(v.Humanoid, v.HumanoidRootPart.CFrame, 99, 0, Vector3.new(0, 0, 0), 0.01, "rbxassetid://4513955975", 1, 20)
                game.ReplicatedStorage.Damage3:FireServer(v.Humanoid, v.HumanoidRootPart.CFrame, 99, 10, Vector3.new(9e999,9e999,0), 0.01, "rbxassetid://4513955975", 1, 20)
            end
        end
    end
end

function creamtrushtest()
    local creamrushtest = Instance.new("BodyVelocity")
    creamrushtest.MaxForce = Vector3.new(100000, 0, 100000)
    creamrushtest.P = math.huge
    creamrushtest.Velocity = playertest.Character.HumanoidRootPart.CFrame.lookVector * 200
    creamrushtest.Parent = playertest.Character.Torso
    wait()
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    wait()
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    wait()
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    wait()
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    wait()
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    wait()
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    wait()
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    wait()
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    wait()
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    wait()
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    wait()
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    wait()
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    wait()
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    wait()
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    wait()
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    creamrushtest:Destroy()
    wait()
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
end

function creamspintest()
    for i = 1,70 do
        wait()
        creamtdamagetest()
        rstoragetest.UR2:FireServer(2)
        creamtdamagetest()
        rstoragetest.UR2:FireServer(2)
        playertest.Character.HumanoidRootPart.CFrame =  playertest.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-35)
        playertest.Character.HumanoidRootPart.CFrame = playertest.Character.HumanoidRootPart.CFrame * CFrame.fromEulerAnglesXYZ(0,8,0)
        wait(0.01)
        creamtdamagetest()
        rstoragetest.UR2:FireServer(2)
        creamtdamagetest()
        rstoragetest.UR2:FireServer(2)
        playertest.Character.HumanoidRootPart.CFrame =  playertest.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-55)
        playertest.Character.HumanoidRootPart.CFrame = playertest.Character.HumanoidRootPart.CFrame * CFrame.fromEulerAnglesXYZ(0,8,0)
        wait(0.01)
        creamtdamagetest()
        rstoragetest.UR2:FireServer(2)
        creamtdamagetest()
        rstoragetest.UR2:FireServer(2)
        playertest.Character.HumanoidRootPart.CFrame =  playertest.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-35)
        playertest.Character.HumanoidRootPart.CFrame = playertest.Character.HumanoidRootPart.CFrame * CFrame.fromEulerAnglesXYZ(0,8,0)
    end
end

function creamjustcream()
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    wait()
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
end

function creamsidetosidetest()
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    playertest.Character:SetPrimaryPartCFrame(playertest.Character.HumanoidRootPart.CFrame * CFrame.fromEulerAnglesXYZ(0, -13.2, 0))
    playertest.Character:SetPrimaryPartCFrame(playertest.Character.HumanoidRootPart.CFrame * CFrame.new(0, 2, -40))
    playertest.Character:SetPrimaryPartCFrame(playertest.Character.HumanoidRootPart.CFrame * CFrame.fromEulerAnglesXYZ(0, 14, 0))
    wait(0.01)
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    wait(0.01)
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    playertest.Character:SetPrimaryPartCFrame(playertest.Character.HumanoidRootPart.CFrame * CFrame.new(0, 2, -40))
    playertest.Character:SetPrimaryPartCFrame(playertest.Character.HumanoidRootPart.CFrame * CFrame.fromEulerAnglesXYZ(0, -14, 0))
    wait(0.01)
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    wait(0.01)
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    creamtdamagetest()
    playertest.Character:SetPrimaryPartCFrame(playertest.Character.HumanoidRootPart.CFrame * CFrame.new(0, 5, -40))
    playertest.Character:SetPrimaryPartCFrame(playertest.Character.HumanoidRootPart.CFrame * CFrame.fromEulerAnglesXYZ(0, 14, 0))
    wait(0.01)
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    wait(0.01)
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    playertest.Character:SetPrimaryPartCFrame(playertest.Character.HumanoidRootPart.CFrame * CFrame.new(0, 5, -40))
    playertest.Character:SetPrimaryPartCFrame(playertest.Character.HumanoidRootPart.CFrame * CFrame.fromEulerAnglesXYZ(0, -14, 0))
    wait(0.01)
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    playertest.Character:SetPrimaryPartCFrame(playertest.Character.HumanoidRootPart.CFrame * CFrame.new(0, 5, -40))
    playertest.Character:SetPrimaryPartCFrame(playertest.Character.HumanoidRootPart.CFrame * CFrame.fromEulerAnglesXYZ(0, 14, 0))
    wait(0.01)
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    wait(0.01)
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    creamtdamagetest()
    playertest.Character:SetPrimaryPartCFrame(playertest.Character.HumanoidRootPart.CFrame * CFrame.new(0, 5, -40))
    playertest.Character:SetPrimaryPartCFrame(playertest.Character.HumanoidRootPart.CFrame * CFrame.fromEulerAnglesXYZ(0, -14, 0))
    wait(0.01)
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    wait(0.01)
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    creamtdamagetest()
    playertest.Character:SetPrimaryPartCFrame(playertest.Character.HumanoidRootPart.CFrame * CFrame.new(0, 2, -40))
    playertest.Character:SetPrimaryPartCFrame(playertest.Character.HumanoidRootPart.CFrame * CFrame.fromEulerAnglesXYZ(0, 14, 0))
    wait(0.01)
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    creamtdamagetest()
    wait(0.01)
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    playertest.Character:SetPrimaryPartCFrame(playertest.Character.HumanoidRootPart.CFrame * CFrame.new(0, 2, -40))
    playertest.Character:SetPrimaryPartCFrame(playertest.Character.HumanoidRootPart.CFrame * CFrame.fromEulerAnglesXYZ(0, -14, 0))
    wait(0.01)
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
    rstoragetest.UR2:FireServer(2)
    creamtdamagetest()
end

function creamjabtest()
    pcall(function()
        local creamjabtest = Instance.new("BodyVelocity")
        creamjabtest.MaxForce = Vector3.new(100000, 0, 100000)
        creamjabtest.P = math.huge
        creamjabtest.Velocity = playertest.Character.HumanoidRootPart.CFrame.lookVector * 50
        creamjabtest.Parent = playertest.Character.Torso
        wait(0.1)  
        G_Punch = Instance.new("Animation")
        G_Punch.AnimationId = assettest(4774879706)
        G_PunchAnim = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(G_Punch)
        G_PunchAnim:Play()
        local hitbox1 = Instance.new("Part",game.Players.LocalPlayer.Character)
        hitbox1.CFrame = game.Players.LocalPlayer.Character["Left Arm"].CFrame
        hitbox1.Name = "hitbox"
        hitbox1.Anchored = false
        hitbox1.CanCollide = false
        local weld = Instance.new("WeldConstraint",hitbox1)
        weld.Part0 = hitbox1
        weld.Part1 = game.Players.LocalPlayer.Character["Left Arm"]
        hitbox1.Size = game.Players.LocalPlayer.Character["Left Arm"].Size*5
        hitbox1.Massless = true
        hitbox1.Transparency = 1
        hitbox1.Color = Color3.new(0,0,0)
        hitbox1.Touched:Connect(function(hit)
            if hit.Parent:FindFirstChild("Humanoid") and hit.Parent.Name ~= game.Players.LocalPlayer.Name then
                if hit.Parent:FindFirstChild("HumanoidRootPart") then
                    local A_1 = hit.Parent.Humanoid
                    local A_2 = hit.Parent.HumanoidRootPart.CFrame
                    local A_3 = 99
                    local A_4 = 10
                    local A_5 = Vector3.new(0,-10,0)
                    local A_6 = "rbxassetid://"
                    local A_7 = 0.075
                    local A_8 = "rbxassetid://260430079"
                    local A_9 = 0.9
                    local A_10 = 0.44
                    local Event = game:GetService("ReplicatedStorage").Damage
                    Event:FireServer(A_1, A_2, A_3, A_4, A_5, A_6, A_7, A_8, A_9, A_10)
                    for i,v in pairs(hit.Parent:GetChildren()) do
                        if v:IsA("Part") then
                            game:GetService("ReplicatedStorage").Anchor:FireServer(v,false)
                        end
                    end
                        game.ReplicatedStorage.Damage3:FireServer(hit.Parent.Humanoid, CFrame.new(0,0,0), 99, 2, game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame.LookVector*5000+Vector3.new(9e999, 9e999, 0), 0.1, "rbxassetid://1693499499", 0.2, 0)
                end
            end
            wait(0.1)
            if hitbox1 then
            hitbox1:Destroy() 
            creamjabtest:Destroy()
            end
        end)
    end)
end

uidodge1anim = Instance.new("Animation", playertest.Character)
    uidodge1anim.AnimationId = assettest(5633583111)

    _G.anim39 = playertest.Character.Humanoid:LoadAnimation(uidodge1anim)

    uidodge2anim = Instance.new("Animation", playertest.Character)
    uidodge2anim.AnimationId = assettest(5633584586)

    _G.anim40 = playertest.Character.Humanoid:LoadAnimation(uidodge2anim)
function passivedodgeanimatetest()
	local randompassivedodgeanimate = math.random(1, 2)
	if randompassivedodgeanimate == 1 then
_G.anim39:Play()
	elseif randompassivedodgeanimate == 2 then
_G.anim40:Play()
		end
end
function dogdetest()
        wait(1)
        rstoragetest.RTZClient.OnClientEvent:connect(function(gamer)
            if gamer ~= Player then
            local gmhum = gamer.Character.Humanoid
                local gmchr = gamer.Character
                passivedodgeanimatetest()
                rstoragetest.UR2:FireServer(2)
                creamtdamagetest()
            end
        end)
end
dogdetest()

function chargetest()
    pcall(function()
        G_WEEEE = Instance.new("Animation")
        G_WEEEE.AnimationId = assettest(4814777086)
        G_WEEEAnim = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(G_WEEEE)
        G_WEEEAnim:Play(0.1, 1, 2)
        G_WEEEAnim:AdjustSpeed(1.4)
        playertest.Character.Humanoid.WalkSpeed = 16
		playertest.Character.Humanoid.JumpPower = 50
        wait(0.7)
        local charagehitbox = Instance.new("Part",playertest.Character)
        charagehitbox.CFrame = playertest.Character["Left Arm"].CFrame
        charagehitbox.Name = "chargehitboxnametest"
        charagehitbox.Anchored = false
        charagehitbox.CanCollide = false
        local weld = Instance.new("WeldConstraint",charagehitbox)
        weld.Part0 = charagehitbox
        weld.Part1 = playertest.Character["Left Arm"]
        charagehitbox.Size = playertest.Character["Left Arm"].Size*10
        charagehitbox.Massless = true
        charagehitbox.Transparency = 1
        charagehitbox.Color = Color3.new(0,0,0)
        charagehitbox.Touched:Connect(function(ouch)
        local chargeboosttest = Instance.new("BodyVelocity")
        chargeboosttest.MaxForce = Vector3.new(100000, 100000, 100000)
        chargeboosttest.P = math.huge
        chargeboosttest.Velocity = playertest.Character.HumanoidRootPart.CFrame.lookVector * 100
        chargeboosttest.Parent = playertest.Character.Torso
        wait(0.5)
        chargeboosttest:Destroy()
        rstoragetest.UR2:FireServer(2)
        creamtdamagetest()
        rstoragetest.UR2:FireServer(2)
        creamtdamagetest()
        rstoragetest.UR2:FireServer(2)
        creamtdamagetest()
            if ouch.Parent:FindFirstChild("Humanoid") and ouch.Parent.Name ~= game.Players.LocalPlayer.Name then
                if ouch.Parent:FindFirstChild("HumanoidRootPart") then
                    local bruh1 = ouch.Parent.Humanoid
                    local bruh2 = ouch.Parent.HumanoidRootPart.CFrame
                    local bruh3 = 199
                    local bruh4 = 11
                    local bruh5 = Vector3.new(0,-10,0)
                    local bruh6 = "rbxassetid://"
                    local bruh7 = 0.075
                    local bruh8 = "rbxassetid://260430079"
                    local bruh9 = 0.9
                    local bruh10 = 0.44
                    local Event = game:GetService("ReplicatedStorage").Damage
                    Event:FireServer(bruh1, bruh2, bruh3, bruh4, bruh5, bruh6, bruh7, bruh8, bruh9, bruh10)
                    for i,v in pairs(ouch.Parent:GetChildren()) do
                        if v:IsA("Part") then
                            game:GetService("ReplicatedStorage").Anchor:FireServer(v,false)
                        end
                    end
                        game.ReplicatedStorage.Damage3:FireServer(ouch.Parent.Humanoid, CFrame.new(0,0,0), 99, 2, game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame.LookVector*5000+Vector3.new(9e999, 9e999, 0), 0.1, "rbxassetid://1693499499", 0.2, 0)
                end
            end
            wait(0.5)
            playertest.Character.Humanoid.WalkSpeed = 16
		    playertest.Character.Humanoid.JumpPower = 50
            if charagehitbox then
            charagehitbox:Destroy() 
            end
        end)
    end)
end

function airjabgobrrr()
    pcall(function()
        G_jumpjab = Instance.new("Animation")
        G_jumpjab.AnimationId = assettest(4774988533)
        G_jumpjabAnim = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(G_jumpjab)
        G_jumpjabAnim:Play(0.1, 1, 1.4)
        local airjab = Instance.new("Part",playertest.Character)
        airjab.CFrame = playertest.Character["Left Arm"].CFrame
        airjab.Name = "chargehitboxnametest"
        airjab.Anchored = false
        airjab.CanCollide = false
        local weld = Instance.new("WeldConstraint",airjab)
        weld.Part0 = airjab
        weld.Part1 = playertest.Character["Left Arm"]
        airjab.Size = playertest.Character["Left Arm"].Size*8
        airjab.Massless = true
        airjab.Transparency = 1
        airjab.Color = Color3.new(0,0,0)
        airjab.Touched:Connect(function(AIRJABOUCH)
        local airjabboost = Instance.new("BodyVelocity")
        airjabboost.MaxForce = Vector3.new(100000, 0, 100000)
        airjabboost.P = math.huge
        airjabboost.Velocity = playertest.Character.HumanoidRootPart.CFrame.lookVector * 75
        airjabboost.Parent = playertest.Character.Torso
        wait(0.01)
        airjabboost:Destroy()
            if AIRJABOUCH.Parent:FindFirstChild("Humanoid") and AIRJABOUCH.Parent.Name ~= game.Players.LocalPlayer.Name then
                if AIRJABOUCH.Parent:FindFirstChild("HumanoidRootPart") then
                    local ez1 = AIRJABOUCH.Parent.Humanoid
                    local ez2 = AIRJABOUCH.Parent.HumanoidRootPart.CFrame
                    local ez3 = 99
                    local ez4 = 10
                    local ez5 = Vector3.new(0,-10,0)
                    local ez6 = "rbxassetid://"
                    local ez7 = 0.075
                    local ez8 = "rbxassetid://260430079"
                    local ez9 = 0.9
                    local ez10 = 0.44
                    local Event = game:GetService("ReplicatedStorage").Damage
                    Event:FireServer(ez1, ez2, ez3, ez4, ez5, ez6, ez7, ez8, ez9, ez10)
                    for i,v in pairs(AIRJABOUCH.Parent:GetChildren()) do
                        if v:IsA("Part") then
                            game:GetService("ReplicatedStorage").Anchor:FireServer(v,false)
                        end
                    end
                        game.ReplicatedStorage.Damage3:FireServer(AIRJABOUCH.Parent.Humanoid, CFrame.new(0,0,0), 99, 2, game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame.LookVector*5000+Vector3.new(9e999, 9e999, 0), 0.1, "rbxassetid://1693499499", 0.2, 0)
                end
            end
            wait(0.5)
            if airjab then
            airjab:Destroy() 
            end
        end)
    end)
end

function CRASHSERVER()
    pcall(function()
        G_jumpjab = Instance.new("Animation")
        G_jumpjab.AnimationId = assettest(3445715100)
        G_jumpjabAnim = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(G_jumpjab)
        G_jumpjabAnim:Play(0.1, 1, 1.4)
        playertest.Character.Humanoid.WalkSpeed = 100
		playertest.Character.Humanoid.JumpPower = 70
        wait(1)
        local airjab = Instance.new("Part",playertest.Character)
        airjab.CFrame = playertest.Character["Left Arm"].CFrame
        airjab.Name = "chargehitboxnametest"
        airjab.Anchored = false
        airjab.CanCollide = false
        local weld = Instance.new("WeldConstraint",airjab)
        weld.Part0 = airjab
        weld.Part1 = playertest.Character["Left Arm"]
        airjab.Size = playertest.Character["Left Arm"].Size*10
        airjab.Massless = true
        airjab.Transparency = 1
        airjab.Color = Color3.new(0,0,0)
        airjab.Touched:Connect(function(AIRJABOUCH)
        local airjabboost = Instance.new("BodyVelocity")
        airjabboost.MaxForce = Vector3.new(100000, 0, 100000)
        airjabboost.P = math.huge
        airjabboost.Velocity = playertest.Character.HumanoidRootPart.CFrame.lookVector * 10
        airjabboost.Parent = playertest.Character.Torso
        airjabboost:Destroy()
            if AIRJABOUCH.Parent:FindFirstChild("Humanoid") and AIRJABOUCH.Parent.Name ~= game.Players.LocalPlayer.Name then
                if AIRJABOUCH.Parent:FindFirstChild("HumanoidRootPart") then
                    local ez1 = AIRJABOUCH.Parent.Humanoid
                    local ez2 = AIRJABOUCH.Parent.HumanoidRootPart.CFrame
                    local ez3 = 99
                    local ez4 = 10
                    local ez5 = Vector3.new(0,-10,0)
                    local ez6 = "rbxassetid://"
                    local ez7 = 0.075
                    local ez8 = "rbxassetid://260430079"
                    local ez9 = 0.9
                    local ez10 = 0.44
                    local Event = game:GetService("ReplicatedStorage").Damage
                    Event:FireServer(ez1, ez2, ez3, ez4, ez5, ez6, ez7, ez8, ez9, ez10)
                    for i,v in pairs(AIRJABOUCH.Parent:GetChildren()) do
                        if v:IsA("Part") then
                            game:GetService("ReplicatedStorage").Anchor:FireServer(v,true)
                            rstoragetest.UR2:FireServer(2)
                            CRASHTEST()
                            rstoragetest.UR2:FireServer(2)
                            CRASHTEST()
                            rstoragetest.UR2:FireServer(2)
                            CRASHTEST()
                            rstoragetest.UR2:FireServer(2)
                            CRASHTEST()
                            rstoragetest.UR2:FireServer(2)
                            CRASHTEST()
                            rstoragetest.UR2:FireServer(2)
                            CRASHTEST()
                            rstoragetest.UR2:FireServer(2)
                            CRASHTEST()
                            rstoragetest.UR2:FireServer(2)
                            CRASHTEST()
                            rstoragetest.UR2:FireServer(2)
                            CRASHTEST()
                            rstoragetest.UR2:FireServer(2)
                            CRASHTEST()
                            rstoragetest.UR2:FireServer(2)
                            CRASHTEST()
                        end
                    end
                        game.ReplicatedStorage.Damage3:FireServer(AIRJABOUCH.Parent.Humanoid, CFrame.new(0,0,0), 99, 2, game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame.LookVector*5000+Vector3.new(9e999, 9e999, 0), 0.1, "rbxassetid://1693499499", 0.2, 0)
                end
            end
            wait(0.1)
             playertest.Character.Humanoid.WalkSpeed = 30
		     playertest.Character.Humanoid.JumpPower = 50
            if airjab then
            airjab:Destroy()
            CRASHTEST:Destroy()
            end
        end)
    end)
end

mousetest.KeyDown:connect(function(key)
    if key == "y" then
        vanillaiceisangrytest = vanillaiceisangrytest + 1
        if vanillaiceisangrytest == 1 then
            customcreammodetest = true
            customcreammodelegittest = false
            repeat
                rstoragetest.UR2:FireServer(2)
                creamtdamagetest()
                playertest.Character.Humanoid.WalkSpeed = 100
                playertest.Character.Humanoid.JumpPower = 80
                wait()
            until customcreammodetest == false
        end
        if vanillaiceisangrytest == 2 then
            customcreammodetest = false
            customcreammodelegittest = true
            vanillaiceisangrytest = 0
            playertest.Character.Humanoid.WalkSpeed = 50
            playertest.Character.Humanoid.JumpPower = 50
        end
    end
    if key == "f" then
        chargetest()
    end
    if key == "u" then
        dogdeval = dogdeval + 1
        if dogdeval == 1 then
            rstoragetest.RTZ:FireServer(true)
            rstoragetest.UR2:FireServer(2)
        end
        if dogdeval == 2 then
            rstoragetest.RTZ:FireServer(false)
            dogdeval = 0
        end
    end
    if key == "h" then
        creamjustcream()
    end
    if key == "]" then
        CRASHSERVER()
    end
 if key == "g" then
        airjabgobrrr()
    end
    if key == "e" then
        creamjabtest()
    end
    if key == "r" then
        creamsidetosidetest()
    end
    if key == "v" then
        creamtrushtest()
    end
    if key == "z" then
        rstoragetest.UR2:FireServer(2)
        creamtdamagetest()
        playertest.Character.HumanoidRootPart.CFrame = CFrame.new(mousetest.hit.p.X, mousetest.hit.p.Y + 2, mousetest.hit.p.Z)
        wait(0.1)
        rstoragetest.UR2:FireServer(2)
        creamtdamagetest()
    end
    if key == "t" then
        creamspintest()
    end
end)

uistest.InputBegan:Connect(function(Input, IsTyping)
    if IsTyping then return end
    if Input.KeyCode == Enum.KeyCode.C then
        creamorbtest = true
        local creamspeedgobrrtest = Instance.new("BodyVelocity")
        creamspeedgobrrtest.Name = "creamgovroomvroom"
        creamspeedgobrrtest.MaxForce = Vector3.new(100000, 0, 100000)
        creamspeedgobrrtest.P = math.huge
        creamspeedgobrrtest.Velocity = playertest.Character.HumanoidRootPart.CFrame.lookVector * 130
        creamspeedgobrrtest.Parent = playertest.Character.Torso
        repeat
            wait()
            rstoragetest.UR2:FireServer(2)
            creamtdamagetest()
            creamspeedgobrrtest.Velocity = playertest.Character.HumanoidRootPart.CFrame.lookVector * 130
        until creamorbtest == false
    end
end)
uistest.InputEnded:Connect(function(Input, IsTyping)
    if IsTyping then return end
    if Input.KeyCode == Enum.KeyCode.C then
        creamorbtest = false
        game.Players.LocalPlayer.Character.Torso.creamgovroomvroom:Destroy()
    end
end)

l.TS.Changed:Connect(function()
    if l.TS.Value == true then
        if death == true then return end
        rs.RTZ:FireServer(true)
        rs.RTZEffect:FireServer(true)
        wait(0.1)
        rs.RTZ:FireServer(false)
    end
end)
l.TE.Changed:Connect(function()
    if l.TE.Value == true then
        if death == true then return end
        rs.RTZ:FireServer(true)
        rs.RTZEffect:FireServer(true)
        wait(0.1)
        rs.RTZ:FireServer(false)
    end
end)
l.TA.Changed:Connect(function()
    if l.TA.Value == true then
        if death == true then return end
        rs.RTZ:FireServer(true)
        rs.RTZEffect:FireServer(true)
        wait(0.1)
        rs.RTZ:FireServer(false)
    end
end)
l.GI.Changed:Connect(function()
    if l.GI.Value == true then
        if death == true then return end
        rs.RTZ:FireServer(true)
        rs.RTZEffect:FireServer(true)
        wait(0.1)
        rs.RTZ:FireServer(false)
    end
end)
while true do
    wait(1)
    for i,v in pairs(game.Players.LocalPlayer.Character:GetDescendants()) do
        if v:IsA("Part") then 
            game:GetService("ReplicatedStorage").Anchor:FireServer(v,false)
        end
    end
end
