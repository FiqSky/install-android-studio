# Install Android Studio

## Required

- JDK (Java Development Kit)
- Android Studio

| Windows                                    | Mac                                      |
| ------------------------------------------ | ---------------------------------------- |
| Microsoft® Windows® 10 (64-bit) or newer  | macOS 10.15 (Catalina) or newer          |
| Minimum RAM of 4GB, recommended RAM of 8GB; Add 2 GB for Android Emulator or use your phone to run the project | Minimum RAM of 4GB, recommended RAM of 8GB; Add 2 GB for Android Emulator or use your phone to run the project |
| Minimum available disk space of 8GB        | Minimum available disk space of 8GB       |
| 8GB recommended (1GB for IDE + 3GB for Android SDK and system image emulator) | 8GB recommended (1GB for IDE + 3GB for Android SDK and system image emulator) |

## Step 1: Download the JDK

You can download the JDK for free from [Oracle's website](https://www.oracle.com/java/technologies/javase-jdk-downloads.html).

1. Click the **Download** button under the JDK for the latest Java SE version.
2. Accept the License Agreement.
3. Choose the JDK for your operating system.

## Step 2: Install the JDK (for Mac)

1. From either the **Downloads** window of the browser or from the file browser, double-click the `.dmg` file to launch the install file.
2. A **Finder** window appears with an icon of an open box and the name of the `.pkg` file.
3. Double-click the package icon to launch the installation app and follow the prompts.
4. You might need to enter the administrator password to continue.
5. After the installation is complete, feel free to delete the `.dmg` file to save space.

## Step 2: Install the JDK (for Windows)

1. Run the downloaded installer (for example, `jdk-21_windows-x64_bin.exe`), which installs both the JDK and the JRE. By default, the JDK is installed in `C:\Program Files\Java\jdk-21` directory.
2. Accept the defaults and follow the on-screen instructions to install the JDK.

## Step 3: Add the JDK Installation Directory to PATH (Windows only)

1. Open **Control Panel > System > Advanced system settings > Environment Variables**.
2. Under System variables, click **New** and add a variable named `JAVA_HOME` with the JDK's directory as the value. For example, `C:\Program Files\Java\jdk-21`.
3. Under **System variables**, scroll down to select **Path**, then click **Edit**.
4. Add the JDK's `bin` directory to the end of the `Path`, preceded by a semicolon. For example, `;C:\Program Files\Java\jdk-21\bin`.

## Step 4: Verify the JDK Installation

To verify that the JDK was installed correctly, open a terminal (Command Prompt on Windows or Terminal on Mac) and type the following commands:
  java
  java -version
  javac -version
Windows users: If you receive an error from either command, confirm you've added the correct paths for the JDK.

## Step 5: Download and Install Android Studio
1. Download Android Studio from [Android Developer's website](https://developer.android.com/studio).
2. Follow the installation instructions provided on the website to complete the setup.
With these steps, you should have a working setup for Android development with the latest tools and updates for 2024.
