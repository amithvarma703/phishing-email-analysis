# phishing-email-analysis
Task 2: Analyzing a sample phishing email and identifying red flags.
📄 Phishing_Email_Analysis_Report.md
# 📧 Phishing Email Analysis Report

**Task:** Internship Task 2 – Analyze a Phishing Email Sample  
**Prepared by:** Amith Varma  
**Date:** June 2025

---

## 📝 Sample Phishing Email

From: PayPal Support support@paypa1.com
To: your-email@gmail.com
Subject: Urgent: Your Account Has Been Suspended

Dear Customer,

We noticed suspicious activity in your PayPal account.

To protect your account, we have temporarily suspended it.

👉 Please click the link below and confirm your identity:
https://paypal.com.verify-info-login.com

If you don’t do this in 24 hours, your account will be permanently locked.

Sincerely,
PayPal Team



---

## 🔍 Phishing Indicators Identified

### 1. 🚨 Spoofed Email Address
- **Real PayPal domain:** `paypal.com`
- **This sender:** `paypa1.com` → using number "1" instead of letter "l"
- ✅ **Clearly fake**

---

### 2. 🌐 Suspicious URL
- **Shown:** `https://paypal.com.verify-info-login.com`
- **Actual Domain:** `verify-info-login.com` (NOT PayPal)
- ✅ **Designed to trick users into thinking it's PayPal**

---

### 3. ⚠️ Urgent/Threatening Language
- "Act in 24 hours or your account will be locked."
- ✅ Creates fear to make the victim click quickly

---

### 4. 👁️ Mismatched Links (if HTML)
- Link might *look* like PayPal, but hovering reveals the real (malicious) link
- ✅ Common tactic in phishing

---

### 5. 🔡 Generic Greeting
- “Dear Customer” instead of using the real name
- ✅ Sign of mass phishing, not official communication

---

## ✅ Summary of Phishing Traits

| No. | Trait                           | Details                                           |
|-----|----------------------------------|---------------------------------------------------|
| 1   | Fake Email Address              | `support@paypa1.com`                              |
| 2   | Tricky Link                     | Fake PayPal URL to steal data                    |
| 3   | Urgent Language                 | Threatens with account lock                      |
| 4   | Generic Greeting                | Not personalized                                 |
| 5   | Spoofed Domain                  | "paypal" inside a malicious domain               |

---

## 🛡️ Conclusion

This email is a **phishing attempt**. It uses:
- A **spoofed sender address**
- A **fake login link**
- **Urgency and fear tactics**

📢 Do not click on links or enter any information. Always verify the sender and domain carefully.


Thank You
