## Technical Documentation

### Getting ready for VR Installation
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

Now everything is ready for testing. 🙂✅


