# AZ-104 – Blob Storage Lab

This lab demonstrates how to implement and manage Azure Blob Storage using the Azure Portal, aligned with **Domain 2 – Implement and manage storage** of the AZ-104 exam.

---

## Objectives

- Create a storage account
- Configure blob containers
- Upload and manage blobs
- Use virtual directories
- Change blob access tiers
- Validate private access behavior

---

## Step 1 – Create Resource Group

A dedicated resource group was created to isolate all storage resources used in this lab.

![Resource Group](screenshots/01-resource-group.png)

---

## Step 2 – Create Storage Account

A General Purpose v2 (StorageV2) storage account was created with the following configuration:

- Region: UK South  
- Performance: Standard  
- Replication: LRS  

![Storage Account Overview](screenshots/02-storage-account-overview.png)

---

## Step 3 – Create Private Blob Container

A blob container was created with **private access level**, ensuring blobs are not accessible anonymously.

![Private Container](screenshots/03-container-private.png)

---

## Step 4 – Upload Blobs

Sample image files were uploaded into the container to validate blob operations.

![Uploaded Blobs](screenshots/04-uploaded-blobs.png)

---

## Step 5 – Create Virtual Directory

A virtual directory structure (`reports/`) was created to logically organize blobs within the container.

![Virtual Directory](screenshots/05-virtual-directory.png)

---

## Step 6 – Change Blob Access Tier

The blob access tier was modified from **Hot** to **Cool** to demonstrate cost-optimization capabilities.

![Blob Access Tier](screenshots/06-blob-access-tier.png)

---

## Step 7 – Validate Private Access

Direct public access to the blob URL was tested and correctly failed with a **ResourceNotFound** error, confirming private access behavior.

![Private Access Test](screenshots/07-private-access-test.png)

---

## Result

- Azure Blob Storage successfully configured
- Private access enforced
- Data organization and tiering validated
- Storage concepts aligned with AZ-104 exam objectives
