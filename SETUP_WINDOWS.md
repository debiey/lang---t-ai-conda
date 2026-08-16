# Windows Setup Guide — Lang-&-t-ai-conda

This guide is written specifically for **Windows** students who are complete beginners.

Follow the steps carefully. Do not skip any step.

---

## Step 1: Download and Install Miniconda

1. Go to the official Miniconda download page:  
   https://docs.conda.io/en/latest/miniconda.html

2. Download the **Windows 64-bit** installer (Python 3.11 or 3.12 recommended).

3. Run the installer:
   - Click **Next**
   - Accept the license
   - Choose **Just Me** (recommended)
   - Keep the default installation location
   - **Important**: Check the box that says  
     **"Add Miniconda3 to my PATH environment variable"**  
     (Even though it warns you, for students it makes life easier)
   - Click **Install**

4. When installation finishes, close the installer.

---

## Step 2: Open Anaconda Prompt

- Press the Windows key
- Type **Anaconda Prompt**
- Open it

You should see something like:
```
(base) C:\Users\YourName>
```

---

## Step 3: Navigate to the Lab Folder

If you downloaded the lab as a ZIP:
1. Extract it to a simple location, for example:  
   `C:\AI-Lab\Lang-&-t-ai-conda`

2. In Anaconda Prompt, type:

```powershell
cd C:\AI-Lab\Lang-&-t-ai-conda
```

(Replace the path with your actual location)

---

## Step 4: Create the Environment

Run this command:

```powershell
conda env create -f environment.yml
```

This will take several minutes the first time (it downloads packages).  
Be patient and keep the internet connected.

When it finishes, you should see a success message.

---

## Step 5: Activate the Environment

```powershell
conda activate lang-t-ai
```

Your prompt should now look like:
```
(lang-t-ai) C:\AI-Lab\Lang-&-t-ai-conda>
```

---

## Step 6: Launch Jupyter Lab

```powershell
jupyter lab
```

A browser window will open automatically.  
On the left side you will see the `notebooks` folder.  
Start with **01_python_basics.ipynb**.

---

## Useful Commands

| Action                        | Command                          |
|------------------------------|----------------------------------|
| Activate environment         | `conda activate lang-t-ai`      |
| Deactivate                   | `conda deactivate`              |
| List all environments        | `conda env list`                |
| Update packages later        | `conda env update -f environment.yml --prune` |
| Launch Jupyter Lab           | `jupyter lab`                   |
| Launch classic Jupyter       | `jupyter notebook`              |

---

## Common Windows Problems & Fixes

### 1. "conda is not recognized"
- Close and reopen **Anaconda Prompt**
- Or reinstall Miniconda and make sure you checked "Add to PATH"

### 2. PowerShell Execution Policy Error
If you prefer using normal PowerShell instead of Anaconda Prompt:

```powershell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
```

### 3. Installation is very slow or fails
- Disable antivirus temporarily during installation
- Make sure you have a stable internet connection
- Try running Anaconda Prompt **as Administrator**

### 4. Jupyter does not open in browser
Copy the link that appears in the terminal (starts with `http://localhost:8888/...`) and paste it into Chrome or Edge.

### 5. "Long path" or permission errors
Move the lab folder to a short path such as:
```
C:\AI-Lab\
```

---

## Recommended Tools (Optional but Helpful)

- **VS Code** (free): https://code.visualstudio.com/  
  Install the Python and Jupyter extensions.
- **GitHub Desktop** (if you want to clone instead of download ZIP)

---

You are now ready!  
Go back to the main README and start learning.
