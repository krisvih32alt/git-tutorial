
# Git Online Session Guide

## Welcome & Questions
Please feel free to post any questions in chat or raise your hand in Teams to ask questions.

We will talk about Git later, but here are the instructions we will follow for the same.

## Git Installation

### Prerequisites
If you already have Android Studio, you can use the terminal in Android Studio to run git commands.

### Windows Installation
In PowerShell, type:
```powershell
winget install --id Git.Git -e --source winget
```
Press Enter to execute.

### Mac Installation
On MacOS Mavericks (10.9) or above, open Terminal and run:
```bash
git --version
```

### Other Operating Systems
If you have any other version of any other operating system, please feel free to tell me in the chat and I will tell you how to install Git for your OS.

## Git Tutorial Commands

### Step 1: Clone a repository
```bash
git clone https://github.com/krisvih32alt/git-tutorial.git
```

### Step 2: Check file status (none changed yet)
```bash
git status
```

### Step 3: See changes to files (none yet)
```bash
git diff
```

### Step 4: Modify README.md
Edit README.md in any text editor...

Now it shows that you have a change in README.md

### Step 5: Check status again
```bash
git status
```

### Step 6: View your changes
```bash
git diff
```

### Step 7: Stage your changes
```bash
git add README.md
```

### Step 8: Create a commit
```bash
git commit -m "Changed readme to add John"
```

### Step 9: Configure email (if commit fails)
```bash
git config --global user.email john@abc.com
```

### Step 10: Configure name (if commit fails)
```bash
git config --global user.name "John"
```

### Step 11: Commit again (if needed)
```bash
git commit -m "Changed readme to add John"
```

### Step 12: Push to server
```bash
git push
```

### Step 13: View commit history
```bash
git log
```

### Step 14: Fetch latest changes
```bash
git fetch
```
Now you can see other branches (like Vihaan's branch)

### Step 15: Create a Pull Request
Open this page: https://github.com/krisvih32alt/git-tutorial/pulls

Click New Pull request button

Select your branch name under "compare:"

Hit "Create new Pull Request"
