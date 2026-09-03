# Unity-and-Visual-Studio-Code-Setup-Procedure

Before we get started with downloading and setting up Unity, please make sure that [GitHub](https://github.com) and [GitHub Desktop](https://desktop.github.com/download/) are installed on your computer. If they are not, please download and install them, as we will use them for future class projects. If you don't already have a GitHub account, you can use your school email address to create one. You will need a GitHub account later in this tutorial.

**Note for those who have previously used GitHub through the command line:** Trust me, GitHub Desktop will make your life much easier. :)

Now, go to [Unity's website](https://unity.com/releases/unity-6) and download Unity Hub. You can use your school email address to create a Unity account. Once Unity Hub is installed, it should look something like this after you sign in:

![Basic Unity Hub Page](/Images/Basic.png)

**Please do not click the blue `Install` button yet.** Instead, select `Installs` from the sidebar, as shown below:

![Step 1](/Images/Step_1.png)

Then click on the blue `Install Editor` button on the right side of the window as shown in the picture below -

![Step 2](/Images/Step_2.png)

This will open a pop-up window. From there, you need to click on the blue `Install` icon next to the Unity version that you want to install, as shown in the picture below -

![Step 3](/Images/Step_3.png)

**Note that all of us in the class will use the exact same Unity version in the class.**

Once you click on the `Install` button, it will open another pop-up window, where, you need to make sure that you chose the three check marks and then click on `Continue` to install Unity properly in your computer so that you can work with the headsets easily. The three checkmarks are shown in the picture below -

![Step 4](/Images/Step_4.png)

**If you cannot find the required Unity version after clicking the blue `Install Editor` button, you can find older versions in the Unity Editor archive.**

Click the `Archive` tab in the pop-up window, as shown below:

![Step 5](/Images/Step_9.png)

Select the Unity major version you need from the dropdown menu, as shown below:

![Step 6](/Images/Step_10.png)

Find the required Unity version in the list and click the `Install` button next to it:

![Step 7](/Images/Step_11.png)

**If You Installed Unity Without the XR Modules**
If you installed Unity without the XR-specific modules, you can add them through Unity Hub later. Open Unity Hub and select `Installs`, as shown below:

![Step 8](/Images/Step_1.png)

Click the `Manage` dropdown menu next to your installed Unity Editor, as shown below:

![Step 9](/Images/Step_5.png)

Select `Manage Modules`:

![Step 10](/Images/Step_6.png)

In the module window, select these three options:

`Android Build Support`,
`OpenJDK`, and
`Android SDK and NDK Tools`

![Step 11](/Images/Step_7.png)

Then click `Install` to download and install the selected modules on your computer:

![Step 12](/Images/Step_8.png)

Unity is now configured for XR development.

---

## Visual Studio Code Setup

If you are using macOS, `Visual Studio Code` will be downloaded automatically along with Unity. Wait for the installation to finish, then open `Visual Studio Code`.

**For Windows Users**
If you are using Windows, the Unity installation window may include `Microsoft Visual Studio Community` as an optional development tool. We will use Visual Studio Code instead, so uncheck the `Microsoft Visual Studio Community` option. It is a large application and is not required for this setup.

Next, download and install `Visual Studio Code` from the official [Visual Studio Code download page](https://code.visualstudio.com/download).

During the Windows installation, look for the additional options near the end of the setup window. Check `Add to PATH` (or `Add to PATH (requires shell restart)`) so that Visual Studio Code and its command-line tools are added to your computer's PATH environment variable. Then complete the installation.

After installation, open `Visual Studio Code` so you can install the extensions needed for Unity development. Click on the Extensions icon on the left side bar of your Visual Studio Code, and download these extensions one by one -

`C#`,

`C# Dev Kit`,

`.NET Install Tool`,

`.NET Extension Pack`,

`Unity`, and

`Unity Tools`,

Feel free to sign in with your Microsoft or GitHub Id in your Visual Studio Code and "Turn on Syncing", so that you do not have to do the Extension setups in your other computers. They will automatically be synchronized on your Visual Studio Code Editor once you sign in.

Once all of your Extensions are downloaded, you will see that there will be multiple tabs opened up in the editor. Find the tab that shows the C# Dev Kit installation procedure. If you cannot find it, you can also click on File > New Window, and from there you can select the setup procedure for C# Dev Kit which will show up as a link on the right hand side of the window (It will be shown something like - `Get Started with C# Dev Kit`), shown in the picture below.

![C# Dev Kit Set Up Link in Visual Studio Code](/Images/NET%20First%20Page.PNG)

If you cannot see it, please click on the `More` link below (shown in the picture above), and you will be able to see all the links in the newly opened dropdown menu. From there, you can select the `Get Started with C# Dev Kit` link. Once, you select that link, click on `Set up your environment` option (or the option where it will ask you to install .NET SDK), shown in the picture below.

![Link to Install .NET SDK from the C# Dev Kit in Visual Studio Code](/Images/Install%20NET.PNG)

Then click on the button to install .NET SDK. It will open another new tab on the side where you will see another button saying install .NET SDK (shown below).

![Installing .NET SDK Finally](/Images/Install%20NET%202nd.PNG)

Click on it, to install the .NET SDK in your computer. It will install the sdk partially through terminal and partially through set up executable. Once, it is installed, then close the editor. Theoretically, it should set up everything by now. However, I found in one of my computer, turning off my editor was not enough. I had to restart my computer. So, you can restart your computer to install everything properly.

**_NOTE:_**
If you see any pop up shows up in Visual Studio Code at the bottom right corner that asks you to set up C++ library, or set up Git, or set up Cmake, etc., then click on the right buttons to set up Visual Studio Code with the packages and PATH variables properly. For example, if it asks you to set up C/C++ with your Visual Studio Code, and give you two choices, i.e., Yes and No, then click on Yes to set it up properly with the IDE.

**That's it! Unity and Visual Studio Code should now be set up and ready for your Unity projects. Have fun developing! :)**
