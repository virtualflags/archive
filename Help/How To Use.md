---
title: How To Use
icon: devices
---

## :icon-question: Bloxstrap How to Use:
1. **Open** the **[Bloxstrap Menu](https://github.com/pizzaboxer/bloxstrap)**.
2. **Navigate** to `Fast Flags` >> `Fast Flags Editor` >> `Add New` >>  `Import Json`.
3. **Paste** in the **JSON**.
4. **Save** and your good to go!

## :icon-question: Normal Roblox Bootstrapper How to Use:
###### You can also do Roblox Studio
1. **Navigate** to your **Roblox Installation directory**. Typically found at `%localappdata%\Roblox\Versions\` or `C:\Program Files (x86)\Roblox\Versions`.
2. **Identify** the folder `version-xxxxxxxxxxxxxxxx` ~~containing `RobloxPlayerBeta.exe`~~ **You can do this for Roblox Studio too.**
3. **Create a new folder named `ClientSettings`. Inside this folder, **add** a file `ClientAppSettings.json`.**
4. **Paste** the **JSON** into `ClientAppSettings.json`. (**You can utilize ChatGPT to format multiple JSONs for clarity if needed**)
5. **Save** and you're good to go!
###### Do note that after roblox updates you have to do this process again

[Watch a Video Tutorial](https://streamable.com/rk5an6)

## :icon-question: Android Rootless Roblox (MT Manager) How to Use:
> [!CAUTION]
> Roblox is implementing anti-tamper measures on mobile. Proceed at your own risk.

1. **Download a Roblox APK** file from a trusted source. 
2. **Open MT Manager** and navigate to the **Roblox APK** file.
3. Tap on the APK and select **View**. `/assets` >> `main.1.com.roblox.client.obb` and click on it then **Archive Viewer**.
4. Create a new folder named **`ClientSettings`**.
5. Place your **`ClientAppSettings.json`** file inside the `ClientSettings` folder. (You can use ChatGPT to help format JSON files for clarity if needed)
6. Tap on the back button (`..`) to exit the archive. It will prompt you to update the file `main.1.com.roblox.client.obb`—click **OK**.
7. Long-press the **Roblox APK** file, choose **Sign File**, and click **OK** with default settings.
8. **Install the modified APK.**
###### This process must be repeated whenever a new Roblox build is released, as the modifications will not carry over to new updates.

## :icon-question: How to Use _PlaceFilter
1. **Add** `_PlaceFilter` **after** the **Fast Flag name**.
2. **Add** a **semicolon after** the Value (`;`). **Examples**: `True;`, `1;`.
3. **Include** a **Place ID after** the **semicolon**. **Examples**: `True;4483381587`, `1;4483381587`.
4. Your configuration is **complete**!**
