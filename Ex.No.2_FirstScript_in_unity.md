Ex.No: 2 Welcome Script in Unity
DATE: 18-05-2026
REGISTER NUMBER : 212224240029
AIM:
To learn the basic scripting in Unity and print welcome message in Console window.

Procedure:
Start the program
Open the Unity hub and Create a new 3D project
In Assets window, create the new folder and name it as Scripts
Create a new script with file name as FirstScript
Open the Script and print message "Welcome to Unity" inside the start function
Save the script
Create a new 3D game object in Hierarchy window and name it as 3DObject.
Add the component Firstscript in inspector window of 3Dobject.
Run the program
Stop the program.
Program:
```
using System.Collections;
using System.Collections.Generic;
using UnityEngine;
public class FirstScript : MonoBehaviour
{
    // Start is called before the first frame update
    void Start()
    {
        print("Welcome to Unity");
    }

    // Update is called once per frame
    void Update()
    {
        
    }
}
```
Output:
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/ff7dbc3e-ea82-4975-a8ba-206de7f9afb3" />

Result:
Thus the welcome script was printed on Console Window sucessfully.
