local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()

local Window = Rayfield:CreateWindow({
	Name = "Angel Prueba 1",
	LoadingTitle = "Angel St1l3",
	LoadingSubtitle = "The King (Angel)",
	ConfigurationSaving = {
		Enabled = false,
		FolderName = "Rayfield Interface Suite",
		FileName = "BG"
	},
	KeySystem = true, -- Set this to true to use their key system
	KeySettings = {
		Title = "Angel key",
		Subtitle = "Key System",
		Note = "Key in -https://pastebin.com/Lz6VjJru-",
		SaveKey = false,
		Key = "KeyPrueba1"
	}
})

 Rayfield:Notify({
   Title = "Bienvenido",
   Content = "Script de Angel en Proceso",
   Duration = 3.0,
   Image = 4483362458,
})

local Tab = Window:CreateTab("Prueba de botones", 4483362458) -- Title, Image

local Section = Tab:CreateSection("Secciones")

local Toggle = Tab:CreateToggle({
	Name = "Auto Gain Power",
	CurrentValue = false,
	Flag = "Gain Power", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
	Callback = function(Value)
    AutoGainPowerEnabled = state
        if AutoGainPowerMultiEnabled then
            task.spawn(function()
                upgradeLoop(function() return Bubble end, 5)
            end)
        end
		-- The function that takes place when the toggle is pressed
    		-- The variable (Value) is a boolean on whether the toggle is true or false
	end,
})

local Tab = Window:CreateTab("Universal scripts", 4483362458) -- Title, Image

local Section = Tab:CreateSection("Scripts")

local Button = Tab:CreateButton({
    Name = "Aimbot Exunys",
    Callback = function()
        local url = "https://raw.githubusercontent.com/Exunys/AirHub-V2/main/src/Main.lua"
        local scriptContenido = game:HttpGet(url)
        local ejecutar = loadstring(scriptContenido)
        ejecutar()
    end,
})

local Button = Tab:CreateButton({
    Name = "Instant Interaction",
    Callback = function()
        local url = "https://raw.githubusercontent.com/Exunys/AirHub-V2/main/src/Main.lua"
        local scriptContenido = game:HttpGet(url)
        local ejecutar = loadstring(scriptContenido)
        ejecutar()
    Rayfield:Notify({
   Title = "Executado",
   Content = "El Script ha sido executado",
   Duration = 3.0,
   Image = 4483362458,
})
    end,
})

local Button = Tab:CreateButton({
    Name = "Fly Gui",
    Callback = function()
        local url = "https://raw.githubusercontent.com/XNEOFF/FlyGuiV3/main/FlyGuiV3.txt"
        local scriptContenido = game:HttpGet(url)
        local ejecutar = loadstring(scriptContenido)
        ejecutar()
    end,
})

local Button = Tab:CreateButton({
	Name = "Infinite jump",
	Callback = function()
local InfiniteJumpEnabled = true
game:GetService("UserInputService").JumpRequest:connect(function()
	if InfiniteJumpEnabled then
		game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")
	end
end)
	end,
})

local Slider = Tab:CreateSlider({
   Name = "WalkSpeed Slider",
   Range = {1, 350},
   Increment = 1,
   Suffix = "Speed",
   CurrentValue = 16,
   Flag = "sliderws", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(Value)
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = (Value)
   end,
})

local Slider = Tab:CreateSlider({
   Name = "JumpPower Slider",
   Range = {1, 350},
   Increment = 1,
   Suffix = "Speed",
   CurrentValue = 16,
   Flag = "sliderjp", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(Value)
        game.Players.LocalPlayer.Character.Humanoid.JumpPower = (Value)
   end,
})

