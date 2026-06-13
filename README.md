# CPT-project-comp-eng
This repo includes a readme.md file, an images file and a source code file
## Design
### What the robot needs to do
The robot should turn away from the edges of the arena, otherwise drive forward/swerve. Edge detection will be primarily used to turn away from the edges and middle of the arena. Once the robot detects an edge, it will initially start moving backwards, and then turn just enough to detect another edge. This design is primarily achieved through a photoresistor on the front of the robot with a LED. Our robot acts as a “speed bump”, essentially allowing it to go under opposing robots. Hopefully, this will allow the robot to stand it’s ground without being pushed/displaced. 

### Success Criteria
| Requirement | How you tested it | PAss condition |
| :--- | :---: | ---: |
| Must be able to distinguish between black and white | By putting the bot in the arena | Changes phases when robot touches the black line consistently |
| Make sure everything works correctly and according to the plan. | Test every single movement state separately.  | Must stay in the arena for 1+ min  |

### System architechture
![Alt text here](Images/design.png)

### Circuit design
![Alt text here](Images/Circuit.png)

### Physical Layout
Add image for adrian here

## Build

### Chassis
### Wiring
### Decisions made during the build
### Callibration
## Code
### Project structure
### [Name this section after the algorithm, e.g. Edge Detection]

### [Name this section after the next key algorithm, e.g. Main Loop]

### GPIO Cleanup

## Competition & Reflection

### Results

### What worked

### What failed

### Next iteration

