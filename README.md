# 🚀 GitQuest — Event Feedback Challenge

Welcome to the **GitQuest First PR Challenge!** 🎉

Share your experience of the GitQuest workshop by adding a text file with your name and feedback. Push your changes to your fork and open a **Pull Request (PR)** for review.

## 📝 Steps to Contribute

### 1. Fork This Repository
1. Click the **Fork** button at the top-right of this repository's GitHub page.
2. Select your GitHub account to create a copy of the repository.

### 2. Set Up the Repository Locally

Copy the URL of your fork from GitHub, then open your terminal and run:

```bash
git init
git remote add origin <your-fork-repository-url>
git branch -M main
git pull origin main
```

Replace `<your-fork-repository-url>` with your fork's URL.

### 3. Add Your Feedback

Create a text file named after yourself, for example, `Manas-Sharma.txt`.

Write your feedback about the event. You can include:
- What you learned during the workshop.
- Your favourite part of the event.
- Suggestions for improvement.
- What you'd like to learn in future workshops.

### 4. Create a New Branch

Do not push your changes directly to the `main` branch. Create a new branch using your name:

```bash
git checkout -b your-name
```

Replace `your-name` with your own name.

### 5. Commit and Push Your Changes

```bash
git add .
git commit -m "Add event feedback"
git push -u origin your-name
```

**Important:** Replace `your-name` in the push command with the branch name you created in Step 4.

### 6. Open a Pull Request

1. Open your fork on GitHub.
2. Click **Compare & pull request** (or go to **Pull requests → New pull request**).
3. Set the **base repository** to the original GitQuest feedback repository and the **base branch** to `main`.
4. Set the **compare branch** to your newly created branch.
5. Add a title and a short description.
6. Click **Create pull request**.

## 🎯 That's It!

Your contribution will be reviewed by the organizers. Make sure your feedback is meaningful and your file is named correctly.

**Remember:** Always create a new branch and open a Pull Request. Never push your changes directly to `main`.

**Happy Contributing! 💻**