# Valorant Optimal Settings For Best Performance

## Sensitivity
1. To Get Your Starting Sensitivity Just Take 280 Divide It By ***Your DPI***.
This Will Give You A Base Sensitivity For Finding Your Perfect Sens
   - 400 DPI = 0.7
   - 800 DPI = 0.35
   - 1600DPI = 0.175
2. Now Go to [Sensitivity Calculator](https://jscalc.io/embed/vqOrqXRpMgmwb8tV)
3. Type In Your Starting Sensitivity
4. Now Try The Higher & Lower Sensitivities On The Right And Tell Which One Feels Better On The Left.
5. Do This And Get Your Perfect Sensitivity

## In Game Settings For FPS Boost
1. Keep All The Graphics Settings Low
2. Set Anisotropic Filtering To 2X OR 4X
3. Set Bloom To On
4. Set Nvidia Reflex Low Latency To - On + Boost
5. Turn On Multithreaded Rendering

- Extra Tips
1. Set Your Resolution The Same As Your Monitor's Default Resolution
2. Limit FPS Always Can Be Kept Off But For More Stable FPS Cap It 2-3 FPS Below Ur Monitors Refresh Rate
(I Personally Turn It Off)

## Windows Settings For Best Performance
1. Download [Process Lasso](https://bitsum.com) And Copy What Is Done In This [Video](https://www.youtube.com/watch?v=r2A0YbMjOY8)
2. Go To This Path `C:\Users\***Your Username***\AppData\Local\VALORANT\Saved\Config\Windows`
   - Open `RiotLocalMachine.ini`
   - See A Random String Of Digits? Copy Them
   - `C:\Users\***Your Username***\AppData\Local\VALORANT\Saved\Config\***Paste Them Here***\Windows` Go To This Path Now
   - Open It And Open `GameUserSettings.ini`
   - In It Scroll Down And Find Scalability Groups
   - Now Set Everything To 0 And In Resolution Quality Instead Of 100.00000... (just Change The 100 TO 80 Dont Touch The Zeros!)
   - Save This
3. Go To This Path `C:\Riot Games\VALORANT\live`
   - Right Click On `Valorant.exe` The Go to Compatibility And Check The Disable Fullscreen Optimizations Box
   - Now, Go To This Path `C:\Riot Games\VALORANT\live\ShooterGame\Binaries\Win64`
   - And Do The Same For `Win-64-Shipping.exe`
### Advanced
**IMPORTANT!** (Create A Restore Point)
1. Download This [CLEANER](https://discord.com/channels/1141288490479403038/1155132704543739905/1155138921148194919) And Run It As Administrator
2. Download [NVIDIA Profile Inspector](https://discord.com/channels/1141288490479403038/1155132704543739905/1155140636824047676) And Open It
   - Find Where It Is Written `_GLOBAL_DRIVER_PROFILE (Base Profile)`
   - Click On It, Delete It And Search Valorant
   - In The Searches Click On Valorant And Then On The Right Click On Apply Changes
3. Download [MSI Utility V3](https://discord.com/channels/1141288490479403038/1155132704543739905/1155146800970354790) And  Run as administator
   - Find your GPU and turn on MSI mode if supported
   - Set interrupt prioity to high
   - And Click On Apply On The Top Right
4. CTT Tool
   - Now Run Powershell As Admin
   - Paste This `iwr -useb https://christitus.com/win | iex` And Enter
   - Go To The Tweaks Tab From The Navbar Up Top
   - Click On Desktop
   - And The Run Selected Tweaks On The Bottom Right
5. Win32PrioritySeparation
   - Download [18HEX](https://discord.com/channels/1141288490479403038/1155132704543739905/1155155212210810941) And Run It
   - If It Reduces Your FPS Then
   - Download [18HEX REVERT](https://discord.com/channels/1141288490479403038/1155132704543739905/1155156332110958683) And Run This
6. Allocate Virtual Memory (Page File):
   - First Check The Installed RAM On Your Computer By Going Into Settings -> System -> About
   - Click Windows + R
   - Type In "Regedit"
   - Hit Enter
   - Now On The Left Side Go To HKEY_LOCAL_MACHINE\SOFTWARE\Intel\GMM\
   - If You Dont Have A DWORD There
   - Right Click Create New DWORD (32-Bit Value)
   - Name It "Dedicated Segment Size"
   - And Now If You Have.

| RAM         | Value       |
| ----------- | ----------- |
| 4GB         | 512         |
| 8GB         | 1024        |
| 16GB        | 2048        |
| 32GB        | 4096        |
 7. ISLC (Intelligent standby list cleaner)
   - Download [Intelligent standby list cleaner](https://www.wagnardsoft.com/content/Intelligent-standby-list-cleaner-ISLC-v1029-Released)
   - Run ISLC as Administrator
   - Set "The list size is at least":
     
| RAM         | Value       |
| ----------- | ----------- |
| 8GB         | 4096        |
| 16GB        | 8192        |
| 32GB        | 16384       |
