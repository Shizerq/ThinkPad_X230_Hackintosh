# EFI folder for hackintoshing ThinkPad X230

My config for X230 based on xxx10101xxx's repo. Works with High Sierra and Mojave.

# My setup:
- Intel Core I5-3320M;
- 4 GB of RAM;
- 120 GB SSD drive.

# What's working?
- TouchPad;
- TrackPoint (fixed sensitivity and scrolling speed);
- Keyboard;
- Ethernet;
- Backlight (with control);
- Webcam;
- Bluetooth;
- Audio;
- Microphone;
- Jack 3,5mm;
- iCloud;
- App Store;
- Mini DP;
- Shut down/reboot;
- Battery status;
- Native Power Managment;
- USB;
- QE/CI.
- AirDrop (You have to change Intel WI-FI to Broadcom one)

# What's not working?
- SD Card reader;
- VGA port (doesn't exist in real Mac);
- Fingerprint reader.

# What can work but I'm not sure:
- FaceTime and iMessage - It's possible that my Apple ID is blocked or it's fault of USB WI-FI

# Bugs:
- Boot animation.

# Audio:
I'm using voodoo kext. You can also patch AppleHDA. If You use voodoohda, You have to swap between jack and built in speakers manually.

# Other:
If you have fixed something, fork this repository and pull request. I will update the repository after checking the changes.

If you have found any error, fell free to open issue. 
