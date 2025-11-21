# EXP 14 - INSTALLING-AND-RUNNING-APPLICATIONS-ON-ANDROID-STUDIO-DATE
## AIM
To install Android Studio on a Windows system and configure the required environment for developing Android applications, including setting up the Android SDK and creating an Android Virtual Device (AVD).

## PROCEDURE
## Step 1: Verify System Requirements

Check whether your computer supports Android development tools.

## Required software:

Java JDK (version 5 or later)

Java Runtime Environment (JRE)

Android Studio (latest version)

## Hardware requirements:

Minimum 4GB RAM (8GB recommended)

At least 4GB free disk space

Internet connection is required for downloading SDK components.

## Step 2: Download Java JDK

Visit Oracle’s official website or OpenJDK website.

Choose the correct installer for your OS (Windows 64-bit).

Download → Run the installer → Click Next until installation completes.

Note the installation path. 

## Example:
```
C:\Program Files\Java\jdk1.8.0_301
```
## Step 3: Download Android Studio

Go to the official Android Studio download page.

Click Download Android Studio (Windows).

## The file will be named like:

android-studio-bundle-143.xxxxxxx-windows.exe

Once downloaded, double-click to open the installer.

## Step 4: Install Android Studio

The Android Studio Setup Wizard opens.

Click Next → Accept the default installation settings.

## Select the components:

Android Studio

Android SDK

Android Virtual Device (AVD)

HAXM (Intel Hardware Acceleration Manager)

Choose the installation folder (default recommended).

## Specify:

SDK Location (default: C:\Users\<name>\AppData\Local\Android\Sdk)

Allow the wizard to extract files and install the SDK tools.

Installation takes around 2–5 minutes depending on system speed.

## Step 5: Provide JDK Path

After launching Android Studio for the first time, it asks for the JDK path.

## Browse and select:
```
C:\Program Files\Java\jdk<version>
```
Click Next, and Android Studio proceeds with configuration.

## Step 6: SDK Component Download

## Android Studio downloads:

Android SDK Tools

Android Platform Tools

Emulator Components

System Images

This takes time and consumes approx 2.6 GB of disk space.

Wait until the Finish button appears.

## Step 7: Launch Android Studio

Click Finish.

## Android Studio opens the Welcome Screen:

Start new project

Open existing project

Configure SDK Manager

AVD Manager

## Step 8: Create a New Android Project

Click Start a new Android Studio project.

## Fill:

Application Name

Package Name

Project Location

## Select:

Phone and Tablet

Minimum SDK (e.g., Android 6.0 - API 23)

## Choose an Activity template:

Empty Activity (most common for beginners)

Set Activity Name and Layout Name.

Click Finish → Project loads in the editor.

## Step 9: Configure Android Virtual Device (AVD)

Click AVD Manager icon on the toolbar.

Click Create Virtual Device.

Select a device model (e.g., Pixel XL, Nexus 5X).

Select a System Image (Android version like Pie, Oreo).

Click Next → Choose RAM size (default is good).

Click Finish → AVD will appear in the list.

You can now click Play to start the virtual device.

## Step 10: Verify Emulator Setup

The AVD boots like a real smartphone.

## You can:

Rotate screen

Install apps

Test UI

Debug apps

Once AVD runs smoothly, Android Studio setup is fully complete.

## Step 11: Ready for Development

## With Android Studio open and AVD running:

You can write Java/Kotlin code

Add XML layouts

Build APKs

Run apps in emulator or real device

The environment is fully functional for Android application development.

## OUTPUT

Android Studio is installed successfully.

Android SDK and emulator (AVD) are configured.

A sample Android project can be created and opened.

A virtual Android device is available to run and test applications.

## RESULT

The installation and setup of Android Studio were completed successfully. The system is now ready for developing Android applications, running them on a virtual device, and using all Android Studio features for app development.
