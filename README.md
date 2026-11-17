# Week 3: Password Cracking Using John the Ripper(JTR) & Networkwalks Tools

## Project overview
This repository documents my completion of two assigned password-security lab exercises using the password-protected PDF supplied for the internship. The exercises introduced PDF hash extraction and password-recovery workflows, and demonstrated why strong, unique passwords matter.

> **Responsible use:** These tools should only be used on files, hashes, systems, and accounts you own or have explicit permission to assess. Do not publish the recovered password, complete PDF hash, or the protected PDF. Do not upload confidential documents to third-party services.

## Project Module 1 – Password Cracking with John the Ripper (JTR) and Johnny

### 🛠️Tools
- John the Ripper (JTR)
- Johnny GUI
- PDF hash extraction tool specified in the assignment
- Windows PC and Notepad

### Workflow completed
1. Downloaded and installed John the Ripper on my Windows PC.
2. Installed Johnny and configured it to use `john.exe`.


<img width="876" height="705" alt="JTR GUI" src="https://github.com/user-attachments/assets/57cdbe01-8517-4849-90f8-b13680ae399f" />

  
3. Used the assigned password-protected PDF supplied for the lab.
4. Extracted the PDF hash using the method specified in the task.

<img width="1121" height="716" alt="JTR HASH LOADED" src="https://github.com/user-attachments/assets/fef7644e-14b0-409b-865c-a7871a2a8ee3" />

 
5. Saved the complete hash in a text file named.
6. Loaded `hash in Johnny using **Open password file**.
7. Started a new attack and allowed the recovery process to run.
8. Used the recovered password to open the assigned PDF and confirmed it opened successfully.


<img width="871" height="712" alt="JTR RECOVERY RESULT" src="https://github.com/user-attachments/assets/90573a6e-6837-41f7-8785-06ff14a82d3e" />
  

**Outcome: Completed.** The password was recovered through the JTR/Johnny workflow and the PDF opened successfully.


<img width="634" height="894" alt="PDF 1" src="https://github.com/user-attachments/assets/cda85d47-68e4-4348-9bcb-3ce8edbe83c7" />


<img width="835" height="765" alt="PDF 2" src="https://github.com/user-attachments/assets/1f1419de-7a5a-419e-84fa-271275e4b07a" />


<img width="1045" height="843" alt="PDF 3" src="https://github.com/user-attachments/assets/d71db62d-851a-463d-a2af-ba16d46ef118" />


## Project Module 2 – Password Cracking with NetworkWalks Tools

### 🛠️Tools
- NetworkWalks Hash Calculator
- NetworkWalks Password Cracker
- Windows laptop and web browser

### Workflow completed
1. Downloaded the assigned protected PDF from the NetworkWalks project lab page.
2. Uploaded the PDF to the NetworkWalks Hash Calculator.


<img width="1477" height="881" alt="NETWORKWALKS HASH CALCULATOR" src="https://github.com/user-attachments/assets/ba75c2bc-7b88-421b-89dd-ed0a11a4e510" />


3. Obtained and copied the complete PDF hash beginning with `$pdf$`.
4. Pasted the hash into the NetworkWalks Password Cracker.


<img width="1398" height="813" alt="NETWORKWALKS PASSWORD CRACKER" src="https://github.com/user-attachments/assets/919ccf7b-2873-47ea-a4f3-f8936797986e" />


5. Started the recovery process and waited for the result.
6. Entered the recovered password into the protected PDF.


<img width="916" height="862" alt="NETWORKWALKS RECOVERY RESULT" src="https://github.com/user-attachments/assets/13b279a9-b2e4-426a-b58e-256699993a1c" />


7. Confirmed that the PDF opened successfully.

**Outcome: Completed.** The password was recovered using the NetworkWalks tools and the PDF opened successfully.

## Key learning outcomes
- Understood the relationship between a protected PDF and its stored password hash.
- Practised two approaches to password recovery: a locally installed tool and browser-based tools.
- Learned that short, common, or predictable passwords may be easier to recover.
- Recognised that extracted hashes are sensitive because they can be used for offline password guessing.

## 🔒Security recommendations
- Use long, unique passphrases.
- Avoid reusing passwords.
- Use a reputable password manager.
- Treat password hashes as sensitive information.
- Never test against files or systems without permission.
- Avoid uploading private documents to public tools unless explicitly authorised and the privacy implications are understood.

**Author:** Elizabeth Ogijoh  
**NetworkWalks Cybersecurity and Ethical Hacking Internship – Week 3**
