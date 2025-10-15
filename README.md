local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()

local Window = Rayfield:CreateWindow({
   Name = "RoRaRe Loader",
   Icon = 0, 
   LoadingTitle = "Loading..",
   LoadingSubtitle = "by : Like2get Studio",
   ShowText = "RoRaRe™", 
   Theme = "Default", 

   ToggleUIKeybind = "K", 

   DisableRayfieldPrompts = false,
   DisableBuildWarnings = false, 

   ConfigurationSaving = {
      Enabled = true,
      FolderName = nil, 
      FileName = "Big Hub"
   },

   Discord = {
      Enabled = false, 
      Invite = "noinvitelink", 
      RememberJoins = true 
   },

   KeySystem = true, 
   KeySettings = {
      Title = "No key",
      Subtitle = "Key System",
      Note = "key for verify : RoRaRe", 
      FileName = "Key", 
      SaveKey = true, 
      GrabKeyFromSite = false, 
      Key = {"RoRaRe"} 
   }
})

local Tab = Window:CreateTab("Home", 4483362458) 

local Paragraph = Tab:CreateParagraph({Title = "RoRaRe Hub", Content = "thanks for using my hub, it took 4 days to make it (only me)but now it keyless enjoy!"})

local Tab = Window:CreateTab("Load RoRaRe Hub™", 4483362458) 

local Button = Tab:CreateButton({
   Name = "Load RoRaRe™ (Now keyless!)",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/LaxHubOfficial/RoRaRe/refs/heads/main/README.md",true))()
   end,
})
