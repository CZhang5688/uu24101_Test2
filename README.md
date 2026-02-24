# uu24101_Test2

# Git Usage
## Main Branch
The main branch contains all functional code, and can be used to as the most up-to-date functional version of this code base.

## Testing Branch
This branch is where I did tests on new code / changes to ensure they're functional before pulling them and committing them to the main branch. 

## Pull Requests
I used pull requests to pull changes that I was certain wasn't breaking code and fully functional into the main branch using pull requests. I used one initially when just adding all missing files, then one final pull request when pulling in all the changes that fixed the codebase fully and allowed the visualisations provided to work without error and compile the code without error. 

## Commits
I used multiple commits to keep track of the changes I was making to the testing branch in Git, ensuring that there was a strict version control so I had a working / "correct" version to return to if any changes I made broke or damaged the codebase further. 


# Main Modifications
## 1. Recreating the header files. 
Firstly, I recreated the missing system.h and disk.h files, recreating them exactly using the documentation provided by the "refman.pdf" file.

## 2. Updated the main.cpp and system.cpp files to add the missing include statements. 
Updated the main.cpp with the missing "include system.h" that was required, as suggested by the hint given. 

## 3. system.cpp member function class
Completed the hint that required providing a definition for a member function of the system class called uniform.

## 4. disk.cpp calculation method
Completed the calculation method for calculating distance between disk and other disk. 

# How to run the code and create the visualisation
1) Compile all the code into an executable using the command below:
"g++ -std=c++17 -g main.cpp system.cpp disk.cpp -o main.exe"

2) Execute the main.exe using the following command below:
"./main"

3) Run the view.py or view.ipynb code to output the visualisation created. 

