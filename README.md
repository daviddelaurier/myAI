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

## Expanded Uses and Long-term Analysis

myAI's capabilities extend beyond daily tasks and can provide valuable insights through long-term data analysis. By continuously monitoring various aspects of your life and work, myAI can identify patterns, optimize processes, and help you make informed decisions. Some expanded uses include:

1. **Productivity Analysis**
   - Track the time spent on different tasks and projects
   - Identify productivity patterns and suggest improvements
   - Monitor progress towards long-term goals and deadlines

2. **3D Printing Optimization**
   - Analyze the success rate of prints over time
   - Identify common issues and suggest preventive measures
   - Optimize print settings based on historical data

3. **Pen Plotting Art Evolution**
   - Track the progression of your pen plotting art style
   - Identify popular designs and themes based on client feedback
   - Suggest new design ideas based on previous successful projects

4. **Coffee Consumption Insights**
   - Analyze coffee consumption patterns over time
   - Identify factors influencing coffee intake (e.g., workload, stress)
   - Suggest optimal coffee consumption for productivity and well-being

5. **Kitchen Inventory Management**
   - Track the usage of ingredients over time
   - Predict when certain items will run out and suggest restocking
   - Identify rarely used items and suggest recipes to minimize waste

6. **Pet Behavior Analysis**
   - Monitor changes in your dogs' behavior and activity levels
   - Identify potential health issues or behavioral changes
   - Suggest adjustments to pet care routines based on insights

7. **Vehicle Maintenance Scheduling**
   - Track vehicle usage and maintenance history
   - Predict when certain maintenance tasks will be required
   - Suggest optimal times for scheduling maintenance appointments

## Roadmap

### Phase 1: Setup and Integration
- [x] Install cameras, microphones, and sensors in designated areas
- [x] Connect 3D printer and pen plotting robot to the system
- [x] Integrate object detection and tracking model
- [x] Implement text-to-3D model conversion system
- [x] Set up natural language processing for request understanding and response generation
- [ ] Configure robotic control system for pen plotting robot
- [ ] Customize scheduling and reminder systems

### Phase 2: Basic Functionality
- [ ] Implement business desk monitoring and task tracking
- [ ] Enable 3D printer control and print monitoring
- [ ] Develop pen plotting robot control and letter writing functionality
- [ ] Set up coffee pot monitoring and consumption tracking
- [ ] Implement office kitchen monitoring and recipe suggestion
- [ ] Enable backyard and parking area surveillance and reminders

### Phase 3: Advanced Features and Analysis
- [ ] Implement productivity analysis and insights
- [ ] Develop 3D printing optimization based on historical data
- [ ] Track pen plotting art evolution and suggest new design ideas
- [ ] Provide coffee consumption insights and recommendations
- [ ] Enable kitchen inventory management and waste reduction
- [ ] Implement pet behavior analysis and care suggestions
- [ ] Set up vehicle maintenance scheduling and predictions

### Phase 4: Refinement and Expansion
- [ ] Refine AI models based on user feedback and collected data
- [ ] Expand myAI's capabilities to cover additional areas of daily life and work
- [ ] Integrate with external services and APIs for enhanced functionality
- [ ] Develop a user-friendly interface for interacting with myAI
- [ ] Implement security measures to protect user data and privacy

### Phase 5: Testing and Deployment
- [ ] Conduct thorough testing of all features and integrations
- [ ] Resolve any bugs or issues identified during testing
- [ ] Optimize performance and resource usage
- [ ] Prepare documentation and user guides
- [ ] Deploy myAI to your personal environment
- [ ] Monitor performance and gather feedback for future improvements
