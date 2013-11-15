MugMe
=====

Mobile Action, Puzzler, PvP Game

Contributers:
++++GETTING STARTED++++
Follow these intructions if using Windows.

1. Download Android SDK
2. Download Android NDK
3. Make sure you have Java jdk
4. Download Apache Ant
5. Download cocos2dx 3.0 alpha
5. Save all of these in C:\Android (make a new folder) *Note: when naming files, don't use spaces or Cygwin will freak*
6. Download Cygwin with all Dev packages selected. Save it at C:\
7. Downloading python is optional. So I will not go through it.
8. Go to environment variables and set Paths as follows:
    1. New Path: ANDROID_SDK (set to your android sdk folder)
    2. New Path: NDK_ROOT (set to your ndk folder)
    3. Set another path to Java jdk if you have not already Name it JAVA_HOME
    4. Set another path to Ant. Name it ANT_HOME
    5. Finally, add this to your Path (edit Path) C:\cygwin64\bin;%Android_SDK%\tools;%ANDROID_SDK%\platform-tools;%ANDROID_NDK%;%JAVA_HOME%\bin;%ANT_HOME%\bin;%NDK_ROOT%
9. Copy the MyGame folder into your project folder (in cocos2dx folder)
10. Open cygwin and navigate to the project folder. Go into MyGame. Go into proj.android.
11. type "make" (this should make something called MyGame-debug.apk in your bin)
12. You will probably get a crapload of errors and I will do my best to answer your questions in the FAQ below.
13. If make says build successful, then go ahead an plug in your Android Device into your computer.
14. Download the USB driver for the device
15. In Cygwin, type "make run" (this should put the app MyGame on your phone)
16. Open up MyGame
17. Edit the cpp and h files in Classes folder (in cocos, in projects, in mygame)
18. Test on your phone
19. Push to github
