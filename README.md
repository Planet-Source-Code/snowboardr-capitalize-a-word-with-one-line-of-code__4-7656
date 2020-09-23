<div align="center">

## Capitalize a word with one line of code\.


</div>

### Description

Capalize a word with one line of code. Or first letter in a sentence.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[snowboardr](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/snowboardr.md)
**Level**          |Beginner
**User Rating**    |3.2 (19 globes from 6 users)
**Compatibility**  |ASP \(Active Server Pages\)
**Category**       |[Coding Standards](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/coding-standards__4-33.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/snowboardr-capitalize-a-word-with-one-line-of-code__4-7656/archive/master.zip)





### Source Code

```
<%
Function Capit(MyWord)
Capit = Ucase(left(MyWord,1)) & Right(MyWord,Cint(Len(MyWord)) - 1)
End Function
Response.Write(CapIt("jason")) 'Capitalize our word
%>
```

