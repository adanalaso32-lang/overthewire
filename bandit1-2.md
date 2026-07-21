Bandit Level 1 to 2

Goal: Find the password stored in a file called - in the home directory

Command used:
cat ./-

Password: PK8fYLZg2hnHSz83plBL1iEPKdD3QToB

What I learned:
Files that start with a hyphen cannot be read with cat directly because the terminal treats it as a command flag. Using ./ before the filename tells the terminal to treat it as a file in the current directory rather than an option.

Status: Completed

Screenshot
<img width="1215" height="172" alt="image" src="https://github.com/user-attachments/assets/db9ad70f-7503-449a-9463-4660975ca9ee" />
