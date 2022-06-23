- [Set up DVWA inside a Docker container](https://github.com/digininja/DVWA#docker-container)
- http://localhost/setup.php -> http://localhost/login.php -> http://localhost/index.php

- Instead of `Xmx2g` in can be `Xmx1024m` (the amount of RAM memory given for this process):

```cmd 
C:\Users\You\Desktop\BurpSuite>"C:\Program Files\Java\jdk-13.0.2\bin\java.exe" -jar -Xmx2g burpsuite_pro_v2022.5.1.jar
```

Burp -> Proxy -> Intercept -> switch to 'Intercept is off'