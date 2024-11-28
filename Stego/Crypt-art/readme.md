# [Crypt-art](https://www.root-me.org/en/Challenges/Steganography/Crypt-art)
This challenge gave a a PPM file, after ```display``` it using ```imagemagick```, it returned to me a colorful picture.  
![image](https://github.com/user-attachments/assets/9be43b75-1076-408f-9061-9f6478995478)  
I searched on google and learned it is a type code named **```Piet```** .After reading the file, i obtain this material: "The encrypted pass is: EPCQFBXKWURQCTXOIPMNV".  
I decoded a picture using [Npietonline](https://www.bertnase.de/npiet/npiet-execute.php) and found that the key is EYJFRGTT but it is not a flag.  
Based on the encrypted pass and the key, i realized it's related to the **[Vigenère Cipher](https://en.wikipedia.org/wiki/Vigen%C3%A8re_cipher)**.
After matching them and solving it using GPT, i obtained a flag.  
![image](https://github.com/user-attachments/assets/bb4f773b-1041-42ec-b648-1f6bea6bca5f)  
## FLAG: **```ARTLOVERSWILLNEVERDIE```**
