# unzip-subagent

A lightweight PowerShell utility that automatically finds and extracts all `.zip` archives within a directory and its subdirectories.

## 🚀 Features
* **Recursive Search:** Automatically dives into subfolders to find nested zip files.
* **Auto-Organization:** Extracts each zip file into its own dedicated folder (named after the archive) to prevent file clutter.
* **Safe Extraction:** Uses the native `Expand-Archive` command with the `-Force` flag to ensure consistent overwriting if needed.
* **Visual Feedback:** Provides real-time console updates on which file is currently being processed.

## 🛠️ How to Use
1. **Download the script:** Place `Unzip-Recursive.ps1` in the root folder where your zip files are located.
2. **Open PowerShell:** Navigate to that directory.
3. **Run the script:**
   ```powershell
   ./Unzip-Recursive.ps1
