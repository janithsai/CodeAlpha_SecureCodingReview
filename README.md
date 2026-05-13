# CodeAlpha_SecureCodingReview
# Secure Coding Review Report

## Project Description
This project reviews a Python login application to identify security vulnerabilities and improve secure coding practices.

---

## Vulnerabilities Identified

### 1. Hardcoded Credentials
Username and password are directly written in the code.

**Risk:** Credentials may be exposed if source code is leaked.

**Recommendation:** Store credentials securely.

---

### 2. Plain Text Passwords
Passwords are compared in plain text.

**Risk:** Passwords can be easily stolen.

**Recommendation:** Use password hashing techniques.

---

### 3. No Input Validation
User inputs are not validated.

**Risk:** Can cause security issues and unexpected behavior.

**Recommendation:** Validate and sanitize inputs.

---

## Secure Coding Best Practices

- Use password hashing
- Avoid hardcoded credentials
- Validate user inputs
- Use secure authentication methods

---

## Conclusion

The review identified multiple vulnerabilities in the application. Implementing secure coding practices improves application security and protects user data.
