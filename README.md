# IBM-Practica-Virgil

## Cuprins

 1. [Caiet practica](#caiet-practica)
 2. [Teme](#teme)
 3. [Proiect](#proiect)
 4. [Resurse](#resurse)


## Caiet practica
### Sesiunea 1
 
### Sesiunea 2

### Sesiunea 3

### Sesiunea 4

### Sesiunea 5

### Sesiunea 6

### Sesiunea 7


## (#teme)Teme
### Sesiunea 1
 1. Use the awk command to extract the „rights” column of a document/file/folder and output it in the terminal.
 ```bash
  ls -hrtl | awk {'print $1'}
 ```
 ![s1ex1](ss/s1ex1.png)

  **2. Use the chmod command to change the permissions of a file as it follows : user has read write execute, group has read and execute, others have nothing at all.**
 ```bash
  chmod 750 chmodtest.txt
 ```
 ![s1ex2](ss/s1ex2.png)

  **3. Use the wc command to count the number of lines, words, and characters in a file or set of files.**
 ```bash
  wc -lwc wctest.txt
 ```
 ![s1ex3](ss/s1ex3.png)
 ![s1ex3](ss/s1ex3_2.png)

  **4. Use the grep command to search for a specific keyword in a file or set of files and output the results to a new file.**
 ```bash
  grep "mere" greptest-in.txt > greptest-out.txt
 ```
 ![s1ex4](ss/s1ex4.png)

  **5. Use the sed command to find and replace a specific string in a file**
 ```bash
  sed -i 's/mere/pere/g' sedtest.txt
 ```
 ![s1ex5](ss/s1ex5.png)

  **6. Use the tar command to create a compressed archive of a directory**
 ```bash
  tar -czvf tartest.tar.gz tartest
 ```
 ![s1ex6](ss/s1ex6.png)

  **7. Create a bash script that takes as input a log file and executes a search in it, using grep for the keyword “error”. As soon as the “error” word is detected through the log file, the script should return a message saying “Errors found in log < name_of_log >”.**

  **Note: Do not forget to include the fullpath to the file before it’s name, when called as a parameter to the script run. Also, the log file must be populated by you.**
```bash
#!/bin/bash
#ghideaza scriptul catre interpretor
#-q ca sa nu mai afiseze in termina
if grep -q "error" "/home/jimmy/Desktop/log_file.txt"; then
  echo "Errors found in log_file.txt"
else
  echo "No errors found in log_file.txt"
fi
 ```
  ![s1ex7](ss/s1ex7.png)
  ![s1ex7](ss/s1ex7_2.png)
  ![s1ex7](ss/s1ex7_3.png)
  ![s1ex7](ss/s1ex7_4.png)
  
### Sesiunea 2

### Sesiunea 3

### Sesiunea 4

### Sesiunea 5

### Sesiunea 6

### Sesiunea 7

## Proiect

## Resurse

### Bash
- [Learn Linux TV](https://www.youtube.com/watch?v=YrE1Qg-Aw0Q&list=PLT98CRl2KxKGj-VKtApD8-zCqSaN2mD4w&index=5&ab_channel=LearnLinuxTV)