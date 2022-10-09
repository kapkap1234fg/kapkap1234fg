repeat wait() until game:IsLoaded()
getgenv().IsMultiStrat = true
getgenv().GoldenPerks = {"Scout"}

getgenv().Maps = {["Harbor"] = {"Farm", "Commander", "Accelerator", "Scout", "DJ Booth"},["Toyboard"] = {"Farm", "Commander", "Accelerator", "Scout", "DJ Booth"},["Portland"] = {"Farm", "Commander", "Accelerator", "Scout", "DJ Booth"}}
maplist = {"Harbor","Toyboard", "Portland"}

if game.PlaceId == 3260590327 then
    loadstring(game:HttpGet("https://raw.githubusercontent.com/banbuskox/dfhtyxvzexrxgfdzgzfdvfdz/main/ckmhjvskfkmsStratFun2", true))()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/banbuskox/dfhtyxvzexrxgfdzgzfdvfdz/main/asjhxnjfdStratFunJoin", true))()
end

if game.PlaceId == 5591597781 then
    map = game:GetService("ReplicatedStorage").State.Map.Value
    game:GetService("Players").PlayerAdded:Connect(function() --back to lobby if it detected player join the game
        game:GetService("TeleportService"):Teleport(3260590327)
        wait(10)
    end)
    for i,v in pairs(game:GetService("Players"):GetPlayers()) do --back to lobby if there is more than 1 player
        if i==2 then
            game:GetService("TeleportService"):Teleport(3260590327)
            wait(10)
        end
    end
    if map == maplist[1] then
local TDS = loadstring(game:HttpGet("https://raw.githubusercontent.com/banbuskox/dfhtyxvzexrxgfdzgzfdvfdz/main/ckmhjvskfkmsStratFun2", true))() 
TDS:Loadout("Farm", "Commander", "Accelerator", "Scout", "DJ Booth") 
TDS:Map("Harbor", true, "Survival")
TDS:Mode('Insane')
task.spawn(function()
    wait(1)
    for i,v in pairs(game.CoreGui:GetDescendants()) do
        if v:IsA("TextLabel") and v.Name == "section_lbl" and v.Text == "" then
            v.Text = "Strat By: Gurt#9903"
        end
    end
end)
TDS:Place('Scout', -29.244461059570312, 0.112127386033535, 6.871329307556152, 0, 0, 5)--1
TDS:Place('Scout', -26.15570831298828, 0.112127386033535, 6.809249401092529, 0, 0, 5)--2
TDS:Place('Scout', -29.321231842041016, 0.112127386033535, 0.6274676322937012, 0, 0, 4)--3
TDS:Place('Scout', -26.316696166992188, 0.112127386033535, 0.514862060546875, 1, 0, 3)--4
TDS:Place('Farm', -17.30438995361328, 0.112127386033535, -8.638969421386719, 2, 0, 3)--5 farm 1
TDS:Place('Scout', -23.085277557373047, 0.112127386033535, 6.665768623352051, 3, 0, 57)--6
TDS:Upgrade(5, 3, 0, 3)--farm 1 upgrade 1
TDS:Upgrade(5, 4, 0, 3)--farm 1 upgrade 2 Gurt#9903
TDS:Place('Farm', -17.32556915283203, 0.112127386033535, -11.735369682312012, 5, 1, 0)--7 farm 2
TDS:Place('Farm', -20.375041961669922, 0.112127386033535, -11.41246223449707, 5, 0, 3)--8 farm 3
TDS:Upgrade(7, 5, 0, 3)--farm 2 upgrade 1
TDS:Upgrade(7, 6, 0, 3)--farm 2 upgrade 2
TDS:Upgrade(8, 6, 0, 3)--farm 3 upgrade 1
TDS:Place('Scout', -23.24798583984375, 0.112127386033535, 0.481439471244812, 6, 0, 2)--9
TDS:Place('Scout', -20.194480895996094, 0.112127386033535, 0.57600998878479, 7, 1, 0)--10
TDS:Place('Scout', -19.93366241455078, 0.112127386033535, 6.670043468475342, 7, 1, 0)--11
TDS:Place('Scout', -19.924301147460938, 0.112127386033535, 9.738581657409668, 7, 0, 59)--12
TDS:Place('Scout', -22.974918365478516, 0.112127386033535, 9.76410961151123, 7, 0, 55)--13
TDS:Upgrade(8, 7, 0, 3)--farm 3 upgrade 2
TDS:Place('Farm', -20.667530059814453, 0.112127386033535, -8.353532791137695, 8, 0, 56)--14 farm 4
TDS:Upgrade(14, 8, 0, 55)--farm 4 upgrade 1
TDS:Upgrade(5, 8, 0, 3)--farm 1 upgrade 3
TDS:Upgrade(7, 9, 1, 0)--farm 2 upgrade 3
TDS:Upgrade(12, 9, 0, 3)--scout 9 upgrade 1
TDS:Upgrade(12, 9, 0, 3)--scout 9 upgrade 2
TDS:Upgrade(12, 10, 1, 0)--scout 9 upgrade 3
TDS:Upgrade(13, 10, 0, 59)--scout 10 upgrade 1
TDS:Upgrade(6, 10, 0, 58)--scout 5 upgrade 1
TDS:Upgrade(11, 10, 0, 52)--scout 8 upgrade 1
TDS:Upgrade(14, 10, 0, 3)--farm 4 upgrade 2
TDS:Place('Farm', -23.66617202758789, 0.112127386033535, -11.631689071655273, 10, 0, 3)--15 farm 5
TDS:Upgrade(8, 11, 1, 0)--farm 3 upgrade 3
TDS:Upgrade(14, 11, 0, 3)--farm 4 upgrade 3
TDS:Upgrade(15, 11, 0, 3)--farm 5 upgrade 1
TDS:Place('Farm', -23.924510955810547, 0.112127386033535, -8.208226203918457, 11, 0, 2)--16 farm 6
TDS:Upgrade(11, 12, 1, 0)--scout 8 upgrade 2
TDS:Upgrade(11, 12, 1, 0)--scout 8 upgrade 3
TDS:Upgrade(15, 12, 0, 3)--farm 5 upgrade 2
TDS:Upgrade(16, 12, 0, 3)--farm 6 upgrade 1
TDS:Place('Farm', -24.336727142333984, 0.21212738752365112, -14.664576530456543, 12, 0, 2)--17 farm 7
TDS:Upgrade(17, 12, 0, 2)--farm 7 upgrade 1
TDS:Upgrade(17, 12, 0, 2)--farm 7 upgrade 2
TDS:Upgrade(15, 13, 0, 58)--farm 5 upgrade 3
TDS:Upgrade(16, 13, 0, 57)--farm 6 upgrade 2 Gurt#9903
TDS:Upgrade(16, 13, 0, 56)--farm 6 upgrade 3
TDS:Upgrade(17, 13, 0, 3)--farm 7 upgrade 3
TDS:Place('Farm', -17.329864501953125, 0.112127386033535, -15.055961608886719, 13, 0, 3)--18 farm 8
TDS:Upgrade(13, 14, 1, 0)--scout 10 upgrade 2
TDS:Upgrade(13, 14, 1, 0)--scout 10 upgrade 3
TDS:Upgrade(6, 14, 0, 56)--scout 5 upgrade 2
TDS:Upgrade(18, 14, 0, 3)--farm 8 upgrade 1
TDS:Upgrade(18, 14, 0, 3)--farm 8 upgrade 2
TDS:Place('DJ Booth', -17.158260345458984, 0.112127386033535, 0.41845011711120605, 15, 1, 0)--19 DJ
TDS:Upgrade(19, 15, 0, 59)--DJ upgrade 1
TDS:Upgrade(19, 15, 0, 59)--DJ upgrade 2
TDS:Upgrade(19, 15, 0, 58)--DJ upgrade 3
TDS:Upgrade(18, 15, 0, 3)--farm 8 upgrade 4
TDS:Upgrade(11, 16, 1, 0)--scout 8 upgrade 4
TDS:Upgrade(12, 17, 1, 0)--scout 9 upgrade 4
TDS:Upgrade(5, 17, 0, 59)--farm 1 upgrade 4
TDS:Upgrade(13, 18, 0, 59)--scout 10 upgrade 4
TDS:Upgrade(14, 18, 0, 3)--farm 4 upgrade 4
TDS:Upgrade(5, 19, 1, 0)--farm 1 upgrade 5
TDS:Place('Commander', -14.084256172180176, 0.112127386033535, 0.45327329635620117, 19, 0, 57)--20 commander 1
TDS:Upgrade(20, 19, 0, 50)--commander 1 upgrade 1
TDS:Upgrade(20, 19, 0, 3)--commander 1 upgrade 2
TDS:Ability(20, "Call Of Arms", 19, 0, 1)
TDS:Upgrade(6, 20, 1, 0)--scout 5 upgrade 3
TDS:Upgrade(6, 20, 1, 0)--scout 5 upgrade 4
TDS:Place('Commander', -17.18905258178711, 0.112127386033535, -2.6245830059051514, 20, 0, 3)--21 commander 2
TDS:Upgrade(21, 21, 1, 0)--commander 2 upgrade 1
TDS:Upgrade(21, 21, 1, 0)--commander 2 upgrade 2 Gurt#9903
TDS:Ability(21, "Call Of Arms", 21, 0, 59)
TDS:Upgrade(14, 21, 0, 57)--farm 4 upgrade 5
TDS:Place('Commander', -13.682574272155762, 0.112127386033535, 3.5715818405151367, 21, 0, 53)--22 commander 3
TDS:Upgrade(22, 21, 0, 52)--commander 3 upgrade 1
TDS:Upgrade(22, 21, 0, 3)--commander 3 upgrade 2
TDS:AutoChain(20, 21, 22, 22, 0, 58)--AUTO CTA 1
TDS:Upgrade(10, 22, 0, 57)--scout 7 upgrade 1
TDS:Upgrade(10, 22, 0, 57)--scout 7 upgrade 2
TDS:Upgrade(10, 22, 0, 56)--scout 7 upgrade 3
TDS:Upgrade(10, 22, 0, 55)--scout 7 upgrade 4
TDS:Upgrade(16, 22, 0, 41)--farm 6 upgrade 4
TDS:Skip(22, 0, 40)
TDS:Upgrade(7, 22, 0, 1)--farm 2 upgrade 4
TDS:Upgrade(16, 23, 0, 59)--farm 6 upgrade 5
TDS:Upgrade(9, 23, 0, 58)--scout 6 upgrade 1
TDS:Upgrade(9, 23, 0, 57)--scout 6 upgrade 2
TDS:Upgrade(9, 23, 0, 57)--scout 6 upgrade 3
TDS:Skip(23, 0, 40)
TDS:Upgrade(7, 23, 0, 3)--farm 2 upgrade 5
TDS:Upgrade(8, 24, 0, 59)--farm 3 upgrade 4
TDS:Upgrade(8, 24, 0, 57)--farm 3 upgrade 5
TDS:Upgrade(15, 24, 0, 55)--farm 5 upgrade 4
TDS:Upgrade(17, 24, 0, 3)--farm 7 upgrade 4
TDS:Upgrade(15, 25, 1, 0)--farm 5 upgrade 5
TDS:Upgrade(17, 25, 0, 59)--farm 7 upgrade 5
TDS:Upgrade(4, 25, 0, 54)--scout 4 upgrade 1
TDS:Upgrade(4, 25, 0, 54)--scout 4 upgrade 2 Gurt#9903
TDS:Upgrade(3, 25, 0, 53)--scout 3 upgrade 1
TDS:Upgrade(3, 25, 0, 53)--scout 3 upgrade 2
TDS:Upgrade(1, 25, 0, 52)--scout 1 upgrade 1
TDS:Upgrade(1, 25, 0, 52)--scout 1 upgrade 2
TDS:Upgrade(2, 25, 0, 51)--scout 2 upgrade 1
TDS:Upgrade(2, 25, 0, 51)--scout 2 upgrade 2
TDS:Upgrade(18, 25, 0, 44)--farm 8 upgrade 4
TDS:Upgrade(9, 26, 1, 0)--scout 6 upgrade 4
TDS:Upgrade(19, 26, 0, 57)--DJ upgrade 4
TDS:Upgrade(18, 26, 0, 55)--farm 8 upgrade 5
TDS:Upgrade(19, 27, 1, 0)--DJ upgrade 5
TDS:Place('Accelerator', -11.01107120513916, 0.112127386033535, 0.49067163467407227, 27, 0, 55)--23 accel 1
TDS:Upgrade(23, 27, 0, 54)--accel 1 upgrade 1
TDS:Upgrade(23, 27, 0, 53)--accel 1 upgrade 2
TDS:Upgrade(23, 27, 0, 52)--accel 1 upgrade 3
TDS:Upgrade(23, 28, 1, 0)--accel 1 upgrade 4
TDS:Upgrade(4, 28, 0, 58)--scout 4 upgrade 3
TDS:Upgrade(3, 28, 0, 57)--scout 3 upgrade 3
TDS:Upgrade(1, 28, 0, 55)--scout 1 upgrade 3
TDS:Upgrade(2, 28, 0, 54)--scout 2 upgrade 3
TDS:Skip(28, 0, 40)
TDS:Upgrade(23, 29, 1, 0)--accel 1 upgrade 5
TDS:Upgrade(21, 29, 0, 56)--commander 2 upgrade 3
TDS:Upgrade(21, 29, 0, 46)--commander 2 upgrade 4
TDS:Skip(29, 0, 40)
TDS:Upgrade(2, 30, 1, 20)--scout 2 upgrade 4
TDS:Upgrade(1, 30, 1, 19)--scout 1 upgrade 4
TDS:Upgrade(4, 30, 1, 18)--scout 4 upgrade 4
TDS:Upgrade(3, 30, 1, 17)--scout 3 upgrade 4
TDS:Place('Accelerator', -14.143939971923828, 0.112127386033535, -2.6483895778656006, 30, 1, 7)--24 accel 2
TDS:Upgrade(24, 30, 1, 6)--accel 2 upgrade 1
TDS:Upgrade(24, 30, 1, 5)--accel 2 upgrade 2 Gurt#9903
TDS:Upgrade(24, 30, 1, 2)--accel 2 upgrade 3
TDS:Skip(30, 0, 54)
TDS:Upgrade(24, 30, 0, 3)--accel 2 upgrade 4
TDS:Upgrade(24, 31, 1, 9)--accel 2 upgrade 5
TDS:Place('Accelerator', -11.067309379577637, 0.112127386033535, -2.555945873260498, 31, 1, 5)--25 accel 3
TDS:Upgrade(25, 31, 1, 3)--accel 3 upgrade 1
TDS:Upgrade(25, 31, 0, 5)--accel 3 upgrade 2
TDS:Upgrade(25, 32, 1, 20)--accel 3 upgrade 3
TDS:Upgrade(25, 32, 1, 19)--accel 3 upgrade 4
TDS:Upgrade(25, 33, 1, 20)--accel 3 upgrade 5
TDS:Place('Accelerator', -8.00653076171875, 0.112127386033535, -2.544466018676758, 33, 1, 15)--26 accel 4
TDS:Upgrade(26, 33, 1, 14)--accel 4 upgrade 1
TDS:Upgrade(26, 33, 1, 13)--accel 4 upgrade 2
TDS:Upgrade(26, 33, 1, 13)--accel 4 upgrade 3
TDS:Upgrade(26, 33, 1, 13)--accel 4 upgrade 4
TDS:Skip(33, 0, 54)
TDS:Upgrade(26, 34, 1, 20)--accel 4 upgrade 5
TDS:Place('Accelerator', -7.991148948669434, 0.112127386033535, 0.4820065498352051, 34, 1, 17)--27 accel 5
TDS:Upgrade(27, 34, 1, 16)--accel 5 upgrade 1
TDS:Upgrade(27, 34, 1, 15)--accel 5 upgrade 2
TDS:Upgrade(27, 34, 1, 15)--accel 5 upgrade 3
TDS:Upgrade(27, 34, 1, 8)--accel 5 upgrade 4
TDS:Skip(34, 0, 54)
TDS:Upgrade(27, 34, 0, 3)--accel 5 upgrade 5
TDS:Place('Accelerator', -14.262953758239746, 0.112127386033535, -5.700279235839844, 35, 1, 17)--28 accel 6
TDS:Upgrade(28, 35, 1, 16)--accel 6 upgrade 1
TDS:Upgrade(28, 35, 1, 16)--accel 6 upgrade 2 Gurt#9903
TDS:Upgrade(28, 35, 1, 15)--accel 6 upgrade 3
TDS:Upgrade(28, 35, 1, 15)--accel 6 upgrade 4
TDS:Skip(35, 0, 54)
TDS:Upgrade(28, 36, 1, 20)--accel 6 upgrade 5
TDS:Place('Accelerator', -11.137608528137207, 0.112127386033535, -5.580723762512207, 36, 1, 8)--29 accel 7
TDS:Upgrade(29, 36, 1, 5)--accel 7 upgrade 1
TDS:Upgrade(29, 36, 1, 5)--accel 7 upgrade 2
TDS:Upgrade(29, 36, 1, 5)--accel 7 upgrade 3
TDS:Upgrade(29, 36, 1, 4)--accel 7 upgrade 4
TDS:Upgrade(29, 36, 1, 0)--accel 7 upgrade 5
TDS:Place('Accelerator', -8.086207389831543, 0.112127386033535, -5.624287128448486, 37, 1, 19)--30 accel 8
TDS:Upgrade(30, 37, 1, 18)--accel 8 upgrade 1
TDS:Upgrade(30, 37, 1, 18)--accel 8 upgrade 2
TDS:Upgrade(30, 37, 1, 17)--accel 8 upgrade 3
TDS:Upgrade(30, 37, 1, 17)--accel 8 upgrade 4
TDS:Upgrade(30, 37, 1, 5)--accel 8 upgrade 5
TDS:Place('Scout', -26.031536102294922, 0.112127386033535, 9.952803611755371, 37, 1, 0)--31
TDS:Upgrade(31, 37, 0, 59)--scout 11 upgrade 1
TDS:Upgrade(31, 37, 0, 59)--scout 11 upgrade 2
TDS:Upgrade(31, 37, 0, 58)--scout 11 upgrade 3
TDS:Upgrade(31, 37, 0, 58)--scout 11 upgrade 4
TDS:Skip(37, 0, 54)
TDS:Place('Scout', -13.667950630187988, 0.112127386033535, 6.623224258422852, 38, 1, 20)--32
TDS:Place('Scout', -13.666844367980957, 0.112127386033535, 9.665231704711914, 38, 1, 20)--33
TDS:Place('Scout', -13.62413501739502, 0.112127386033535, 12.688302040100098, 38, 1, 19)--34
TDS:Place('Scout', -13.675512313842773, 0.112127386033535, 15.724610328674316, 38, 1, 19)--35
TDS:Place('Scout', -10.629263877868652, 0.112127386033535, 15.692133903503418, 38, 1, 18)--36
TDS:Place('Scout', -10.545794486999512, 0.112127386033535, 12.6326265335083, 38, 1, 18)--37
TDS:Place('Scout', -10.664463996887207, 0.112127386033535, 9.554142951965332, 38, 1, 17)--38
TDS:Place('Scout', -10.588156700134277, 0.112127386033535, 6.488218307495117, 38, 1, 17)--39
TDS:Upgrade(39, 38, 1, 16)--scout 19 upgrade 1
TDS:Upgrade(39, 38, 1, 16)--scout 19 upgrade 2 Gurt#9903
TDS:Upgrade(39, 38, 1, 15)--scout 19 upgrade 3
TDS:Upgrade(39, 38, 1, 15)--scout 19 upgrade 4
TDS:Upgrade(32, 38, 1, 14)--scout 12 upgrade 1
TDS:Upgrade(32, 38, 1, 14)--scout 12 upgrade 2
TDS:Upgrade(32, 38, 1, 13)--scout 12 upgrade 3
TDS:Upgrade(32, 38, 1, 13)--scout 12 upgrade 4
TDS:Upgrade(38, 38, 1, 12)--scout 18 upgrade 1
TDS:Upgrade(38, 38, 1, 12)--scout 18 upgrade 2
TDS:Upgrade(38, 38, 1, 11)--scout 18 upgrade 3
TDS:Upgrade(38, 38, 1, 11)--scout 18 upgrade 4
TDS:Upgrade(33, 38, 1, 10)--scout 13 upgrade 1
TDS:Upgrade(33, 38, 1, 10)--scout 13 upgrade 2
TDS:Upgrade(33, 38, 1, 9)--scout 13 upgrade 3
TDS:Upgrade(33, 38, 1, 9)--scout 13 upgrade 4
TDS:Upgrade(37, 38, 1, 8)--scout 17 upgrade 1
TDS:Upgrade(37, 38, 1, 8)--scout 17 upgrade 2
TDS:Upgrade(37, 38, 1, 7)--scout 17 upgrade 3
TDS:Upgrade(37, 38, 1, 7)--scout 17 upgrade 4
TDS:Upgrade(34, 38, 1, 6)--scout 14 upgrade 1
TDS:Upgrade(34, 38, 1, 6)--scout 14 upgrade 2
TDS:Upgrade(34, 38, 1, 5)--scout 14 upgrade 3
TDS:Upgrade(34, 38, 1, 5)--scout 14 upgrade 4
TDS:Upgrade(35, 38, 1, 4)--scout 15 upgrade 1
TDS:Upgrade(35, 38, 1, 4)--scout 15 upgrade 2
TDS:Upgrade(35, 38, 1, 3)--scout 15 upgrade 3
TDS:Upgrade(35, 38, 1, 3)--scout 15 upgrade 4
TDS:Upgrade(36, 38, 1, 2)--scout 16 upgrade 1
TDS:Upgrade(36, 38, 1, 2)--scout 16 upgrade 2 Gurt#9903
TDS:Upgrade(36, 38, 1, 1)--scout 16 upgrade 3
TDS:Upgrade(36, 38, 1, 1)--scout 16 upgrade 4
TDS:Skip(38, 0, 54)
TDS:Sell(5, 39, 2, 0)--farm 1 sell
TDS:Sell(7, 39, 2, 0)--farm 2 sell
TDS:Sell(8, 39, 2, 0)--farm 3 sell
TDS:Sell(14, 39, 1, 59)--farm 4 sell
TDS:Sell(15, 39, 1, 59)--farm 5 sell
TDS:Sell(16, 39, 1, 59)--farm 6 sell
TDS:Sell(17, 39, 1, 58)--farm 7 sell
TDS:Sell(18, 39, 1, 58)--farm 8 sell
TDS:Place('Scout', -7.482595920562744, 0.112127386033535, 3.5039968490600586, 39, 1, 55)--40
TDS:Place('Scout', -7.495752811431885, 0.112127386033535, 6.517093181610107, 39, 1, 55)--41
TDS:Place('Scout', -7.535982608795166, 0.112127386033535, 9.559296607971191, 39, 1, 54)--42
TDS:Place('Scout', -7.49515438079834, 0.112127386033535, 12.589154243469238, 39, 1, 54)--43
TDS:Place('Scout', -7.580657005310059, 0.112127386033535, 15.74446964263916, 39, 1, 53)--44
TDS:Upgrade(40, 39, 1, 53)--scout 20 upgrade 1
TDS:Upgrade(40, 39, 1, 52)--scout 20 upgrade 2
TDS:Upgrade(40, 39, 1, 52)--scout 20 upgrade 3
TDS:Upgrade(40, 39, 1, 51)--scout 20 upgrade 4
TDS:Upgrade(41, 39, 1, 51)--scout 21 upgrade 1
TDS:Upgrade(41, 39, 1, 50)--scout 21 upgrade 2
TDS:Upgrade(41, 39, 1, 50)--scout 21 upgrade 3
TDS:Upgrade(41, 39, 1, 49)--scout 21 upgrade 4
TDS:Upgrade(42, 39, 1, 49)--scout 22 upgrade 1
TDS:Upgrade(42, 39, 1, 48)--scout 22 upgrade 2 Gurt#9903
TDS:Upgrade(42, 39, 1, 48)--scout 22 upgrade 3
TDS:Upgrade(42, 39, 1, 47)--scout 22 upgrade 4
TDS:Upgrade(43, 39, 1, 47)--scout 23 upgrade 1
TDS:Upgrade(43, 39, 1, 46)--scout 23 upgrade 2
TDS:Upgrade(43, 39, 1, 46)--scout 23 upgrade 3
TDS:Upgrade(43, 39, 1, 45)--scout 23 upgrade 4
TDS:Upgrade(44, 39, 1, 45)--scout 24 upgrade 1
TDS:Upgrade(44, 39, 1, 44)--scout 24 upgrade 2
TDS:Upgrade(44, 39, 1, 44)--scout 24 upgrade 3
TDS:Upgrade(44, 39, 1, 43)--scout 24 upgrade 4
TDS:Upgrade(20, 39, 1, 43)--commander 1 upgrade 3
TDS:Upgrade(20, 39, 1, 42)--commander 1 upgrade 4
TDS:Upgrade(22, 39, 1, 42)--commander 3 upgrade 3
TDS:Upgrade(22, 39, 1, 41)--commander 3 upgrade 4
TDS:Place('Scout', -20.27185821533203, 0.112127386033535, -2.68989896774292, 39, 1, 41)--45
TDS:Upgrade(45, 39, 1, 40)--scout 25 upgrade 1
TDS:Upgrade(45, 39, 1, 40)--scout 25 upgrade 2
TDS:Upgrade(45, 39, 1, 39)--scout 25 upgrade 3
TDS:Upgrade(45, 39, 1, 39)--scout 25 upgrade 4
TDS:Place('Scout', -17.319866180419922, 0.112127386033535, -5.802767276763916, 39, 1, 38)--46
TDS:Upgrade(46, 39, 1, 38)--scout 26 upgrade 1
TDS:Upgrade(46, 39, 1, 37)--scout 26 upgrade 2 Gurt#9903
TDS:Upgrade(46, 39, 1, 37)--scout 26 upgrade 3
TDS:Upgrade(46, 39, 1, 36)--scout 26 upgrade 4
TDS:Place('Scout', -20.441017150878906, 0.112127386033535, -5.755815505981445, 39, 1, 36)--47
TDS:Upgrade(47, 39, 1, 35)--scout 27 upgrade 1
TDS:Upgrade(47, 39, 1, 35)--scout 27 upgrade 2
TDS:Upgrade(47, 39, 1, 34)--scout 27 upgrade 3
TDS:Upgrade(47, 39, 1, 34)--scout 27 upgrade 4
TDS:Place('Scout', -20.107887268066406, 0.112127386033535, 12.822029113769531, 39, 1, 33)--48
TDS:Upgrade(48, 39, 1, 33)--scout 28 upgrade 1
TDS:Upgrade(48, 39, 1, 32)--scout 28 upgrade 2
TDS:Upgrade(48, 39, 1, 32)--scout 28 upgrade 3
TDS:Upgrade(48, 39, 1, 31)--scout 28 upgrade 4
TDS:Skip(39, 1, 20)
TDS:Sell(1, 40, 98, 54)--scout 1 sell
TDS:Sell(31, 40, 98, 54)--scout 11 sell
TDS:Sell(2, 40, 98, 52)--scout 2 sell
TDS:Sell(3, 40, 98, 52)--scout 3 sell
TDS:Place('Scout', -23.485034942626953, 0.112127386033535, -2.7553162574768066, 40, 98, 50)--49
TDS:Upgrade(49, 40, 98, 50)--scout 29 upgrade 1
TDS:Upgrade(49, 40, 98, 49)--scout 29 upgrade 2
TDS:Upgrade(49, 40, 98, 49)--scout 29 upgrade 3
TDS:Upgrade(49, 40, 98, 48)--scout 29 upgrade 4
TDS:Place('Scout', -23.61341094970703, 0.112127386033535, -5.869134902954102, 40, 98, 48)--50
TDS:Upgrade(50, 40, 98, 47)--scout 30 upgrade 1
TDS:Upgrade(50, 40, 98, 47)--scout 30 upgrade 2 Gurt#9903
TDS:Upgrade(50, 40, 98, 46)--scout 30 upgrade 3
TDS:Upgrade(50, 40, 98, 46)--scout 30 upgrade 4
TDS:Place('Scout', -17.329235076904297, 0.112127386033535, -8.920942306518555, 40, 98, 45)--51
TDS:Upgrade(51, 40, 98, 45)--scout 31 upgrade 1
TDS:Upgrade(51, 40, 98, 44)--scout 31 upgrade 2
TDS:Upgrade(51, 40, 98, 44)--scout 31 upgrade 3
TDS:Upgrade(51, 40, 98, 43)--scout 31 upgrade 4
TDS:Place('Scout', -20.37903594970703, 0.112127386033535, -8.92264461517334, 40, 98, 43)--52
TDS:Upgrade(52, 40, 98, 42)--scout 32 upgrade 1
TDS:Upgrade(52, 40, 98, 42)--scout 32 upgrade 2
TDS:Upgrade(52, 40, 98, 41)--scout 32 upgrade 3
TDS:Upgrade(52, 40, 98, 41)--scout 32 upgrade 4
TDS:Sell(13, 40, 98, 35)--scout 10 sell
TDS:Place('Scout', -23.46405029296875, 0.112127386033535, -8.91861629486084, 40, 98, 35)--53
TDS:Upgrade(53, 40, 98, 34)--scout 33 upgrade 1
TDS:Upgrade(53, 40, 98, 34)--scout 33 upgrade 2
TDS:Upgrade(53, 40, 98, 33)--scout 33 upgrade 3
TDS:Upgrade(53, 40, 98, 33)--scout 33 upgrade 4
TDS:Sell(48, 40, 98, 30)--scout 28 sell
TDS:Sell(12, 40, 98, 30)--scout 9 sell
TDS:Sell(11, 40, 98, 29)--scout 8 sell
TDS:Sell(6, 40, 98, 29)--scout 5 sell
TDS:Place('Scout', -11.037110328674316, 0.112127386033535, -14.308218955993652, 40, 98, 28)--54
TDS:Place('Scout', -7.795172214508057, 0.112127386033535, -14.384610176086426, 40, 98, 28)--55
TDS:Place('Scout', -4.569000244140625, 0.112127386033535, -14.345255851745605, 40, 98, 28)--56
TDS:Place('Scout', -11.033262252807617, 0.112127386033535, -17.406044006347656, 40, 98, 27)--57
TDS:Upgrade(54, 40, 98, 27)--scout 34 upgrade 1
TDS:Upgrade(54, 40, 98, 27)--scout 34 upgrade 2 Gurt#9903
TDS:Upgrade(54, 40, 98, 26)--scout 34 upgrade 3
TDS:Upgrade(54, 40, 98, 26)--scout 34 upgrade 4
TDS:Upgrade(55, 40, 98, 26)--scout 35 upgrade 1
TDS:Upgrade(55, 40, 98, 25)--scout 35 upgrade 2
TDS:Upgrade(55, 40, 98, 25)--scout 35 upgrade 3
TDS:Upgrade(55, 40, 98, 25)--scout 35 upgrade 4
TDS:Upgrade(56, 40, 98, 24)--scout 36 upgrade 1
TDS:Upgrade(56, 40, 98, 24)--scout 36 upgrade 2
TDS:Upgrade(56, 40, 98, 24)--scout 36 upgrade 3
TDS:Upgrade(56, 40, 98, 23)--scout 36 upgrade 4
TDS:Upgrade(57, 40, 98, 23)--scout 37 upgrade 1
TDS:Upgrade(57, 40, 98, 23)--scout 37 upgrade 2
TDS:Upgrade(57, 40, 98, 22)--scout 37 upgrade 3
TDS:Upgrade(57, 40, 98, 22)--scout 37 upgrade 4
TDS:Sell(19, 40, 98, 15)--DJ sell
TDS:Place('DJ Booth', -1.2708368301391602, 0.112127386033535, -1.4145374298095703, 40, 98, 15)--58 DJ Replaced
TDS:Upgrade(58, 40, 98, 15)--DJ Replaced upgrade 1
TDS:Upgrade(58, 40, 98, 14)--DJ Replaced upgrade 2
TDS:Upgrade(58, 40, 98, 14)--DJ Replaced upgrade 3
TDS:Upgrade(58, 40, 98, 14)--DJ Replaced upgrade 4
TDS:Upgrade(58, 40, 98, 14)--DJ Replaced upgrade 5
TDS:Sell(24, 40, 98, 13)--accel 2 sell
TDS:Place('Accelerator', -1.2248952388763428, 0.112127386033535, -4.598272323608398, 40, 98, 13)--59 accel 9
TDS:Upgrade(59, 40, 98, 12)--accel 9 upgrade 1
TDS:Upgrade(59, 40, 98, 12)--accel 9 upgrade 2 Gurt#9903
TDS:Upgrade(59, 40, 98, 12)--accel 9 upgrade 3
TDS:Upgrade(59, 40, 98, 11)--accel 9 upgrade 4
TDS:Upgrade(59, 40, 98, 11)--accel 9 upgrade 5
TDS:Sell(28, 40, 98, 11)--accel 6 sell
TDS:Place('Accelerator', 1.8217988014221191, 0.112127386033535, -4.27323055267334, 40, 98, 10)--60 accel 10
TDS:Upgrade(60, 40, 98, 10)--accel 10 upgrade 1
TDS:Upgrade(60, 40, 98, 10)--accel 10 upgrade 2
TDS:Upgrade(60, 40, 98, 9)--accel 10 upgrade 3
TDS:Upgrade(60, 40, 98, 9)--accel 10 upgrade 4
TDS:Upgrade(60, 40, 98, 9)--accel 10 upgrade 5
TDS:Sell(23, 40, 98, 8)--accel 1 sell
TDS:Place('Accelerator', 4.833676338195801, 0.112127386033535, -3.935666084289551, 40, 98, 8)--61 accel 11
TDS:Upgrade(61, 40, 98, 8)--accel 11 upgrade 1
TDS:Upgrade(61, 40, 98, 7)--accel 11 upgrade 2
TDS:Upgrade(61, 40, 98, 7)--accel 11 upgrade 3
TDS:Upgrade(61, 40, 98, 7)--accel 11 upgrade 4
TDS:Upgrade(61, 40, 98, 6)--accel 11 upgrade 5
TDS:Sell(25, 40, 98, 6)--accel 3 sell
TDS:Place('Accelerator', 7.871827125549316, 0.112127386033535, -3.8332905769348145, 40, 98, 6)--62 accel 12
TDS:Upgrade(62, 40, 98, 5)--accel 12 upgrade 1
TDS:Upgrade(62, 40, 98, 5)--accel 12 upgrade 2
TDS:Upgrade(62, 40, 98, 5)--accel 12 upgrade 3
TDS:Upgrade(62, 40, 98, 4)--accel 12 upgrade 4
TDS:Upgrade(62, 40, 98, 4)--accel 12 upgrade 5
TDS:Sell(29, 40, 98, 4)--accel 7 sell
TDS:Place('Accelerator', 10.87435531616211, 0.112127386033535, -4.037872314453125, 40, 98, 3)--63 accel 13
TDS:Upgrade(63, 40, 98, 3)--accel 13 upgrade 1
TDS:Upgrade(63, 40, 98, 3)--accel 13 upgrade 2
TDS:Upgrade(63, 40, 98, 2)--accel 13 upgrade 3
TDS:Upgrade(63, 40, 98, 2)--accel 13 upgrade 4
TDS:Upgrade(63, 40, 98, 2)--accel 13 upgrade 5
TDS:Sell(27, 40, 98, 1)--accel 5 sell
TDS:Place('Accelerator', 7.858397483825684, 0.112127386033535, -7.1831464767456055, 40, 98, 1)--64 accel 14
TDS:Upgrade(64, 40, 98, 1)--accel 14 upgrade 1
TDS:Upgrade(64, 40, 98, 0)--accel 14 upgrade 2 Gurt#9903
TDS:Upgrade(64, 40, 98, 0)--accel 14 upgrade 3
TDS:Upgrade(64, 40, 98, 0)--accel 14 upgrade 4
TDS:Upgrade(64, 40, 97, 59)--accel 14 upgrade 5
TDS:Sell(26, 40, 97, 59)--accel 4 sell
TDS:Place('Accelerator', 4.833776473999023, 0.112127386033535, -7.362361907958984, 40, 97, 59)--65 accel 15
TDS:Upgrade(65, 40, 97, 58)--accel 15 upgrade 1
TDS:Upgrade(65, 40, 97, 58)--accel 15 upgrade 2
TDS:Upgrade(65, 40, 97, 58)--accel 15 upgrade 3
TDS:Upgrade(65, 40, 97, 57)--accel 15 upgrade 4
TDS:Upgrade(65, 40, 97, 57)--accel 15 upgrade 5
TDS:Sell(30, 40, 97, 57)--accel 8 sell
TDS:Place('Accelerator', 1.7956347465515137, 0.112127386033535, -7.416245460510254, 40, 97, 56)--66 accel 16
TDS:Upgrade(66, 40, 97, 56)--accel 16 upgrade 1
TDS:Upgrade(66, 40, 97, 56)--accel 16 upgrade 2
TDS:Upgrade(66, 40, 97, 55)--accel 16 upgrade 3
TDS:Upgrade(66, 40, 97, 55)--accel 16 upgrade 4
TDS:Upgrade(66, 40, 97, 55)--accel 16 upgrade 5
TDS:Sell(20, 40, 97, 54)--commander 1 sell
TDS:Sell(21, 40, 97, 54)--commander 2 sell
TDS:Sell(22, 40, 97, 54)--commander 3 sell
TDS:Place('Commander', 10.908498764038086, 0.112127386033535, -7.094564437866211, 40, 97, 53)--67 commander 4
TDS:Upgrade(67, 40, 97, 53)--commander 4 upgrade 1
TDS:Upgrade(67, 40, 97, 53)--commander 4 upgrade 2
TDS:Upgrade(67, 40, 97, 52)--commander 4 upgrade 3
TDS:Upgrade(67, 40, 97, 52)--commander 4 upgrade 4
TDS:Place('Commander', 10.893294334411621, 0.112127386033535, -10.119662284851074, 40, 97, 52)--68 commander 5
TDS:Upgrade(68, 40, 97, 51)--commander 5 upgrade 1
TDS:Upgrade(68, 40, 97, 51)--commander 5 upgrade 2
TDS:Upgrade(68, 40, 97, 51)--commander 5 upgrade 3
TDS:Upgrade(68, 40, 97, 50)--commander 5 upgrade 4
TDS:Place('Commander', 7.852128982543945, 0.112127386033535, -10.329614639282227, 40, 97, 50)--69 commander 6
TDS:Upgrade(69, 40, 97, 50)--commander 6 upgrade 1
TDS:Upgrade(69, 40, 97, 49)--commander 6 upgrade 2
TDS:Upgrade(69, 40, 97, 49)--commander 6 upgrade 3
TDS:Upgrade(69, 40, 97, 49)--commander 6 upgrade 4
TDS:AutoChain(67, 68, 69, 40, 97, 48)--AUTO CTA 2 Gurt#9903
    end
    if map == maplist[2] then
local TDS = loadstring(game:HttpGet("https://raw.githubusercontent.com/banbuskox/dfhtyxvzexrxgfdzgzfdvfdz/main/ckmhjvskfkmsStratFun2", true))() 
TDS:Loadout("Farm", "Commander", "Accelerator", "Scout", "DJ Booth") 
TDS:Map("Toyboard", true, "Survival")
TDS:Mode('Insane')
task.spawn(function()
    wait(1)
    for i,v in pairs(game.CoreGui:GetDescendants()) do
        if v:IsA("TextLabel") and v.Name == "section_lbl" and v.Text == "" then
            v.Text = "Strat By: Gurt#9903"
        end
    end
end)
TDS:Place('Scout', 36.43179702758789, 0.0492095947265625, 0.4721055030822754, 0, 0, 5)--1
TDS:Place('Scout', 33.424034118652344, 0.0492095947265625, 0.4647202491760254, 0, 0, 5)--2
TDS:Place('Scout', 30.404083251953125, 0.0492095947265625, 0.4719226360321045, 0, 0, 4)--3
TDS:Place('Scout', 36.48541259765625, 0.0492095947265625, -2.627331256866455, 1, 0, 3)--4
TDS:Place('Farm', 21.188568115234375, 0.0492095947265625, -10.692459106445312, 2, 0, 3)--5 farm 1
TDS:Place('Scout', 33.45753479003906, 0.0492095947265625, -2.5685768127441406, 3, 0, 57)--6
TDS:Upgrade(5, 3, 0, 3)--farm 1 upgrade 1
TDS:Upgrade(5, 4, 0, 3)--farm 1 upgrade 2 Gurt#9903
TDS:Place('Farm', 18.005247116088867, 0.0492095947265625, -10.508173942565918, 5, 0, 59)--7 farm 2
TDS:Place('Farm', 14.815888404846191, 0.0492095947265625, -10.797279357910156, 5, 0, 3)--8 farm 3
TDS:Upgrade(7, 5, 0, 3)--farm 2 upgrade 1
TDS:Upgrade(7, 6, 0, 3)--farm 2 upgrade 2
TDS:Upgrade(8, 6, 0, 3)--farm 3 upgrade 1
TDS:Place('Scout', 30.422882080078125, 0.0492095947265625, -2.642636775970459, 6, 0, 2)--9
TDS:Place('Scout', 36.31648254394531, 0.0492095947265625, 6.650517463684082, 7, 1, 0)--10
TDS:Place('Scout', 33.206504821777344, 0.0492095947265625, 6.68778133392334, 7, 1, 0)--11
TDS:Place('Scout', 27.293264389038086, 0.0492095947265625, 0.3974491357803345, 7, 0, 59)--12
TDS:Place('Scout', 27.39914321899414, 0.0492095947265625, -2.8639845848083496, 7, 0, 55)--13
TDS:Upgrade(8, 7, 0, 3)--farm 3 upgrade 2
TDS:Place('Farm', 24.659086227416992, 0.0492095947265625, -10.814179420471191, 8, 0, 55)--14 farm 4
TDS:Upgrade(14, 8, 0, 54)--farm 4 upgrade 1
TDS:Upgrade(5, 8, 0, 3)--farm 1 upgrade 3
TDS:Upgrade(7, 9, 1, 0)--farm 2 upgrade 3
TDS:Upgrade(13, 9, 1, 0)--scout 10 upgrade 1
TDS:Upgrade(12, 9, 0, 3)--scout 9 upgrade 1
TDS:Upgrade(12, 9, 0, 3)--scout 9 upgrade 2
TDS:Upgrade(12, 10, 1, 0)--scout 9 upgrade 3
TDS:Upgrade(9, 10, 0, 58)--scout 6 upgrade 1
TDS:Upgrade(3, 10, 0, 51)--scout 3 upgrade 1
TDS:Upgrade(14, 10, 0, 3)--farm 4 upgrade 2
TDS:Place('Farm', 24.546493530273438, 0.0492095947265625, -13.962356567382812, 10, 0, 3)--15 farm 5
TDS:Upgrade(8, 11, 1, 0)--farm 3 upgrade 2
TDS:Upgrade(15, 11, 0, 57)--farm 5 upgrade 1
TDS:Upgrade(14, 11, 0, 3)--farm 4 upgrade 3
TDS:Place('Farm', 21.427387237548828, 0.0492095947265625, -14.027795791625977, 11, 0, 3)--16 farm 6
TDS:Upgrade(13, 12, 1, 0)--scout 10 upgrade 2
TDS:Upgrade(13, 12, 0, 59)--scout 10 upgrade 3
TDS:Upgrade(15, 12, 0, 3)--farm 5 upgrade 2
TDS:Upgrade(16, 12, 0, 3)--farm 6 upgrade 1
TDS:Place('Farm', 18.259004592895508, 0.0492095947265625, -14.238418579101562, 12, 0, 2)--17 farm 7
TDS:Upgrade(17, 12, 0, 2)--farm 7 upgrade 1
TDS:Upgrade(15, 13, 1, 0)--farm 5 upgrade 3
TDS:Upgrade(16, 13, 0, 58)--farm 6 upgrade 2 Gurt#9903
TDS:Upgrade(16, 13, 0, 58)--farm 6 upgrade 3
TDS:Upgrade(17, 13, 0, 3)--farm 7 upgrade 2
TDS:Place('Farm', 14.77685546875, 0.0492095947265625, -14.28951644897461, 13, 0, 3)--18 farm 8
TDS:Upgrade(9, 14, 1, 0)--scout 6 upgrade 2
TDS:Upgrade(9, 14, 0, 59)--scout 6 upgrade 2
TDS:Upgrade(17, 14, 0, 56)--farm 7 upgrade 3
TDS:Upgrade(18, 14, 0, 55)--farm 8 upgrade 1
TDS:Upgrade(18, 14, 0, 3)--farm 8 upgrade 2
TDS:Upgrade(18, 14, 0, 3)--farm 8 upgrade 3
TDS:Place('DJ Booth', 21.132522583007812, 0.0492095947265625, 0.7563388347625732, 15, 1, 0)--19 DJ
TDS:Upgrade(19, 15, 1, 0)--DJ upgrade 1
TDS:Upgrade(19, 15, 0, 59)--DJ upgrade 2
TDS:Upgrade(19, 15, 0, 58)--DJ upgrade 3
TDS:Upgrade(12, 16, 1, 0)--scout 9 upgrade 4
TDS:Upgrade(3, 16, 0, 59)--scout 3 upgrade 2
TDS:Upgrade(14, 17, 1, 0)--farm 4 upgrade 4
TDS:Upgrade(13, 17, 0, 58)--scout 10 upgrade 4
TDS:Upgrade(3, 18, 1, 0)--scout 3 upgrade 3
TDS:Upgrade(9, 18, 0, 59)--scout 6 upgrade 3
TDS:Upgrade(14, 19, 1, 0)--farm 4 upgrade 5
TDS:Place('Commander', 21.14395523071289, 0.0492095947265625, 3.813899517059326, 19, 0, 3)--20 commander 1
TDS:Upgrade(20, 19, 0, 3)--commander 1 upgrade 1
TDS:Upgrade(20, 19, 0, 2)--commander 1 upgrade 2 Gurt#9903
TDS:Ability(20, "Call Of Arms", 20, 1, 0)
TDS:Upgrade(3, 20, 0, 59)--scout 3 upgrade 4
TDS:Upgrade(5, 20, 0, 3)--farm 1 upgrade 4
TDS:Place('Commander', 21.170141220092773, 0.0492095947265625, -2.266202449798584, 20, 0, 3)--21 commander 2
TDS:Upgrade(21, 20, 0, 2)--commander 2 upgrade 1
TDS:Upgrade(21, 21, 1, 0)--commander 2 upgrade 2
TDS:Ability(21, "Call Of Arms", 21, 1, 0)
TDS:Upgrade(5, 21, 0, 55)--farm 1 upgrade 5
TDS:Place('Commander', 21.03677749633789, 0.0492095947265625, 6.944663047790527, 21, 0, 49)--22 commander 3
TDS:Upgrade(22, 21, 0, 48)--commander 3 upgrade 1
TDS:Upgrade(22, 22, 1, 0)--commander 3 upgrade 2
TDS:AutoChain(20, 21, 22, 22, 1, 0)--AUTO CTA 1
TDS:Place('Scout', 30.172515869140625, 0.0492095947265625, 6.607441425323486, 22, 0, 55)--23
TDS:Upgrade(23, 22, 0, 54)--scout 11 upgrade 1
TDS:Upgrade(23, 22, 0, 54)--scout 11 upgrade 2
TDS:Upgrade(23, 22, 0, 54)--scout 11 upgrade 3
TDS:Upgrade(23, 22, 0, 54)--scout 11 upgrade 4
TDS:Skip(22, 0, 40)
TDS:Upgrade(7, 22, 0, 3)--farm 2 upgrade 4
TDS:Upgrade(7, 23, 0, 59)--farm 2 upgrade 5
TDS:Place('Scout', 27.13835906982422, 0.0492095947265625, 6.557769298553467, 23, 0, 55)--24
TDS:Upgrade(24, 23, 0, 54)--scout 12 upgrade 1
TDS:Upgrade(24, 23, 0, 54)--scout 12 upgrade 2 Gurt#9903
TDS:Upgrade(24, 23, 0, 53)--scout 12 upgrade 3
TDS:Upgrade(24, 23, 0, 46)--scout 12 upgrade 4
TDS:Skip(23, 0, 40)
TDS:Upgrade(8, 23, 0, 3)--farm 3 upgrade 4
TDS:Upgrade(8, 24, 1, 0)--farm 3 upgrade 5
TDS:Upgrade(15, 24, 0, 59)--farm 5 upgrade 4
TDS:Upgrade(16, 24, 0, 3)--farm 6 upgrade 4
TDS:Upgrade(15, 25, 1, 0)--farm 5 upgrade 5
TDS:Upgrade(16, 25, 0, 56)--farm 6 upgrade 5
TDS:Upgrade(17, 25, 0, 53)--farm 7 upgrade 4
TDS:Upgrade(17, 25, 0, 3)--farm 7 upgrade 5
TDS:Upgrade(6, 26, 1, 0)--scout 5 upgrade 1
TDS:Upgrade(6, 26, 1, 0)--scout 5 upgrade 2
TDS:Upgrade(2, 26, 0, 59)--scout 2 upgrade 1
TDS:Upgrade(2, 26, 0, 58)--scout 2 upgrade 2
TDS:Upgrade(2, 26, 0, 56)--scout 2 upgrade 3
TDS:Upgrade(11, 26, 0, 55)--scout 8 upgrade 1
TDS:Upgrade(11, 26, 0, 55)--scout 8 upgrade 2
TDS:Upgrade(11, 26, 0, 54)--scout 8 upgrade 3
TDS:Upgrade(18, 26, 0, 3)--farm 8 upgrade 4
TDS:Upgrade(18, 26, 0, 3)--farm 8 upgrade 5
TDS:Upgrade(6, 26, 0, 2)--scout 5 upgrade 3
TDS:Upgrade(19, 27, 0, 58)--DJ upgrade 4
TDS:Upgrade(19, 27, 0, 58)--DJ upgrade 5
TDS:Upgrade(10, 27, 0, 53)--scout 7 upgrade 1
TDS:Upgrade(10, 27, 0, 53)--scout 7 upgrade 2 Gurt#9903
TDS:Upgrade(1, 27, 0, 51)--scout 1 upgrade 1
TDS:Upgrade(1, 27, 0, 51)--scout 1 upgrade 2
TDS:Upgrade(4, 27, 0, 50)--scout 4 upgrade 1
TDS:Upgrade(4, 27, 0, 49)--scout 4 upgrade 2
TDS:Upgrade(4, 27, 0, 49)--scout 4 upgrade 3
TDS:Upgrade(1, 27, 0, 47)--scout 1 upgrade 3
TDS:Upgrade(10, 27, 0, 46)--scout 7 upgrade 3
TDS:Place('Accelerator', 10.16781997680664, 0.0492095947265625, 8.468976020812988, 28, 0, 57)--25 accel 1
TDS:Upgrade(25, 28, 0, 57)--accel 1 upgrade 1
TDS:Upgrade(25, 28, 0, 56)--accel 1 upgrade 2
TDS:Upgrade(25, 28, 0, 56)--accel 1 upgrade 3
TDS:Upgrade(25, 28, 0, 53)--accel 1 upgrade 4
TDS:Skip(28, 0, 40)
TDS:Upgrade(25, 29, 0, 59)--accel 1 upgrade 5
TDS:Upgrade(22, 29, 0, 41)--commander 3 upgrade 3
TDS:Skip(29, 0, 40)
TDS:Upgrade(22, 30, 1, 20)--commander 3 upgrade 4
TDS:Upgrade(11, 30, 1, 19)--scout 8 upgrade 4
TDS:Upgrade(6, 30, 1, 17)--scout 5 upgrade 4
TDS:Upgrade(2, 30, 1, 17)--scout 2 upgrade 4
TDS:Upgrade(10, 30, 1, 4)--scout 7 upgrade 4
TDS:Upgrade(4, 30, 0, 57)--scout 4 upgrade 4
TDS:Upgrade(1, 30, 0, 54)--scout 1 upgrade 4
TDS:Skip(30, 0, 54)
TDS:Place('Accelerator', 10.111770629882812, 0.0492095947265625, 5.433967590332031, 31, 1, 20)--26 accel 2
TDS:Upgrade(26, 31, 1, 19)--accel 2 upgrade 1
TDS:Upgrade(26, 31, 1, 19)--accel 2 upgrade 2 Gurt#9903
TDS:Upgrade(26, 31, 1, 18)--accel 2 upgrade 3
TDS:Upgrade(26, 31, 1, 18)--accel 2 upgrade 4
TDS:Upgrade(26, 32, 1, 20)--accel 2 upgrade 5
TDS:Place('Accelerator', 10.17647647857666, 0.0492095947265625, 2.4095757007598877, 32, 1, 17)--27 accel 3
TDS:Upgrade(27, 32, 1, 17)--accel 3 upgrade 1
TDS:Upgrade(27, 32, 1, 16)--accel 3 upgrade 2
TDS:Upgrade(27, 32, 1, 16)--accel 3 upgrade 3
TDS:Upgrade(27, 32, 1, 11)--accel 3 upgrade 4
TDS:Upgrade(27, 33, 1, 14)--accel 3 upgrade 5
TDS:Place('Accelerator', 10.176214218139648, 0.0492095947265625, -0.757958173751831, 33, 1, 7)--28 accel 4
TDS:Upgrade(28, 33, 1, 7)--accel 4 upgrade 1
TDS:Upgrade(28, 33, 1, 6)--accel 4 upgrade 2
TDS:Upgrade(28, 33, 1, 6)--accel 4 upgrade 3
TDS:Upgrade(28, 33, 0, 59)--accel 4 upgrade 4
TDS:Skip(33, 0, 54)
TDS:Upgrade(28, 34, 1, 13)--accel 4 upgrade 5
TDS:Place('Accelerator', 7.129390716552734, 0.0492095947265625, 8.471026420593262, 34, 1, 5)--29 accel 5
TDS:Upgrade(29, 34, 1, 4)--accel 5 upgrade 1
TDS:Upgrade(29, 34, 1, 4)--accel 5 upgrade 2
TDS:Upgrade(29, 34, 1, 3)--accel 5 upgrade 3
TDS:Upgrade(29, 34, 1, 3)--accel 5 upgrade 4
TDS:Skip(34, 0, 54)
TDS:Upgrade(29, 35, 1, 20)--accel 5 upgrade 5
TDS:Place('Accelerator', 7.082403182983398, 0.0492095947265625, 5.4486918449401855, 35, 1, 0)--30 accel 6
TDS:Upgrade(30, 35, 0, 59)--accel 6 upgrade 1
TDS:Upgrade(30, 35, 0, 59)--accel 6 upgrade 2 Gurt#9903
TDS:Upgrade(30, 35, 0, 58)--accel 6 upgrade 3
TDS:Skip(35, 0, 54)
TDS:Upgrade(30, 36, 1, 20)--accel 6 upgrade 4
TDS:Upgrade(30, 36, 1, 10)--accel 6 upgrade 5
TDS:Place('Accelerator', 7.149409294128418, 0.0492095947265625, 2.4246468544006348, 36, 0, 3)--31 accel 7
TDS:Upgrade(31, 36, 0, 3)--accel 7 upgrade 1
TDS:Upgrade(31, 36, 0, 2)--accel 7 upgrade 2
TDS:Upgrade(31, 36, 0, 2)--accel 7 upgrade 3
TDS:Upgrade(31, 37, 1, 20)--accel 7 upgrade 4
TDS:Upgrade(31, 37, 1, 20)--accel 7 upgrade 5
TDS:Place('Accelerator', 7.162595272064209, 0.0492095947265625, -0.7587049007415771, 37, 1, 17)--32 accel 8
TDS:Upgrade(32, 37, 1, 17)--accel 8 upgrade 1
TDS:Upgrade(32, 37, 1, 16)--accel 8 upgrade 2
TDS:Upgrade(32, 37, 1, 16)--accel 8 upgrade 3
TDS:Upgrade(32, 37, 1, 9)--accel 8 upgrade 4
TDS:Skip(37, 0, 54)
TDS:Upgrade(32, 37, 0, 3)--accel 8 upgrade 5
TDS:Place('Scout', 27.37271499633789, 0.0492095947265625, -5.9994635581970215, 38, 1, 18)--33
TDS:Place('Scout', 16.38585662841797, 0.0492095947265625, -4.374680519104004, 38, 1, 18)--34
TDS:Place('Scout', 16.31001091003418, 0.0492095947265625, -1.3168895244598389, 38, 1, 18)--35
TDS:Place('Scout', 16.42064666748047, 0.0492095947265625, 1.770423412322998, 38, 1, 17)--36
TDS:Place('Scout', 16.35547637939453, 0.0492095947265625, 4.863699913024902, 38, 1, 17)--37
TDS:Place('Scout', 16.241798400878906, 0.0492095947265625, 7.908880233764648, 38, 1, 17)--38
TDS:Place('Scout', 16.303722381591797, 0.0492095947265625, 11.024847030639648, 38, 1, 16)--39
TDS:Place('Scout', 30.48232650756836, 0.0492095947265625, -5.919834136962891, 38, 1, 16)--40
TDS:Upgrade(33, 38, 1, 16)--scout 13 upgrade 1
TDS:Upgrade(33, 38, 1, 15)--scout 13 upgrade 2
TDS:Upgrade(33, 38, 1, 15)--scout 13 upgrade 3 Gurt#9903
TDS:Upgrade(33, 38, 1, 15)--scout 13 upgrade 4
TDS:Upgrade(34, 38, 1, 14)--scout 14 upgrade 1
TDS:Upgrade(34, 38, 1, 14)--scout 14 upgrade 2
TDS:Upgrade(34, 38, 1, 14)--scout 14 upgrade 3
TDS:Upgrade(34, 38, 1, 13)--scout 14 upgrade 4
TDS:Upgrade(35, 38, 1, 13)--scout 15 upgrade 1
TDS:Upgrade(35, 38, 1, 13)--scout 15 upgrade 2
TDS:Upgrade(35, 38, 1, 12)--scout 15 upgrade 3
TDS:Upgrade(35, 38, 1, 12)--scout 15 upgrade 4
TDS:Upgrade(36, 38, 1, 12)--scout 16 upgrade 1
TDS:Upgrade(36, 38, 1, 11)--scout 16 upgrade 2
TDS:Upgrade(36, 38, 1, 11)--scout 16 upgrade 3
TDS:Upgrade(36, 38, 1, 11)--scout 16 upgrade 4
TDS:Upgrade(37, 38, 1, 10)--scout 17 upgrade 1
TDS:Upgrade(37, 38, 1, 10)--scout 17 upgrade 2
TDS:Upgrade(37, 38, 1, 10)--scout 17 upgrade 3
TDS:Upgrade(37, 38, 1, 9)--scout 17 upgrade 4
TDS:Upgrade(38, 38, 1, 9)--scout 18 upgrade 1
TDS:Upgrade(38, 38, 1, 9)--scout 18 upgrade 2
TDS:Upgrade(38, 38, 1, 8)--scout 18 upgrade 3
TDS:Upgrade(38, 38, 1, 8)--scout 18 upgrade 4 Gurt#9903
TDS:Upgrade(39, 38, 1, 8)--scout 19 upgrade 1
TDS:Upgrade(39, 38, 1, 7)--scout 19 upgrade 2
TDS:Upgrade(39, 38, 1, 7)--scout 19 upgrade 3
TDS:Upgrade(39, 38, 1, 7)--scout 19 upgrade 4
TDS:Upgrade(40, 38, 1, 6)--scout 20 upgrade 1
TDS:Upgrade(40, 38, 1, 6)--scout 20 upgrade 2
TDS:Upgrade(40, 38, 1, 6)--scout 20 upgrade 3
TDS:Upgrade(40, 38, 1, 5)--scout 20 upgrade 4
TDS:Skip(38, 0, 54)
TDS:Sell(5, 39, 2, 0)--farm 1 sell
TDS:Sell(7, 39, 2, 0)--farm 2 sell
TDS:Sell(8, 39, 2, 0)--farm 3 sell
TDS:Sell(14, 39, 1, 59)--farm 4 sell
TDS:Sell(15, 39, 1, 59)--farm 5 sell
TDS:Sell(16, 39, 1, 59)--farm 6 sell
TDS:Sell(17, 39, 1, 58)--farm 7 sell
TDS:Sell(18, 39, 1, 58)--farm 8 sell Gurt#9903
TDS:Place('Scout', 27.3304443359375, 0.0492095947265625, -9.076135635375977, 39, 1, 58)--41
TDS:Place('Scout', 24.162511825561523, 0.0492095947265625, -10.579460144042969, 39, 1, 57)--42
TDS:Place('Scout', 21.14040756225586, 0.0492095947265625, -10.62503719329834, 39, 1, 57)--43
TDS:Place('Scout', 18.038970947265625, 0.0492095947265625, -10.625178337097168, 39, 1, 57)--44
TDS:Place('Scout', 14.946166038513184, 0.0492095947265625, -10.615018844604492, 39, 1, 56)--45
TDS:Place('Scout', 11.781850814819336, 0.0492095947265625, -10.581521987915039, 39, 1, 56)--46
TDS:Place('Scout', 10.146815299987793, 0.0492095947265625, -4.030245304107666, 39, 1, 56)--47
TDS:Place('Scout', 10.175230026245117, 0.0492095947265625, -7.383111953735352, 39, 1, 55)--48
TDS:Place('Scout', 24.13037872314453, 0.0492095947265625, 7.052547454833984, 39, 1, 55)--49
TDS:Upgrade(41, 39, 1, 55)--scout 21 upgrade 1
TDS:Upgrade(41, 39, 1, 54)--scout 21 upgrade 2
TDS:Upgrade(41, 39, 1, 54)--scout 21 upgrade 3
TDS:Upgrade(41, 39, 1, 54)--scout 21 upgrade 4
TDS:Upgrade(42, 39, 1, 53)--scout 22 upgrade 1
TDS:Upgrade(42, 39, 1, 53)--scout 22 upgrade 2
TDS:Upgrade(42, 39, 1, 53)--scout 22 upgrade 3
TDS:Upgrade(42, 39, 1, 52)--scout 22 upgrade 4
TDS:Upgrade(43, 39, 1, 52)--scout 23 upgrade 1
TDS:Upgrade(43, 39, 1, 52)--scout 23 upgrade 2
TDS:Upgrade(43, 39, 1, 51)--scout 23 upgrade 3
TDS:Upgrade(43, 39, 1, 51)--scout 23 upgrade 4
TDS:Upgrade(44, 39, 1, 51)--scout 24 upgrade 1
TDS:Upgrade(44, 39, 1, 50)--scout 24 upgrade 2
TDS:Upgrade(44, 39, 1, 50)--scout 24 upgrade 3
TDS:Upgrade(44, 39, 1, 50)--scout 24 upgrade 4
TDS:Upgrade(45, 39, 1, 49)--scout 25 upgrade 1
TDS:Upgrade(45, 39, 1, 49)--scout 25 upgrade 2
TDS:Upgrade(45, 39, 1, 49)--scout 25 upgrade 3
TDS:Upgrade(45, 39, 1, 48)--scout 25 upgrade 4
TDS:Upgrade(46, 39, 1, 48)--scout 26 upgrade 1
TDS:Upgrade(46, 39, 1, 48)--scout 26 upgrade 2
TDS:Upgrade(46, 39, 1, 47)--scout 26 upgrade 3
TDS:Upgrade(46, 39, 1, 47)--scout 26 upgrade 4 Gurt#9903
TDS:Upgrade(47, 39, 1, 47)--scout 27 upgrade 1
TDS:Upgrade(47, 39, 1, 46)--scout 27 upgrade 2
TDS:Upgrade(47, 39, 1, 46)--scout 27 upgrade 3
TDS:Upgrade(47, 39, 1, 46)--scout 27 upgrade 4
TDS:Upgrade(48, 39, 1, 45)--scout 28 upgrade 1
TDS:Upgrade(48, 39, 1, 45)--scout 28 upgrade 2
TDS:Upgrade(48, 39, 1, 45)--scout 28 upgrade 3
TDS:Upgrade(48, 39, 1, 44)--scout 28 upgrade 4
TDS:Upgrade(20, 39, 1, 44)--commander 1 upgrade 3
TDS:Upgrade(20, 39, 1, 44)--commander 1 upgrade 4
TDS:Upgrade(21, 39, 1, 43)--commander 2 upgrade 3
TDS:Upgrade(21, 39, 1, 43)--commander 2 upgrade 4
TDS:Skip(39, 1, 20)
TDS:Sell(4, 40, 99, 7)--scout 4 sell
TDS:Sell(6, 40, 99, 6)--scout 5 sell
TDS:Place('Scout', 6.981669902801514, 0.0492095947265625, -4.036678791046143, 40, 99, 6)--49
TDS:Upgrade(49, 40, 99, 6)--scout 29 upgrade 1
TDS:Upgrade(49, 40, 99, 5)--scout 29 upgrade 2
TDS:Upgrade(49, 40, 99, 5)--scout 29 upgrade 3
TDS:Upgrade(49, 40, 99, 5)--scout 29 upgrade 4
TDS:Place('Scout', 7.069154739379883, 0.0492095947265625, -7.107075214385986, 40, 99, 4)--50
TDS:Upgrade(50, 40, 99, 4)--scout 30 upgrade 1
TDS:Upgrade(50, 40, 99, 4)--scout 30 upgrade 2
TDS:Upgrade(50, 40, 99, 3)--scout 30 upgrade 3
TDS:Upgrade(50, 40, 99, 3)--scout 30 upgrade 4
TDS:Sell(1, 40, 98, 50)--scout 1 sell
TDS:Sell(10, 40, 98, 49)--scout 7 sell
TDS:Place('Scout', 24.111169815063477, 0.0492095947265625, 6.849252700805664, 40, 98, 48)--51
TDS:Upgrade(51, 40, 98, 48)--scout 31 upgrade 1
TDS:Upgrade(51, 40, 98, 48)--scout 31 upgrade 2
TDS:Upgrade(51, 40, 98, 48)--scout 31 upgrade 3
TDS:Upgrade(51, 40, 98, 47)--scout 31 upgrade 4
TDS:Place('Scout', 3.950850009918213, 0.0492095947265625, 2.7013511657714844, 40, 98, 47)--52
TDS:Upgrade(52, 40, 98, 46)--scout 32 upgrade 1
TDS:Upgrade(52, 40, 98, 46)--scout 32 upgrade 2
TDS:Upgrade(52, 40, 98, 46)--scout 32 upgrade 3
TDS:Upgrade(52, 40, 98, 45)--scout 32 upgrade 4 Gurt#9903
TDS:Sell(2, 40, 98, 40)--scout 2 sell
TDS:Sell(3, 40, 98, 39)--scout 3 sell
TDS:Sell(9, 40, 98, 38)--scout 6 sell
TDS:Sell(40, 40, 98, 37)--scout 20 sell
TDS:Place('Scout', 3.9932470321655273, 0.0492095947265625, 5.795187950134277, 40, 98, 37)--53
TDS:Upgrade(53, 40, 98, 37)--scout 33 upgrade 1
TDS:Upgrade(53, 40, 98, 36)--scout 33 upgrade 2
TDS:Upgrade(53, 40, 98, 36)--scout 33 upgrade 3
TDS:Upgrade(53, 40, 98, 36)--scout 33 upgrade 4
TDS:Place('Scout', 0.8921546936035156, 0.0492095947265625, 2.5502982139587402, 40, 98, 35)--54
TDS:Upgrade(54, 40, 98, 35)--scout 34 upgrade 1
TDS:Upgrade(54, 40, 98, 35)--scout 34 upgrade 2
TDS:Upgrade(54, 40, 98, 34)--scout 34 upgrade 3
TDS:Upgrade(54, 40, 98, 34)--scout 34 upgrade 4
TDS:Place('Scout', 0.8654537200927734, 0.0492095947265625, 5.6512451171875, 40, 98, 34)--55
TDS:Upgrade(55, 40, 98, 33)--scout 35 upgrade 1
TDS:Upgrade(55, 40, 98, 33)--scout 35 upgrade 2
TDS:Upgrade(55, 40, 98, 33)--scout 35 upgrade 3
TDS:Upgrade(55, 40, 98, 32)--scout 35 upgrade 4
TDS:Sell(11, 40, 98, 30)--scout 8 sell
TDS:Sell(23, 40, 98, 29)--scout 11 sell
TDS:Place('Scout', -1.0179662704467773, 0.0492095947265625, -3.6405391693115234, 40, 98, 29)--56
TDS:Upgrade(56, 40, 98, 29)--scout 36 upgrade 1
TDS:Upgrade(56, 40, 98, 28)--scout 36 upgrade 2
TDS:Upgrade(56, 40, 98, 28)--scout 36 upgrade 3
TDS:Upgrade(56, 40, 98, 28)--scout 36 upgrade 4
TDS:Place('Scout', -1.047872543334961, 0.0492095947265625, -6.876655101776123, 40, 98, 27)--57
TDS:Upgrade(57, 40, 98, 27)--scout 37 upgrade 1
TDS:Upgrade(57, 40, 98, 27)--scout 37 upgrade 2
TDS:Upgrade(57, 40, 98, 26)--scout 37 upgrade 3
TDS:Upgrade(57, 40, 98, 26)--scout 37 upgrade 4
TDS:Sell(24, 40, 98, 26)--scout 12 sell
TDS:Place('Scout', -4.050123691558838, 0.0492095947265625, -3.5343728065490723, 40, 98, 25)--58
TDS:Upgrade(58, 40, 98, 25)--scout 38 upgrade 1
TDS:Upgrade(58, 40, 98, 25)--scout 38 upgrade 2
TDS:Upgrade(58, 40, 98, 24)--scout 38 upgrade 3
TDS:Upgrade(58, 40, 98, 24)--scout 38 upgrade 4 Gurt#9903
TDS:Sell(12, 40, 98, 24)--scout 9 sell
TDS:Place('Scout', -4.0748677253723145, 0.0492095947265625, -6.543254375457764, 40, 98, 23)--59
TDS:Upgrade(59, 40, 98, 23)--scout 39 upgrade 1
TDS:Upgrade(59, 40, 98, 23)--scout 39 upgrade 2
TDS:Upgrade(59, 40, 98, 22)--scout 39 upgrade 3
TDS:Upgrade(59, 40, 98, 22)--scout 39 upgrade 4
TDS:Sell(13, 40, 98, 22)--scout 10 sell
TDS:Place('Scout', -7.088996887207031, 0.0492095947265625, -3.5042262077331543, 40, 98, 21)--60
TDS:Upgrade(60, 40, 98, 21)--scout 40 upgrade 1
TDS:Upgrade(60, 40, 98, 21)--scout 40 upgrade 2
TDS:Upgrade(60, 40, 98, 20)--scout 40 upgrade 3
TDS:Upgrade(60, 40, 98, 20)--scout 40 upgrade 4
TDS:Sell(33, 40, 98, 20)--scout 13 sell
TDS:Place('Scout', -7.119686126708984, 0.0492095947265625, -6.547432899475098, 40, 98, 19)--61
TDS:Upgrade(61, 40, 98, 19)--scout 40 upgrade 1
TDS:Upgrade(61, 40, 98, 19)--scout 40 upgrade 2
TDS:Upgrade(61, 40, 98, 18)--scout 40 upgrade 3
TDS:Upgrade(61, 40, 98, 18)--scout 40 upgrade 4
TDS:Sell(41, 40, 98, 18)--scout 21 sell
TDS:Place('Scout', -10.092744827270508, 0.0492095947265625, -3.345820903778076, 40, 98, 17)--62
TDS:Upgrade(62, 40, 98, 17)--scout 40 upgrade 1
TDS:Upgrade(62, 40, 98, 17)--scout 40 upgrade 2
TDS:Upgrade(62, 40, 98, 16)--scout 40 upgrade 3
TDS:Upgrade(62, 40, 98, 16)--scout 40 upgrade 4
TDS:Sell(42, 40, 98, 16)--scout 22 sell
TDS:Place('Scout', -10.176299095153809, 0.0492095947265625, -6.349203586578369, 40, 98, 15)--63
TDS:Upgrade(63, 40, 98, 15)--scout 40 upgrade 1
TDS:Upgrade(63, 40, 98, 15)--scout 40 upgrade 2
TDS:Upgrade(63, 40, 98, 14)--scout 40 upgrade 3
TDS:Upgrade(63, 40, 98, 14)--scout 40 upgrade 4
TDS:Sell(19, 40, 98, 13)--DJ sell
TDS:Place('DJ Booth', -16.957136154174805, 0.0492095947265625, 0.31340980529785156, 40, 98, 13)--64 DJ Replaced
TDS:Upgrade(64, 40, 98, 13)--DJ Replaced upgrade 1
TDS:Upgrade(64, 40, 98, 12)--DJ Replaced upgrade 2
TDS:Upgrade(64, 40, 98, 12)--DJ Replaced upgrade 3
TDS:Upgrade(64, 40, 98, 12)--DJ Replaced upgrade 4
TDS:Upgrade(64, 40, 98, 11)--DJ Replaced upgrade 5 Gurt#9903
TDS:Sell(25, 40, 98, 11)--accel 1 sell
TDS:Place('Accelerator', -30.08814811706543, 0.0492095947265625, -9.009061813354492, 40, 98, 11)--65 accel 9
TDS:Upgrade(65, 40, 98, 10)--accel 9 upgrade 1
TDS:Upgrade(65, 40, 98, 10)--accel 9 upgrade 2
TDS:Upgrade(65, 40, 98, 10)--accel 9 upgrade 3
TDS:Upgrade(65, 40, 98, 9)--accel 9 upgrade 4
TDS:Upgrade(65, 40, 98, 9)--accel 9 upgrade 5
TDS:Sell(32, 40, 98, 9)--accel 8 sell
TDS:Place('Accelerator', -30.22004508972168, 0.0492095947265625, -12.03073787689209, 40, 98, 8)--66 accel 10
TDS:Upgrade(66, 40, 98, 8)--accel 10 upgrade 1
TDS:Upgrade(66, 40, 98, 8)--accel 10 upgrade 2
TDS:Upgrade(66, 40, 98, 7)--accel 10 upgrade 3
TDS:Upgrade(66, 40, 98, 7)--accel 10 upgrade 4
TDS:Upgrade(66, 40, 98, 7)--accel 10 upgrade 5
TDS:Sell(26, 40, 98, 6)--accel 2 sell
TDS:Place('Accelerator', -30.238018035888672, 0.0492095947265625, -5.964327812194824, 40, 98, 6)--67 accel 11
TDS:Upgrade(67, 40, 98, 6)--accel 11 upgrade 1
TDS:Upgrade(67, 40, 98, 5)--accel 11 upgrade 2
TDS:Upgrade(67, 40, 98, 5)--accel 11 upgrade 3
TDS:Upgrade(67, 40, 98, 5)--accel 11 upgrade 4
TDS:Upgrade(67, 40, 98, 4)--accel 11 upgrade 5
TDS:Sell(31, 40, 98, 4)--accel 7 sell
TDS:Place('Accelerator', -30.185659408569336, 0.0492095947265625, -2.9519412517547607, 40, 98, 4)--68 accel 12
TDS:Upgrade(68, 40, 98, 3)--accel 12 upgrade 1
TDS:Upgrade(68, 40, 98, 3)--accel 12 upgrade 2
TDS:Upgrade(68, 40, 98, 3)--accel 12 upgrade 3
TDS:Upgrade(68, 40, 98, 2)--accel 12 upgrade 4
TDS:Upgrade(68, 40, 98, 2)--accel 12 upgrade 5
TDS:Sell(27, 40, 98, 2)--accel 3 sell
TDS:Place('Accelerator', -27.16065216064453, 0.0492095947265625, -12.072626113891602, 40, 98, 1)--69 accel 13
TDS:Upgrade(69, 40, 98, 1)--accel 13 upgrade 1
TDS:Upgrade(69, 40, 98, 1)--accel 13 upgrade 2
TDS:Upgrade(69, 40, 98, 0)--accel 13 upgrade 3
TDS:Upgrade(69, 40, 98, 0)--accel 13 upgrade 4
TDS:Upgrade(69, 40, 98, 0)--accel 13 upgrade 5 Gurt#9903
TDS:Sell(30, 40, 97, 59)--accel 6 sell
TDS:Place('Accelerator', -27.028409957885742, 0.0492095947265625, -8.987671852111816, 40, 97, 59)--70 accel 14
TDS:Upgrade(70, 40, 97, 59)--accel 14 upgrade 1
TDS:Upgrade(70, 40, 97, 58)--accel 14 upgrade 2
TDS:Upgrade(70, 40, 97, 58)--accel 14 upgrade 3
TDS:Upgrade(70, 40, 97, 58)--accel 14 upgrade 4
TDS:Upgrade(70, 40, 97, 57)--accel 14 upgrade 5
TDS:Sell(28, 40, 97, 57)--accel 4 sell
TDS:Place('Accelerator', -27.176164627075195, 0.0492095947265625, -5.88355016708374, 40, 97, 57)--71 accel 15
TDS:Upgrade(71, 40, 97, 56)--accel 15 upgrade 1
TDS:Upgrade(71, 40, 97, 56)--accel 15 upgrade 2
TDS:Upgrade(71, 40, 97, 56)--accel 15 upgrade 3
TDS:Upgrade(71, 40, 97, 55)--accel 15 upgrade 4
TDS:Upgrade(71, 40, 97, 55)--accel 15 upgrade 5
TDS:Sell(29, 40, 97, 55)--accel 5 sell
TDS:Place('Accelerator', -27.146276473999023, 0.0492095947265625, -2.8607993125915527, 40, 97, 54)--72 accel 16
TDS:Upgrade(72, 40, 97, 54)--accel 16 upgrade 1
TDS:Upgrade(72, 40, 97, 54)--accel 16 upgrade 2
TDS:Upgrade(72, 40, 97, 53)--accel 16 upgrade 3
TDS:Upgrade(72, 40, 97, 53)--accel 16 upgrade 4
TDS:Upgrade(72, 40, 97, 53)--accel 16 upgrade 5
TDS:Sell(22, 40, 97, 52)--commander 3 sell
TDS:Sell(20, 40, 97, 52)--commander 1 sell
TDS:Sell(21, 40, 97, 52)--commander 2 sell
TDS:Place('Commander', -30.079116821289062, 0.0492095947265625, 10.971200942993164, 40, 97, 51)--73 commander 4
TDS:Upgrade(73, 40, 97, 51)--commander 4 upgrade 1
TDS:Upgrade(73, 40, 97, 51)--commander 4 upgrade 2
TDS:Upgrade(73, 40, 97, 50)--commander 4 upgrade 3
TDS:Upgrade(73, 40, 97, 50)--commander 4 upgrade 4
TDS:Place('Commander', -27.013202667236328, 0.0492095947265625, 10.881728172302246, 40, 97, 50)--74 commander 5
TDS:Upgrade(74, 40, 97, 49)--commander 5 upgrade 1
TDS:Upgrade(74, 40, 97, 49)--commander 5 upgrade 2
TDS:Upgrade(74, 40, 97, 49)--commander 5 upgrade 3
TDS:Upgrade(74, 40, 97, 48)--commander 5 upgrade 4
TDS:Place('Commander', -32.16020965576172, 0.44921034574508667, 11.09609603881836, 40, 97, 48)--75 commander 6
TDS:Upgrade(75, 40, 97, 48)--commander 6 upgrade 1
TDS:Upgrade(75, 40, 97, 47)--commander 6 upgrade 2
TDS:Upgrade(75, 40, 97, 47)--commander 6 upgrade 3
TDS:Upgrade(75, 40, 97, 47)--commander 6 upgrade 4
TDS:AutoChain(73, 74, 75, 40, 97, 46)--AUTO CTA 2 Gurt#9903
    end
    if map == maplist[3] then
local TDS = loadstring(game:HttpGet("https://raw.githubusercontent.com/banbuskox/dfhtyxvzexrxgfdzgzfdvfdz/main/ckmhjvskfkmsStratFun2", true))() 
TDS:Loadout("Farm", "Commander", "Accelerator", "Scout", "DJ Booth") 
TDS:Map("Portland", true, "Survival")
TDS:Mode('Insane')
task.spawn(function()
    wait(1)
    for i,v in pairs(game.CoreGui:GetDescendants()) do
        if v:IsA("TextLabel") and v.Name == "section_lbl" and v.Text == "" then
            v.Text = "Strat By: Gurt#9903"
        end
    end
end)
TDS:Place('Scout', -10.530301094055176, 0.22917842864990234, 25.674259185791016, 0, 0, 5)--1
TDS:Place('Scout', -10.505566596984863, 0.22917652130126953, 28.677841186523438, 0, 0, 5)--2
TDS:Place('Scout', -13.536166191101074, 0.2294454574584961, 25.718467712402344, 0, 0, 4)--3
TDS:Place('Scout', -14.78584098815918, 0.22955608367919922, 28.796661376953125, 1, 0, 3)--4
TDS:Place('Farm', 3.765626907348633, 0.2299213409423828, 11.731639862060547, 2, 0, 3)--5 farm 1
TDS:Place('Scout', -4.366228103637695, 0.23059463500976562, 28.32471466064453, 3, 0, 56)--6
TDS:Upgrade(5, 3, 0, 3)--farm 1 upgrade 1
TDS:Upgrade(5, 4, 0, 3)--farm 1 upgrade 2
TDS:Place('Farm', 0.6332387924194336, 0.2301807403564453, 11.761360168457031, 5, 1, 0)--7 farm 2
TDS:Place('Farm', 0.5934848785400391, 0.23018455505371094, 14.775947570800781, 5, 0, 3)--8 farm 3
TDS:Upgrade(7, 5, 0, 3)--farm 2 upgrade 1
TDS:Upgrade(7, 6, 0, 3)--farm 2 upgrade 2
TDS:Upgrade(8, 6, 0, 3)--farm 3 upgrade 1
TDS:Place('Scout', -4.389462947845459, 0.23059654235839844, 25.31739044189453, 6, 0, 2)--9
TDS:Place('Scout', -4.2743425369262695, 0.23058700561523438, 22.248550415039062, 7, 1, 0)--10
TDS:Place('Scout', -7.287134647369385, 0.23083782196044922, 19.55182647705078, 7, 1, 0)--11
TDS:Place('Scout', -10.306001663208008, 0.2291584014892578, 19.540302276611328, 7, 1, 0)--12
TDS:Place('Scout', -13.363954544067383, 0.2294301986694336, 19.502525329589844, 7, 0, 54)--13
TDS:Upgrade(8, 7, 0, 3)--farm 3 upgrade 2
TDS:Place('Farm', 3.8725318908691406, 0.22991180419921875, 14.760883331298828, 8, 0, 59)--14 farm 4
TDS:Upgrade(14, 8, 0, 58)--farm 4 upgrade 1
TDS:Upgrade(7, 8, 0, 3)--farm 2 upgrade 3
TDS:Upgrade(13, 9, 1, 0)--scout 10 upgrade 1 Gurt#9903
TDS:Upgrade(5, 9, 0, 3)--farm 1 upgrade 3
TDS:Upgrade(13, 9, 0, 3)--scout 10 upgrade 2
TDS:Upgrade(13, 10, 1, 0)--scout 10 upgrade 3
TDS:Upgrade(12, 10, 0, 59)--scout 9 upgrade 1
TDS:Upgrade(11, 10, 0, 59)--scout 8 upgrade 1
TDS:Upgrade(3, 10, 0, 54)--scout 3 upgrade 1
TDS:Upgrade(14, 10, 0, 3)--farm 4 upgrade 2
TDS:Place('Farm', 3.965961456298828, 0.2299051284790039, 17.834381103515625, 10, 0, 3)--15 farm 5
TDS:Upgrade(14, 11, 1, 0)--farm 4 upgrade 3
TDS:Upgrade(15, 11, 0, 58)--farm 5 upgrade 1
TDS:Place('Farm', 0.82513427734375, 0.2301654815673828, 17.959144592285156, 11, 0, 3)--16 farm 6
TDS:Upgrade(15, 11, 0, 3)--farm 5 upgrade 2
TDS:Upgrade(16, 11, 0, 3)--farm 6 upgrade 1
TDS:Place('Farm', 3.8000192642211914, 0.2299184799194336, 21.08603286743164, 11, 0, 2)--17 farm 7
TDS:Upgrade(12, 12, 1, 0)--scout 9 upgrade 2
TDS:Upgrade(12, 12, 1, 0)--scout 9 upgrade 3
TDS:Upgrade(8, 12, 0, 3)--farm 3 upgrade 3
TDS:Upgrade(17, 12, 0, 3)--farm 7 upgrade 1
TDS:Upgrade(11, 13, 1, 0)--scout 8 upgrade 2
TDS:Upgrade(11, 13, 1, 0)--scout 8 upgrade 3
TDS:Upgrade(15, 13, 0, 3)--farm 5 upgrade 3
TDS:Place('Farm', 0.7420501708984375, 0.23017120361328125, 21.23715591430664, 13, 0, 3)--18 farm 8
TDS:Upgrade(18, 13, 0, 2)--farm 8 upgrade 1
TDS:Upgrade(16, 14, 0, 59)--farm 6 upgrade 2
TDS:Upgrade(16, 14, 0, 59)--farm 6 upgrade 3
TDS:Upgrade(18, 14, 0, 57)--farm 8 upgrade 2
TDS:Upgrade(18, 14, 0, 48)--farm 8 upgrade 3
TDS:Upgrade(17, 14, 0, 3)--farm 7 upgrade 2
TDS:Upgrade(3, 15, 0, 59)--scout 3 upgrade 2 Gurt#9903
TDS:Upgrade(3, 15, 0, 58)--scout 3 upgrade 3
TDS:Upgrade(17, 15, 0, 57)--farm 7 upgrade 3
TDS:Place('DJ Booth', -8.77216625213623, 0.23095989227294922, 14.078132629394531, 15, 0, 54)--19 DJ
TDS:Upgrade(19, 15, 0, 52)--DJ upgrade 1
TDS:Upgrade(19, 15, 0, 3)--DJ upgrade 2
TDS:Upgrade(19, 16, 1, 0)--DJ upgrade 3
TDS:Upgrade(13, 17, 1, 0)--scout 10 upgrade 4
TDS:Upgrade(18, 17, 0, 58)--farm 8 upgrade 4
TDS:Upgrade(17, 17, 0, 3)--farm 7 upgrade 4
TDS:Upgrade(12, 18, 0, 58)--scout 9 upgrade 4
TDS:Upgrade(16, 18, 0, 3)--farm 6 upgrade 4
TDS:Upgrade(11, 19, 1, 0)--scout 8 upgrade 4
TDS:Place('Commander', -11.830575942993164, 0.2292938232421875, 13.976882934570312, 19, 0, 52)--20 commander 1
TDS:Upgrade(20, 19, 0, 51)--commander 1 upgrade 1
TDS:Upgrade(20, 19, 0, 3)--commander 1 upgrade 2
TDS:Ability(20, "Call Of Arms", 20, 1, 0)
TDS:Upgrade(3, 20, 0, 59)--scout 3 upgrade 4
TDS:Upgrade(15, 20, 0, 3)--farm 5 upgrade 4
TDS:Place('Commander', -5.668186187744141, 0.23070240020751953, 13.925968170166016, 20, 0, 3)--21 commander 2
TDS:Upgrade(21, 21, 1, 0)--commander 2 upgrade 1
TDS:Upgrade(21, 21, 1, 0)--commander 2 upgrade 2
TDS:Ability(21, "Call Of Arms", 21, 0, 59)
TDS:Upgrade(18, 21, 0, 52)--farm 8 upgrade 5
TDS:Place('Commander', -14.849031448364258, 0.22956180572509766, 13.977214813232422, 22, 1, 0)--22 commander 3
TDS:Upgrade(22, 22, 1, 0)--commander 3 upgrade 1
TDS:Upgrade(22, 22, 0, 59)--commander 3 upgrade 2
TDS:AutoChain(20, 21, 22, 22, 0, 59)--AUTO CTA
TDS:Upgrade(1, 22, 0, 57)--scout 1 upgrade 1
TDS:Upgrade(1, 22, 0, 57)--scout 1 upgrade 2
TDS:Upgrade(1, 22, 0, 57)--scout 1 upgrade 3
TDS:Upgrade(16, 22, 0, 41)--farm 6 upgrade 4
TDS:Skip(22, 0, 40)
TDS:Upgrade(1, 23, 0, 59)--scout 1 upgrade 4
TDS:Upgrade(10, 23, 0, 59)--scout 7 upgrade 1
TDS:Upgrade(10, 23, 0, 58)--scout 7 upgrade 2
TDS:Upgrade(10, 23, 0, 58)--scout 7 upgrade 3
TDS:Upgrade(10, 23, 0, 55)--scout 7 upgrade 4
TDS:Upgrade(15, 23, 0, 3)--farm 5 upgrade 5
TDS:Upgrade(17, 24, 1, 0)--farm 7 upgrade 5
TDS:Upgrade(14, 24, 0, 57)--farm 4 upgrade 4
TDS:Upgrade(8, 24, 0, 3)--farm 3 upgrade 4
TDS:Upgrade(14, 25, 1, 0)--farm 4 upgrade 5
TDS:Upgrade(9, 25, 0, 59)--scout 6 upgrade 1 Gurt#9903
TDS:Upgrade(9, 25, 0, 59)--scout 6 upgrade 2
TDS:Upgrade(9, 25, 0, 59)--scout 6 upgrade 3
TDS:Upgrade(9, 25, 0, 58)--scout 6 upgrade 4
TDS:Upgrade(8, 25, 0, 3)--farm 3 upgrade 5
TDS:Upgrade(7, 26, 1, 0)--farm 2 upgrade 4
TDS:Upgrade(7, 26, 1, 0)--farm 2 upgrade 5
TDS:Upgrade(5, 26, 0, 59)--farm 1 upgrade 4
TDS:Upgrade(5, 26, 0, 5)--farm 1 upgrade 5
TDS:Upgrade(19, 27, 1, 0)--DJ upgrade 4
TDS:Upgrade(19, 27, 0, 58)--DJ upgrade 5
TDS:Upgrade(4, 27, 0, 47)--scout 4 upgrade 1
TDS:Upgrade(4, 27, 0, 47)--scout 4 upgrade 2
TDS:Upgrade(4, 27, 0, 46)--scout 4 upgrade 3
TDS:Upgrade(4, 27, 0, 5)--scout 4 upgrade 4
TDS:Upgrade(2, 27, 0, 3)--scout 2 upgrade 1
TDS:Upgrade(2, 27, 0, 3)--scout 2 upgrade 2
TDS:Upgrade(6, 27, 0, 1)--scout 5 upgrade 1
TDS:Upgrade(6, 27, 0, 1)--scout 5 upgrade 2
TDS:Upgrade(6, 28, 1, 0)--scout 5 upgrade 3
TDS:Upgrade(2, 28, 0, 58)--scout 2 upgrade 3
TDS:Place('Accelerator', -2.4756436347961426, 0.23070049285888672, 7.687252044677734, 28, 0, 54)--23 accel 1
TDS:Upgrade(23, 28, 0, 53)--accel 1 upgrade 1
TDS:Upgrade(23, 28, 0, 53)--accel 1 upgrade 2
TDS:Upgrade(23, 28, 0, 52)--accel 1 upgrade 3
TDS:Skip(28, 0, 40)
TDS:Upgrade(23, 28, 0, 3)--accel 1 upgrade 4
TDS:Upgrade(23, 29, 0, 46)--accel 1 upgrade 5
TDS:Skip(29, 0, 40)
TDS:Upgrade(21, 30, 1, 20)--commander 2 upgrade 3
TDS:Upgrade(21, 30, 1, 20)--commander 2 upgrade 4 Gurt#9903
TDS:Upgrade(2, 30, 1, 18)--scout 2 upgrade 4
TDS:Upgrade(6, 30, 1, 13)--scout 5 upgrade 5
TDS:Skip(30, 0, 54)
TDS:Place('Accelerator', -2.549677848815918, 0.23044490814208984, 10.867149353027344, 31, 1, 15)--24 accel 2
TDS:Upgrade(24, 31, 1, 14)--accel 2 upgrade 1
TDS:Upgrade(24, 31, 1, 14)--accel 2 upgrade 2
TDS:Upgrade(24, 31, 1, 14)--accel 2 upgrade 3
TDS:Upgrade(24, 31, 1, 13)--accel 2 upgrade 4
TDS:Upgrade(24, 31, 1, 4)--accel 2 upgrade 5
TDS:Place('Accelerator', -5.5154314041137695, 0.23083877563476562, 7.5781097412109375, 32, 1, 19)--25 accel 3
TDS:Upgrade(25, 32, 1, 17)--accel 3 upgrade 1
TDS:Upgrade(25, 32, 1, 17)--accel 3 upgrade 2
TDS:Upgrade(25, 32, 1, 17)--accel 3 upgrade 3
TDS:Upgrade(25, 32, 1, 17)--accel 3 upgrade 4
TDS:Upgrade(25, 33, 1, 20)--accel 3 upgrade 5
TDS:Place('Accelerator', -5.644209384918213, 0.23070049285888672, 10.740570068359375, 33, 1, 17)--26 accel 4
TDS:Upgrade(26, 33, 1, 16)--accel 4 upgrade 1
TDS:Upgrade(26, 33, 1, 16)--accel 4 upgrade 2
TDS:Upgrade(26, 33, 1, 16)--accel 4 upgrade 3
TDS:Upgrade(26, 33, 1, 9)--accel 4 upgrade 4
TDS:Skip(33, 0, 54)
TDS:Upgrade(26, 34, 1, 20)--accel 4 upgrade 5
TDS:Place('Accelerator', -8.548417091369629, 0.23097515106201172, 7.662403106689453, 34, 1, 11)--27 accel 5
TDS:Upgrade(27, 34, 1, 10)--accel 5 upgrade 1
TDS:Upgrade(27, 34, 1, 9)--accel 5 upgrade 2
TDS:Upgrade(27, 34, 1, 9)--accel 5 upgrade 3
TDS:Upgrade(27, 34, 1, 8)--accel 5 upgrade 4
TDS:Skip(34, 0, 54)
TDS:Upgrade(27, 35, 1, 20)--accel 5 upgrade 5
TDS:Place('Accelerator', -8.71972942352295, 0.2309560775756836, 10.789806365966797, 35, 1, 17)--28 accel 6
TDS:Upgrade(28, 35, 1, 16)--accel 6 upgrade 1
TDS:Upgrade(28, 35, 1, 16)--accel 6 upgrade 2
TDS:Upgrade(28, 35, 1, 16)--accel 6 upgrade 3
TDS:Upgrade(28, 35, 1, 12)--accel 6 upgrade 4 Gurt#9903
TDS:Upgrade(28, 36, 1, 17)--accel 6 upgrade 5
TDS:Place('Accelerator', -8.474196434020996, 0.23100662231445312, 1.5010719299316406, 36, 1, 7)--29 accel 7
TDS:Upgrade(29, 36, 1, 6)--accel 7 upgrade 1
TDS:Upgrade(29, 36, 1, 6)--accel 7 upgrade 2
TDS:Upgrade(29, 36, 1, 6)--accel 7 upgrade 3
TDS:Upgrade(29, 36, 1, 6)--accel 7 upgrade 4
TDS:Upgrade(29, 36, 0, 59)--accel 7 upgrade 5
TDS:Place('Accelerator', -5.443291187286377, 0.23087787628173828, 1.3947067260742188, 37, 1, 18)--30 accel 8
TDS:Upgrade(30, 37, 1, 17)--accel 8 upgrade 1
TDS:Upgrade(30, 37, 1, 17)--accel 8 upgrade 2
TDS:Upgrade(30, 37, 1, 17)--accel 8 upgrade 3
TDS:Upgrade(30, 37, 1, 17)--accel 8 upgrade 4
TDS:Upgrade(30, 37, 1, 4)--accel 8 upgrade 5
TDS:Skip(37, 0, 54)
TDS:Place('Scout', -16.39341163635254, 0.22969913482666016, 19.55059814453125, 38, 1, 20)--31
TDS:Place('Scout', -19.407012939453125, 0.22996807098388672, 19.557083129882812, 38, 1, 20)--32
TDS:Place('Scout', -22.45785903930664, 0.2302389144897461, 19.496417999267578, 38, 1, 20)--33
TDS:Place('Scout', -24.212650299072266, 0.2303943634033203, 16.448566436767578, 38, 1, 19)--34
TDS:Place('Scout', -24.163249969482422, 0.23038959503173828, 13.432811737060547, 38, 1, 19)--35
TDS:Place('Scout', -24.135334014892578, 0.23038768768310547, 10.381397247314453, 38, 1, 19)--36
TDS:Place('Scout', -21.075428009033203, 0.2301158905029297, 7.61676025390625, 38, 1, 18)--37
TDS:Place('Scout', -18.050148010253906, 0.22984695434570312, 7.605854034423828, 38, 1, 18)--38
TDS:Place('Scout', -14.982032775878906, 0.22957324981689453, 7.586811065673828, 38, 1, 18)--39
TDS:Place('Scout', -11.865697860717773, 0.22929763793945312, 7.584522247314453, 38, 1, 17)--40
TDS:Upgrade(31, 38, 1, 17)--scout 11 upgrade 1
TDS:Upgrade(31, 38, 1, 17)--scout 11 upgrade 2
TDS:Upgrade(31, 38, 1, 16)--scout 11 upgrade 3
TDS:Upgrade(31, 38, 1, 16)--scout 11 upgrade 4 Gurt#9903
TDS:Upgrade(32, 38, 1, 16)--scout 12 upgrade 1
TDS:Upgrade(32, 38, 1, 15)--scout 12 upgrade 2
TDS:Upgrade(32, 38, 1, 15)--scout 12 upgrade 3
TDS:Upgrade(32, 38, 1, 15)--scout 12 upgrade 4
TDS:Upgrade(33, 38, 1, 14)--scout 13 upgrade 1
TDS:Upgrade(33, 38, 1, 14)--scout 13 upgrade 2
TDS:Upgrade(33, 38, 1, 14)--scout 13 upgrade 3
TDS:Upgrade(33, 38, 1, 13)--scout 13 upgrade 4
TDS:Upgrade(34, 38, 1, 13)--scout 14 upgrade 1
TDS:Upgrade(34, 38, 1, 13)--scout 14 upgrade 2
TDS:Upgrade(34, 38, 1, 12)--scout 14 upgrade 3
TDS:Upgrade(34, 38, 1, 12)--scout 14 upgrade 4
TDS:Upgrade(35, 38, 1, 12)--scout 15 upgrade 1
TDS:Upgrade(35, 38, 1, 11)--scout 15 upgrade 2
TDS:Upgrade(35, 38, 1, 11)--scout 15 upgrade 3
TDS:Upgrade(35, 38, 1, 11)--scout 15 upgrade 4
TDS:Upgrade(36, 38, 1, 10)--scout 16 upgrade 1
TDS:Upgrade(36, 38, 1, 10)--scout 16 upgrade 2
TDS:Upgrade(36, 38, 1, 10)--scout 16 upgrade 3 Gurt#9903
TDS:Upgrade(36, 38, 1, 9)--scout 16 upgrade 4
TDS:Upgrade(37, 38, 1, 9)--scout 17 upgrade 1
TDS:Upgrade(37, 38, 1, 9)--scout 17 upgrade 2
TDS:Upgrade(37, 38, 1, 8)--scout 17 upgrade 3
TDS:Upgrade(37, 38, 1, 8)--scout 17 upgrade 4
TDS:Upgrade(38, 38, 1, 8)--scout 18 upgrade 1
TDS:Upgrade(38, 38, 1, 7)--scout 18 upgrade 2
TDS:Upgrade(38, 38, 1, 7)--scout 18 upgrade 3
TDS:Upgrade(38, 38, 1, 7)--scout 18 upgrade 4
TDS:Upgrade(39, 38, 1, 6)--scout 19 upgrade 1
TDS:Upgrade(39, 38, 1, 6)--scout 19 upgrade 2
TDS:Upgrade(39, 38, 1, 6)--scout 19 upgrade 3
TDS:Upgrade(39, 38, 1, 5)--scout 19 upgrade 4
TDS:Upgrade(40, 38, 1, 5)--scout 20 upgrade 1
TDS:Upgrade(40, 38, 1, 5)--scout 20 upgrade 2
TDS:Upgrade(40, 38, 1, 4)--scout 20 upgrade 3
TDS:Upgrade(40, 38, 1, 4)--scout 20 upgrade 4
TDS:Skip(38, 0, 54)
TDS:Sell(5, 39, 2, 0)--farm 1 sell
TDS:Sell(7, 39, 2, 0)--farm 2 sell
TDS:Sell(8, 39, 2, 0)--farm 3 sell
TDS:Sell(14, 39, 1, 59)--farm 4 sell
TDS:Sell(15, 39, 1, 59)--farm 5 sell
TDS:Sell(16, 39, 1, 59)--farm 6 sell
TDS:Sell(17, 39, 1, 58)--farm 7 sell
TDS:Sell(18, 39, 1, 58)--farm 8 sell Gurt#9903
TDS:Place('Scout', -4.114710330963135, 0.2305736541748047, 19.149303436279297, 39, 1, 58)--41
TDS:Upgrade(41, 39, 1, 57)--scout 21 upgrade 1
TDS:Upgrade(41, 39, 1, 57)--scout 21 upgrade 2
TDS:Upgrade(41, 39, 1, 57)--scout 21 upgrade 3
TDS:Upgrade(41, 39, 1, 56)--scout 21 upgrade 4
TDS:Place('Scout', -21.102542877197266, 0.2301177978515625, 16.226245880126953, 39, 1, 56)--42
TDS:Place('Scout', -17.91156005859375, 0.22983455657958984, 16.389930725097656, 39, 1, 56)--43
TDS:Upgrade(43, 39, 1, 55)--scout 23 upgrade 1
TDS:Upgrade(43, 39, 1, 55)--scout 23 upgrade 2
TDS:Upgrade(43, 39, 1, 55)--scout 23 upgrade 3
TDS:Upgrade(43, 39, 1, 54)--scout 23 upgrade 4
TDS:Upgrade(42, 39, 1, 54)--scout 22 upgrade 1
TDS:Upgrade(42, 39, 1, 54)--scout 22 upgrade 2
TDS:Upgrade(42, 39, 1, 53)--scout 22 upgrade 3
TDS:Upgrade(42, 39, 1, 53)--scout 22 upgrade 4
TDS:Place('Scout', -20.95364761352539, 0.2301044464111328, 13.144981384277344, 39, 1, 53)--44
TDS:Place('Scout', -17.88612937927246, 0.22983264923095703, 13.255664825439453, 39, 1, 52)--45
TDS:Upgrade(45, 39, 1, 52)--scout 25 upgrade 1
TDS:Upgrade(45, 39, 1, 52)--scout 25 upgrade 2
TDS:Upgrade(45, 39, 1, 51)--scout 25 upgrade 3
TDS:Upgrade(45, 39, 1, 51)--scout 25 upgrade 4
TDS:Upgrade(44, 39, 1, 51)--scout 24 upgrade 1
TDS:Upgrade(44, 39, 1, 50)--scout 24 upgrade 2
TDS:Upgrade(44, 39, 1, 50)--scout 24 upgrade 3
TDS:Upgrade(44, 39, 1, 50)--scout 24 upgrade 4
TDS:Place('Scout', -11.85487174987793, 0.2292957305908203, 10.670909881591797, 39, 1, 49)--46
TDS:Upgrade(46, 39, 1, 49)--scout 26 upgrade 1
TDS:Upgrade(46, 39, 1, 49)--scout 26 upgrade 2
TDS:Upgrade(46, 39, 1, 48)--scout 26 upgrade 3
TDS:Upgrade(46, 39, 1, 48)--scout 26 upgrade 4
TDS:Place('Scout', -2.5771493911743164, 0.23044681549072266, 15.96261978149414, 39, 1, 48)--47
TDS:Upgrade(47, 39, 1, 47)--scout 27 upgrade 1
TDS:Upgrade(47, 39, 1, 47)--scout 27 upgrade 2
TDS:Upgrade(47, 39, 1, 47)--scout 27 upgrade 3
TDS:Upgrade(47, 39, 1, 46)--scout 27 upgrade 4
TDS:Place('Scout', -16.617433547973633, 0.2297191619873047, 25.58395004272461, 39, 1, 45)--48
TDS:Upgrade(48, 39, 1, 45)--scout 28 upgrade 1
TDS:Upgrade(48, 39, 1, 45)--scout 28 upgrade 2
TDS:Upgrade(48, 39, 1, 44)--scout 28 upgrade 3
TDS:Upgrade(48, 39, 1, 44)--scout 28 upgrade 4
TDS:Upgrade(20, 39, 1, 44)--commander 1 upgrade 3
TDS:Upgrade(20, 39, 1, 43)--commander 1 upgrade 4
TDS:Upgrade(22, 39, 1, 43)--commander 3 upgrade 3
TDS:Upgrade(22, 39, 1, 43)--commander 3 upgrade 4 Gurt#9903
TDS:Skip(39, 1, 20)
TDS:Sell(6, 40, 99, 10)--scout 5 sell
TDS:Sell(2, 40, 99, 9)--scout 2 sell
TDS:Sell(4, 40, 99, 8)--scout 4 sell
TDS:Place('Scout', 0.5913143157958984, 0.23018455505371094, 11.59444808959961, 40, 99, 8)--49
TDS:Upgrade(49, 40, 99, 8)--scout 29 upgrade 1
TDS:Upgrade(49, 40, 99, 7)--scout 29 upgrade 2
TDS:Upgrade(49, 40, 99, 7)--scout 29 upgrade 3
TDS:Upgrade(49, 40, 99, 7)--scout 29 upgrade 4
TDS:Place('Scout', 0.5212078094482422, 0.23019027709960938, 14.66708755493164, 40, 99, 6)--50
TDS:Upgrade(50, 40, 99, 6)--scout 30 upgrade 
TDS:Upgrade(50, 40, 99, 6)--scout 30 upgrade 
TDS:Upgrade(50, 40, 99, 5)--scout 30 upgrade 
TDS:Upgrade(50, 40, 99, 5)--scout 30 upgrade 
TDS:Place('Scout', 3.6864757537841797, 0.2304372787475586, 5.324699401855469, 40, 99, 5)--51
TDS:Upgrade(51, 40, 99, 4)--scout 31 upgrade 
TDS:Upgrade(51, 40, 99, 4)--scout 31 upgrade 
TDS:Upgrade(51, 40, 99, 4)--scout 31 upgrade 
TDS:Upgrade(51, 40, 99, 3)--scout 31 upgrade 
TDS:Sell(48, 40, 98, 32)--scout 28 sell
TDS:Sell(3, 40, 98, 31)--scout 3 sell
TDS:Sell(1, 40, 98, 31)--scout 1 sell
TDS:Sell(9, 40, 98, 30)--scout 6 sell Gurt#9903
TDS:Place('Scout', 3.8543081283569336, 0.22991371154785156, 11.867477416992188, 40, 98, 30)--52
TDS:Upgrade(52, 40, 98, 30)--scout 32 upgrade 
TDS:Upgrade(52, 40, 98, 29)--scout 32 upgrade 
TDS:Upgrade(52, 40, 98, 29)--scout 32 upgrade 
TDS:Upgrade(52, 40, 98, 29)--scout 32 upgrade
TDS:Place('Scout', 6.878602027893066, 0.23029327392578125, 5.375480651855469, 40, 98, 28)--53
TDS:Upgrade(53, 40, 98, 28)--scout 33 upgrade 
TDS:Upgrade(53, 40, 98, 28)--scout 33 upgrade 
TDS:Upgrade(53, 40, 98, 27)--scout 33 upgrade 
TDS:Upgrade(53, 40, 98, 27)--scout 33 upgrade 
TDS:Place('Scout', 3.6896400451660156, 0.23045921325683594, 2.059417724609375, 40, 98, 27)--54
TDS:Upgrade(54, 40, 98, 26)--scout 34 upgrade 
TDS:Upgrade(54, 40, 98, 26)--scout 34 upgrade 
TDS:Upgrade(54, 40, 98, 26)--scout 34 upgrade 
TDS:Upgrade(54, 40, 98, 25)--scout 34 upgrade 
TDS:Place('Scout', 6.8684539794921875, 0.2303142547607422, 2.320575714111328, 40, 98, 25)--55
TDS:Upgrade(55, 40, 98, 25)--scout 35 upgrade 
TDS:Upgrade(55, 40, 98, 24)--scout 35 upgrade 
TDS:Upgrade(55, 40, 98, 24)--scout 35 upgrade 
TDS:Upgrade(55, 40, 98, 24)--scout 35 upgrade 
TDS:Sell(28, 40, 98, 15)--accel 6 sell
TDS:Place('Accelerator', -2.431410312652588, 0.23074054718017578, 1.4529991149902344, 40, 98, 15)--56 accel 9
TDS:Upgrade(56, 40, 98, 15)--accel 9 upgrade 1
TDS:Upgrade(56, 40, 98, 14)--accel 9 upgrade 2
TDS:Upgrade(56, 40, 98, 14)--accel 9 upgrade 3
TDS:Upgrade(56, 40, 98, 14)--accel 9 upgrade 4
TDS:Upgrade(56, 40, 98, 13)--accel 9 upgrade 5
TDS:Sell(26, 40, 98, 13)--accel 4 sell
TDS:Place('Accelerator', -8.519424438476562, 0.23100662231445312, -1.576171875, 40, 98, 13)--57 accel 10
TDS:Upgrade(57, 40, 98, 12)--accel 10 upgrade 1
TDS:Upgrade(57, 40, 98, 12)--accel 10 upgrade 2
TDS:Upgrade(57, 40, 98, 12)--accel 10 upgrade 3
TDS:Upgrade(57, 40, 98, 11)--accel 10 upgrade 4
TDS:Upgrade(57, 40, 98, 11)--accel 10 upgrade 5
TDS:Sell(27, 40, 98, 11)--accel 5 sell Gurt#9903
TDS:Place('Accelerator', -5.441405773162842, 0.2308979034423828, -1.6319198608398438, 40, 98, 10)--58 accel 11
TDS:Upgrade(58, 40, 98, 10)--accel 11 upgrade 1
TDS:Upgrade(58, 40, 98, 10)--accel 11 upgrade 2
TDS:Upgrade(58, 40, 98, 9)--accel 11 upgrade 3
TDS:Upgrade(58, 40, 98, 9)--accel 11 upgrade 4
TDS:Upgrade(58, 40, 98, 9)--accel 11 upgrade 5
TDS:Sell(25, 40, 98, 8)--accel 3 sell
TDS:Place('Accelerator', -2.318161964416504, 0.2307577133178711, -1.7775306701660156, 40, 98, 8)--59 accel 12
TDS:Upgrade(59, 40, 98, 8)--accel 12 upgrade 1
TDS:Upgrade(59, 40, 98, 7)--accel 12 upgrade 2
TDS:Upgrade(59, 40, 98, 7)--accel 12 upgrade 3
TDS:Upgrade(59, 40, 98, 7)--accel 12 upgrade 4
TDS:Upgrade(59, 40, 98, 6)--accel 12 upgrade 5
TDS:Sell(24, 40, 98, 6)--accel 2 sell
TDS:Place('Accelerator', -5.490995407104492, 0.23092174530029297, -4.775691986083984, 40, 98, 6)--60 accel 13
TDS:Upgrade(60, 40, 98, 5)--accel 13 upgrade 1
TDS:Upgrade(60, 40, 98, 5)--accel 13 upgrade 2
TDS:Upgrade(60, 40, 98, 5)--accel 13 upgrade 3
TDS:Upgrade(60, 40, 98, 4)--accel 13 upgrade 4
TDS:Upgrade(60, 40, 98, 4)--accel 13 upgrade 5
TDS:Sell(23, 40, 98, 4)--accel 1 sell
TDS:Place('Accelerator', -8.615983009338379, 0.23100662231445312, -4.605218887329102, 40, 98, 3)--61 accel 14
TDS:Upgrade(61, 40, 98, 3)--accel 14 upgrade 1
TDS:Upgrade(61, 40, 98, 3)--accel 14 upgrade 2
TDS:Upgrade(61, 40, 98, 2)--accel 14 upgrade 3
TDS:Upgrade(61, 40, 98, 2)--accel 14 upgrade 4
TDS:Upgrade(61, 40, 98, 2)--accel 14 upgrade 5 Gurt#9903
    end
end
