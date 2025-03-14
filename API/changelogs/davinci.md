# 26-June-2022
- Switched to user builds
- Updated blobs from miui_SWEETEEAGlobal_V13.0.10.0.SKFEUXM
- Added Neural Networks and Snapdragon Computer Vision Engine stack
- Updated VantomKernel
- Other misc. changes and fixes

# 18-Jun-2022
- Fixed issues related to audio
- Updated kernel

# 09-Jun-2022
- Updated blobs from MIUI V13.0.8.0.SKFMIXM
- Update adreno from LA.UM.9.1.r1-11500.02-SMxxx0
- Switched to EROFS (Enhanced read only file system)
- Enabled F2FS compression (Needs a clean flash to work)
- Optimize native executables for Cortex-A76 CPU
- Switch to dot product CPU variant
- Nuked Vulkan (due to some heating/drain)
- Fixed picture adjustment in LiveDisplay (Do NOT change kernel if you want LiveDisplay to function properly)
- Updated VantomKernel and PlayGround clang
- Other misc. changes

# 6-May-2022
- Kernel update
- Better RAM Management

# 30-Apr-2022
- Added a few missing blobs
- Fixed anti flicker mode
- Enable zygote unspecialized app process pool
- Configure SQLite to operate in MEMORY mode
- Added MGLRU for better memory management
- Dropped SLMK in favor of LMKD
- Use LMKD from YAAP for better memory management
- Updated kernel
- Misc. changes and fixes

# 27-Apr-2022
- Changed kernel to VantomKernel compiled with PlayGround clang 15
- Updated blobs from sweet MIUI V13.0.8.0.SKFEUXM
- Introduced haptic control
- Introduced livedisplay
- Fixed WiFi Display (Miracast)
- Fixed some issues with NFC
- Increased volume steps from 15 to 25
- Misc. fixes and changes

# 10-Mar-2022
- Merged April Security Patch

# 2-Mar-2022
- Improved vibrations
- Improved UDFPS
- Configure physical power, volume and fingerprint locations
- Changed default status bar height
- HBM is now white
- Miscellaneous changes and fixes from xiaomi-sm6150

# 2-Feb-2022
- February security patch

# 16-Jan-2022
- Jan-security patch

# 02-Jan-2022
- Fixed bluetooth audio

# 01-Jan-2022
- December Security patch
- Fixed FOD on AOD
- Fixed OTA asserts
- Switched to VantomKernel
- Finetuned statusBar padding
- Fixed Hey Google voice match
- Fixed APN not getting recognized 
- Fixed camera on telegram
