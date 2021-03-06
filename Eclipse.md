# Eclipse


## Tips

**Workspace**

* An Eclipse Workspace can contain several projects, which can be organized into virtual Working Sets.
* A Perspective determines how user would like to interact with a Workspace. Use *Menu: Window > Perspective > Customize Perspective...* to customize Perspective.


[Eclipse help - Working with projects, folders and files](https://help.eclipse.org/luna/index.jsp?topic=%2Forg.eclipse.platform.doc.user%2Ftasks%2Ftasks-45a.htm)

**Working Set**

Projects can be organized with Working Sets

* Open Project Explorer
    * Menu: Window > Show View > [Project Explorer]
* Enable Working Set
    * Project Exploere: Click the little triangle > Select Working Set > Manage Working Set here

**Project Nature**

* Menu: Project > [Properties] > Project Natures
    * Add things like `C Nature` or `CDT Builder Project`

Another way to do it: right click a general project in Project Explorer to show the context menu, then select New > Convert to a C/C++ Project.

**turn off cursor blinking**

Not that I know, but you can turn off cursor blinking at system level [How to disable Caret Blinking in Eclipse?](https://stackoverflow.com/questions/49233299/how-to-disable-caret-blinking-in-eclipse)

**Mark Occurrences**

`Alt + Shift + O` to toggle Mark Occurrences

## Plugins

**protobuf-dt**

[protobuf-dt](https://github.com/google/protobuf-dt) is Google's Eclipse plugin for protobuf.
However it cannot be installed on Eclipse Photon because of [this issue](https://marketplace.eclipse.org/content/error/report/4252575)