## OS Home Assignment 2

(use desktop view)

<img src="./home2img.jpg" width="100%" alt="file structure">

**$mkdir -p ROOT/{Folder1,Folder2,Folder3/{Text5,Text6},Folder4}**<br>
**$cd ROOT**<br>
**$touch Folder1/{Text1.txt,Text2.txt} Folder2/{Text3.txt,Text4.txt} Folder4/{Text7.txt,Text8.txt}**<br>
**$cd Folder1**<br>
**$cat>Text1.txt**<br>
**who<br>who -a<br>tty<br>ctrl+z<br>**
**$cat>Text2.txt**<br>
**name: dogesh<br>sec: a<br>roll: 100<br>ctrl+z<br>**
**$cd ../Folder2**<br>
**$cat>Text3.txt**<br>
**man who<br>ctrl+z<br>**
**$cat>Text4.txt**<br>
**tty<br>w<br>ctrl+z<br>**
**$cd ..**

---

_1. Run the files text1,text3._<br>

**$sh Folder1/Text1.txt**<br>
**$sh Folder2/Text3.txt**

---

_2. For text4 do the typescripting._<br>

**$script Folder2/Text4.typescript**<br>
**$sh Folder2/Text4.txt**<br>
**$exit**

---

_3. Change the name of Typescripting to T1._<br>

**$mv Folder2/Text4.typescript Folder2/T1.typescript**

---

_4. Copy the content of Text1 to Text8._<br>

**$cp Folder1/Text1.txt Folder4/Text8.txt**

---

_5. Copy the content of Text3 and Text4 to Text7._<br>

**$cat Folder2/Text3.txt Folder2/Text4.txt>Folder4/Text7.txt**

---

_6. Move the file Text2 to directory Text5._<br>

**$mv Folder1/Text2.txt Folder3/Text5**

---

_7. Combine Text3 and Text4 to a file named COMBINETEXT._<br>

**$cat Folder2/Text3.txt Folder2/Text4.txt > Folder2/COMBINETEXT.txt**

---

_8. Change the permission of Text5 whose contents can be read by you, write and execute by group and no permission for 3rd user level._<br>

**$chmod 430 Folder3/Text5**

---

_9. Delete the directory Folder3._<br>

**$rm -rv Folder3**
