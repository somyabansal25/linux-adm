Experiment-3
Use vim, nano to edit the editing_final_lab_file.txt file. Use the lab_file shell 
variable. Enter the visual mode of vim. Remove the last seven characters from the 
first column on the first line. Preserve only the four characters of the first column.

Approach-
Use `vim` or `nano` to open `editing_final_lab_file.txt` using the `lab_file` shell variable. In vim, enter visual mode, highlight the last seven characters of the first column on the first line, delete them, and keep the first four characters intact.

![image](https://github.com/user-attachments/assets/e51eecf2-7988-442e-b48f-b7fddfdd81f6)

Command used-
lab_file="editing_final_lab.txt" echo $lab_file vim $lab_file nano $lab_file

