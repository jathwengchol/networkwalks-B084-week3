# Week 3 - Password Cracking - Project Modules 1 & 2
Name: Jathweng Chol
Course: NetworkWalks - Cybersecurity & Ethical Hacking
Week:Week 3

## Objective
Recover the password of a protected PDF using two different methods, to understand how password cracking works and why strong passwords matter.

## Method 1: Project Module 1 - John the Ripper + Johnny GUI
Tools: John the Ripper (John) + Johnny GUI on Windows
What I Did:
1. Downloaded and installed John the Ripper and Johnny GUI
2. Uploaded the locked PDF to PDF Hash Extractor to get its hash
3. Saved the hash
4. Opened hash1.txt in Johnny and started a new attack
5. Recovered the password and used it to open the PDF
Result:
- Hash File: hash1.txt
- Cracked Password:password1
- Status: PDF successfully opened

## Method 2: Project Module 2 - NetworkWalks Tools (No Install)
Tools: NetworkWalks Hash Calculator + NetworkWalks Password Cracker - in browser only
What is Hashing?
Hashing is one-way. It scrambles a password into a unique value like $pdf$...
You cannot reverse it directly, you have to try passwords until one matches the hash.
What I Did:
1. Downloaded My Locked PDF1.pdf from the lab page
2. Uploaded it to Hash Calculator - networkwalks.com/hash-calculator/
3. Got the hash starting with $pdf$...
4. Copied the full hash
5. Pasted the hash into Password Cracker - networkwalks.com/password-cracker/
6. Started the attack and waited
7. Got the cracked password and opened the PDF

## Key Learning
A simple password like password1 can be cracked very fast.
A simple 8-character lowercase password can be cracked in minutes, while a strong 12-character mixed password can take many years.
Always use long, strong, unique passwords.
## screenshots
### PM1 - John the Ripper + Johnny
![Johnny cracked password](<screenshots/All passwords.png>)
### PM2 - NetworkWalks Tools
![Password Cracker](<screenshots/password 1.png>)
![Password Cracker](<screenshots/password 2.png>)
![Password Cracker](<screenshots/password 3.png>)
## Skills
Password Cracking, Hashing, John the Ripper, Johnny GUI, Hash Calculator, Ethical Hacking Documentation