Extend-Windows-7-Trial-Period-Up-To-One-Year
============================================

With a simple registry tweak extend Windows 7 trial period to one year.

If you can not afford the price or want to try Windows 7 before you buy it, you can use the official trial version of Windows 7. Microsoft allows you to download the Windows 7 and use it as 30 days trial version. So, you have the maximum 30 days in hand to use Windows 7. But there is a trick by which you can extend the trial period.

There is a command by which the trial period can be extended up to three months. Each time you run that command, it increases the duration of the trial for the next thirty days. But, this command can be used only three times. So, by this, you can extend the trial period of Windows 7 to maximum 3 months.

After three months, you can also extend the useability of the command with a simple registry tweak and extend Windows 7 trial period to one year.

Below is the method in details for both the Windows 7 32-Bit And 64-bit Version.

## Command Prompt Tricks to Extend Windows 7 Trial Period

* Type ```cmd``` in the Windows 7 start menu search box then right click on ‘Command Prompt’ and chose ‘Run as administrator’. You can also run the command prompt as administrator by typing “cmd” in the start menu search box and then pressing the ```Shift + Ctrl + Enter``` key combination from the keyboard.

![windows-7-command-prompt](https://cloud.githubusercontent.com/assets/139233/4180133/a8ece7a0-36e8-11e4-85c7-bd2fbfe824aa.png)

Note: You may be asked for a password. If so then put it and hit ‘Enter’.

* In the command prompt, type the following command: ```slmgr -rearm```

![windows-7-command](https://cloud.githubusercontent.com/assets/139233/4180134/aef28006-36e8-11e4-84ec-e957378e9c43.png)

* Immediately, the system will prompt for a restart. Restart your computer and check the system status.

Voila! Your trial period has been extended to more 30 days. You can apply this command only three times. So here you can extend your trial period to maximum 90 day.

## Registry Tweak to Extend the Trial Period to more 9 months

There is a registry tweak by which you can increase the boundary of using ```slmgr -rearm``` command. As this tweak is about to edit your registry, I recommend to keep a backup of your registry.

* Type “regedit” in the start menu search box and hit ‘Enter’. The registry editor will open. You may be prompted for permission to access the registry editor.

* Navigate to the following path at the registry editor from the left sidebar.

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\SoftwareProtectionPlatform

* In the right pane, find out the value SkipRearm. Now double-click on it and change the value from 0 to 1. Press ‘OK’.

![windows-7-registry](https://cloud.githubusercontent.com/assets/139233/4180135/b18d6d6c-36e8-11e4-8ced-1f0f5d1fa314.png)

You are done! Now you can apply the slmgr -rearm command for 8 times more. So, you can extend the trial period to extra 240 days.

The total extended trial period is now 120 + 240 = 360 days.

Note: At first, apply slmgr -rearm command for 3 times then apply the registry tweak. After so you will be allowed to apply the command again for extra 8 times. To extend the trial period to exactly 360 days, apply the command in each 30th day of it.
