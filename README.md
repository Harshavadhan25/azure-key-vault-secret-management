# 🔐 Azure Key Vault Secret Management (RBAC)

This project demonstrates secure secret management using **Azure Key Vault**, 
**RBAC-based access control**, and **runtime secret retrieval** to authenticate 
to **Azure Storage**.

---

## 🚀 Features
- Azure Key Vault with RBAC enabled
- Secure storage of secrets (API keys, DB passwords)
- Service Principal–based authentication
- Runtime secret retrieval using Python
- No hardcoded credentials
- Azure Storage authentication using retrieved secret

---

## 🧱 Architecture
Python Script → Azure AD (Service Principal) → Azure Key Vault → Azure Storage

---

## 📦 Tech Stack
- Azure Key Vault
- Azure Active Directory
- Azure Storage
- Python (Azure SDK)
- RBAC


git clone https://github.com/<your-username>/azure-key-vault-secret-management.git
cd azure-key-vault-secret-management
