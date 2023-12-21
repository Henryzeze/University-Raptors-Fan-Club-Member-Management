# University-Raptors-Fan-Club-Member-Management

![University Raptors Fan Club](university_fan_club_membership_banner.jpg)

### Problem

The local university's Raptors fan club maintains a register of its active members on a .txt document. Each month, they update the file by removing members who are not active. The task is to automate this process using Python skills.

Given the file currentMem.txt, the objective is to remove each member with a 'no' in their 'Active' column and retain the format of the original files. Additionally, keep track of the removed members and append them to the exMem.txt file. This should be achieved by reading/writing whole lines and ensuring the header remains intact.

### Solution Overview

The solution involves writing a Python script to handle the removal of inactive members from the currentMem.txt file while preserving the file's structure. The script will identify and remove members with 'no' in their 'Active' column and append them to the exMem.txt file.

### Code Skeleton

The provided code skeleton includes a function cleanFiles() where the main logic needs to be implemented. The function performs the required operations to clean the member files as per the problem statement.

![](University Raptors Fan Club Member Management python code.png)

### Getting Started

To run the code, execute the provided cleanFiles() function after setting up the necessary environment and ensuring the files currentMem.txt and exMem.txt are in place.

### Instructions

1. Ensure Python is installed on your system.
2. Open the Python script containing the cleanFiles() function.
3. Implement the logic inside the cleanFiles() function based on the problem statement.
4. Run the script to execute the cleaning process.

### Files

currentMem.txt: Contains the register of active members.
exMem.txt: File to append removed members.

### Usage

Modify the cleanFiles() function as instructed in the comments of the provided Python script and execute the script to automate the process.

### Contributing

Contributions are welcome! Feel free to submit issues or pull requests.
