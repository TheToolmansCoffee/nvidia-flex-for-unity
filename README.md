# nvidia-flex-for-unity

An unofficial reposity for the NVIDIA Flex plugin/demo(s) for Unity.

NVIDIA Flex is a bunch of physics systems built for Unity by NVIDIA.

My own notes:
Seems to work with even non-NVIDIA based devices (Intel, AMD, and so on). I wouldn't suggest trying to build for mobile or older devices though, as Flex seems to be pretty heavy on performance. It also seems to work with even the newest versions (2021 LTS, 2022.1, etc), though I'm not sure if it works properly on HDRP or URP, as I personally could only get a stable FPS when running it on the built-in pipeline, as I'm using a lower-end PC. You might get a few compiler errors in newer versions of Unity, but you can fix them by just deleting the mentioned scripts in the errors and it should work still fine.

**INSTRUCTIONS:**

1. Download the reposity as a .zip file, and extract it once you're done downloading.

2. Open your Unity project, and drop the following files in to your asset folder; Actors, Assets, Auxiliary, Editor, Helpers, Native, & Resources.

3. (optional) Drop the Flex Samples folder to your assets folder if you want to experiment with already created examples.

*NOTE:* If you already have an Editor folder in your project, open the folder before importing and only import the following folders; Editors & Tests to your existing Unity Editor folder. 

You also can't have two folders with the same name, so if you already have a folder in-engine with the same name as any of the mentioned folders, rename the existing ones or the ones that you're importing.

Here is the water example that is included in the rep:

![water](https://user-images.githubusercontent.com/93699568/188477181-37c8c481-db9d-498a-aebd-9653e17650d8.png)

Here is the solid actor example:

![solidactor](https://user-images.githubusercontent.com/93699568/188478419-27d0f037-5117-479c-ac3e-1c2be162d2d7.png)

Examples included are: 

![examples](https://user-images.githubusercontent.com/93699568/188478941-2aac84aa-6b99-4b02-b780-ca438446eb13.PNG)

WORKS ONLY WITH UNITY - THIS IS THE UNITY VERSION OF NVIDIA FLEX

It has come to my attention as of recently, that an unspecified company that may or may not include Open & AI in it's name sent an Cease and Desist letter to a fellow educational reposity's creator, so I have the joy of presenting you with a brand new legal notice to avoid quick triggerfingers from the legal departments of huge greedy companies;

**LEGAL DISCLAIMER:**

I am not saying that I own Flex, or the rights to it, nor the rights to distribute it. All the content in this reposity, excluding the screenshots of course, are owned by NVIDIA. This entire reposity is for EDUCATIONAL USE ONLY, and in no way or form is this supposed to be an endorsement for illegal use, such as piracy of this package. 

[The license in this reposity was taken from the official NVIDIA reposity for the downloadable Flex demo]

THIS IS ONLY FOR RESEARCH, EDUCATIONAL AND TESTING PURPOSES.
## *USING THIS PACKAGE FOR ANY SORT OF COMMERCIAL PROJECT MAY BREAK NVIDIA'S LICENSING TERMS
