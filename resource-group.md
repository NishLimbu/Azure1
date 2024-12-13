# How to Use Azure: Resource Groups and Storage Accounts

This tutorial extends the process of creating an Azure account by demonstrating how to create a Resource Group and a Storage Account.

---

## Table of Contents
- [Introduction](#introduction)
- [Step 1: Create a Resource Group](#step-1-create-a-resource-group)
- [Step 2: Create a Storage Account](#step-2-create-a-storage-account)
- [Conclusion](#conclusion)

---

## Introduction

Azure's **Resource Groups** help organize resources logically for easier management. A **Storage Account** is a scalable cloud storage solution for files, blobs, queues, and tables.

---

## Step 1: Create a Resource Group

1. Log into the [Azure Portal](https://portal.azure.com).
2. In the left-hand menu, select **Resource Groups**.
3. Click **+ Create**.

   ![Create Resource Group Button](./images/create-resource-group-button.png)

4. Fill out the required details:
   - **Subscription:** Select your Azure subscription.
   - **Resource Group Name:** Enter a unique name (e.g., `my-first-resource-group`).
   - **Region:** Choose the location where your resources will reside.

   ![Resource Group Form](./images/resource-group-form.png)

5. Click **Review + Create**, then **Create**.

---

## Step 2: Create a Storage Account

1. Navigate to **Storage Accounts** from the Azure Portal menu.
2. Click **+ Create**.

   ![Create Storage Account Button](./images/create-storage-account-button.png)

3. Fill out the required details:
   - **Subscription:** Choose your subscription.
   - **Resource Group:** Select the group you just created.
   - **Storage Account Name:** Enter a globally unique name (e.g., `myfirststorageacct`).
   - **Region:** Select a region (preferably the same as your resource group).
   - **Performance:** Choose **Standard** for general-purpose storage.
   - **Replication:** Select a replication option (e.g., **Locally-redundant storage**).

   ![Storage Account Form](./images/storage-account-form.png)

4. Click **Review + Create**, then **Create**.

---

## Conclusion

Congratulations! You've successfully created:
- A Resource Group for logical resource organization.
- A Storage Account for scalable cloud storage.
