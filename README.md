# Asteroid Run
###### A CINEMATIC SEQUENCE OF A SPACESHIP COLLIDING WITH AN ASTEROID

<br><br>

## 1. Project Overview

This project is a training scene in Unreal Engine, created as a background for a virtual production workflow. According to the brief, the scene must include Dynamic Environmental Composition and a Chain of Events with Secondary Consequences that unfold inside the virtual world.

The concept for my contribution is a space environment, where a spaceship travels through an asteroid field. An asteroid (with several smaller debris pieces) appears on its trajectory, leading to a collision event. This impact then triggers a set of secondary dynamic effects.

<img src="https://github.com/user-attachments/assets/28b1012d-eaf3-475b-9fc9-6b028d58c554" width="400" alt="image">

This drawing represents my early storyboard and event-chain concept for the project “spaceship colliding with an asteroid.”

The sketch contains three main components:

 - **Spaceship trajectory.**

>It shows the ship moving forward in one direction and approaching an asteroid field.

 - **Asteroid field.**

> A group of large and small rocks is drawn, moving toward the spaceship. Some of the rocks are intended to bounce off the ship on impact (dynamic environmental composition).

 - **Chain of secondary consequences.**

> After the collision, the main asteroid falls downward (toward a planet surface or deeper into space), while smaller debris pieces scatter around the ship, creating secondary effects-flashes, sparks, and changes in object movement.

An additional note includes a camera goal, indicating the planned cinematic angle to capture the event.

This sketch serves as a visual planning tool for building the event sequence inside Unreal Engine.

## 2.  My Role in the Team

The project was initially planned as a team assignment, but later our group was divided so that each student could complete an individual version of the task. This approach allowed everyone to demonstrate their skills independently, avoid delays, and eliminate shared responsibility issues.

As a result, the teamwork ended at the conceptual stage, and the full implementation of the scene was carried out by me individually.

## 3.  Dynamic Environment Composition
## 4. Chain of Events and Secondary Consequences
## 5. Code and Blueprint Logic
## 6. Issues and Fixes

 - **Difficulties with GitHub**

> One of the tasks was to document the entire project creation process through GitHub. This includes tracking work stages, uploading updates, maintaining version history, and clearly demonstrating how the scene evolved throughout the development period.

I experienced challenges working with GitHub, especially with uploading the project and understanding the repository structure. Some parts are still not fully clear, but I believe that with more practice I will become confident using this tool.

 - **World-building logic and background setup**

> I had issues creating a proper background for the scene. Specifically, I couldn’t set up an HDRI environment or successfully import texture cubes (2D skybox elements) into Unreal Engine. I plan to return to this after completing the main task in order to improve the visual quality of the scene.

 - **Project restart**

> After the lecturer approved an individual approach, I restarted the project from scratch - approximately one week before the submission deadline. This was challenging but helped me better understand the structure and logic of assembling the scene.
> This is one of my early versions of the world layout, created during the initial stage of the project. However, after reviewing the brief and clarifying the requirements, I decided to rebuild the environment from scratch. On December 9th, I started assembling a new version of the project, incorporating the skills and improved understanding I had gained.

&nbsp;&nbsp;&nbsp;&nbsp;<p align="center">
  <img src="https://github.com/user-attachments/assets/8d001dcb-c06d-47d3-b984-25df3c9c8dbc" width="400" alt="image">
  <br>
  <sub><em>Early World Build</em></sub>
</p>

&nbsp;&nbsp;&nbsp;&nbsp;<p align="center">
  <img src="https://github.com/user-attachments/assets/000ef0e2-c461-43af-9b52-433c8bffbdfa" width="400" alt="image">
  <br>
  <sub><em>Early World Build</em></sub>
</p>

- **Report Update - December 10**

> Due to the GitHub issues I mentioned to Michael, I recreated all my changes from today using my detailed step descriptions. I am rebuilding the spaceship Blueprint with the previously created thruster material and setting up a Niagara effect for the engine thrusters.

## 7. What I Learned



# My Intentions & Completed List 
##### December 9

For December 9, Start of Documentation - Plan
> Begin collecting media materials and documenting the first project steps in the README and Trello.

*Result:*
&nbsp;&nbsp;&nbsp;&nbsp;<p align="center">
  <img src="https://github.com/user-attachments/assets/5eb3b23c-443c-45e1-9b11-85f45f3f2b01" width="400" alt="image">
  <br>
  <sub><em>Trello</em></sub>
</p>
&nbsp;&nbsp;&nbsp;&nbsp;<p align="center">
  <img src="https://github.com/user-attachments/assets/699fce20-f586-4361-a812-4adf6c3a999a" width="400" alt="image">
  <br>
  <sub><em>README in GitHub</em></sub>
</p>

______________________________________
##### December 10

For December 10, I planned the following tasks related to the dynamic environment and visual effects:

- **Dynamic Environment Composition - Plan:**
> Set up an animated asteroid field moving toward the spaceship.
> Ensure that the asteroids’ movement and behavior change in real time.

- **Chain of Events and Secondary Consequences - Plan:**
> Configure the collision event between the spaceship and an asteroid.
> Add secondary consequences: debris scattering and trajectory shifts after the impact.

- **Engine Thrusters — Plan:**
> Add engine thrusters to the spaceship.
> Set up a glowing effect and a small particle stream to simulate propulsion.
> Use these effects to enhance realism and highlight the direction of movement.

*Result:*
- I added engine thrusters to the spaceship to create a visual propulsion effect. The thrusters include animated glow and a small particle stream that simulates engine activity during flight. This enhances the realism of the scene and clearly emphasizes the direction of movement.
- The engine thrusters that create the visual propulsion effect are currently implemented using Niagara. However, I am considering reworking them with a different method to improve the visual quality and achieve a more accurate effect.

<img width="400" alt="image" src="https://github.com/user-attachments/assets/dcf4293b-45f4-4150-aba0-bdc782c64aaa" />
<img width="400" alt="image" src="https://github.com/user-attachments/assets/9e851b2c-dbf2-4417-9835-c27ee74ea808" />
<img width="400" alt="scheme material of engine thrusters to the spaceship" src="https://github.com/user-attachments/assets/464c7eee-0b6b-4f2e-8db6-c83edbbbdebe" />
<img width="400" alt="scheme material of engine thrusters to the spaceship" src="https://github.com/user-attachments/assets/71d14976-bd1c-4e10-8d85-3880882bfc1a" />

______________________________________
##### December 11 - Update

Set up an animated asteroid field moving toward the spaceship. Ensure that the asteroids’ movement and behavior change in real time.

- **Dynamic Environment Composition - (addition):**
> I am creating a levitation effect for the asteroids to make their motion look more natural in the space environment.

*Result:*

- I created a levitation effect for the asteroids. Now I am working on limiting their movement so they don’t drift too far outside the scene.
-

<img width="400" alt="scheme material of engine thrusters to the spaceship" src="https://github.com/user-attachments/assets/8f097317-b2ae-4075-af03-5a0721d7fced" />
<img width="400" alt="scheme material of engine thrusters to the spaceship" src="https://github.com/user-attachments/assets/d2366655-64c4-45d2-97d7-116e56709cbe" />

______________________________________
##### December 12 - Update

Set up an animated asteroid field moving toward the spaceship. Ensure that the asteroids’ movement and behavior change in real time.

- **Dynamic Environment Composition - (addition):**
> I am creating movement limits for the asteroid spread. Small asteroids receive a random initial impulse and move independently. On collision, the Event Hit is triggered.
- Two scenarios are planned: when hitting an invisible sphere or a large asteroid, the direction changes (bounce effect); when hitting the spaceship, a special effect is triggered — sound, flash, and fragmentation into smaller pieces.

*Result:*

- All asteroids were dispersing at the same time, so I decided to change the scene logic and switch to a more controlled, cinematic approach.

>
______________________________________
##### December 15 - Update

**Updated Scene Logic - Cinematic Plan**
- The camera is a component inside BP_Spaceship and follows the ship

*Result:*

> <img width="400" alt="scheme material of engine thrusters to the spaceship" src="https://github.com/user-attachments/assets/53ce3135-08d3-41b6-847a-c73ec7331187" />
> <img width="400" alt="scheme material of engine thrusters to the spaceship" src="https://github.com/user-attachments/assets/a3ccc15e-0616-4573-b0c7-4e58260b40db" />

- The large asteroid (BP_BigAsteroid) slowly levitates
- Small asteroids (BP_SmallAsteroid) are manually placed around the large one
- All small asteroids exist within an imaginary sphere around the big asteroid

- The spaceship flies directly toward the large asteroid
  
> The camera represents what the audience sees, so I first establish the cinematic frame and then adjust all other movement and scene logic around it.

*Result:*

> <img width="400" alt="scheme material of engine thrusters to the spaceship" src="https://github.com/user-attachments/assets/7e22dd07-ed27-4b2e-b43e-298e160ecde3" />
> <img width="400" alt="scheme material of engine thrusters to the spaceship" src="https://github.com/user-attachments/assets/20857e09-4bd1-4dc5-87fd-6d876a865fdd" />
> <img width="400" alt="scheme material of engine thrusters to the spaceship" src="https://github.com/user-attachments/assets/9d8054bf-0c7f-404c-8e35-cc1a38e13cfa" />

- Button 1 enables collision mode (small asteroids hit the ship)

> Collisions in the scene are activated by pressing key 1, allowing controlled timing of interactions in a cinematic setup.

*Result:*
> I made a mistake by planning the camera shot to start at game launch while the spaceship was already moving toward the collision. I am now reworking the logic by separating the shooting stages directly inside BP_Spaceship, before the scene on the Big Asteroid.

> <img width="400" alt="scheme material of engine thrusters to the spaceship" src="https://github.com/user-attachments/assets/466a6f1a-907c-47c1-9013-04716ed05f29" />
> <img width="400" alt="scheme material of engine thrusters to the spaceship" src="https://github.com/user-attachments/assets/" />
  
> When the spaceship collides with a small asteroid, I plan to teleport it to a LandingPoint inside BP_BigAsteroid_Landing. At the moment, the teleport works only by world coordinates and does not yet correctly attach the ship to the asteroid surface.

*Result:*
> Despite multiple attempts to implement landing on the asteroid, the teleportation moves the spaceship to an unexpected LandingPoint inside BP_BigAsteroid_Landing, instead of the intended position on the asteroid’s surface.

> <img width="400" alt="scheme material of engine thrusters to the spaceship" src="https://github.com/user-attachments/assets/42ba96fa-5b7b-4981-b8ac-073815efc364" />
> <img width="400" alt="scheme material of engine thrusters to the spaceship" src="https://github.com/user-attachments/assets/a15d2c8c-13db-4f00-b2b5-fe0348e5f697" />
> <img width="400" alt="scheme material of engine thrusters to the spaceship" src="https://github.com/user-attachments/assets/c62fcc0f-6066-4c60-aaa2-7dff24949b71" />


______________________________________
##### January 5 - Update

**Updated Scene Logic - Cinematic Plan**
- teleport

*Result:*
> The teleportation mechanic was successfully implemented. The issue occurred because I was attempting to land the spaceship on a levitating large asteroid, where the landing point could not be calculated correctly due to its continuous movement. To solve this, I created an additional large asteroid in a static state and defined a fixed landing point on it.

> <img width="400" alt="scheme material of engine thrusters to the spaceship" src="https://github.com/user-attachments/assets/39951575-64d1-4069-9d6f-373de8197dce" />
> <img width="400" alt="scheme material of engine thrusters to the spaceship" src="https://github.com/user-attachments/assets/bc840a86-22a1-4f0e-a374-01e62c5379b1" />
> <img width="400" alt="scheme material of engine thrusters to the spaceship" src="https://github.com/user-attachments/assets/dfc05b91-a209-4052-a803-35eca0c27ac0" />
> <img width="400" alt="scheme material of engine thrusters to the spaceship" src="https://github.com/user-attachments/assets/7577be8c-fa76-4494-a539-38cbbe6da2b0" />

> After that, I added a screen fade effect at the moment of impact with the small asteroid and just before the spaceship teleportation, to visually connect the collision and the scene transition.

> <img width="400" alt="scheme material of engine thrusters to the spaceship" src="https://github.com/user-attachments/assets/87eb45c6-10e6-4b4c-aec0-d4d6cead4f48" />



______________________________________
##### January 6 - Building a Static Big Asteroid Scene to Connect Two Assignments (3D Modelling and Asset Creation - Scene Building in Asteroid Run)
**Updated Scene Logic - Cinematic Plan**
- I am connecting two assignments within a single project by developing a static Big Asteroid scene.
After the cinematic collision and landing sequence, the project transitions into an environmental showcase, shifting the focus from movement to environment, lighting, and composition.

In this scene:

1. The spaceship has landed, with smoke coming from it.
2. Astronauts exit the ship and move toward a building ahead.
3. The camera follows them, transitioning from a ship-follow camera to a cinematic scene camera.
4. The camera is planned to move along a curve (Spline) instead of a straight line for smoother cinematic motion.

*Result:*
> The








<img width="400"  alt="image" src="https://github.com/user-attachments/assets/8b364fbb-8bea-48a4-ad07-9567d4733e5f" />
<img width="400" alt="image" src="https://github.com/user-attachments/assets/c5813569-8cc8-43da-a764-bae0402e24d9" />

<img width="400" alt="image" src="https://github.com/user-attachments/assets/bec70ab8-c775-4054-b332-f0f1ba552c57" />



- FX (debris, particles) spawn only on collision and are handled separately

> I did not have enough time to implement additional visual effects using the Post Process Volume. Specifically, I was unable to add enhanced engine exhaust, a glow effect on asteroid impact, and a fog or haze effect on the asteroid surface after landing.

- The main scene is cinematic, not a physical simulation
  
- After landing, the camera does not change - the same camera that initially followed the spaceship continues to be used. It simply captures what is happening from the ship’s landing position, without switching to a different camera or viewpoint.





<br> 
<br>
<hr>
<p align="center">
<sub>© 2025 Yuliia Chervynska</sub> <br>
<sub>Faculty of Film, Art & Creative Technologies. Department of Technology & Psychology</sub><br>
<sub>DL850 BA (Hons) Immersive Media Production</sub><br>
<sub>BA Immersive Media Production 2023-24 / Storytelling Through Media</sub><br>
<sub>3D Modelling and Asset Creation</sub><br>
<sub>Lector - Michael Ó Donnchadha</sub><br>
<sub>Dynamic Responsive Environment for Virtual Production</sub><br>
</p>

