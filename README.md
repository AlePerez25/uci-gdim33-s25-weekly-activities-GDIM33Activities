# GDIM 33 In-Class Activities
## W1
### Activity 1
1. [Inspiration Board](https://pin.it/6Y1FlTtbe)
2. Questions:
    - I notice that my inspiration images feature many gameplay concepts involving chases and puzzles. Consequently, I am leaning more toward the idea of ​​a 3D horror game, as I would like to learn how to design and implement a chase sequence—specifically, one where a monster pursues the player—within a setting characterized by confined spaces, low lighting, jarring sound effects, and similar elements. Most of my reference images are quite macabre, and I would like to harness this atmosphere for my game. I envision a setting resembling a laboratory, where the player can interact with the environment until, at a certain point, they are attacked by a grotesque, deformed creature. Alternatively—to offer another example—the game could center on a player spending a weekend camping, gathering supplies to survive the night, only to be forced to fend off attacking monsters once darkness falls, much like in the movie "The Blair Witch Project".

    - Each of us has a distinct concept, yet we all aim to incorporate a plot twist; for instance, one friend plans to create a novel game with feminist themes, while another intends to develop a simulation game, and so on. Although diverse, all of these ideas appear promising.

    - After discussing this with our LA, it seems he is quite fond of the concept; he recommended that we employ the "Blue Sky" brainstorming technique to identify the specific elements that would best serve our project. Our LA also reviewed my concept, noting that the accompanying reference images were visually compelling.

### Activity 2
- Break-down:
<img width="1356" height="1129" alt="Screenshot 2026-04-01 191719" src="https://github.com/user-attachments/assets/d9005dfe-9696-4cbc-b0bb-63fb649d31fe" />


## W3

### Activity 1

- Break-Down:
<img width="1512" height="1130" alt="Screenshot 2026-04-15 194411" src="https://github.com/user-attachments/assets/8d6c550b-4bda-4226-914e-fcaeed80bd0c" />

### Activity 2

- Question 1:
    - Saving it as a Scene variable causes it to be accessible for any graph, because being a Scene variable makes it a global variable, compared to an Object variable which is not very accessible.

- Question 2:
    - Definitely, using Debug.Log() strings helped me a lot. I had many errors and confusions when attaching the nodes, and when I saw that the messages were not showing, it made me go back and experiment to see what I was missing until they finally appeared. In all the areas where the activity told us to add a debug, they didn’t work until after many changes and attempts.

- Question 3:
    - Definitely, this is related to my vertical slice. I have been trying to implement Set Cursor Lock for the past two days, and I wasn’t able to find a way to connect the nodes correctly. Seeing that this was our activity for the week made me very happy, and I focused on learning more so I can do it in my own project.

- Question 4:
    - I’m not completely sure. I don’t know if it would be better for my vertical slice if the player can click on objects directly, or if I should make it so interactions happen by locking the cursor in the center of the screen and using it that way.

## W4
### Activity 1

- Playtesting notes:

    - Game:

    The player moves using WASD. There is a lamp that can be toggled on and off, and a monster (NPC) that wanders across the terrain to random points; when the player approaches, it begins to chase them.

    - Questions:

    Is the monster actually scary? Do its movements feel natural when chasing the player? Is it too slow?
    How does the camera sensitivity feel?
    Does the lamp feel right? Is it confusing?

    - Feedback:

    The monster currently lacks animations, so it isn't as scary as it ought to be; however, I will work on this as quickly as possible. If the monster still fails to be frightening, I will look for an asset that is compatible and works better. I was advised to extend the detection radius so the monster spots the player sooner; otherwise, it simply appears right in front of you, leaving the player no time to run. I also received a recommendation to adjust the monster's speed.

    I was given feedback that both the camera and the flashlight feel good.

## Activity 2

1) Personally, I think yes, since the programmer would only need to keep creating Scriptable Objects and adding them to the list so it can continue, and since the main code that changes displays them is already there, I don’t think more code would be needed.

2) As far as I know, there isn’t an exact limit because there is no limit to creating Scriptable Objects or to the size of a list. But if the dialogue becomes very complex, from what I understand the writer would have to use some other system to have better visualization and flow, which can later be connected to Unity.

3) Its purpose is to generate its information and update itself accordingly; for example, when we create a custom event. Unity only updates when a class inherits from MonoBehaviour and Scriptable Object.

## W5

### Activity 1

Scriptable objects: Create inventory for mushrooms.

Big Steps:
- Create C# script to be able to create ScriptableObject and modify information.
- Create a C# script to connect PickUp(I already created this system) script and UI inventory using singleton?. 

Small Steps: 

- Create the Scriptable objects including prefab and name to be easy to identify in the future. If I’m able to add the information that a ask for in the script then it works 
- Create the canvas UI. I would build in and run my project to see if the UI is aligned with the screen correctly.
- Find a way to connect this IU to the inventory script. Maybe by using singletons to connect script and UI. I would see if by clicking on the items the image shows if not I would add a debug.log(“here”) to the connection method/singleton and see if the problem is in my script or in canva. 
- Find a way to create the note for the player to display in the UI but by clicking a button being able to open it so the player can see the information any time they need it. For this one I would also add a debug.log to see it by pressing the keyword this message comes out.
- Create a method to identify the scriptable objects by name. In that way I can manage when to end the game. I can add a debug.log(“Quess complete”) to let me know if this method is working correctly.
Create a particle effect to make the mushrooms glow in the dark and find a way to make them still difficult to find. I would be able to see if my particle system is working or not in the Scene.

### Activity 2

For today's class I was able to create the Scriptable objects C# script and I was able to fill in the necessary information. Also I created my prefabs and I started to create my manager inventory script using singleton. 
 
## W6

### Activity 1
- Testers:
    - Kai
    - Laura
    - TA

- Playtesting Goal:
    - How does the inventory feel?
    - It was very difficult to find the mushroom?
    - Should I add more than one monster?
    - Are the instruction difficult to understand

- Notes:
    - The TA and my playtesting partners let me know that my game was really good and interesting. They let me know that I definitely need a better instruction paper and idea of the game. They tell me that the inventory was smooth and well implemented. I ask about adding more monsters because the space is too big and it is difficult to find the monster around the forest. The TA also recommended that I create a way to show the monster by making damage to the player like red around the screen or something like that which I think is a great idea. 

### Activity 2

- Questions:
    1) As I understand it, when you multiply them, the intensity increases because the RGB values—which are responsible for creating the pixel's color—are being multiplied; and when these values ​​are multiplied, the intensity goes up.
    2) This will cause it to appear more translucent, because the alpha is responsible for managing pixel transparency; consequently, when it is added in the graph, the object's translucency will be reflected.
    3) From what I understood in the exercise, the shader gets these UV values ​​from the UV Map of the Shiba that we added to our material.
    4) I find this very interesting. I hadn't imagined that it would be necessary to create textures and manipulate colors, but I can understand it, and I can see why it is necessary.


## W7

- Questions: 

    1) The data for the Vertex Color node comes from the mesh of the original 3D model.

    2) Because each of these vertices, with their specific colors, blends based on the distance of each one.

    3) Because it lacks texture, it creates a solid visual effect without excessive detail. This allows us to spot errors in the mesh—such as the one visible in the dog from the activity—that were made by our artist.

    4) If I am observing correctly, on one of the Shiba's sides (the thigh), a slight hole is visible—to the point where the mesh itself is somewhat exposed—unlike the rest of the body; this leads me to believe that it is a mesh error.

    5) For example, to add lighting to a terrain, the player needs to have good visibility; with this tool, we can ensure that the lighting is properly configured. Alternatively, it can be used to highlight a specific object through the use of lighting.

    6) Because having two vectors pointing in opposite directions results in a negative dot product—an effect that contradicts what we are trying to achieve.

    7) Personally I'm not entirely sure, but I think it's so that the textures and the assigned color blend together.

## W8

### Activity 1

Playtester partners:
Billal and Laura

1) Did the game make sense?
2) Are four monsters enough for the whole terrain?
4) Did you find the instruction easy ? should I move them to be a separate scene after starting the game?
5) Is it too difficult to find all the mushrooms and filters?
6) Is the music too much? Should it be less volume?
7) Which sound effects should I add?
8) Does the game feel okay?

- Playtest notes:

    - The players let me know that the core gameplay loop is solid, the sound design and monsters are well-implemented, and the instructions are clear. However, they did recommend applying a brighter material to the filters; this would make them easier to spot—much like the yellow ones. Personally, I liked the fact that they were hard to find, as that aligns with the game's core concept, but I do understand the frustration. They also suggested adding more monsters; while four is a decent number, it is still too few for the large terrain I created. Aside from that, everything went well; the game successfully made them feel nervous and scared.


