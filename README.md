# Sonic Robo Blast 2 with Discord rich presence support
Experimental branch. Huge thanks to Prisima and SteelTitanium for helping out with this project!

_Support for other platforms (macOS, Linux) is currently untested. Use at your own risk._

## Demo
[View a quick feature demonstration here.](https://serval.is-very-cute.moe/ZXupoAAK.webm)

## Compiling
Use the flag `DISCORD-RPC=1` when compiling, so for instance to build a Windows SDL2 exe you should use: 
```
mingw32-make MINGW=1 CC=gcc WINDOWSHELL=1 SDL=1 NOOBJDUMP=1 DISCORD-RPC=1
```

You will also need **discord-rpc.dll**, which can be found [here](https://github.com/discordapp/discord-rpc/releases). 
Download and open discord-rpc-win.zip, then navigate to `discord-rpc\win32-dynamic\bin` and copy discord-rpc.dll to your SRB2 folder.

## Disclaimer
Sonic Team Junior is in no way affiliated with SEGA or Sonic Team. We do not claim ownership of any of SEGA's intellectual property used in SRB2.
