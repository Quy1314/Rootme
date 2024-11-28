# [Yellow dots](https://www.root-me.org/en/Challenges/Steganography/Yellow-dots)  
This challenge gave me a file of newspaper with nothing special in there, after i searched about yellow dot, i decided to inspect this file by [Stegonline](https://georgeom.net/StegOnline/image)  
![image](https://github.com/user-attachments/assets/8a726130-2f5d-4443-a8b4-3f6971c6bf1b)
You can find it at top upper of the picture.  
![image](https://github.com/user-attachments/assets/ca19f68f-1e4c-4f55-9248-dbf2068edb9e)  
I detected these dots using [Dotspotter](https://www.forensicdots.de/)  
![image](https://github.com/user-attachments/assets/31a93bbf-a801-4081-b30f-3882fc0fc237)  
Then, i depend on detox method to solved the problem.  
![image](https://github.com/user-attachments/assets/e5b5020d-380d-489e-a31b-9db111bbcc24)    
Date, time, and serial values ​​can be expressed with yellow dots within the horizontal and vertical black lines, and the horizontal lines are divided into time (2-5), date (6-8), separator (10), and serial (11-14) as shown in the picture. Each value is determined by the vertical line, and each cell of the vertical line is expressed in the form of 2^n.  

Let's explain the number 2 in the picture as an example. The yellow dots are marked at 32, 16, and 2, and if you add up all of these values, it's 50. In other words, 50 minutes in time is expressed by two yellow dots. If you add up the values ​​where the yellow dots are located in this way, you can obtain the date, time, and serial values.  
Before:  
![image](https://github.com/user-attachments/assets/3ba57bd7-7aaa-47a4-9b3c-1c7991465636)
After:  
![image](https://github.com/user-attachments/assets/d26bbdce-9993-43ac-b11b-27e0721bfa18)
## FLAG: **```11:05 27/07/2014 06922930```**





