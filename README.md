<div align="center">

## TextBox \- Only Accept Numbers


</div>

### Description

This short little code example shows you how to only accept numbers to be inputed into a textbox by using the KeyPress event procedure. This is beginner, but I've seen alot of people that don't know how to do this.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Chris Pietschmann](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/chris-pietschmann.md)
**Level**          |Beginner
**User Rating**    |3.9 (27 globes from 7 users)
**Compatibility**  |VB\.NET
**Category**       |[Controls/ Forms/ Dialogs/ Menus](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/controls-forms-dialogs-menus__10-3.md)
**World**          |[\.Net \(C\#, VB\.net\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/net-c-vb-net.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/chris-pietschmann-textbox-only-accept-numbers__10-1684/archive/master.zip)





### Source Code

```
Private Sub txtHoursDay_KeyPress(ByVal sender As Object, ByVal e As System.Windows.Forms.KeyPressEventArgs) Handles txtHoursWeek.KeyPress
''Only accept numbers
If Not e.KeyChar.IsDigit(e.KeyChar.ToString) Then
e.Handled = True
End If
End Sub
```

