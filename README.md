MugMe
=====

Mobile Action, Puzzler, PvP Game

Contributors: ++++GETTING STARTED++++ Follow these instructions if using Windows.

1. Download Android SDK
2. Download Android NDK
3. Make sure you have Java jdk
4. Download Apache Ant
5. Download cocos2dx 3.0 alpha
6. Save all of these in C:\Android (make a new folder) Note: when naming files, don't use spaces or Cygwin will freak
7. Download Cygwin with all Dev packages selected. Save it at C:\
8. Downloading python is optional. So I will not go through it.
9. Go to environment variables and set Paths as follows:
	a. New Path: ANDROID_SDK (set to your android sdk folder)
	b. New Path: NDK_ROOT (set to your ndk folder)
	c. Set another path to Java jdk if you have not already Name it JAVA_HOME
	d. Set another path to Ant. Name it ANT_HOME
	e. Finally, add this to your Path (edit Path) C:\cygwin64\bin;%Android_SDK%\tools;%ANDROID_SDK%\platform-tools;%ANDROID_NDK%;%JAVA_HOME%\bin;%ANT_HOME%\bin;%NDK_ROOT%
10. Copy the MyGame folder into your project folder (in cocos2dx folder)
11. Open cygwin and navigate to the project folder. Go into MyGame. Go into proj.android.
12. type "make" (this should make something called MyGame-debug.apk in your bin)
13. You will probably get a crapload of errors and I will do my best to answer your questions in the FAQ below.
14. If make says build successful, then go ahead an plug in your Android Device into your computer.
15. Download the USB driver for the device
16. In Cygwin, type "make run" (this should put the app MyGame on your phone)
17. Open up MyGame
18. Edit the cpp and h files in Classes folder (in cocos, in projects, in mygame)
19. Test on your phone
20. Edit and push changed to GitHub

GitHub Tutorial:
1. Download Windows Github
2. BUT DON'T USE WINDOWS GITHUB...there are some errors with its commits...at least for android
3. Use the git shell. Just run a search for it on your computer.
4. Follow this tutorial to familiarize yourself with git. http://lifehacker.com/5983680/how-the-heck-do-i-use-github
5. YOU CAN IGNORE THE PART ABOUT SSH KEYS. Windows Github does it for you.
6. I'm still trying to figure out how you would submit edits. I think I would have to approve them.
