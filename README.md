Sigma-Spy
A complete Remote Spy with an incredible parser that captures incoming and outgoing remotes data with Actor support!

Socials 💬
Sigma Spy Showcase (Youtube)
Discord
Loadstring
--// Sigma Spy @depso
loadstring(game:HttpGet("https://raw.githubusercontent.com/antifortbloxalliancescripts/sigma-spy/refs/heads/main/Sigma-Spy-main/Sigma-Spy-main/Main.lua"))()
Notices 🔔
Sigma Spy will have bugs, please report any bugs by opening an issue on Github
If you gave a suggestion, please post it in the discussions
If you have issues with the executor's comm library (get_comm_channel, create_comm_channel), enable ForceUseCustomComm in Sigma Spy/Config.lua which is found in your Executor's workspace folder after running
AWP and Zenith is recommended to use as of 11/06/25
Features ⚡
These are some of the many features Sigma Spy has

Actors support	Keybinds for toggling options
__index and __namecall support	Dumping logs to file
Decompile large scripts	Argument values for log titles
Block remotes from firing	Wide range of supported data types
Spoof return values (Return spoofs.lua)	Logging client recieves (e.g OnClientEvent)
Variable compression in the parser	Remote stacking (Known as 'Grouping') (optional)
Mobile devices are supported	Pop-out editors
Screenshots 🖼️
	 Pop-out Decompile with Connections viewer
 Mulitple Pop-out editors	 Executor function patches
Config.lua options ⚙️
Name	Description
ForceUseCustomComm	Forces Sigma Spy to use the built-in comm library. This is automatically used if you executor does not support it
ForceKonstantDecompiler	Forces the decompile option to use Kontant for decompiling scripts. This is enabled automatically if your executor does not support `decompile`
NoFunctionPatching	Disables patches for functions in your executor that may be vulnerable
ReplaceMetaCallFunc	Replaces the meta call function using getrawmetatable instead of using hookmetamethod
NoReceiveHooking	Disables the hooking of callback functions such as .OnClientInvoke
VariableNames	Variable names used by the parser if the generated is not usuable
Required functions ⚠️
Sigma spy will prompt you if your executor does not support it. Your executor must support these functions in order for it to function:

Required	Optional
hookmetamethod	getcustomasset (Optional for the true ImGui theme)
hookfunction	Comm library (get_comm_channel, create_comm_channel) (Optional)
getrawmetatable	
setreadonly	
File library	
getconnections	
newcclosure	
Libraries used
ReGui (Depso)
Roblox-Parser (Depso)
