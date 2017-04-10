## Project Proposal

### Summary
Currently, the Microsoft HoloLens spatializes sound based only on position relative to the source of the sound. We will raytrace sounds in real space using the Microsoft HoloLens' wall detection to create physically accurate audio.
### Background
Currently, the Microsoft HoloLens utilizes spatial audio to create the illusion that sounds are coming from particular places in the augmented reality environment. However, the HoloLens does not take into account any properties of the room during audio processing. The size and shape of a room can significantly influence sound, and taking these parameters into consideration can improve imersion in an augmented reality environment. 
 
 Our plan is to develop a parallel ray tracing algorithm on the HoloLens GPU, and use it to trace sounds in the augmented reality environment in real time. The HoloLens is already capable of detecting walls in the room by detecting planes, and we will use this information to model size and shape of the room the user is currently in.
 
 +***insert paragraph on how to parallelize ray tracing for a GPU here***

### The Challenge
The graphics card on the HoloLens, referred to as the Holographic Processing Unit (HPU), is proprietary and not easy to interact with directly. Additionally, parallel raytracing is too computationally expensive to include in real time rendering. We will need to make the algorithm run fast enough to keep the hololens operating in real time.
### Resources

### Goals and Deliverables
Finish in time.
### Platform Choice
Microsoft HoloLens
C++/DirectX
### Schedule
