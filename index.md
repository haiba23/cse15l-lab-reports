# Let us commence forth!
---
*Lab Report 1*
---
# CD
![Image](cdScreenshot.PNG)
```
1. Entering cd without an argument in the command terminal does nothing. The working directory is /home.
2. Entering cd and a directory changes the working directory to /home/lecture1. The working directory was /home before running, and is /home/lecture1 after running.
3. Entering cd and a file returns a statement that it is not a directory. The working directory is /home/lecture1. The output implies that it was an error, seeing as changing directory to a file would not work.
```

# LS
![Image](lsScreenshot.PNG)
```
1. Entering ls without an argument returns lecture1. The working directory is /home.
2. Entering ls with the directory lecture1 returns 4 things: Hello.class, Hello.java, messages, and README. The working directory is /home.
3. Entering ls with the file en-us.txt with lecture1/messages/en-us.txt returns lecture1/messages/en-us.txt. The working directory is /home.
```

# CAT
![Image](catNoarg.PNG)
```
1. Entering cat without an argument does nothing, but the terminal goes on to the next line. Entering any text causes the terminal to return the same text, except the command CTRL-D, which allowed for commands again. The working directory is /home. This is unusual, but it does not seem to be an error.
```
![Image](catDirectory.PNG)
```
2. Entering cat with the directory messages returns the statement that messages is a directory. The working directory is /home. The output implies that this is an error because cat is used to read files, not directories.
```
![Image](catFile.PNG)
```
3. Entering cat with the file en-us.txt returns the text within the .txt file, "Hello World!" The working directory is /home.
```
