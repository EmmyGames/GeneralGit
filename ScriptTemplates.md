Replacing the Unity Default Template

C:\Program Files\Unity\Hub\Editor\2020.3.26f1\Editor\Data\Resources\ScriptTemplates

Replace the contents of:\
81-C# Script-NewBehaviourScript.cs.txt

You will get permission denied so save the file somewhere else and manually drag it into the directory.

```
using UnityEngine;

#ROOTNAMESPACEBEGIN#
/// <summary>
/// Brief summary of what the class does
/// </summary>
public class #SCRIPTNAME# : MonoBehaviour
{   
    private void Awake()
    {
        #NOTRIM#
    }
    
    private void Update()
    {
        #NOTRIM#
    }
}
#ROOTNAMESPACEEND#
```

Custom Scriptable Object Template create new file named:\
80-Custom Script Templates__New ScriptableObject-NewScriptableObject.cs.txt

```
using UnityEngine;

[CreateAssetMenu(fileName = "New #SCRIPTNAME#", menuName = "ScriptableObjects/#SCRIPTNAME#")]
public class #SCRIPTNAME# : ScriptableObject
{
    #NOTRIM#
}
```