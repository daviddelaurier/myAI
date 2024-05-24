# myAI
Cameras and Microphones Are All You Need

## WARNING

I believe that AI systems must be fully integrated into your environment to truly enhance its users. 
This causes issues when building ML and LLMs into products because you must violate all privacy of the user.

Realizing this, I have decided to build it myself. Anyone is welcome to use my R&D, but dont come crying to me when your entire life is somehow leaked online. 

USE AT YOUR OWN RISK!

## Overview

- Step 1: Mount cameras and microphones in all rooms you regularly use at your home or office.
- Step 2: Connect all input devices to your machine using OBS (or whatever you prefer).
- Step 3: Record/Stream to your machine.
- Step 4: Ask questions about events in any room in your house.
- ?

## Initial Implementations (more to come)

1. Business desk:
   - Monitor your actions and progress on business paperwork, such as taxes and payroll.
   - Help you keep track of what you were previously working on to ensure continuity and efficiency.

2. 3D printer:
   - Implement a text-to-3D model file system that allows you to ask the AI to create objects for you.
   - Monitor the success or failure of prints to keep track of your 3D printing progress.

3. Pen plotting robot:
   - Route LLM/AI output to the robot, enabling the AI to control it for various tasks.
   - Have the AI write thank you letters to your clients using the pen plotter.
   - Allow the AI to create drawing mockups for new project ideas you are working on.

4. Coffee pot:
   - Monitor your coffee consumption and the amount of coffee left in the pot.
   - Suggest when to make more coffee based on your consumption averages over time.

5. Office kitchen:
   - Monitor the contents of your refrigerator and suggest recipes based on available ingredients.
   - Alert you when it's time to load the dishes into the dishwasher.
   - Notify you when the dishwasher cycle is complete.

6. Backyard and parking area:
   - Monitor your dogs' activities to ensure their well-being and safety.
   - Track your vehicle usage for maintenance and scheduling purposes.
   - Remind you to take the trash out on the designated day and time.

## Stack

### moondream
- Object detection and tracking (for monitoring the 3D printer, coffee pot, refrigerator, dogs, and vehicles)

### lume AI (?)
- Text-to-3D model conversion

### Groq
- Natural language processing for understanding your requests and generating appropriate responses

### ???
- Robotic control for the pen plotting robot

### OBS Overlays (dont need API's...)
- Scheduling and reminder system

