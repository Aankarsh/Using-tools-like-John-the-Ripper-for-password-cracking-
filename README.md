# EX - 7 Using-tools-like-John-the-Ripper-for-password-cracking
## AIM:
To crack password hashes using John the Ripper in Kali Linux.

## DESIGN STEPS:
### Step 1:
Right-click on the Desktop and choose Create Document → Empty Document.
 Name the file: scerect.txt.
 <img width="458" height="342" alt="step 1" src="https://github.com/user-attachments/assets/b35ca5d0-949a-4fc2-b45b-4d33620f3a27" />
• Open it and type:
<img width="842" height="496" alt="step 2" src="https://github.com/user-attachments/assets/43ea3aa1-16a5-42a1-9878-651448aca4c0" />

### Step 2: Create a Password-Protected ZIP File
Prepare the password hash file (e.g., using unshadow for Linux password and shadow files).
<img width="917" height="410" alt="step 3" src="https://github.com/user-attachments/assets/56f62a55-6e84-426a-bdc4-46d0aeefeac0" />
• Select .zip format.
• Click Other Options, set a password (e.g., 1234), then click Create.
<img width="908" height="402" alt="step 4" src="https://github.com/user-attachments/assets/0ae05740-9c1a-42d9-8c01-2793d8b0488f" />
A file named scerect.txt.zip will appear.

### Step 3: Confirm the ZIP File is Present
• Run: “ls” command
<img width="887" height="158" alt="step 5" src="https://github.com/user-attachments/assets/7bd96137-fc62-43c9-a966-81fbac931d2b" />

### Step 4: Generate Hash Using zip2john
• Execute:
<img width="960" height="53" alt="step 6" src="https://github.com/user-attachments/assets/d40c2bf0-5815-4ba5-923a-e6729cb6c598" />

### Step 5:Verify the Hash File (Optional)
• Open hash.txt to ensure it contains the hash line.
<img width="848" height="456" alt="step 7" src="https://github.com/user-attachments/assets/9df5edbe-24b7-44bd-8c01-4220b935dad6" />


### Step 6:Start Cracking the Password
• Run:
<img width="936" height="422" alt="step 8" src="https://github.com/user-attachments/assets/c748267a-a773-4787-b776-a63a91a0f719" />

### Step 7:View the Cracked Password
• After cracking is complete, reveal the password using:
<img width="1047" height="183" alt="step 9" src="https://github.com/user-attachments/assets/b3b7f0c5-eda7-4343-9376-c6b05452d5c5" />


## PROGRAM:
Password Cracking with John the Ripper

## OUTPUT:
Step 10: Result
• The terminal will display the filename and its cracked password.




## RESULT:
The password hashes were successfully cracked using John the Ripper.
