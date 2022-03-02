# ReadOnlyEditorField-Repository
Repository of a Custom attribute that allows you to mark Unity Editor's field as "ReadOnly".

Setup: <br/>
Drag 'Custom Attributes' folder inside the **Asset** Folder, <br/>
Drag 'Editor' folder inside the folder where you put all the scripts. <br/>

How To Use: <br/>

**Step 1**: <br/>
To use it, You will need to **either** put 'using AG' on top of each script (the place where using Unity is written). <br/>

**Or** change your script format to <br/>
namespace AG <br/>
{<br/>
YOUR SCRIPT CONTENT HERE! <br/>
}<br/>

**Step 2**: <br/>
Use it like any other attributes in Unity, just put **[ReadOnlyInspector]** before variable's Access Modifiers.
