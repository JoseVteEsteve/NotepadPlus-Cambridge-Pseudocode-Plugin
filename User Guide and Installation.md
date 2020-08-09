# Unofficial Cambdridge Pseudocode Language Plugin for Notepad ++

### Cambridge Pseudocode
Cambridge International offers their students the opportunity to course the subject Computer Science in the following key stages:

* 0478 Computer Science in Key Stage 4 (IGCSE)
* 9618 Computer Science in Key Stage 5 (A Level)

Writing pseudocode is one of the most important parts of these syllabuses and Cambridge offers a specific syntax. Since I have not found any text editor with this syntax,
I have created an **user-defined language (UDL)** to share it with my students and with all people studying this subject.

In this repository you can find two files:
* the last version of Notepad++ (at the moment of writing this document)
* the user-defined language xml file


### Installation
To install the program and the udl file, please follow the next steps:

1.**Installation of Notepad++**
You can download the file I have provided to you or go to [Notepad++] (https://notepad-plus-plus.org/downloads/) to download the last version
* download the file
* click on Install
* finish the installation by clicking Ok or Next in all the windows of the setup wizard
* launch the program

2. **Configuration of Notepad++**
In order to use Notepad++ with the UDL that you are going to install, please, do the following ammendments:
1. Open Notepad**
2. Go to *Settings --> Preferences*
3. In the window it will appear, go to *Editing* and make sure that in the section *Line Wrap* the radio button *Aligned* is selected
4. Go to *Language* and, in the section *Tab Size*, please change 4 by 2 and make sure that the option *Replace by space* is selected
5. Go to *Print* and select *Print line number*
6. Click *Close* to exit.

Until now, Notepad++ has been installed and configured and you can use it to write something, but it remains to install the UDL file.

3. **UDL Configuration**
Follow the next steps:
1. Download the file *PseudocodeByJoseVteEsteve.xml* you can find in this repository
2. Open Notepad++
3. Go to *Language* --> *User Defined Language* -->*Define your language*
4. In the new window (**Language Editor**) it appears, click on *Import...*
5. Browse the **xml** file you have downloaded in step 1 and upload it. When done, a little window should appear informing you that the importing has been successful
6. Close the Language Editor by clicking on the cross button at the top right of the window
7. Close Notepad++

Now, you should check if the installation has been successful and all is done. Do the following:
1. Launch Notepad++
2. Go to *Language*, and, if the language called **_PseudocodeByJosEsteve_** appears, the installation has been succesfully done.
3. Select **PseudocodeByJosEsteve**


### Writing pseudocode
Now, you can begin writing pseudocode programs using this hightlighting syntax. 

# Improvements for newer versions
- Make <-- using only one character




