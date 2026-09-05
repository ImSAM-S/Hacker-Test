#LEVEL 2

![image](https://github.com/ImSAM-S/Hacker-Test/blob/39dd53140d3e6ef68752f413b6e9aa2875ac75ee/Level%201/level1.png)

#SOLUTION
Go to its View Source and look at this code

```
</script>


</head>
<body onLoad=password()>

<script language=JavaScript>
{
var a="null";
function check()
{
if (document.a.c.value == a)
{
document.location.href="http://www.hackertest.net/"+document.a.c.value+".htm";
}
else
{
alert ("Try again");
}
}
}
</script>
```
We can see in here ``` var a="null"; ``` so the password (var a) is set to 'null' 

### Enter "null" the password

**Next level:** [www.hackertest.net/null.htm](https://www.hackertest.net/null.htm)

**Next solution:** [Level 2](https://github.com/ImSAM-S/Hacker-Test/tree/main/level%202%20)



