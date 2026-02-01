# Lab 1 – Azure Blob Storage (AZ-104)

This lab demonstrates how to create and manage Azure Blob Storage using the Azure Portal.

---

## 🎯 Lab Objectives

- Create a resource group for storage
- Create a Storage Account (GPv2)
- Configure redundancy and region
- Create blob containers
- Upload blobs
- Create virtual directories
- Change blob access tiers
- Verify private access behavior

---

## 🧪 Lab Tasks Performed

### 1️⃣ Resource Group Creation
- Created a dedicated resource group for storage labs.

### 2️⃣ Storage Account Creation
- Created a General Purpose v2 (StorageV2) account.
- Region: UK South
- Performance: Standard
- Redundancy: LRS

### 3️⃣ Container Creation
- Created private blob containers.
- Verified anonymous access is disabled.

### 4️⃣ Blob Upload
- Uploaded image files as block blobs.

### 5️⃣ Virtual Directory Structure
- Created a logical folder structure inside the container.

### 6️⃣ Blob Access Tier Management
- Changed blob access tier from Hot to Cool.

### 7️⃣ Access Verification
- Attempted direct public URL access.
- Verified private access restriction.

---

## 📸 Screenshots

### 1️⃣ Resource Group Created
![Resource Group](screenshots/01-resource-group.png)

---

### 2️⃣ Storage Account Overview
![Storage Account Overview](screenshots/02-storage-account-overview.png)

---

### 3️⃣ Private Blob Container Created
![Private Container](screenshots/03-container-private.png)

---

### 4️⃣ Blobs Uploaded
![Uploaded Blobs](screenshots/04-uploaded-blobs.png)

---

### 5️⃣ Virtual Directory Created
![Virtual Directory](screenshots/05-virtual-directory.png)

---

### 6️⃣ Blob Access Tier Changed
![Access Tier](screenshots/06-blob-access-tier.png)

---

### 7️⃣ Private Access Test (Expected Failure)
![Private Access Test](screenshots/07-private-access-test.png)


---

## ✅ Result

Successfully configured Azure Blob Storage with private access and validated storage behavior according to AZ-104 exam requirements.
