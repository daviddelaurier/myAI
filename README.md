![myAI](https://i.imgur.com/GXpjcgB.png)

# Cameras and Microphones Are All You Need

## WARNING

I believe that AI systems must be fully integrated into your environment to truly enhance its users. 
This causes issues when building ML and LLMs into products because you must violate all privacy of the user.

Realizing this, I have decided to build it myself. Anyone is welcome to try this for themselves obviously, but dont come crying to me when your entire life is used as training data for GPT-5. 

USE AT YOUR OWN RISK!

## Initial Implementations (more to come)

1. Business desk:
   - Monitor my actions and progress on business paperwork, such as taxes and payroll.
   - Keep track of what I was previously working on because I never remember and no app exists that does this well.

2. 3D printer:
   - Natural language to 3d printed object.
   - Monitor the success or failure of prints to keep track of my 3D printing progress.

3. Pen plotting robot:
   - Natural language to SVG text/image that is routed to the robot.
   - Ask my AI write personalized thank you letters to clients using the pen plotter.
   - Ask my AI to create drawing mockups for new project ideas I am working on.

4. Coffee pot:
   - Monitor my coffee consumption and the amount of coffee left in the pot.
   - Tell when to make more coffee based on consumption averages over time.

5. Office kitchen:
   - Monitor the contents of my refrigerator and tell me what to make based on available ingredients, previous meals, and expiration dates.
   - Tell me when it's time to load the dishes into the dishwasher.
   - Tell me when the dishwasher cycle is complete.

6. Backyard and parking area:
   - Monitor my two dogs' activities to ensure their well-being and safety.
   - Track both of my vehicle usages for maintenance and scheduling.
   - Tell me to take the trash out on the designated day and time.
   - Tell me if someone other than me or my wife are in the backyard or parking area.

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
- Scheduling and reminder system via screencapture/VLM request of all datastreams I am interested in.

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
- [x] Setup media storage system
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
