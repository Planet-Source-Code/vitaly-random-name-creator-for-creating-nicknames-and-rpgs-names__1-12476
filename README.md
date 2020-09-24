<div align="center">

## Random name creator \(For creating nicknames and RPGs names\)


</div>

### Description

The code generates a random name. I am giving basically two simple functions with which you can create a loop that will make many thousands of nicknames or names for roleplay games. Check it out.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Vitaly](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/vitaly.md)
**Level**          |Beginner
**User Rating**    |4.3 (13 globes from 3 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[String Manipulation](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/string-manipulation__1-5.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/vitaly-random-name-creator-for-creating-nicknames-and-rpgs-names__1-12476/archive/master.zip)





### Source Code

```
Function C() As String
  Const Consonants = "bcdfghijklmnpqrstvwxz"
  Randomize
  C = Mid(Consonants, Int(Rnd * 21) + 1, 1)
End Function
Function V() As String
  Const Vowels = "aeiouy"
  Randomize
  V = Mid(Vowels, Int(Rnd * 6) + 1, 1)
End Function
'Now lets create few random names in the debug window.
'Write there: print C & V & C & V & C
'And run this line a few times. Here are the results I got:
'bapai
'zymam
'luler
'zaio
'I am sure that you would find to these two functions 1001 uses.
```

