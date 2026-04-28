# Ex.No: 3  Basic movements in Unity 
### DATE:   28-04-2026                                                                         
### REGISTER NUMBER : 212224240029
### AIM: 
 To learn the basic movements translation,scaling and rotation of game objects through code.
### Procedure:
1. Setup the Scene
2. Open Unity and create a 3D Scene.
3. Add three objects:Cube → Rename to Object1 (for movement),Sphere → Rename to Object2 (for rotation).Capsule → Rename to Object3 (for scaling).
4. Add the Script,Create a C# Script → Name it TransformOperations.cs.
5. Write the code for translation,scaling and rotation,save and close the script
6. Save the script
7. Select any empty GameObject (or create one: GameObject → Create Empty).
8. Attach the TransformOperations script to it.
9. In the Inspector, assign Object1 → Drag the Cube,Object2 → Drag the Sphere.Object3 → Drag the Capsule.
10. Run the Scene Press Play ▶️ in Unity
11. Stop the program.
### Program 
```
using UnityEngine;

public class FirstScript : MonoBehaviour
{
    public Transform O1;
    public Transform O2;
    public Transform O3;

    void Start()
    {

    }

    void Update()
    {
        if (Input.GetKeyUp(KeyCode.X))
        {
            O1.Translate(2f, 0f, 0f);
        }

        if (Input.GetKeyUp(KeyCode.Y))
        {
            O2.Rotate(2f, 0f, 0f);
        }

        if (Input.GetKeyUp(KeyCode.Z))
        {
            O3.localScale += new Vector3(2f, 2f, 2f);
        }
    }
}
```
### Output:



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4a90e1aa-05c0-40a1-9d62-7fe9b82b2b6f" />





### Result:
Thus the basic movement is learned through scripting


