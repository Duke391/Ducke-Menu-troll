local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Ducke Menu Troll", "Ocean")

--Main
local Main = Window:NewTab("Main")
local Mainsection = Main:NewSection("Main")

Mainsection:NewButton("Infinite Yield", "Fe Admins Comandos", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)

Mainsection:NewButton("Emotes Fe", "Fe Emotes", function()
    loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-TIKTOK-Emote-Gui-Script-48411"))()
end)

Mainsection:NewSlider("Walkspeed", "Walkspeed", 500, 0, function(s) -- 500 (MaxValue) | 0 (MinValue)
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s
end)

Mainsection:NewButton("Emotes Sus FE", "Fe Emotes", function()
    loadstring(game:HttpGet("http://tuxmenu.ct.ws/tuxraw/raw/689d38a4501895192.txt"))()
end)

Mainsection:NewButton("Animação Fe Scp-096", "Animação universal", function()
    loadstring(game:HttpGet("https://pastefy.app/YsJgITXR/raw"))()
end)
