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

<img width="585" height="58" alt="image" src="https://github.com/user-attachments/assets/e1befc6d-1883-4fe3-86c3-5b6930f61a74" />


## COMMAND AND OUTPUT

Remove the directory "my-folder"

<img width="531" height="47" alt="image" src="https://github.com/user-attachments/assets/4ab39a3a-2411-4e35-934d-7eb01371e721" />


## COMMAND AND OUTPUT

Create the file Rose.txt

<img width="747" height="430" alt="image" src="https://github.com/user-attachments/assets/bf7d8b1a-d338-4c13-9efd-f6dd56137f5e" />


## COMMAND AND OUTPUT

Create the file hello.txt using echo and redirection

<img width="652" height="96" alt="image" src="https://github.com/user-attachments/assets/04e7e157-4e38-463b-9990-79c7581b087f" />


## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt

<img width="647" height="64" alt="image" src="https://github.com/user-attachments/assets/80218933-f0e5-4454-a745-622e1cea5331" />


## COMMAND AND OUTPUT

Remove the file hello1.txt

<img width="488" height="50" alt="image" src="https://github.com/user-attachments/assets/4b478997-675a-40a4-a945-ebb1a7b9855c" />


## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory

<img width="620" height="226" alt="image" src="https://github.com/user-attachments/assets/1e3440b6-e11c-4bea-8a78-8530822211f3" />


## COMMAND AND OUTPUT

List out all the associated file extensions 

<img width="544" height="680" alt="image" src="https://github.com/user-attachments/assets/2da869ee-ac90-40f9-99bf-f8b213c00dcb" />


## COMMAND AND OUTPUT

Compare the file hello.txt and rose.txt

<img width="642" height="222" alt="image" src="https://github.com/user-attachments/assets/704e92c2-cad2-496f-9cdd-ef6cb8f66747" />


## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".


## OUTPUT

<img width="485" height="183" alt="image" src="https://github.com/user-attachments/assets/01587411-456e-4da5-9397-01888ffad73a" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT


<img width="677" height="614" alt="image" src="https://github.com/user-attachments/assets/c3246b6a-8a32-41a2-96fd-90dd3df5b5ea" />


Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT


<img width="536" height="230" alt="image" src="https://github.com/user-attachments/assets/a9dba036-a2e6-4186-8c8c-e6509e72fbdc" />


Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="543" height="145" alt="image" src="https://github.com/user-attachments/assets/b6249a59-4d3f-4d92-b9b6-a1d330bff993" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT


<img width="646" height="454" alt="image" src="https://github.com/user-attachments/assets/44089d05-2447-43e0-ba4c-e7522f7f672b" />



# RESULT:
The commands/batch files are executed successfully.

