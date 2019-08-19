# RemoteControlPC-Studio

Remote Control PC

Use your Android phone to control your Laptop.

### Features

1. Control Left Click, Right Click, Mouse Scroll
2. Type text 
3. Transfer files from phone to laptop
4. Download files from laptop to phone
5. Use your laptop as speaker to play mp3 files of phone
6. See images of phone on laptop
7. Control presentation on laptop via phone
8. Suspend, Restart or Shutdown your laptop using phone
9. Fetch your laptop screen to Android (only single click supported)
10. Browse Android files on Desktop (View and Download
11.Used as a wireless game joystick or controller


## How does it work?

###### Step 1:
Start hotspot on phone and connect your laptop via wifi

###### Step 2:
Open the desktop app on your laptop (See instructions below)

###### Step 3:
Open Android app and enter connection details provided by desktop app to connect

###### Step 4:
Enjoy :sparkles: :boom: :wink:

### Dependencies
You need Java 8


### How to start desktop app?
1. Clone this Repository / Download zip 
2. Open terminal (Ctrl + Alt + T)
3. Type `cd /path/to/repository/RemoteControlPC-JavaFXML/dist/RemoteControlPC.jar`
4. Type `java -jar RemoteControlPC-Desktop.jar`
5. Lock icon to launcher
6. Make sure you have Java 8 installed (hit `java -version`) 

### How to start android app?
1. Install apk from /Remote-Control-PC/RemoteControlPC-Studio/app/build/outputs/apk/app-debug.apk
2. Connect your laptop with your phone via hotspot (or any local network)
3. Start Desktop app
4. Enter connection details shown on Desktop
5. Tested on Android 4.2.2 (Samsung Duos)

#### Steps to deploy app on your machine-
1. There are three folders-
    1. RemoteControlPC-Studio- Android part, Import in Android Studio 
    2. RemoteControlPC-JavaFXML- Desktop part, Import in Netbeans (Use SceneBuilder)
    3. RemoteControlPC-Libraries- Libraries (Jar file) that is being used in android as well as desktop, Import in Netbeans
2. Library has a dist folder that contains jar file.
3. Add this jar file in build path of Desktop (Netbeans) as well as Android part. See steps below.
4. To change/modify the java files inside library folder, import it in Netbeans and 'clean and build project' after changing.
5. Make sure to clean android as well as desktop part after modifying library files.

#### Testing of android app:
* Android 4.2.2 Samsung(GT-S7582)
* Android 6.0.1 Redmi 4A
* Android 5, API 22 (Emulator)
* Android 7, API 24 (Emulator)

### path:
https://github.com/ethakur217/RemoteControlPC-Studio

#### For query/issues open Github issue or contact: ethakur217@gmail.com
