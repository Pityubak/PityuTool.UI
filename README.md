# PityuTool.UI

![Nuget](https://img.shields.io/nuget/v/PityuTool.UI?color=green&style=for-the-badge)  ![Nuget](https://img.shields.io/nuget/dt/PityuTool.UI?style=for-the-badge)\
Component for borderless windows forms 


### Overview

1. Drag/move by name or type
2. Resizing
3. Rounded form
3. Custom border
4. Custom shadow

### Example

<table >
  <tr>
    <td ><img height="300px" src="https://github.com/Pityubak/assets/blob/master/pityutool/shadow2.png" /></td>
    <td><img height="300px" src="https://github.com/Pityubak/assets/blob/master/pityutool/shadow3.png" /></td>
     <td ><img height="300px" src="https://github.com/Pityubak/assets/blob/master/pityutool/shadow4.png" /></td>
  </tr>

</table>




#### Limitations 
Previous version(1.0.0) make controls transparent by mouse, but this(1.1.4) use another approach, this is the reason for the resizing limitations:
just pure form is resizeable, exactly parts of form that does not cover another control.
Drawing of the shadow is not perfect, and in my opinion the rounded shape is ugly.

#### Dependencies
.NET Framework 3.5+

#### License 
MIT

