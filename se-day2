# se-day2-assignment

# PART ONE

# QUESTION 1: Describe the steps required to install git on windows machine. What key options should you pay attention to during installation and why? 

1. Download the latest Git version from the official Git website ([https://git-scm.com/downloads](https://git-scm.com/downloads)) and download the best-suited version for your Windows. 

2. Double-click the downloaded file to launch the installer. 

3. Configure your Preferences, while paying attention to the following key options: 

     Easy Access: Checking "Add Git to PATH" lets you use Git commands directly from the command prompt.  

     Finding Git: Choose where you want Git shortcuts in the Start menu. 

     Editing Text Files: Select your favourite text editor for working with Git configuration files. 

     Secure Connections (SSH): If you'll be using SSH with Git, configure your SSH client or choose the default options. 

     Command Line Interface: Make sure to install Git Bash if you prefer a command-line interface. 

     Quick Git Actions: Decide if you want Git commands integrated into the Windows Explorer right-click menu. 

4. Click "Finish" to complete the installation. 

  

To confirm everything's working, open a command prompt or terminal and type `git --version`. If Git is installed correctly, you'll see the version number. 

  

# QUESTION 2:Explain the purpose of configuring your username and email on git. How does this configuration affect your git workflow? 

Purpose of Configuring Username and Email on Git: 

When you initialize Git on your system, you’re typically asked to provide your username and email address. These details are essential for identifying you as the author of your commits, as it is easy to keep track of the changes and resolving conflicts.  

By configuring your username and email, you’re essentially creating a digital identity that is associated with your Git commits. This helps maintain a clear and traceable record of your contributions. 

  

How it Affects Your Git Workflow: 

Collaboration: When working on a team project, your unique identity helps differentiate your contributions from others. This prevents conflicts and ensures proper credit for your work. 

Commit Attribution: Every commit you make includes your name, time stamp and email, making it clear who made the changes. 

Open Source Recognition: Your public username and email allow others to acknowledge and appreciate your contributions to open-source projects. 

  

Best Practices: 

 Use a consistent username and email for all your Git activities and workflow. 

 Use a dedicated email address for Git, especially if you contribute to open-source projects. 

  

# QUESTION 3: What is ssh key And why is it recommended to connect git with github using ssh? Provide a step by step guide for generating and adding an ssh key to github 

 SSH (Secure Shell) key is a pair of cryptographic keys (public and private) used for secure authentication. It’s like a digital lock and key for your computer. 

  

Why Use SSH for GitHub? 

SSH keys offer a more secure way to connect to GitHub compared to passwords. They’re harder to crack and protect against unauthorized access. 

SSH keys can be used to automate tasks that require frequent authentication, like deploying code or running scripts. 

SSH keys can be used with Two-Factor Authentication (2FA) for even stronger security. 

  

Steps to Generate and Add an SSH Key to GitHub: 

1. Check for Existing SSH Keys: 

    Open a terminal or command prompt and run the following command: 

  	bash Ls -al ~/.ssh 

If there’s an existing `id_rsa` file, you can skip to step 4. 

 

2. Generate a New SSH Key: 

    Run the following command, replacing `your_email@example.com` with your actual email address: 

  bash Ssh-keygen -t rsa -b 4096 -C your_email@example.com 

Follow the prompts to create a passphrase for your private key. 

  

3. Find the Public Key: 

    The public key will be saved in a file named `id_rsa.pub` in the `~/.ssh` directory. 

  

4. Add the Public Key to GitHub: 

    Go to your GitHub settings and navigate to “SSH and GPG keys.” 

    Click “New SSH key.” 

    Give the key a title (e.g., “Your Computer”) and paste the contents of the `id_rsa.pub` file into the “Key” field. 

    Click “Add SSH key.” 

  

Testing the SSH Connection: 

Run the following command, replacing `your_github_username` with your GitHub username: 

   	ash Ssh -T git@github.com 

If the connection is successful, you’ll see a message like “Hi your_github_username! You’ve successfully authenticated over SSH.” 

  

# QUESTION 4: Provide the git command for the following tasks and explain what each command does; 

i) Initialize a new Git repository: 

bash Git init  

Creates a new Git repository in the current directory. It initializes the necessary files and directories for version control. 

ii) Clone an existing repository: 

bash Git clone <repository_url>  

Creates a local copy of an existing Git repository from a specified URL by downloading the entire history of the repository and setting up a remote tracking branch. 

iii) Add all modified files to the staging area: 

bash Git add.  

Adds all modified files in the current directory and its subdirectories to the staging area. 

iv) Commit the changes with a message: 

bash Git commit -m “Commit message”.  

It commits the staged changes to the local repository with a specified commit message 

v) Push the changes to the main branch on GitHub: 

bash Git push origin main.  

It pushes the changes from your local repository to the `main` branch on the remote repository named `origin`. 

  

# QUESTION 5: After setting up git and github, how can you verify that your local git setup is properly connected to github? What’s the expected output? 

 Run this command in your terminal:  

bash Git remote –v  

It will show you a list of all the remote repositories you’ve connected to your local project.  

Expected output: 

Origin https://github.com/your_username/your_repository.git (fetch) 

Origin https://github.com/your_username/your_repository.git (push) 

  

Replace `your_username` and `your_repository` with your details. 

The expected output means you have a remote repository named “origin” that’s configured to both fetch updates from GitHub (pull) and send your changes back (push). 

  

# PART TWO: PYTHON NAVIGATOR QUESTIONS: 

  

# QUESTION 1: Explain the concept of variables and data types in Python. Provide an example in Python where different data types (integer, string, and boolean) are used. 

Variables are used to store data that can be referenced and manipulated in a program. Python has several built-in data types, including integers, strings, booleans, floats, etc. Each data type determines the operations that can be performed on the variable and the storage required. 

Integer: Whole numbers (e.g., 1, 2, -3) 

 Float: Decimal numbers (e.g., 3.14, -0.5) 

 String: Sequences of characters (e.g., “Hello”, “Python”) 

 Boolean: True or False values 

 

 Code: 

age = 54 

name = "Getrude" 

is_married = True 

print(f"{name} is {age} years old. Marital status: {is_married}") 

 

Output:  

Getrude is 54 years old. Marital status: True 

# QUESTION 2: What is control flow in Python? Write a Python script using if, elif, and else statements to check if a number is positive, negative, or zero. 

Control flow is the order in which individual statements, instructions, or function calls are executed or evaluated. Python supports control flow tools such as if, elif, else, for, while etc., to direct the flow of execution based on conditions or loops. 

Code: 

Number = int(input("Enter a number: "))  

if Number > 0:  

       print("The number is positive.")  

elif Number < 0:  

       print("The number is negative.")  

else:  

       print("The number is zero.") 

Output:  

Enter a number: 

# QUESTION 3: Differentiate between for loops and while loops in Python. Provide examples of each where a list of numbers is iterated over, and only even numbers are printed. 

Loops are used to iterate over a sequence (such as a list, tuple, string, or range). 

While loops repeat as long as a specified condition is `True`.   

Loop code to determine the visibility test for 3: 

numbers = [1, 2, 4, 6,11,17,21] 

for num in numbers: 

       if num % 3 == 0: 

           print(num) 

 Output:  

6,21 

 

While loop code: 

numbers = [11, 12, 13, 14, 15, 16] 

i= 0 

while i < len(numbers): 

       if numbers[i] % 2 == 0: 

           print(numbers[i]) 

       i+= 1 

  Output:  

12,14,16 

# QUESTION 4: Define what a function is in Python and explain its importance. Write a Python function that takes two arguments (a and b) and returns their sum. 

A function n is a block of reusable code that performs a specific task.  

Functions are important as they help to organize code into manageable sections, make the code more readable, and reduce redundancy by allowing code to be reused. 

  

Code: 

a = float(input (“Enter a number  a: “)) 

b = float(input (“Enter a number  b: “)) 

def add_numbers(a, b):  

       return a + b  

result = add_numbers(a, b)  

print(f"The sum is: {result}") 

 Output:  

30 

# QUESTION 5: Compare lists and dictionaries in Python. How would you use a list and a dictionary to store the names and ages of three people? Provide a Python code example. 

 List is an ordered collection of items that can be of any data type. Lists are indexed by integers and can be modified (mutable). Lists are best for sequences where order is important, like a list of names as they use case. 

Dictionary is an unordered collection of key-value pairs. Each key must be unique, and it maps to a specific value. Dictionaries are also mutable and ideal for associating one piece of data (e.g., a name) with another (e.g., an ag 

Code: 

person = [  

    {"name": "J.L.George", "age": 43, "id": 33454},  

    {"name": "B.W.Brian", "age": 19, "id": 33640}, 

    {"name": "AV..Brian", "age": 28, "id": 33640}, 

    {"name": "K.J.Brendah", "age": 25, "id": 33478}  

] 

for student in person:  

    print(f"{student['name']} with ID {student['id']} is {student['age']} years old.") 

Output:  

J.L.George with ID 33454 is 43 years old. 

B.W.Brian with ID 33640 is 19 years old. 

AV..Brian with ID 33640 is 28 years old. 

K.J.Brendah with ID 33478 is 25 years old.
