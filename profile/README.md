![Header](https://github.com/cyubeVR-Modding/.github/blob/1ac0eced9e05cb5cfa5127d687684bf39a0aff9b/profile/modding%20banner.png "Header")

# cyubeVR Modding Overview

cyubeVR supports **three different types of modding**, each requiring different skills, and best suited for different types of mods. Here you can find an overview of those three types of modding.

## Custom Blocks

Custom blocks are the simplest type of modding you can do in cyubeVR - creating blocks with custom textures and custom recipes, that can be used the same like any other block in the game. 

Making a custom block is very easy, it requires no programming at all. If you know how to use any image editing software, you can create a custom block! 

[The guide for how to create custom blocks can be found here.](https://steamcommunity.com/app/619500/discussions/3/1640917625019543783/)

## VoxelAPI Modding

cyubeVR has a native modding API, called the VoxelAPI. It is an easy to use API for interacting with the voxel world in cyubeVR. Placing blocks, removing blocks, teleporting the player to some location, damaging/healing the player, any similar things. With the VoxelAPI, you can easily create any mod that is "block based". Want to generate custom ores in the ground? VoxelAPI! Want to procedurally generate a whole castle when the player places one block? VoxelAPI! Want to create a minigame with blocks that spawn around the player? VoxelAPI! 

To create a VoxelAPI mod, knowing how to create custom blocks is very useful, most VoxelAPI mods will also contain one or multiple custom blocks. To create VoxelAPI mods, you should know at least some programming - which programming language you know isn't too important and importantly, you do not need to know how any game engine works. As long as you know the basic concepts of programming, you will be able to create a VoxelAPI mod, it's all designed to be very easy to understand.

[Here you can find the repository for the VoxelAPI, where everything about it is nicely explained in the Readme.](https://github.com/sbsce/cyubeVR-VoxelAPI-Modding)

## Unreal Engine 4 Blueprint Modding

Unreal Engine 4 Blueprint (UE4 BP) Modding is the most powerful type of modding supported in cyubeVR. With UE4 BP Modding, you can create basically *anything* that you can make in UE4 and make it work inside of cyubeVR! Want to spawn your own enemies into the game? UE4 BP Mod! Want to make the deer play a nuclear explosion instead of the normal fireworks when they explode? UE4 BP Mod! Want to add driveable tanks into cyubeVR? UE4 BP Mod!

UE4 Modding is very powerful, but requires you to need to know at least the basics of how to use Unreal Engine 4, the game engine that cyubeVR is made with. UE4 BP Modding can also be combined with VoxelAPI modding - for example, you can make a VoxelAPI Mod spawn a particle effect or a sound effect from a UE4 BP Mod.

[Here you can find a YouTube playlist that explains how to get started with UE4 BP Modding in cyubeVR.](https://www.youtube.com/watch?v=MvVLacyToX0&list=PL6kr-0TUTN58n8QrQoFVq4JI-HZj4eDbY&index=1)
