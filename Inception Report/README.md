# Inception Report

## Aims & Background Material

Develop a system which utilizes the camera on the Baxter/iCub in order to recognize and track people and objects in the robot Field of View ( FOV ). Using the information gathered on the objects/people, system should be able to label and track the labeled objects as they move around the scene.

The next part of the project involves modelling the real world in the scene, perhaps using Markov Logic Networks, in order to make inferences about the real world based on who is being tracked and what the robot has seen that person do before. For instance, if a person often comes close to the robot, the robot will understand that with the direction and present velocity of the person being tracked, it should be more careful with the movement of its arms. Or perhaps the robot could indicate to the wearer of the headset that it is aware that this person may come closer soon.

For the augmented reality aspect, provide the user wearing the Hololens with a display that presents information, such as which objects are being tracked, the label assigned to the object, whether the object can be reached by the robot. Also communicate to the wearer the next state the robot predicts it will be in, for instance, after it is asked to 'pick up an object', the robot will infer from past actions the movement of the arm, the direction, and communicate to the wearer the final position of the arm.

I would like to make this project more Computer Vision and Machine Learning/Inference based as opposed to Augmented Reality. The augmented reality part acts as a supplement, a way to display to the user the underlying thoughts and actions of the robot.

## Student Summary of Project Deliverables, Fallbacks & Extensions

### Person and Object Detection

Core to the project, computer vision aspect. Very important to implement at least the person and object tracking, since this is what i am mainly interested in.

### Scene Modelling

Depending on how well the person and object detection is done, as well as my understanding of MLNs and other machine learning/ai techniques, this part is up for debate.

### Augmented Reality Display

As per the title of the project, there has to be some augmented reality. Mainly used to display machine state.

## Summary of Risks

Unable to understand MLNs enough in order to implement scene modelling. Will require a lot of research, as well as taking modules in EE and DoC that are heavily machine learning based.