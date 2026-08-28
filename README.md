# 🔐 Password Cracking & Recovery

## Networkwalks Cybersecurity Internship — Week 3

> **Practical:** Password Recovery & Hash Analysis  
> **Focus:** PDF Password Protection • Hash Extraction • John the Ripper

---

## 📌 Project Summary

This week's practical introduced me to password security and password recovery techniques.

I was provided with a password-protected PDF and challenged to recover the password through an authorized cybersecurity training exercise.

The practical allowed me to work through the complete process, from extracting the password hash to using a password-auditing tool and finally verifying the recovered password by opening the protected PDF.

---

# 🛠️ Resources Used

### 1. Networkwalks Hash Calculator

The Networkwalks Hash Calculator was used to process the password-protected PDF and extract the hash required for the password-recovery stage.

**Purpose:**
- Generate hashes
- Process files
- Extract a usable hash from a password-protected PDF

---

### 2. Johnny / John the Ripper

I used **Johnny**, the graphical interface for John the Ripper, to perform the password-recovery process.

The extracted PDF hash was loaded into the application and the password-recovery attack was started.

The tool successfully identified the password.

**Result:** ✅ Password recovered

---

### 3. Online HashCrack

Online HashCrack was also used as part of the password-auditing workflow.

The platform provides password-audit and recovery functionality for supported hash types and encrypted files.

---

# 🔄 THE ATTACK WORKFLOW

```text
              🔒 LOCKED PDF
                    │
                    ▼
        NETWORKWALKS HASH CALCULATOR
                    │
                    ▼
             📋 EXTRACTED HASH
                    │
                    ▼
              SAVE HASH LOCALLY
                    │
                    ▼
          JOHNNY / JOHN THE RIPPER
                    │
                    ▼
          🔑 PASSWORD RECOVERED
                    │
                    ▼
             🔓 UNLOCK PDF
                    │
                    ▼
             ✅ ACCESS VERIFIED
🔎 STEP 1 — IDENTIFYING THE LOCKED FILE

The exercise started with a PDF that required a password before its contents could be accessed.

My objective was to recover the password using the tools provided during the training.

🧮 STEP 2 — HASH EXTRACTION

I opened the onlinehashcrack.com and used the PDF option to process the protected document.

The tool was designed to generate or extract the hash required for further password analysis.

The resulting hash became the input for the next stage.

📂 STEP 3 — PREPARING THE HASH

After obtaining the hash, I saved it locally and prepared it for use with John the Ripper.

This stage helped me understand how password-auditing tools work with extracted hash data rather than directly attacking the original document.

⚔️ STEP 4 — PASSWORD RECOVERY WITH JOHNNY

I opened Johnny, the graphical interface for John the Ripper.

The extracted PDF hash was loaded into the application.

The password-recovery process was then started.

The screenshot from the exercise shows the PDF hash loaded into Johnny and the password field populated after the recovery process.

Result

Password successfully recovered — 1/1 cracked. ✅

🔓 STEP 5 — VERIFYING THE PASSWORD

After the password was recovered, I used it to open the original protected PDF.

The file opened successfully, confirming that the recovered password was correct.

Hash → Password Recovery → Password → PDF Access
                              │
                              ▼
                         ✅ VERIFIED
🧰 STEP 6 — NETWORKWALKS HASH CALCULATOR

Another important part of the practical was working with the Networkwalks Hash Calculator.

The interface provided options for:

Text hashing
File hashing
PDF processing
Hash generation
PDF password-hash extraction

This helped me understand that different types of files and data can require different approaches when performing password-security assessments.

🧠 WHAT I LEARNED

This practical changed the way I understand password protection.

I learned that a password-protected document is not simply a file that can only be opened by entering a password.

During a security assessment, password-verification information can potentially be extracted and tested offline.

I also learned how tools such as John the Ripper can be used to assess password strength in an authorized environment.

⚠️ SECURITY OBSERVATIONS
🔑 Weak passwords can be recovered

A password that is short, predictable, or commonly used may be easier to recover.

🧩 Hashes are valuable security information

If password-related hash data is exposed, it can potentially be subjected to offline password-testing attacks.

🔐 Strong passwords matter

Long, unique passwords make password-recovery attempts more difficult.

♻️ Password reuse increases risk

Using the same password across multiple services can increase the impact of a compromised password.

🛡️ SECURITY RECOMMENDATIONS
Use long, unique passwords.
Avoid common and predictable passwords.
Never reuse passwords for sensitive accounts.
Protect password hashes and authentication data.
Use multi-factor authentication where available.
Regularly audit password security within authorized environments.
Protect sensitive documents with strong encryption and access controls.
📸 PRACTICAL EVIDENCE

The following evidence was collected during the exercise:

Hash Calculator

The Networkwalks Hash Calculator was used during the hash-generation/extraction stage.

Johnny / John the Ripper

Evidence shows the PDF hash loaded into Johnny and the successful password-recovery result.

Online HashCrack

Evidence shows the password-audit/recovery resource used during the exercise.

Completion

The Networkwalks completion/flag screen confirms successful completion of the practical.

🏁 RESULT
Activity	Status
Locked PDF identified	✅
Hash extracted	✅
Hash prepared	✅
John the Ripper installed	✅
Hash loaded into Johnny	✅
Password recovered	✅
Password verified	✅
Training exercise completed	✅
💭 FINAL REFLECTION

Week 3 gave me practical experience with password security and password recovery.

I learned how to move from a protected PDF to its hash representation, prepare that hash for analysis, use John the Ripper through Johnny, recover the password, and verify the result by opening the original document.

The biggest lesson I took from this exercise is that password strength is a critical part of information security.

As I continue my cybersecurity journey, I am learning not only how attackers can identify weaknesses, but also how security professionals can use these techniques responsibly to identify and reduce those weaknesses.

🚀 CYBERSECURITY JOURNEY

Learn → Practice → Analyze → Secure
