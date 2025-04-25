# 01-Azure Compute and Identity Management

This project covers the deployment and management of compute resources in Microsoft Azure, along with implementing identity management using Azure Entra ID (formerly Azure AD).

---

## 🚀 Project Tasks

### 🔹 Step 1: Deploy a Virtual Machine (VM)

1. Log in to the [Azure Portal](https://portal.azure.com/).
2. Go to **Virtual Machines** > **+ Create**.
3. Select your **Subscription** and **Resource Group**.
4. Choose a VM name, region, and image (e.g., Windows Server 2022 or Ubuntu).
5. Configure the size, admin credentials, and inbound ports (e.g., RDP or SSH).
6. Review and create the VM.

### 🔹 Step 2: Connect and Test the VM

1. Once deployed, go to the VM overview page.
2. Click **Connect** and choose RDP or SSH based on OS.
3. Test login access using the credentials created earlier.

### 🔹 Step 3: Set Up Entra ID (Azure AD)

1. Navigate to **Microsoft Entra ID** > **Users**.
2. Create new users with defined roles.
3. Assign users to appropriate groups for access control.

### 🔹 Step 4: Assign Roles and RBAC

1. Go to **Subscriptions** > Select your subscription.
2. Under **Access control (IAM)**, add role assignments.
3. Assign roles (e.g., Reader, Contributor) to users/groups created in Entra ID.

---

## ✅ Summary

In this project, we deployed a virtual machine, connected to it securely, and used Microsoft Entra ID to manage users and access through role-based access control (RBAC). This is essential for secure compute and identity operations in Azure.
