## Technical Documentation

### Manual Installation by building for VR 
You need to complete following instructions to make Convai Plugin compatible with VR

The following packages will be needed:
- Universal Render Pipeline (URP)
- OpenXR Plugin
- XR Interaction Toolkit
- Convai Custom VR Package
- Convai URP Converter
  
If these packages are not present, they will be installed with the script.

**Warning: If the target build platform is not Android, it will be switched to Android.**

### Installation
1. Click on " Convai / Convai Custom Package Installer / Install VR Package "

   <img src="https://3358478024-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FEtUJA212Zc1S9ACc8T4l%2Fuploads%2F21bOM5YePk9F46dEKSkr%2FConvaiCustomPackageInstaller.png?alt=media&token=c20d32f6-aff5-459f-8213-e0ce83bc8f1d">
   
2. Confirm the changes and processes to be made. If you agree, the process will start. Click " **Yes, Proceed** " and the process will begin. You'll see logs in the console.

   <img src="https://3358478024-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FEtUJA212Zc1S9ACc8T4l%2Fuploads%2FGy6nnyA0L2vgaXXLQkF9%2FConvaiCustomPackageInstallerConfirmWindow.png?alt=media&token=2ae378ec-0aac-4b34-b377-6db86af7b013">

3. If you encounter an error like " Failed to Resolve Packages " don't worry. The process will continue and the error will be resolved automatically after the package installations are complete.

   <img src="https://3358478024-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FEtUJA212Zc1S9ACc8T4l%2Fuploads%2FPfhlasAaDsBnTIckCmct%2FVRLogs.png?alt=media&token=8dff5c2d-7331-4815-9254-34022be73dd3">

4. When you open the scene first time TMP importer may appear. If the TMP Importer window appears, click " Import TMP Essentials " to install TextMeshPro for UI text objects.

   <img src="https://3358478024-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FEtUJA212Zc1S9ACc8T4l%2Fuploads%2F69nbgYYrti9eBL9Ogfbo%2FAutomaticallyImportTMPEssentials.png?alt=media&token=31bdc58f-c282-4d6d-88db-8ff7ae9a1045">

5. Build the project by going to " File /Build Settings / Build " Ensure that the main scene is included in the Scenes in Build section.

Now everything is ready for testing. ✅

## Automatic Installation by SideQuest(for Oculus Quest)

### Prerequisites

#### 1. Enable Developer Mode on Quest

Turn on your Quest headset and open the Oculus app on the Android or iOS device you used to set up your Quest.

<img src="https://cdn-learn.adafruit.com/assets/assets/000/086/760/medium800/hacks_app-dev-mode.png?1578521683">

Follow these steps to enable Developer mode on your Quest:

1. Tap **Settings** (bottom-right)
2. **Select** your connected Quest from the device list and connect to it
3. Tap **More Settings** which appears below your Quest in the device list
4. Tap **Developer Mode**
5. Tap the **switch** to enable developer mode
6. Exit Settings on the app & **reboot your Quest** using the right-side power button

<img src="https://cdn-learn.adafruit.com/assets/assets/000/086/757/medium800/hacks_quest-dev-menu.png?1578521198">

After your Quest reboots, developer mode should be enabled. You can confirm this by checking for the **Developer** category in the Quest's **Settings menu** as seen above.

#### 2. Install SideQuest on Your PC

Follow official installation tutorial by using the link below:

[![SideQuest Installation](https://img.youtube.com/vi/d7qeXI-h4A8/0.jpg)](https://www.youtube.com/watch?v=d7qeXI-h4A8)

### Using SideQuest

1. Make sure you have **downloaded the *.apk** for the application you are trying to download
2. **Plug in your  Oculus Quest  to your computer.** Connect your headset to your pc via your USB-C cable. The long black charging cable should work for this.
3. Open SideQuest
4. Click **Install APK from folder**

<img src="https://github.com/akinogunc/VR-Assistant-Convai/blob/main/sidequest1.png">

5. Select the  ***.apk** file
6. Wait for it to install, you can watch the progress by clicking the pink '1'

<img src="https://github.com/akinogunc/VR-Assistant-Convai/blob/main/sidequest2.jpeg">

When the  pink install bar turns green,  the application is installed

### How to Launch

Follow these 4 steps to launch the app:

1. Click Home
2. Click Library
3. Select Unknown Sources
4. Run your app!

