# Ex.No: 3  Basic movements in Unity 
### DATE: 12/08/2025                                                                        
### REGISTER NUMBER : 212223240088
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
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class movement : MonoBehaviour
{
 public Transform Object1;
 public Transform Object2;
 public Transform Object3;
 void Start()
 {
    

 }

 // Update is called once per frame
 void Update()
 {
     Object1.Translate(0.02f, 0, 0);
     Object2.Rotate(0.2f, 0, 0);
     Object3.localScale += new Vector3(0, 0.02f, 0);
 }
}
```
### Output:
# BEFORE:
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/1e3435e4-7cf8-4172-b80d-76e5a66e6c90" />

# AFTER:
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/2337f7d2-dcd5-46c3-af6b-b2990222116a" />









### Result:
Thus the basic movement is learned through scripting


