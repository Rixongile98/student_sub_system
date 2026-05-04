# Module 2 – Thinking Like A Programmer
## Component 1: VS Code & Git Basics — Summative Assessment

> **Occupational Certificate: Software Development**
> *This assessment is aligned with the QCTO requirements for assessments and is focused on preparing the student for the EISA exam.*

---

##  Before You Begin

1. **Fill in your learner details** — open [`LEARNER_DETAILS.md`](./LEARNER_DETAILS.md) and complete all fields before starting the assessment.
2. You have **2 hours** to complete this assessment.
3. You are **NOT allowed** to use AI or Google. If we suspect external help was used, you will be marked **Not Competent** for this assessment.
4. All questions must be completed on your **Bash Terminal** and **VS Code**, using your GitHub account at `https://github.com/[yourusername]`.

---

##  Scenario

You have just been hired as a **Junior Developer** at **Tech Performance Centre (TPC Digital Team)**.

On your first day, your team lead assigns you a developer onboarding task to ensure you are ready to work in the company's development environment.

**The company uses:**
- GitHub (via SSH) for version control
- VS Code as the development environment
- Terminal-based workflows *(no GUI shortcuts allowed)*

**Your Objective — You must:**
- Set up secure access to the company repository
- Clone and work on the project locally
- Create basic files
- Use proper Git workflow to track and push your work

---

## Section A: Environment & SSH Setup `[15 Marks]`

> **Before you start**, clear your previous history using the following command:
> ```bash
> history -c && history -w
> ```

### Task
Before accessing company code, you must securely authenticate using SSH.

**You are required to:**

1. Generate a new SSH key using your Git Bash or CMD terminal. Take a screenshot of your terminal output and submit it. **(10 Marks)**

2. Add your SSH key to your GitHub account at `https://github.com/yourusername`. Take a screenshot of your GitHub added SSH key or success message and submit it. **(5 Marks)**

**After successfully connecting, you should see the following on your terminal:**
```
Hi username! You've successfully authenticated…
```

---

## Section B: Repository Setup `[10 Marks]`

### Task
After setting up your SSH keys, your team lead provides you with a GitHub repository link containing a starter project.

**You are required to:**

1. Clone the repository using **SSH (not HTTPS)** on your Bash or CMD terminal. Take a screenshot of your terminal output after cloning and submit it. **(5 Marks)**

2. Navigate into the project folder using terminal commands on Bash or CMD. **(3 Marks)**

3. Open the project in VS Code from your Bash or CMD terminal. Take a screenshot of your terminal output and submit it. **(2 Marks)**

---

## Section C: Git Workflow `[25 Marks]`

### Task
The company wants you to create basic files for the cloned repository from Section B.

**You are required to:**

1. **Create the following files using only terminal commands** (Git Bash or CMD). Submit a screenshot of your terminal outputs after creating all three. **(6 Marks)**
   - `index.html` — **(2 Marks)**
   - `about.html` — **(2 Marks)**
   - `history.txt` — **(2 Marks)**

2. **Stage your changes** and submit a screenshot of your terminal output. **(5 Marks)**

3. **Commit your changes** — Make a commit after creating your files. Your commit message must describe the changes you made to the repository. Submit a screenshot of your terminal output after using the command. **(4 Marks)**

4. **Update `history.txt` and Commit Again** — Type `history` in your terminal and copy/paste the result into `history.txt`. Commit the changes to `history.txt`. Submit a screenshot of your terminal output after using the command. **(5 Marks)**

5. **Push to GitHub** — Push your changes to the GitHub repository. Copy the URL or SSH link of the pushed repository from your GitHub account and submit it. **(5 Marks)**

---

##  Mark Summary

| Section | Description | Marks |
|---------|-------------|-------|
| A | Environment & SSH Setup | 15 |
| B | Repository Setup | 10 |
| C | Git Workflow | 25 |
| **Total** | | **50** |

---

##  Submission Checklist

- [ ] `LEARNER_DETAILS.md` completed
- [ ] Section A: SSH key generation screenshot
- [ ] Section A: GitHub SSH key added screenshot
- [ ] Section B: Clone terminal screenshot
- [ ] Section B: VS Code open terminal screenshot
- [ ] Section C: File creation screenshots (all 3 files)
- [ ] Section C: Staged changes screenshot
- [ ] Section C: First commit screenshot
- [ ] Section C: `history.txt` update and commit screenshot
- [ ] Section C: GitHub repository URL / SSH link submitted
