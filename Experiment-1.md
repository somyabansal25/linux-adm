Experiment 1 
Use the touch command to create sets of empty practice files to use during this lab. In each set replace, replace X with the numbers 1 through 6. Create six files with names of 
the form songX.mp3, snapX.jpg and filmX.avi. Create three subdirectories for organizing your files and name the subdirectories friends, family and work. Use a single command to 
create all three subdirectories at the same time. 
Approach- Use the touch command with brace expansion to create the files and the mkdir command with space-separated names to create the directories.

![image](https://github.com/user-attachments/assets/df73778b-4828-4e8e-a1d8-3f335122dd22)
![image](https://github.com/user-attachments/assets/62dbc06d-ef20-4e41-845e-1152337a4f96)

commands used:
touch song{1..6}.mp3 snap{1..6}.jpg film{1..6}.avi mkdir family friends work
