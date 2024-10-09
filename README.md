# SWE_2021_41_2024_2_week_6

## WEEK4

>>[github](https://github.com/younghounSon/SWE_2021_41_2024_2_week_4)
```python

def isHappy(n):  
　a=set()  
　while(n not in a):  
     　　 a.add(n)  
     　　 if(n==1):  
　　　　　return True  
　  　b=0  
　　 for i in str(n):  
　　　b+=int(i)**2  
　　n=b  
　return False
```
----------------------------
Repeat until the sum of the squares of each digit becomes 1.<br>
If a number that has already appeared once is obtained using a set, it cannot be a happy number, so the repetition ends.


## WEEK5

>![img1](https://github.com/user-attachments/assets/1a93245b-d168-478d-96ea-b72b33c79d66)<br>
A command that outputs version information about the Linux operating system installed in the ossp-container, 
and as a result, various results related to Ubuntu were output.,<br>

>![img2](https://github.com/user-attachments/assets/6588c7d0-391c-483d-a761-ac17e2cf05cf)<br>
This command prints the host location of the shared folder.
The path to the shared folder on the desktop is displayed.

>![img3](https://github.com/user-attachments/assets/a1db06e2-46ef-4733-8ee1-5fa5bb4e923e)<br>
The version of "Python3" installed in ossp-container is printed.

>![img4](https://github.com/user-attachments/assets/e8263327-caf5-4286-9b21-65e37e2a6e6d)<br>
The version of "git" installed in ossp-container is printed.
