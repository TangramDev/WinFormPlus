<div align=center>

# Enable Your <i>WinForm Application</i> <br/>to Support <i><ins>Web Runtime</ins></i>
  
## (1)Prepare a C# WinForm Project<br>(create a new Project, or open an existing Project)
</div>
<h3> 

Copy all files included with [***WinFormPlus***](https://github.com/TangramDev/WinFormPlus/archive/refs/tags/v1.0.0.3.zip) into the prepared WinForm Project, reference “cosmos.dll”, adjust manifest and compilation configurations</h3>


<div align=center id ="WinFormDev_manifest"><img src="https://user-images.githubusercontent.com/26355688/183294437-cf6a3f96-69ed-4274-936c-ba963e21537d.jpg" width="80%"/></div>

<h3 align=center><p>(2)Open "program.cs" file.</p> <p align=left><i>Modify main function</i>: replace "Application.Run" with:<p align=center>Universe.WebRT.Run</p></p>
</h3>

<h2 align=center>Building WinForm Applications that <br/></i>Have <i>Unlimited Docking Abilities</i> and <i>Support Web Content Ecology</i></h2>

<h3>

We borrowed two aerospace concepts from wikipedia: [_Docking_](https://en.wikipedia.org/wiki/Docking_and_berthing_of_spacecraft#Docking) and [_Berthing_](https://en.wikipedia.org/wiki/Docking_and_berthing_of_spacecraft#Berthing). When we think that each WinForm is a huge spacecraft, a very important fact is:： while the WinForm has unlimited docking ability with other types of WinForms, it also has unlimited berthing ability.</h3>

<h2 align=center>Dynamic <i>Docking</i></h2>
<h3 align=left>If there is a UserControl object with a variable size in a WinForm object, and the value of the Dock property of the object is "DockFill" or "Dock FillNone", then the object will provide an unlimited number of WinForms Docking Port.</h3>

<h2 align=center>Dynamic <i>Berthing</i></h2>
<h3 align=left>If there is a UserControl object with a variable size in a WinForm object, and the value of the Dock property of the object is "DockFill" or "Dock FillNone", then the object will provide an unlimited number of WinForms Docking Port.</h3>
