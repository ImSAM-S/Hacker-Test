# LEVEL 20

![image](https://github.com/ImSAM-S/Hacker-Test/blob/6266bf3572ce1cf8d5c2eaccc394011db1d340c5/level%2020/level20.png)

# SOLUTION

Open View Source:

```
<p align="center"><b><font face="Arial" size="2">
VldwSk5Gb3lVa2hQUjJSclRUSlJlbFJITlU5TlIwNTBWbTE0YTFJelVqSlpNakF4WWtkT2NFNVlWbUZYUmtZeVYycEtTbG95U25SUFZFNU5Xbm93T1QwOT09<br>
<font color="#FFFFFF">&nbsp;^^^^^^^^^^ Change domain, add "22332" at the end, reach it and then get hold of ... ^^^^^^^^^^ </font></font></b></p>
```
In here we have 2 jobs:

JOB 1: decode this : 'VldwSk5Gb3lVa2hQUjJSclRUSlJlbFJITlU5TlIwNTBWbTE0YTFJelVqSlpNakF4WWtkT2NFNVlWbUZYUmtZeVYycEtTbG95U25SUFZFNU5Xbm93T1QwOT09'

Go to: ' dcode.fr ' to know what is that encode (base64) and decode it (x4 times)

And we got: " Go to www.streetkorner.net/gb now. "  Hold on! Don't go there because it is empty. Go to job 2

JOB 2: When we done job 1, we add "22332" at the end -> " ../gb22332" take that to our main domain and we have this screen:

```

Not Found
The requested URL /gb22332/login.php was not found on this server.

Additionally, a 505 Not Found error was encountered while trying to use an ErrorDocument to handle the request.

```

According to web standards, a 404 error indicates "Not Found," whereas a 505 error indicates that the HTTP version is not supported. So, this is a fake news.

View Source and look here:
```
HTML><HEAD>
<TITLE>505 Not Found Here</TITLE>
</HEAD><BODY>
<H1>Not Found</H1>
The requested URL /gb22332/login.php was not found on this server.<P>
<P>Additionally, a 505 Not Found
error was encountered while trying to use an ErrorDocument to handle the request.
```

The 'title' tag is upcase, so the hint i think is: take '505' to link like this: 'hackertest.net/505'

Oh yea! We have new hint, in here:
```
Not Found
The requested URL /505 was not found on this server.

Additionally, a 403 Not Found error was encountered while trying to use an ErrorDocument to handle the request.
```

403 means "Forbident"  not "Not Found" :V so add 404 to link like '505' , we got: 'hackertest.net/505/403'

![image](https://github.com/ImSAM-S/Hacker-Test/blob/c995e373baca4a1971e8f21b96d633532606132d/level%2020/level20_1.png)

Look at this setence: 'What is the answer to life, the universe, and everything?'. Search it! And we got: '42'
It originating from the famous science fiction novel *The Hitchhiker's Guide to the Galaxy* by Douglas Adams

So now we have new link to search: 'hackertest.net/42.php'

Finally, click "Enter" 

![image](https://github.com/ImSAM-S/Hacker-Test/blob/ac6f5ed22ad231259ad5a56add15c2030a549ea8/level%2020/enter.png)

###                                    NICE GAME MY FELLAS! ALL 20 LEVELS HAVE BEEN SOLVED! 













