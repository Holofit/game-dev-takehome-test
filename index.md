## RECREATE THE HUNTABLE SYSTEM

Huntables are objects you can collect by gazing while going through the environment. The objective of this assignment is to recreate the behavior of the Huntable system:

- In order to catch a Huntable, you have to target it long enough using the center point of the camera.
- A Huntable will only be “catchable” when a threshold distance to it is met-when you’re close enough to it. 
- There is a static white circle showing the area where you have to focus your view. 
- When you target a Huntable, a UI element is getting filled. If you get off focus, the filing progress is lost.

Analyse the following gif and list every other aspect of its behavior:
<video loop src="https://user-images.githubusercontent.com/108401755/176420758-575139c2-4394-4887-b59a-dfbadc1b3380.mov" controls="controls" style="max-width: 730px;">
</video>

- Make the fillable circle always visible (even behind objects in the scene)

<video loop src="https://user-images.githubusercontent.com/108401755/178465196-e2a82a82-bd22-42eb-89e4-7f8380e7fa22.mov" controls="controls" style="max-width: 730px;">
</video>

- Place the Huntables at random from a selection of predefined positions.
- Use Gizmos to enlighten all the predefined positions.
- Display the number of Huntables caught compared by number of huntables available (e.g. 1/3)

**Coding requirement:**
- The Huntable class has to inherit from a superclass.
- Implement a state machine for the lifecycle of a Huntable.
- Prepare an event developers can subscribe to when the state changes.
- Use that event.

_Your code will be reviewed, we expect your code to be clean and readable_.

**The final deliverable can be a desktop or VR application (bonus point for the latter)**

### Platform:
Unity 3D

### VR Frameworks:
- [Oculus Integration](https://assetstore.unity.com/packages/tools/integration/oculus-integration-82022#description)
- [Unity XR Interaction Toolkit](https://docs.unity3d.com/Packages/com.unity.xr.interaction.toolkit@0.9/manual/index.html)



