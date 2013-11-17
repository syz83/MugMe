all:
	./build_native.sh
	ant -Dsdk.dir="D:\Development\Android\android_sdk\sdk" debug
run:
	adb -d uninstall com.MyCompany.AwesomeGame
	adb -d install bin/MyGame-debug.apk
	adb -d logcat | grep cocos2d
clean:
	rm -rf libs/
	rm -rf obj/
	rm -rf bin/*
	rm -rf gen/
	rm -rf assets/*
