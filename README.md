# **GitHub Mobile + Copilot Exploration Report**

### *By Aaron

This repository documents our team’s exploration of **GitHub Mobile** and **GitHub Copilot**, focusing on whether Copilot can autonomously create repositories, create files, edit code, and commit changes **using only a mobile device**.

---

## **📱 Objective**

Evaluate the following on **GitHub Mobile App** and **GitHub Web (mobile browser)**:

* First-time sign-in and onboarding
* Copilot’s ability to automatically:

  * Create a repository
  * Create files
  * Add code
  * Commit and push changes
* Identify what works, what doesn't, and what requires developer involvement
* Document the mobile-focused workflow (no PC)

---

## **📌 Summary of Findings**

### **1. GitHub Mobile App**

* Copilot **cannot** create repositories.
* Copilot **cannot** add or commit files, even with permissions.
* Manual repo creation + initial commit still fails.
* Frequent errors:

  * “I’m sorry, but there was an error.”
  * “I’m struggling with the GitHub API right now.”
* File edits, commits, and pushes are **not functional** via Copilot in the mobile app.

### **2. Web Browser (Mobile or Desktop Mode)**

* Must manually create repository
* Must manually make the initial commit
* After that, Copilot **successfully**:

  * Adds code
  * Edits files
  * Creates commits
* Works reliably once the foundation is set up manually.

---

## **📂 Attempts Documented**

### **Attempt 1 — Mobile App**

* Asked Copilot to create repo → failed
* Created repo manually → asked Copilot to add a file → failed
* Made initial commit manually → Copilot still failed
* Repeated GitHub API errors

### **Attempt 2 — Mobile App**

* Manually created repo + empty `index.html`
* Asked Copilot to write code inside the file
* Copilot attempted → failed again

### **Attempt 3 — GitHub Web (Mobile Browser)**

* Repo created manually
* Initial commit done manually
* Copilot successfully:

  * Added code to existing files
  * Created commits
  * Updated content
* No API issues in the web version

---

## **📝 Reflections (Required for the assignment)**

### **What Was Easy**

* Signing into GitHub Mobile
* Opening Copilot Chat
* Using Copilot on GitHub Web (after manual setup)

### **What Was Hard**

* Getting Copilot to interact with GitHub APIs on mobile app
* Repo creation, file creation, and committing inside the app
* Understanding vague API errors
* Missing features in the mobile app UI

### **What Was Not Possible Without a Developer**

* Automatic repo creation
* Automatic file creation
* Completing full workflow (repo → file → code → commit)
* Managing GitHub API failures on mobile

### **Mobile-Only Experience Summary**

* GitHub Mobile App: **Not reliable for Copilot automation**
* GitHub Web Browser: **Works perfectly once repo & initial commit are manually set up**

---

## **📎 Deliverables Included**

Each team member submitted:

* Loom recordings of first-time GitHub Mobile sign-in
* Documentation of all attempts
* Links to repositories
* Reflections on mobile experience
* Copilot usage notes

---

## **👤 Authors**

**Report by:**
**Aaron
