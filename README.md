### decompiler

custom decompiler using a disassembler & chatgpt

credits to people who made disassembler and me

**EXAMPLE 1:**
```lua
api_key = "YOUR_OPENAI_API_KEY"
loadstring(request({Url="https://raw.githubusercontent.com/dPw4hqVLC576BrasAT3DKJzp/decompiler/main/decompile.lua",Method="GET"}).Body)();

print(decompile(game:GetService("Players").LocalPlayer.PlayerScripts.PlayerScriptsLoader));
```
**EXAMPLE 2:**
```lua
api_key = "YOUR_OPENAI_API_KEY"
local decompile = loadstring(request({Url="https://raw.githubusercontent.com/dPw4hqVLC576BrasAT3DKJzp/decompiler/main/decompile.lua",Method="GET"}).Body)();

print(decompile(game:GetService("Players").LocalPlayer.PlayerScripts.PlayerScriptsLoader));
```
