# [APNG - Just A PNG](https://www.root-me.org/fr/Challenges/Steganographie/APNG-Just-A-PNG-2995)   
This challenge give me APNG file. To start, i used ```APNG Disclaimer``` tool to seperated these png and recieved a stack of txt file.    
```linux
user@LAPTOP-TL39B5OL:/mnt/c/Users/Hoang Quy/Downloads$ apngdis ch21.apng

APNG Disassembler 2.9

Reading 'ch21.apng'...
extracting frame 1 of 13
extracting frame 2 of 13
extracting frame 3 of 13
extracting frame 4 of 13
extracting frame 5 of 13
extracting frame 6 of 13
extracting frame 7 of 13
extracting frame 8 of 13
extracting frame 9 of 13
extracting frame 10 of 13
extracting frame 11 of 13
extracting frame 12 of 13
extracting frame 1
```
Afterthat, i opened all of txt file and noticed that looks like an ASCII code so i decoded it by [ASCII code converter](https://www.dcode.fr/ascii-code) and obtained the flag. 
```linux
user@LAPTOP-TL39B5OL:/mnt/c/Users/Hoang Quy/Downloads/APNG$ cat apngframe*.txt
delay=70/10
delay=76/10
delay=65/10
delay=71/10
delay=58/10
delay=80/10
delay=51/10
delay=80/10
delay=111/10
delay=70/10
delay=82/10
delay=111/10
delay=71/10
```
![image](https://github.com/user-attachments/assets/9dfb8c48-30df-4567-be86-766a6a5b38dd)  
## FLAG: **```P3PoFRoG```**  
