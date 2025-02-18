# [MAIA Mobile AI Assistant](https://github.com/ovidiurosu90/maia-mobile-ai-assistant)

## Important - abandoned
I've abandoned this version of the project, as the current design is impractical and not worth iterating over.
The servo motors are too weak, they break easily, and they're not precise enough for the task at hand.
Even with the smaller version of the arm, the movements are shaky, inconsistent, and quite noisy.

I will explore a new design with different motors on a different chassis.

![MAIA Mobile AI Assistant September 2024 V4 real world disassemble](./Images/MAIA_Mobile_AI_Assistant_September_2024_v4_real_world_disassemble.jpg "MAIA Mobile AI Assistant September 2024 V4 real world disassemble")


## Abstract
### Problem
Interact with people in an unknown environment, and execute simple actions autonomously

### Solution
Mobile AI Assistant that is able to receive voice commands from people, navigate autonomously, and execute simple actions leveraging AI

### How
- the whole project is open-source, and can be replicated by interested parties (note it requires a variety of skills like setting up a web server, conding, 3d printing, soldering & crimping)
- this robot will be mounted on the [3R2 ROS Real Robot v2](https://github.com/ovidiurosu90/3r2-ros-real-robot-v2), in order to navigate autonomously

### Notes
- the project is in early stages, and everything will change along the way (requirements, design, components, etc.)
- at the moment there is no clear end-solution, so a lot of its core capabilities are still to be researched

## Robot potential capabilities
- monitor people and take actions based on their sentiments (e.g. say a joke if I'm sad, or tell me when my girlfriend is upset)
- meet and greet at the door, or in any room of the apartment
- simple voice interaction (e.g. answering what's the temperature outside)
- follow a person inside an apartment and take notes (e.g. for shopping list, or documenting training exercises)


## Important Links

| Name | README |
| --------------------- | ------------- |
| BOM Bill Of Materials | [BOM.md](BOM.md) |


## Images

I've started with a bigger version (longer arms, June 2024), though the lower servo motors were not strong enough to move the arm.

After that attempt, I've created a smaller version (shorter arms, September 2024), which helped, allowing the arm to move.

![MAIA Mobile AI Assistant September 2024 V4 CAD 1](./Images/MAIA_Mobile_AI_Assistant_September_2024_v4_CAD1.jpg "MAIA Mobile AI Assistant September 2024 V4 CAD 1")

![MAIA Mobile AI Assistant September 2024 V4 CAD 2](./Images/MAIA_Mobile_AI_Assistant_September_2024_v4_CAD2.jpg "MAIA Mobile AI Assistant September 2024 V4 CAD 2")

![MAIA Mobile AI Assistant September 2024 V4 Real World 1](./Images/MAIA_Mobile_AI_Assistant_September_2024_v4_real_world_1.jpg "MAIA Mobile AI Assistant September 2024 V4 Real World 1")

![MAIA Mobile AI Assistant September 2024 V4 Real World 2](./Images/MAIA_Mobile_AI_Assistant_September_2024_v4_real_world_2.jpg "MAIA Mobile AI Assistant September 2024 V4 Real World 2")

![MAIA Mobile AI Assistant CAD 2](./Images/MAIA_Mobile_AI_Assistant_June_2024_CAD2.PNG "MAIA Mobile AI Assistant CAD 2")

![MAIA Mobile AI Assistant CAD 1](./Images/MAIA_Mobile_AI_Assistant_June_2024_CAD1.PNG "MAIA Mobile AI Assistant CAD 1")

![MAIA Mobile AI Assistant Real World Partial 1](./Images/MAIA_Mobile_AI_Assistant_June_2024_real_world_partial1.jpg "MAIA Mobile AI Assistant Real World Partial 1")

![NVIDIA Jetson Orin Nano Developer Kit](./Images/NVIDIA_Jetson_Orin_Nano_Developer_Kit.jpg "NVIDIA Jetson Orin Nano Developer Kit")

![Servo motors HS-805BB](./Images/Servo_motors_HS-805BB.jpg "Servo motors HS-805BB")

