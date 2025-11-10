# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"

<img width="370" height="52" alt="image" src="https://github.com/user-attachments/assets/cd4a2dd8-1e61-48be-a738-e6c473d53440" />


## COMMAND AND OUTPUT

Remove the directory "my-folder"


<img width="461" height="56" alt="image" src="https://github.com/user-attachments/assets/cd5e82a9-3e00-4064-a13d-4d1ff5edae50" />


## COMMAND AND OUTPUT


Create the file Rose.txt


<img width="441" height="57" alt="image" src="https://github.com/user-attachments/assets/61448b70-9031-4af5-8982-fc31875ef83b" />


## COMMAND AND OUTPUT


Create the file hello.txt using echo and redirection


<img width="578" height="47" alt="image" src="https://github.com/user-attachments/assets/492d04a4-53c0-4062-a666-0d0b222b8a31" />


## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt


<img width="502" height="70" alt="image" src="https://github.com/user-attachments/assets/fb6e5442-befb-42df-8c65-187ec851c9d2" />


## COMMAND AND OUTPUT

Remove the file hello1.txt


<img width="381" height="54" alt="image" src="https://github.com/user-attachments/assets/9cc5cb5d-1572-47ff-a0d9-e4bbc21d92bc" />


## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory


<img width="443" height="191" alt="image" src="https://github.com/user-attachments/assets/5483d3cd-5f8d-44ec-bfbe-de59dc4c7b77" />


## COMMAND AND OUTPUT

List out all the associated file extensions 


<img width="876" height="1064" alt="Screenshot 2025-11-10 054751" src="https://github.com/user-attachments/assets/10b3cf41-2a7d-4c0a-8154-afef48d896bf" />


<img width="1122" height="1087" alt="Screenshot 2025-11-10 054806" src="https://github.com/user-attachments/assets/700267de-3432-497c-ab19-ccd1e51f4691" />


<img width="683" height="661" alt="Screenshot 2025-11-10 054845" src="https://github.com/user-attachments/assets/3c6f20e2-216e-4cc4-8168-4500c8558578" />


## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt


<img width="514" height="165" alt="image" src="https://github.com/user-attachments/assets/cf87a314-6a2e-4efe-83d2-34065bee57bf" />


## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="401" height="90" alt="image" src="https://github.com/user-attachments/assets/01f353ec-d050-4a6f-83db-041469630bd9" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT


<img width="583" height="305" alt="image" src="https://github.com/user-attachments/assets/f7135303-11d0-4acd-900c-8bc632dc4fe7" />


Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="426" height="245" alt="image" src="https://github.com/user-attachments/assets/a4ec66f0-d8d9-4278-8c2e-c0fec7670acc" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="705" height="234" alt="image" src="https://github.com/user-attachments/assets/7682b6df-7c2e-4e59-b912-c102bcfb7468" />



Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="344" height="472" alt="image" src="https://github.com/user-attachments/assets/26686780-9311-42e4-8b95-ce8e89bcd773" />




# RESULT:
The commands/batch files are executed successfully.

