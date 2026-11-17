# NETWORKWALKS – Week 3: Password Cracking

**Participant:** Elizabeth Ogijoh  
**Programme:** NetworkWalks Cybersecurity and Ethical Hacking Internship  
**Week:** 3

## Project overview
This repository documents my completion of two assigned password-security lab exercises using the password-protected PDF supplied for the internship. The exercises introduced PDF hash extraction and password-recovery workflows, and demonstrated why strong, unique passwords matter.

> **Responsible use:** These tools should only be used on files, hashes, systems, and accounts you own or have explicit permission to assess. Do not publish the recovered password, complete PDF hash, or the protected PDF. Do not upload confidential documents to third-party services.

## Project Module 1 – Password Cracking with John the Ripper (JTR) and Johnny

### Tools
- John the Ripper (JTR)
- Johnny GUI
- PDF hash extraction tool specified in the assignment
- Windows PC and Notepad

### Workflow completed
1. Downloaded and installed John the Ripper on my Windows PC.
2. Installed Johnny and configured it to use `john.exe`.
3. Used the assigned password-protected PDF supplied for the lab.
4. Extracted the PDF hash using the method specified in the task.
5. Saved the complete hash in a text file named `hash1.txt`.
6. Loaded `hash1.txt` in Johnny using **Open password file**.
7. Started a new attack and allowed the recovery process to run.
8. Used the recovered password to open the assigned PDF and confirmed it opened successfully.

**Outcome: Completed.** The password was recovered through the JTR/Johnny workflow and the PDF opened successfully.

## Project Module 2 – Password Cracking with NetworkWalks Tools

### Tools
- NetworkWalks Hash Calculator
- NetworkWalks Password Cracker
- Windows laptop and web browser

### Workflow completed
1. Downloaded the assigned protected PDF from the NetworkWalks project lab page.
2. Uploaded the PDF to the NetworkWalks Hash Calculator.
3. Obtained and copied the complete PDF hash beginning with `$pdf$`.
4. Pasted the hash into the NetworkWalks Password Cracker.
5. Started the recovery process and waited for the result.
6. Entered the recovered password into the protected PDF.
7. Confirmed that the PDF opened successfully.

**Outcome: Completed.** The password was recovered using the NetworkWalks tools and the PDF opened successfully.

## Key learning outcomes
- Understood the relationship between a protected PDF and its stored password hash.
- Practised two approaches to password recovery: a locally installed tool and browser-based tools.
- Learned that short, common, or predictable passwords may be easier to recover.
- Recognised that extracted hashes are sensitive because they can be used for offline password guessing.

## Security recommendations
- Use long, unique passphrases.
- Avoid reusing passwords.
- Use a reputable password manager.
- Treat password hashes as sensitive information.
- Never test against files or systems without permission.
- Avoid uploading private documents to public tools unless explicitly authorised and the privacy implications are understood.

## Evidence
Add your own screenshots to `evidence/` before publishing. Suggested evidence:
1. `01-jtr-johnny-setup.png` – Johnny configured to use `john.exe`.
2. `02-jtr-hash-loaded.png` – hash file loaded in Johnny (mask the hash).
3. `03-jtr-recovery-result.png` – recovery result (hide the password).
4. `04-networkwalks-hash-calculator.png` – hash calculator result (hide the complete hash).
5. `05-networkwalks-password-cracker.png` – completion result (hide password and hash).
6. `06-pdf-opened.png` – PDF opened successfully, with private contents obscured.

**Do not upload:** the protected PDF, recovered password, complete hash, personal data, or confidential document contents. Follow your instructor's evidence requirements.

## Repository structure
```text
.
├── README.md
├── reports/
│   └── WEEK3-PROJECT-SUMMARY.md
└── evidence/
    └── README.md
```

**Author:** Elizabeth Ogijoh  
**NetworkWalks Cybersecurity and Ethical Hacking Internship – Week 3**
