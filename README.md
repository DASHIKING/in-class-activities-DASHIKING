# In class activities
## Devlogs
### W1
#### Activity1
Participate more in LARC and ask about the parts you don't understand.

#### Activity2
1. X = 10
2. X = 2
3. Test if the line of code passes through, if not it will not play the debug message in console
4. MonoBehaviour
5.  Put number 10 in x and print x = 10 in the console
6.  0 is an argument, “x = ” + x is a parameter.
7. You can’t move the transform class, you can only move the specific object.
8. It should be changed to playerTransform

#### Activity3
https://docs.google.com/document/d/1xLpjOiC1mLK6nAbB_YaibtbYXvQONX3D-RQwwT5zzg4/edit?tab=t.0![c965865ad01ef78e2060e0bbefe3c7a8](https://github.com/user-


### W2
#### Activity1

[MG2 breakdown Google doc] 
(https://docs.google.com/document/d/1ROcUxkkaJtYDzNyL0CMq4DnDnnZqHXZwwBghimc3QGE/edit?tab=t.0)

#### Activity2
[MG2 Update](https://docs.google.com/document/d/1ROcUxkkaJtYDzNyL0CMq4DnDnnZqHXZwwBghimc3QGE/edit?tab=t.0)

I created the "player" and "coin" prefabs and add components to them, Create a TextMeshPro to count the score that player earned. 
I also create a ground that player to sit.


### W3
### Activities 0-2 : Partner name: Nathan

#### Activity 3
(![9a9d6f6f9c11040a007897711285b785](https://github.com/user-attachments/assets/0e2899f4-be62-4962-80fc-1d4950c93617)

### W4
#### Activity 0
Andrew 

#### Activity 1 
singleton will delete the remaining locators and leave the first 

#### Activity 2 
![cbe541403a49569be348844191fbe85e](https://github.com/user-attachments/assets/6fbc7096-55e3-43f2-b6f6-349c32f55aa1)

### Activity 3 
I created the "player" character and wrote the code for its jumping function. I also downloaded the resources of the birds and the pipes from the Internet and incorporated them into Unity.
(https://github.com/DASHIKING/HW4/commit/376c267501b48e088837f41c5f3bf109ecffa0df)

### W5
#### Actiity 1
I think the interface and abstract class design in this assignment is quite clear. The "Item" class is responsible for "all items can be used", and the "IBreakable" class is responsible for "some items will break". This separation is quite reasonable. If new items need to be added in the future, it's also very easy to expand: items that can break implement the interface, and those that cannot break only inherit from the "Item" class. If I were to do a project myself, I would probably use a similar structure, but I might put some repetitive durability logic in the parent class to make the subclasses more convenient.

### Activity 2
The player statistics of demo2 will be model, the spriterender and UI will be View, and the Player script, which contains move and collider should be the controller.

### Activity 3

#### Scenario 1

#### Scenario 2
For scenario 2, model should be players should have same HP and walking speed, view will be player's appearences, and the controller should be the logic of the game, like shoot enemys to get success.
we should use abstract base class for shared character behavior. Apart from that, we should use interface to design different shooting abilities. 
Polymorphism allows each character to override specific behaviors.Parent base could be the character base, and the child base could be specific character that the game contains.
The character should have multiple states, such as walking, running, falling down, and charging with electricity, etc.
Singleton should contain UI managers, abilities managers and audio managers etc.
The script objects should contain ability data, character stats etc.


#### Scenario 3


### Activity 4
Attendence: Beiduo Jin

[Final project proposal](https://docs.google.com/document/d/1KHzQUOe_9pFKEXuYQW5sSsAkWXeVOPrjhrICp1-lh7M/edit?usp=sharing)

### W6
Talk : Narrative Writing / Technical Art   Speaker's name : Cory Lanham

