# How to upload a mod to the cyubeVR Steam Workshop

After you've made your mod, you probably want to upload it to the [Steam Workshop of the game](https://steamcommunity.com/app/619500/workshop/). 

This description applies to both **VoxelAPI Mods**, and **UE4 BP Mods**. This description does **not** apply to mods that are purely custom blocks without any code. Pure custom blocks use a simpler setup, as described in the [guide about how to make custom blocks](https://steamcommunity.com/app/619500/discussions/3/1640917625019543783/).

Assuming your mod loads correctly in the game, you can be sure that the folder structure for your mod already is correct. If your mod does not yet load correctly in the game, go back and make sure it does before continuing with this guide. Only mods that are correctly loaded by the game can get uploaded to the Steam Workshop.

After you have your mod working, there are only two additional steps required for a mod to be able to get uploaded to the Steam Workshop:

## The ModProperties.json

There needs to be a `ModProperties.json` file in your mod folder (the folder in `[GameInstallDirectory]/cyubeVR/Mods/ModFolders/`) that contains these two strings:

```
{    
    "DisplayName": "My Great Mod Name",
    "InternalUniqueName": "MyGreatModUniqueNameThatNeverChanges"
}
```

The `DisplayName` is the name of the mod that will be visible on the Steam Workshop, and the `InternalUniqueName` is a unique name that you can't ever change any more after it has been uploaded to the workshop. Changing that `InternalUniqueName` would make it impossible to update the mod on the workshop because Steam would instead think it is a completely new mod. So this setup exists to make it possible to update the mod with a different `Display Name` if required.

[Here you can find a real world example of a ModProperties.json file.](https://github.com/sbsce/cyubeVR-VoxelAPI-Modding/blob/main/Examples/Simple%20House%20Generator/ModProperties.json)

## The Preview Image

Inside of the `[GameInstallDirectory]/cyubeVR/Mods/ModFolders/ModName/Update X/` folder you need a `PreviewImage.jpg` file. That should be a roughly 1024x1024 preview image in JPG format, and it **has to be** below 1 MB in size. That image is what will be visible in the Steam Workshop as the preview image of your mod.

[Here you can find a real world example of a PreviewImage.jpg file.](https://github.com/sbsce/cyubeVR-VoxelAPI-Modding/blob/main/Examples/Simple%20House%20Generator/Update%2051/PreviewImage.jpg)

## Pressing the button

After you have set up everything as described above, your mod is ready to be uploaded to the Steam Workshop! Just launch the game, and in the main menu, click on the "Manage Mods" button. You will see a list of all locally installed mods, with a "Publish to Steam Workshop" button next to them. Just press that button, wait a few seconds, and that's it! Your mod is available on the Steam Workshop of the game. Now the only thing left for you is to visit the Steam Workshop in your Steam client or Browser and fill in a nice description of your mod, and maybe some more screenshots or videos.
