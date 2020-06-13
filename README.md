**Setup Instructions for Android/iOS**

<u>Android</u>:

I used the following tutorial to get set up (https://www.youtube.com/watch?v=EDlywQeg5Vs, also on the Trello task), but here's a simplified version for the Android setup:

1) Make sure you install the latest version of flutter and then add the flutter bin folder to your paths. This is so that you can run the flutter commands from any cmd/bash window or directory. Test this out by typing flutter into the cmd window. 

2) You'll need either a physical android device (lol xD) or an emulator. You can set up the emulator easily after you download Android studio, but keep in mind that if you use a AMD processor, you won't be able to run the AVD stuff for the virtual 
android emulator. Since that is me, I opted to use my old physical android (lol xD), so here are the steps to enable your computer to recognize the device once plugged in via usb:

		- Go to settings > about phone > build number, then tap build number 7 times, and this will enable the developer mode for android 
		- Then, backtrack to the settings, then >developer options and scroll down to "USB debugging". Replug your android device via usb if the box is greyed out, and then click the checkbox for "USB debugging" 
		- Test your connection out by opening a cmd window and typing "flutter devices". If your device shows up, you're all set 

3) You'll need an IDE or a good text editor, so VS Code is a great one with lots of plug ins. If you use VS Code, you can install the Flutter/Dart plugin, and it'll take care of all the formatting. Useful hotkeys are F5 to run the debugger and shift+f5 to stop it

<u>iOS</u>:

I used the following YouTube tutorial video to set up Flutter and related dev tools: https://www.youtube.com/watch?v=THsihXK1-14. I've summarized the setup instructions below, but follow the YouTube tutorial for an in-depth step by step guide c**.

1) Install flutter SDK from website. Move to flutter directory to home directory. Open .bash_profile file and add flutter to your PATH. 

2) Install VS Code to use a text editor. Add Flutter extension.

3) Install Xcode, mainly to use the iOS simulator.

4) To visualize on simulator, run debugger (F5) through VS Code and choose Dart&Flutter environment. Will build code and show app.