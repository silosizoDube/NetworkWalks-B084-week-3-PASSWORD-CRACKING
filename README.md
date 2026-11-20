# NetworkWalks-B084-week-3-PASSWORD-CRACKING# NetworkWalks Cybersecurity Internship – Week 3

## Password Cracking with John the Ripper & NetworkWalks Tools

**Name:** Silosizo Dube  
**Batch:** B084  
**Program:** NetworkWalks Cybersecurity Internship  
**Week:** 03  
**Project:** Password Cracking (PM1 + PM2)

---

## Objective

The objective of this practical was to understand how password-protected files can be tested for password strength by extracting their password hashes and using password-cracking tools.

The practical covers two approaches:

1. John the Ripper (JTR) with the Johnny graphical user interface.
2. NetworkWalks Hash Calculator and Password Cracker web tools.

The exercise demonstrates the importance of strong passwords and the risks associated with weak or commonly used passwords.

---

## PM1 — Password Cracking with John the Ripper

**Tools Used:**

- John the Ripper 1.9.0 Jumbo (Windows 64-bit)
- Johnny GUI
- Windows PowerShell
- PDF hash extraction utility

**Target File:** `My Locked PDF1.pdf`

### Steps Performed

**1. Downloaded and extracted John the Ripper**

Downloaded the John CLI Windows 64-bit package and extracted its contents.

**2. Verified John the Ripper installation**

Opened PowerShell in the John `run` directory and executed the help command to confirm that John was working.

Command used:

```powershell
.\john.exe --help
```

**3. Installed Johnny GUI**

Installed the Johnny graphical interface on the Windows laptop.

**4. Configured Johnny**

Used the John executable path setting in Johnny to locate the John CLI executable.

**5. Extracted the PDF password hash**

Generated the PDF hash for the supplied training document.

**6. Loaded the hash and performed password recovery**

Used John the Ripper and Johnny to process the extracted hash and recover the PDF password.

**7. Verified the recovery**

Confirmed the password recovery using the supplied training PDF.

### Evidence

<img width="657" height="436" alt="extractionScreenshot" src="https://github.com/user-attachments/assets/dc07e163-63cb-4be7-a5d8-72a0bdae76ee" />

<img width="1366" height="768" alt="johnCLIrunningScreenshot" src="https://github.com/user-attachments/assets/83487232-ce08-4b64-8950-bc468c8a1168" />
<img width="890" height="539" alt="hashEstractionScreenshot" src="https://github.com/user-attachments/assets/04a2d2dd-8d5c-4bba-931e-61d4e8a888ae" />

<img width="1366" height="768" alt="passwordRecoveryScreenshot" src="https://github.com/user-attachments/assets/f62ef1ea-6696-4add-b561-7d14ddb10ab4" />

<img width="840" height="512" alt="insertingPasswordsScreenshot" src="https://github.com/user-attachments/assets/d8f3a94c-0680-4c33-a396-8dd511274f4e" />

<img width="1366" height="768" alt="resultsScreenshot" src="https://github.com/user-attachments/assets/5bd534e0-c008-498a-9985-de118a4ca988" />



## PM2 — Password Cracking with NetworkWalks Tools

**Tools Used:**

- NetworkWalks Hash Calculator
- NetworkWalks Password Cracker
- Google Chrome
- Windows 11

**Target File:** `My Locked PDF1.pdf` (NetworkWalks PM2 training file)

### Steps to Be Documented

1. Opened the NetworkWalks Hash Calculator.
2. Selected the supplied password-protected PDF.
3. Extracted the PDF password hash.
4. Copied the extracted hash.
5. Opened the NetworkWalks Password Cracker.
6. Submitted the hash for password recovery.
7. Recorded the recovery result.
8. Verified the recovered password by opening the supplied PDF.

### Evidence

<img width="1366" height="768" alt="hashScreenshot" src="https://github.com/user-attachments/assets/9e2992b3-1051-460d-abfb-dbfacadbe255" />

<img width="1366" height="768" alt="passwordsuccess" src="https://github.com/user-attachments/assets/859d7669-cb23-4f4d-9365-0cf4c7961cac" />

<img width="1366" height="768" alt="recovery result screenshot" src="https://github.com/user-attachments/assets/6c4a4c40-d311-4fd8-9f34-4987985ed7f6" />


*These PM2 steps and evidence are to be updated after completing the practical.*


## Security Lessons Learned

- Password hashes can be extracted from password-protected files for authorized security testing.
- Weak and commonly used passwords are more vulnerable to dictionary-based attacks.
- John the Ripper provides command-line password-testing capabilities.
- Johnny provides a graphical interface for working with John the Ripper.
- Strong, long, and unique passwords improve security.
- Password recovery tools should only be used on files for which permission has been granted.

---

## Conclusion

The Week 3 practical introduced password cracking through both command-line and graphical tools.

In PM1, John the Ripper and Johnny were used to test password recovery on the supplied training PDF. This provided practical experience with installing the tools, configuring the executable path, extracting a PDF hash, and recovering the password.

PM2 extends this knowledge by introducing the NetworkWalks online Hash Calculator and Password Cracker tools.

Together, these exercises demonstrate the importance of password strength and responsible security testing.

---

**Program:** NetworkWalks Cybersecurity Internship  
**Batch:** B084  
**Week:** 03
