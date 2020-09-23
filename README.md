<div align="center">

## MAKE THE KEYBOARD LIGHTS DANCE\!\!\!\!\!


</div>

### Description

this is just a simple code demonstrating the use of the SendKeys function!!! other than that this code is for humor!!! to some this code is useless but this might be helpfull 2 someone, that's why i submitted it. Plus this is pretty funny!!!
 
### More Info
 
put a command button on the form named Command1

This temporarily freezes your computer- (until it finishes the For, Next loop)


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Im\_\[B\]0ReD](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/im-b-0red.md)
**Level**          |Beginner
**User Rating**    |3.3 (23 globes from 7 users)
**Compatibility**  |VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Jokes/ Humor](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/jokes-humor__1-40.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/im-b-0red-make-the-keyboard-lights-dance__1-5213/archive/master.zip)





### Source Code

```
Private Sub Command1_Click()
Dim i As Integer 'declare the variable
For i = 1 To 150 'how many times (you can change the 150 to whatever you want)
 SendKeys "{CAPSLOCK}", True 'turn on the capslocks light, then turn it off
 SendKeys "{DOWN}", True 'just to give more time
 SendKeys "{DOWN}", True '^^^^^
 SendKeys "{SCROLLLOCK}", True 'turn on the scroll lock light, turn it off
 SendKeys "{DOWN}", True 'give more time
 SendKeys "{DOWN}", True '^^^^^
Next i
End Sub
```

