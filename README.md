# Azure DevOps - Create Repository and Provide Access

This guide explains step-by-step how to create a new repository in Azure DevOps and grant access to other users.  
Beginner-friendly and written for first-time Azure DevOps users.

---

## 1. Sign in to Azure DevOps
1. Go to [https://dev.azure.com/](https://dev.azure.com/).
2. Sign in using your Microsoft Work/School account.
3. You will be redirected to your Azure DevOps **Organization Dashboard**.

---

## 2. Create or Open a Project
A repository must belong to a project.

- **If you already have a project** → Click the project name to open it.
- **If you don’t have a project**:
  1. Click **New Project** (top-right).
  2. Fill in:
     - **Project Name** (e.g., `MyFirstProject`)
     - **Visibility** → Select **Private** (recommended for internal use)
  3. Click **Create**.

---

## 3. Create a New Repository
1. In the left sidebar, click **Repos**.
2. At the top, click the **repository dropdown** (next to the repo name).
3. Select **New repository**.
4. Fill in:
   - **Repository name** (e.g., `MyFirstRepo`)
   - **Add a README** → ✅ Recommended
5. Click **Create**.

---

## 4. Provide Access to a User
1. In the left sidebar, click **Project settings** (bottom-left).
2. Under **General**, go to **Permissions** → **Users**.
3. Click **Add** (top-right).
4. Enter the **user’s email address**.
5. Assign a role:
   - **Project Readers** → Read-only
   - **Contributors** → Can clone, push code, create branches
   - **Project Administrators** → Full control (use cautiously)
6. Click **Add**.

---

## 5. Verify Access
- The invited user will receive an **email invitation**.
- After accepting, they can access the repository via your Azure DevOps organization URL.
- To confirm access: **Project settings → Permissions → Users**.

---

## 📌 Recommended Roles
- **Contributor** → For team members who need to work on the code.
- **Reader** → For users who only need to view code.
- **Administrator** → For project managers or leads with full permissions.

---

**Author:** Xitiz Basnet 
**Last Updated:** August 14, 20925  
