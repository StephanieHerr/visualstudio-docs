---
title: "Install Visual Studio for Mac"
description: "Instructions on how to install Visual Studio for Mac and additional components required for cross-platform development."
author: asb3993
ms.author: amburns
ms.date: 04/14/2017
ms.topic: article
ms.technology: vs-ide-install
ms.assetid: 22B1F2CD-32AE-464D-80AC-C8AB4786B015
---

# Setup and Install Visual Studio for Mac

## Setup

To start developing native, cross-platform apps as soon as you download Visual Studio for Mac there are a couple of things that you will want to install and setup in preparation.

For working with iOS in Visual Studio you will need the following:

* a Mac with macOS Sierra 10.12 or above
* Xcode 8.3
* An Apple ID. You can create this at https://appleid.apple.com if you don’t have one already. This is necessary for installing and signing into Xcode.

## Install

1. Download Visual Studio for Mac from [https://www.visualstudio.com/](https://www.visualstudio.com/)

2. Once the installer package is downloaded, click on the **VisualStudioInstaller.dmg** file to mount the installer and then run it by double-clicking on the logo, as illustrated below:

  ![Installer dialog](media/installer-image1.png)

3. You might be prompted with an alert dialog similar to the image below. In this case, click **Open**:

  ![alert dialog](media/installer-image2.png)

4. The installer will inspect your system to verify which components need to be installed or updated:

  ![Assessing your system](media/installer-image3.png)

5. You will then be presented with an alert dialog asking you to acknowledge the Privacy and License terms. Press the **Continue** button to acknowledge the terms:

  ![License dialog](media/installer-image4.png)

6. The installer will present a list of required components that are missing and that need to be downloaded and installed. Select the products you wish to download here:

  ![Select Items](media/installer-image5.png)

  This installation screen displays the version and size of each individual component. You can click on each component to display a list of dependencies for that component (for Android), see additional packages that it will download (for .NET Core), and view any additional applications required (for iOS and macOS):

  ![Android additional dependencies](media/installer-image6.png)

7. Once you are happy with your selection, select the **Install and Update** button to start the installation process.

8. The installer will start the download and install process of the selected items:

  ![Starting Installation](media/installer-image7.png)

  ![Downloading Xamarin.Mac](media/installer-image8.png)

  ![Finishing Installation](media/installer-image9.png)

9. You might be prompted to elevate the permissions necessary for individual components that are needed to complete installation. Enter your administrator credentials here to continue the installation process:

  ![Enter permissions to continue with installer](media/installer-image10.png)

10. Once the installation is successful, you can start developing apps in Visual Studio by pressing **Start**:

  ![Open Visual Studio](media/installer-image11.png)
