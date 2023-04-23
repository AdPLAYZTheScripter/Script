local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Julian's Op Scripts", "Ocean")
 
 
--MAIN
local Main = Window:NewTab("Main")
local MainSection = Main:NewSection("Games")
 
MainSection:NewButton("Arsenal", "Opens Script", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/KeoneGithub/KeoneGithub/main/Arsenal",true))()
end)
 
 
MainSection:NewButton("Phantom Forces (working on)", "Opens Script", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/VoidMasterX/strawhook/main/script.lua", true))()
end)
 
MainSection:NewButton("Welcome to Bloxburg", "Opens Auto Farm Gui", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/PainfulDestroyer/Roblox/main/Scar%20Hub"))()
end)
 
MainSection:NewButton("Da Hood", "Opens Script", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/NighterEpic/Faded/main/YesEpic", true))()
end)
 
MainSection:NewButton("Infinite Yield", "FE Admin Commands", function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'),true))()
end)
 
MainSection:NewButton("Hoopz", "Opens Script", function()
    loadstring(game:HttpGet(('https://pastebin.com/raw/v8RqpA3g'),true))()
end)
 
MainSection:NewButton("Millionaire Empire Tycoon", "Gives Inf Money", function()
    loadstring(game:HttpGet(('https://pastebin.com/q8fLMGGW'),true))()
end)
 
MainSection:NewButton("Multiple Game's Gui", "Has Diffrent Script's", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/GamingResources/GamingResources-Script-Hub/main/Key%20System", true))()
end)
 
MainSection:NewButton("Wizard Tycoon - 2 Player", "Opens Script", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/SlamminPig/rblxgames/main/Wizard%20Tycoon%20-%202%20Player/2pWizardTycoonGUI"))()
end)
 
MainSection:NewButton("Longest Answer Wins", "Give's Answers", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Nicuse/RobloxScripts/main/LongestAnswerWins.lua"))()
end)
 
MainSection:NewButton("Football Fusion", "Reach", function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/SlimLegoHacks/Scripts/main/FootballFusion.lua')))()
end)
 
MainSection:NewButton("War Tycoon", "Gun Mod", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/megamoeus/UI-Engine-V2/main/OWTPublic"))()
end)
 
MainSection:NewButton("Pet Sim X", "Opens Script", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Flxry/Main/MilkyHub/Pet%20Simulator%20X"))()
end)
 
MainSection:NewButton("Fe Sword Reach", "Hits from a distance", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/AJf14WtQ"))()
end)
 
MainSection:NewButton("", "Opens Script", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Flxry/Main/MilkyHub/Pet%20Simulator%20X"))()
end)
 
MainSection:NewButton("Apocalypse Rising 2", "Opens Script", function()
    loadstring(game:HttpGet("https://anomiss.in/script.lua"))()
end)
 
 
--LOCAL PLAYER
local PLAYER = Window:NewTab("Player")
local PlayerSection = PLAYER:NewSection("Player")
 
PlayerSection:NewSlider("Walkspeed", "SPEED!!", 500, 16, function(s)
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s
end)
 
PlayerSection:NewSlider("Jumppower", "JUMP HIGH!!", 350, 50, function(s)
    game.Players.LocalPlayer.Character.Humanoid.JumpPower = s
end)
 
PlayerSection:NewButton("Bypassed Fly (x to unfly)", "bird mode", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Nicuse/RobloxScripts/main/BypassedFly.lua"))() 
 
    Fly(true)
end)
 
 
