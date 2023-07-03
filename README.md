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
6. The keywords for the background is used as input prompt for DALL-E model which generates the background image for each scene.
7. The stable diffusion model is fine tuned with the new character illustration that controlnet generated.
8.   
9. 
<br> 

## Tech Stack

| SpringBoot | Flutter       | DreamBooth |  stable diffusion  | contronet | 
| :--------: | :-----------: | :--------: | :----------------: | :-------: |

![image](https://github.com/I-GRIM/.github/assets/57697721/bbdc7d46-e330-46be-ab58-7a208dc87fc1)

<br><br>
