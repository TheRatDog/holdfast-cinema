# holdfast-cinema
All the assets you need for creating your own Cinema in Holdfast: Nations At War

# Requirements
* A Holdfast Server
* Unity & Holdfast SDK (Refer to Holdfast Official Discord)

# Instructions
1. Create an Empty Mod in Unity (Holdfast SDK Tools -> Create Empty Mod)
2. Using the project window, add all folders & files from this repo into your new folder containing 'Readme.txt'
3. Open Cinema.unity
4. Import your video into the 'Video' Folder
5. IMPORTANT - Click on the Video file, and in the Inspector tab transcode your video. Select VP8 as the Codec to ensure cross platform compatibility
6. Drag & drop your video file into the 'Video Player' component's 'Video Clip' field contained on the HDScreen_On Object in the Hierarchy
7.  (Temporary Step) - Click on the Play button, scroll down to the Material in the Inspector and from the textures folder drag ‘Play_CL_Play_Diffuse’ onto Base Map and ‘Play_CL_Play_Normal’ onto the Normal Map
8.  Make any other modifications as you please, then use the Holdfast SDK Tools to Build & Upload your Cinema to the Steam Workshop
9.  Install your mod via your server config & load into an Army Battlefield Map Rotation running modmap

# FAQ
- My video is too bright/dark!
Adjust the smoothness slider of the HDScreen_On material.

- Why can I see the video but my Linux friend can't?
You need to transcode your video and select VP8 as the Codec. Refer to step 5.

- Why is my play button missing materials?
Refer to Step 7, or Issue #1.

- I can't build my mod!
Check the console tab on Unity and try to rectify the errors.

- I can't upload my mod!
Ensure you have Steam open before opening your Unity project.
