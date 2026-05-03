# 🚀 Day 03 – IAM (Identity & Access Management)

---

## 📌 Overview

On Day 03, I explored **Identity and Access Management (IAM)**, which is used to securely control access to cloud resources.

---

## 🔐 What is IAM?

IAM is a service that helps you manage **who can access what resources** in the cloud.

---

## 👤 Core Components of IAM

### 1. Users

* Individual accounts for people or services
* Example: Developer, Admin

### 2. Groups

* Collection of users
* Permissions can be assigned to groups

### 3. Roles

* Temporary access permissions
* Used by services or external users

### 4. Policies

* JSON-based rules that define permissions
* Example: Allow access to S3

---

## 🔑 Types of Access

* **Authentication** → Who are you?
* **Authorization** → What can you do?

---

## 🛡️ Best Practices

* Use **least privilege principle**
* Avoid using root account
* Enable **Multi-Factor Authentication (MFA)**
* Use roles instead of sharing credentials
* Rotate access keys regularly

---

## ⚙️ Workflow Diagram

![IAM Workflow](diagram.png)

### (Text Version)

```plaintext
User Login
   ↓
Authentication (Username + Password / MFA)
   ↓
IAM Policy Check
   ↓
Access Granted / Denied
```

---

## 🌍 Real-World Use Cases

* Restrict developer access to only specific services
* Grant temporary access to applications
* Secure cloud resources from unauthorized users

---

## 🧠 What I Learned

* IAM fundamentals
* Users, Roles, Policies
* Authentication vs Authorization
* Security best practices

---

## 🚀 Next Step (Day 04)

* Compute Services (EC2 / Azure VM)
* Launching virtual machines

---

## 📌 Author

**Sankar S**
Cloud & AI Learning Journey 🚀
