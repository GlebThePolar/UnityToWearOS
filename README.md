# Hi! I'm Gleb. This asset helps you build your Unity game for Wear OS devices. 

Pls see my tutorial on YouTube first, so I don't need to explain some things twice: https://youtu.be/GaChUiAyLo0

## Technical description:
You can find files in the Assets/Plugins/Android folder. There are 2 templates, one to build for WearOS, and one to build back to Android. Don't forget to adjust templates if you need (e.g. add your AD_ID) and remove prefixes when you use it. Also, there is a .aar file (aka "magic file”) that can prevent closing your game on a right swipe (place it near your manifest). If you don't need it, then make sure you remove the corresponding string in the Wear OS manifest template.

Also, I shared some images that can help you during the porting (developing) on Wear OS — it's a round mask to make UI adjustments easier, and a template for a splash screen.
Detailed steps:
An example of how you can use this asset.

## For WearOS:
Download and copy files "GlebFixRightSwipe.aar” and "WearOS_AndroidManifest.xml” from the Github folder Plugins/Android/ to your folder Plugins/Android.
Rename WearOS_AndroidManifest.xml to AndroidManifest.xml (or merge it with yours).

## For switching back to Android:
Remove GlebFixRightSwipe.aar from your folder Plugins/Android/, and replace your manifest with Android_AndroidManifest.xml from the Github folder Plugins/Android (don't forget to rename it to AndroidManifest.xml).

If you want to use my round mask (find one in Images/ ), then create a panel on your Canvas, replace the image with my round mask and disable the raycast target.
After you finish adjusting the UI, don't forget to disable the mask!

## My Story:
In general, I made this asset when I was porting my Unity game (Recycling: 2048) from Android to WearOS. The game is built on Unity 5, so let me know if I need to adjust it to Unity 6 (write at gleb@glebthepolarcitizen.com). 

In case you like this free asset, and want to support me, check my buymeacoffee: https://buymeacoffee.com/thepolarcitizen

And if you want to contact me write an email: gleb@glebthepolarcitizen.com

### Additional legal notes:
This is the GitHub version of this tool, which is distributed under MIT license. There is another source, Unity Asset Store version, that has another license (Unity Asset Store EULA): https://assetstore.unity.com/packages/slug/321835.

This tool is not affiliated with or endorsed by Google LLC or Unity Technologies. "Wear OS” and "Unity” are trademarks of their respective owners.
