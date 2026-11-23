**Cybersecurity &amp; Ethical Hacking Internship – Networkwalks**

**Project Overview**

This project focused on understanding password cracking techniques using an encrypted PDF as the target. I worked with Networkwalks tools and John the Ripper to extract the PDF hash, test password combinations, and recover the correct password.

**Modules Completed**

Module		Description
	
W3-PM1	Password Cracking with John the Ripper
W3-PM2	Password Cracking with Networkwalks Tools

**Tools and Technologies**

Tool	Purpose
Kali Linux	Environment used to run John the Ripper
John the Ripper (JtR)	Testing password combinations against the extracted PDF hash
Networkwalks Hash Calculator	Extracting the PDF hash
Networkwalks Password Cracker	Testing the hash using a built-in password list

**Phase 1: Hash Extraction and Password Testing (W3-PM2)**

**Objective**

To extract the password hash from the encrypted PDF and test it using the Networkwalks tools.

Activities Performed

1. Extracting the PDF Hash

I uploaded the protected file (My Locked PDF2.pdf") to the Networkwalks Hash Calculator to extract its hash.

The tool generated a hash that could be used for password-cracking activities.

Figure 1: Hash extracted using the Networkwalks Hash Calculator.

<img width="953" height="992" alt="image" src="https://github.com/user-attachments/assets/398c4a4d-afde-4512-b77d-91ea71eed602" /># W3-PM1-FINAL-Password-Cracking-Final-Report

2. Testing the Extracted Hash

I copied the extracted hash into the Networkwalks Password Cracker and tested it against its built-in list of 100 passwords.

The tool found a match.

Key Learning Outcomes

Learned how to extract password hashes from protected PDF files.

Understood the purpose of hash extraction before offline password testing.

Learned that smaller password lists may not contain the correct password.

**Phase 3: Password Verification**

**Objective**

To confirm that the recovered password was correct and access the protected PDF.

Activities Performed

I used the recovered password to open My Locked PDF1.pdf. The password worked, and I was able to access the document.

I then located and captured the flag provided in the PDF.

Captured Flag:

nw{networkwalks_flag_260821_1}

Figure 3: Successfully opening the protected PDF and capturing the flag.

<img width="1048" height="857" alt="PPPDF" src="https://github.com/user-attachments/assets/3a8d48a5-18d5-4486-8650-934f5992ee3f" />


Key Learning Outcomes

Through this project, I gained practical experience in:

Extracting password hashes from encrypted PDF files.

Understanding how dictionary attacks work.

Using John the Ripper to test password combinations.

Understanding why strong and unique passwords are important for protecting files.

Conclusion

I completed both Week 3 modules by extracting the PDF hash, testing it with the available tools, recovering the password, and verifying access to the protected document.

The exercise gave me practical experience with password cracking and a better understanding of how weak passwords can be exposed through dictionary attacks.
