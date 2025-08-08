
# 📧  Email Validation

A simple and efficient Python program to validate email addresses based on standard email formatting rules.  
It checks if the given email follows correct syntax and structure.

## ✨ Features
- Checks for `@` symbol presence
- Validates domain format
- Ensures proper username and domain name
- Displays clear error messages for invalid emails
- Lightweight and easy to use

## 📦 Requirements
- Python 3.x

## 🚀 How to Use
1. **Clone the repository**  
   ```bash
   git clone https://github.com/Sakshi9335/Email-Validation.git
````

2. **Navigate to the project folder**

   ```bash
   cd Email-Validation
   ```
3. **Run the program**

   ```bash
   python email_validation.py
   ```
4. **Enter your email** when prompted — the program will tell you if it is valid or invalid.

## 🖥️ Example

**✅ Valid Email**

```bash
Enter your email: sakshishu10@gmail.com
Valid Email ✅
```

**❌ Invalid Email**

```bash
Enter your email: sakshi@.com
Invalid Email ❌
Reason: Domain name is not valid
```

## 📊 Flow Diagram

```
        ┌─────────────────────┐
        │   Start Program     │
        └───────┬─────────────┘
                │
                ▼
     ┌──────────────────────┐
     │ Input Email Address   │
     └─────────┬────────────┘
               │
               ▼
   ┌──────────────────────────┐
   │ Check '@' in email?      │
   └───────┬────────┬─────────┘
           │        │
        Yes ▼     No ▼
   ┌──────────────────────────┐   ┌──────────────────────┐
   │ Check domain format      │   │  Invalid Email ❌     │
   └───────┬────────┬─────────┘   └──────────────────────┘
           │        │
        Yes ▼     No ▼
   ┌──────────────────────────┐   ┌──────────────────────┐
   │ Display "Valid Email ✅" │   │  Invalid Email ❌     │
   └──────────────────────────┘   └──────────────────────┘
```

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

