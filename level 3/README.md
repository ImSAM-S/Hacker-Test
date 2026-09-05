# LEVEL 3

![image](https://github.com/ImSAM-S/Hacker-Test/blob/1d52a211d4f64cac7b366544b599c10d73ae0813/level%202/level2.png)

# SOLUTION
Go to its View Source and look at this code

```
<body onload=javascript:pass(); alink="#000000">
<SCRIPT LANGUAGE="JavaScript">
function pass()
{
var pw, Eingabe;
pw=window.document.alinkColor;
Eingabe=prompt ("Please enter password");
if (Eingabe==pw)
{
window.location.href=String.fromCharCode(97,98,114,97,101)+".htm";
}
else
{
alert("Try again");
}
}
</SCRIPT>
```
We can see in here the password is ```pw=window.document.alinkColor; ``` and ``` alink="#000000" ```

### Enter "#000000" the password

**Next level:** [www.hackertest.net/null.htm](https://www.hackertest.net/abrae.htm )

**Next solution:** [Level 4](https://github.com/ImSAM-S/Hacker-Test/tree/main/level%204)
