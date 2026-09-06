# LEVEL 16

![image](https://github.com/ImSAM-S/Hacker-Test/blob/f07a8b348424fef94bb99608ad5485167e24ba5c/level%2016/level16.png)

# SOLUTION
Open View Source:

you can see this line:
```
UNAVAILABLE
<!-- level 17: /images" -->
```
So now we have new domain: 'hackertest.net/unavailable/images'

So when we on that web, we View Source again and see:

```
<body background="bg.jpg">
```

So we continue put that at the end of domain and have this link: 'hackertest.net/unavailable/images/bg.jpg'

That take us to a web have nothing with error img :V . So we View Source again and see this line on top:

```
ÿØÿà JFIF   d d  ÿì Ducky.php     P  ÿî Adobe dÀ   ÿÛ
```

That is our answer: 'Ducky.php'

**Next level:** [www.hackertest.net/unavailable/Ducky.php](https://www.hackertest.net/unavailable/Ducky.php)

**Next solution:** [Level 17](https://github.com/ImSAM-S/Hacker-Test/tree/main/level%2017)












