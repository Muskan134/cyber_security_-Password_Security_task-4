# Password Security & Authentication Analysis

## 1. Introduction
Passwords are used to protect user accounts and sensitive data.
This report explains how passwords are stored, why weak passwords
are unsafe, and how strong authentication methods improve security.

---

## 2. What is Hashing?
Hashing is a process of converting a password into a fixed-length
string called a hash. The original password cannot be retrieved
from the hash.

Example:
Password: hello123  
MD5 Hash: 482c811da5d5b4bc6d497ffa98491e38

---

## 3. Difference Between Hashing and Encryption

| Hashing | Encryption |
|-------|------------|
| One-way process | Two-way process |
| Original data cannot be recovered | Original data can be recovered using a key |
| Used for password storage | Used for secure data transmission |

---

## 4. Types of Password Hashes
- **MD5**: Fast and weak, easily crackable
- **SHA-1**: Better than MD5 but still weak
- **bcrypt**: Slow and strong, recommended for password storage

---

## 5. Password Attacks

### Dictionary Attack
In this attack, common passwords like `123456`, `password`, and
`admin` are tried using a wordlist.

### Brute Force Attack
In brute force attacks, all possible combinations of characters
are tried until the correct password is found.

Weak passwords are cracked quickly because they are short and common.

---

## 6. Why Weak Passwords Fail
- Easy to guess
- Short length
- Common words or numbers
- Same password used on multiple websites

---

## 7. Multi-Factor Authentication (MFA)
MFA adds an extra layer of security by requiring more than one
authentication factor such as:
- Password
- OTP sent to mobile/email
- Biometric verification

Even if the password is stolen, MFA protects the account.

---

## 8. Recommendations for Strong Authentication
- Use strong and unique passwords
- Password length should be at least 12 characters
- Use bcrypt for password hashing
- Enable Multi-Factor Authentication
- Do not reuse passwords

---

## 9. Conclusion
Password security is important to protect user data.
Using strong passwords, secure hashing algorithms, and MFA
can prevent most password-related attacks.
