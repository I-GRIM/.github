# IGRIM

## Introduction
IGRIM is an application that turns childrens's drwaings and story content into a beutiful storybook using stable diffusion and dreambooth model.

## User Process
1. User draws character image
![image](https://github.com/I-GRIM/.github/assets/57697721/08c4ff28-229e-4dea-a980-33ec4e52c267)
2. The user drwan image is given as an input to the controlnet. ContorlNet turns the user drawn character into fairy tale like illustration.
![image](https://github.com/I-GRIM/.github/assets/57697721/0e8f6808-a94f-4267-b51d-da92834b240d)
3. User writes story for each scene
4. Keywords about the character (happy, sad, running, jumping, ...) are extracted from the story using chat gpt api.
5. Keywords about the background (rainny, in the forest, ...) are extracted from the story unsing chat gpt.
6. The keywords for the background are used as input prompt for DALL-E model which generates the background image for each scene.
7. The stable diffusion model is fine tuned with the new character illustration that controlnet generated using dreambooth.
8. The kewords for the character are used as input prompt for the fine tuned stable diffusion model.
9. The character and the background images are merged toghether!
![image](https://github.com/I-GRIM/.github/assets/57697721/f856780b-a36f-4e1f-a61e-1444ed3256b6)
![image](https://github.com/I-GRIM/.github/assets/57697721/b5c78f43-d7fd-4848-bd51-d501580df0b3)
![image](https://github.com/I-GRIM/.github/assets/57697721/a99f00af-4843-40bf-aa94-414dbf864de6)
![image](https://github.com/I-GRIM/.github/assets/57697721/8d8adda8-6405-47d9-860c-029780f66d0d)
![image](https://github.com/I-GRIM/.github/assets/57697721/f5b839e3-de39-497c-ac9a-8ba0b7613078)

<br> 

## Tech Stack

| SpringBoot |    Flutter    | DreamBooth |  Stable diffusion  | Contronet | OpenCV | 
| :--------: | :-----------: | :--------: | :----------------: | :-------: | :----: |

![image](https://github.com/I-GRIM/.github/assets/57697721/bbdc7d46-e330-46be-ab58-7a208dc87fc1)

<br><br>
