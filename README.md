# TextUtils
simple console helper module for noob python developers (like me)

Example: creating a simple title Bar at the top of the console screen.
```
from TextUtils import *
clearScreen()
printTitleBar("Title Bar")
input()
```
![image](https://github.com/user-attachments/assets/6adbc923-8662-43a3-9283-d2b41533d92b)

You can use optional parameters boxCollor and textColor to create different results
```
printTitleBar("Title Bar", boxColor=GREEN, textColor=YELLOW)
```
![image](https://github.com/user-attachments/assets/0fe103c4-6df4-48fc-b81a-2933b80b89f2)

Other alternative versions are:
```
printTitleBarBroadBorder("Title Bar", boxColor=GREEN, textColor=YELLOW)
printTitleBarDoubleBorder("Title Bar", boxColor=GREEN, textColor=YELLOW)
printTitleBarHeavyBorder("Title Bar", boxColor=GREEN, textColor=YELLOW)
printTitleBarRoundBorder("Title Bar", boxColor=GREEN, textColor=YELLOW)
```
![image](https://github.com/user-attachments/assets/ce6597a3-b3cf-42dd-999d-44ff62adaa4c)
![image](https://github.com/user-attachments/assets/d0152f1b-72e5-43e0-882f-e628a50c9e00)
![image](https://github.com/user-attachments/assets/14b3fd93-5686-4e3f-b01b-75d2ae4fe12b)
![image](https://github.com/user-attachments/assets/616c1e7c-4055-4cf0-81d0-b474d6da18d4)


