# install-android-studio
### Required
- JDK (Java Development Kit)
- Android Studio

| Windows                                                                                                        | Mac                                                                                                        |
| ---------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|
| Microsoft® Windows® 7/8/10 (32- or 64-bit)                                                                     | Mac® OS X® 10.10 (Yosemite) or newer, up to 10.13 (macOS High Sierra)                                      |
| Minimum RAM of 3GB, recommended RAM of 8GB; Add 1 GB for Android Emulator or use your phone to run project     | Minimum RAM of 3GB, recommended RAM of 8GB; Add 1 GB for Android Emulator or use your phone to run project |
| The minimum available disk space is 2GB,                                                                       | The minimum available disk space is 2GB,                                                                   |
| 4GB recommended (500MB for IDE + 1.5GB for Android SDK and image system emulator)                              | 4GB recommended (500MB for IDE + 1.5GB for Android SDK and image system emulator)                          |

### Step 1: Download the JDK
You can download the JDK for free [here](http://www.oracle.com/technetwork/java/javase/downloads/index.html)
1. Click the **Download** button under the JDK for the latest Java SE version.
2. Select **Accept License Agreement**.
3. Choose the JDK for your operating system.

### Step 2: Install the JDK (for Mac)
From either the **Downloads** window of the browser, or from the file browser, double-click the `.dmg` file to launch the install file.
1. A **Finder** window appears with an icon of an open box and the name of the `.pkg` file.
2. Double-click the package icon to launch the installation app, and follow the prompts as they appear.
3. You might need to enter the administrator password to continue.
4. After the installation is complete, feel free to delete the `.dmg` file to save space.

### Step 2: Install the JDK and JRE (for Windows)
1. Run the downloaded installer (for example, `jdk-12_windows-x64_bin.exe`), which installs both the JDK and the JRE. By default, the JDK is installed in the `C:\Program Files\Java\jdk-12` directory. The JRE is installed in `C:\Program Files\Java\jre1.8.0_x`, where `x` denotes the version number.
2. Accept the defaults, and follow the on-screen instructions to install the JDK.

### Step 3: Add the JDK and JRE installation directories to PATH (Windows only)
Windows searches the current directory and the directories listed in the `PATH` environment variable (system variable) for executable programs.

1. Open **Control Panel > System > Advanced system settings > Environment Variables**.
2. Under System variables, click New and add a variable named JAVA_HOME with the JRE's directory for a value. For example, C:\Program Files\Java\jre1.8.0_x, where x is the version number.
3. Under **System variables**, scroll down to select **Path**, then click **Edit**.
4. Add the JRE's `bin` directory to the start of the `Path`, followed by a semicolon: `%JAVA_HOME%\bin`;
5. Append the JDK's `bin` directory to end of the `Path`, preceded by a semicolon. For example, `;C:\Program Files\Java\jdk-12\bin`.

### Step 4: Verify the JDK installation
To verify that the JDK was installed correctly, type the following commands in a terminal window:
```java
java -version
javac -version
```

> Windows users: If you receive an error from either command, confirm you've added the correct paths for the JRE (java) and the JDK (javac).

### Step 5: Download and Install Android Studio
Download the application [Here](https://developer.android.com/studio) and install as usual
