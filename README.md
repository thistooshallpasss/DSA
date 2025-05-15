# DSA

my DSA knowledge

My initial step in creatng the repository
first i made DSA folder in my both remote and local repo sepeartely and connected them using following steps

To connect and synchronize two DSA (Data Structures and Algorithms) folders—one on your **local machine** and the other on a **remote server** (e.g., GitHub, GitLab, or a remote machine via SSH)—you can follow one of these approaches depending on what you want to achieve.

---

If your remote folder is part of a Git repository (like on GitHub or GitLab), here’s how to connect your local folder to it.

#### ✅ Step-by-step:

1. **Initialize Git in your local folder (if not already):**

   ```bash
   cd path/to/local/dsa-folder
   git init
   ```

2. **Connect your local folder to the remote:**

   ```bash
   git remote add origin <remote-repo-URL>
   ```

   Example:

   ```bash
   git remote add origin https://github.com/yourusername/dsa.git
   ```

3. **Pull from remote to sync (optional if repo already has files):**

   ```bash
   git pull origin main  # or 'master' depending on branch
   ```

4. **Push your local changes:**

   ```bash
   git add .
   git commit -m "Initial commit or update"
   git push -u origin main
   ```

---
