# MCBEx86
An archive for all x86 Dx11 builds of MCBE for Windows since Render Dragon

### How to install .appx files with patched Xbox authentication
- These app packages are considered "untrusted" by Windows, because they were packaged by a 3rd party (me)
- In order to install the appx's certificate, right click it, and go `Propeties` -> `Digital Signatures`
- Click the signature in the signatures list, the click `Details` -> `View Certificate` -> `Install Certificate...`
- Select the `Store Location` to be `Local Machine`, then click `Next`
- Select `Place all certificates in the following store` and set the directory to the `Trusted Root Certification Authorities` folder
- Click `Next`, then `Finish`
- Double click the appx to install with the default App Installer as normal

# DISCLAIMER:
## Obtaining a copy of a Minecraft for Windows app package (.Appx) such as the ones hosted here will NOT allow you to pirate the game. You MUST still own the game in order for it to be played outside of trial mode. I do NOT encourage theft and/or piracy of Minecraft for Windows. This repository is NOT intended to aid in the piracy of Minecraft for Windows.

### Why host direct downloads here?
Microsoft has consistently shown that they can completely screw over parts of the MCBE community without warning or indication. The fact that this repository exists, in light of Render Dragon, is further proof of that. I cannot safely say that direct download links to APPXs from the Microsoft Store will persist over time.

### Why only 1.16.200-1.18.12?
As of 1.16.200, the Render Dragon engine made a full release to the x64 builds of the MCBE Windows 10 client. It continues to be the successor of the Dx11 / previous rendering engine. However, for the span of 1.16.200-1.18.12, the x86 build of the client used the old engine, which netted better stability, performance, no input lag, no "pink glitch", etc. As of 1.18.30, Render Dragon rolled out to the x86 build of the client as well, along with several other platforms. The x86 versions starting from 1.18.30 onward are now effectively less performant due to the older processor architecture, with the same rendering engine as a control.

### Upvote these bug reports!
["pink glitch"](https://bugs.mojang.com/browse/MCPE-105487)<br />
[severe input delay](https://bugs.mojang.com/browse/MCPE-98861)<br />
[general performance degradation](https://bugs.mojang.com/browse/MCPE-142934)