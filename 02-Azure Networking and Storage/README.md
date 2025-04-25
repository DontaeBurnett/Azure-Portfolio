# 02-Azure Networking and Storage

This project demonstrates how to configure networking and storage services in Microsoft Azure. The goal is to create secure, scalable network environments and properly configured storage accounts.

---

## 🚀 Project Tasks

### 🔹 Step 1: Configure a Virtual Network (VNet)

1. Sign in to the [Azure Portal](https://portal.azure.com/).
2. Navigate to **Virtual Networks** > **+ Create**.
3. Select the **Subscription** and **Resource Group**.
4. Name your VNet (e.g., `MyVNet`) and select a region.
5. Add subnets (e.g., `FrontendSubnet`, `BackendSubnet`).
6. Review and create the VNet.

### 🔹 Step 2: Create a Network Security Group (NSG)

1. Go to **Network Security Groups** > **+ Create**.
2. Fill in the NSG name and associate it with the appropriate subnet.
3. Add inbound/outbound security rules to control traffic.
4. Associate the NSG with your VNet’s subnet or network interface.

### 🔹 Step 3: Set Up Azure Storage Account

1. Navigate to **Storage accounts** > **+ Create**.
2. Choose the resource group, name your storage account, and select a region.
3. Choose the **Standard** or **Premium** performance tier.
4. Enable **Blob, File, Queue, or Table storage** based on requirements.
5. Review and create the storage account.

### 🔹 Step 4: Upload and Access Data

1. Open the storage account and go to **Containers**.
2. Create a new container (e.g., `project2data`).
3. Upload sample files and test access using **Azure Storage Explorer** or **SAS token**.

---

## ✅ Summary

In this project, we configured a Virtual Network, applied security controls with NSGs, and created a storage account for secure data management. These foundational services support scalable cloud infrastructure in Azure.
