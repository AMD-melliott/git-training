# Git & GitHub Workshop for Non-Coders

Welcome to the **Git and GitHub for Non-Coders** workshop series! This hands-on training teaches you the fundamental skills for collaborating on documentation using Git, GitHub, and VS Code.

## Workshop Overview

This workshop uses a **docs-as-code** approach, treating documentation like source code. You'll learn the same workflows used by software development teams, but applied to writing and managing documentation in Markdown and reStructuredText.

**By the end of this workshop, you'll be able to:**
- ✅ Fork, clone, and contribute to GitHub repositories
- ✅ Create branches and pull requests
- ✅ Use VS Code's Git integration and visual diff tools
- ✅ Resolve merge conflicts with confidence
- ✅ Write and preview Markdown documentation
- ✅ Perform project-wide search and replace operations

---

## Prerequisites

Before starting the exercises, make sure you have:

- **[GitHub Account](https://github.com/signup)** (free)
- **[Git](https://git-scm.com/downloads)** installed on your computer
- **[VS Code](https://code.visualstudio.com/)** text editor
- Basic familiarity with your computer's terminal/command line

**New to these tools?** Don't worry - each exercise includes detailed step-by-step instructions!

---

## Workshop Exercises

Complete these exercises in order to build your skills progressively:

### 1. Favorite Restaurants 🍕
**Skills:** Fork, clone, branch, commit, push, pull requests

Your first hands-on GitHub workflow! Contribute your favorite restaurant to a collaborative list.

**What you'll learn:**
- The complete fork → clone → branch → commit → push → PR workflow
- How to create and merge pull requests
- Basic Markdown formatting
- Git fundamentals

**[Start Exercise →](https://github.com/AMD-melliott/favorite-restaurants)**

**Duration:** ~30-45 minutes

---

### 2. Style Guide Police 📝
**Skills:** VS Code diff view, staging, visual Git workflow

Fix formatting errors in a press release using VS Code's GUI instead of command-line Git.

**What you'll learn:**
- Cloning repositories using VS Code
- Using the Diff View to review changes
- Staging and committing with VS Code's Source Control panel
- The importance of code review

**[Start Exercise →](https://github.com/AMD-melliott/style-guide-police)**

**Duration:** ~30 minutes

---

### 3. Merge Conflict Simulator 🔥
**Skills:** Conflict resolution, branching, merging

Practice resolving merge conflicts using VS Code's visual conflict resolution tools.

**What you'll learn:**
- What merge conflicts are and why they happen
- How to resolve conflicts using VS Code's clickable interface
- Merging branches safely
- Best practices for avoiding conflicts

**[Start Exercise →](https://github.com/AMD-melliott/merge-conflict-simulator)**

**Duration:** ~30-45 minutes

---

### 4. Release Notes Compiler 📄
**Skills:** Multi-window editing, Markdown preview, documentation formatting

Combine multiple files into professional release notes using split view and live preview.

**What you'll learn:**
- Working with multiple files in split view
- Using live Markdown preview
- Writing well-formatted documentation
- Professional Markdown syntax

**[Start Exercise →](https://github.com/AMD-melliott/release-notes-compiler)**

**Duration:** ~45 minutes

---

### 5. Global Find & Replace 🔍
**Skills:** Project-wide search and replace, batch commits, refactoring

Rebrand a product by replacing text across multiple files simultaneously.

**What you'll learn:**
- Global search across entire projects
- Previewing and executing mass replacements
- Managing multi-file changes
- Batch committing related changes

**[Start Exercise →](https://github.com/AMD-melliott/global-find-replace)**

**Duration:** ~30-45 minutes

---

## Workshop Materials

### Presentation Slides
The workshop includes a 1-hour presentation covering:
- Introduction to docs-as-code workflows
- Why Git and GitHub matter for documentation
- Markdown and reStructuredText basics
- Live demonstrations
- Q&A

**[View Outline](./Git%20GitHub%20Workshop%20Outline.md)**

### Additional Exercise Ideas
- **[Exercise 1 - Favorite Restaurants Details](./GitHub%20Workshop%20Exercise%201.md)**
- **[Exercise 2 - VS Code Concepts](./GitHub%20Workshop%20Exercise%202.md)**

---

## Learning Path

We recommend following this progression:

```
1. Favorite Restaurants (Fundamentals)
          ↓
2. Style Guide Police (VS Code GUI)
          ↓
3. Merge Conflict Simulator (Conflict Resolution)
          ↓
4. Release Notes Compiler (Documentation)
          ↓
5. Global Find & Replace (Advanced Operations)
```

Each exercise builds on skills learned in previous exercises.

---

## What is Docs-as-Code?

**Docs-as-code** means treating documentation with the same practices used for software development:

- **Version Control:** Track every change with Git
- **Collaboration:** Use pull requests for review
- **Automation:** Auto-build and deploy documentation
- **Plain Text:** Write in Markdown/reStructuredText, not proprietary formats

**Benefits:**
- Complete change history
- Collaborative editing and review
- Automated testing and deployment
- Works with any text editor
- Free and open-source tools

---

## Tools Used in This Workshop

### Git
Distributed version control system that tracks changes to files.
- **Website:** https://git-scm.com/
- **Learning:** [Git Handbook](https://guides.github.com/introduction/git-handbook/)

### GitHub
Web-based platform for hosting Git repositories and collaborating.
- **Website:** https://github.com/
- **Learning:** [GitHub Skills](https://github.com/skills)

### VS Code
Free, powerful text editor with excellent Git integration.
- **Website:** https://code.visualstudio.com/
- **Learning:** [VS Code Docs](https://code.visualstudio.com/docs)

### Markdown
Lightweight markup language for formatting text.
- **Website:** https://www.markdownguide.org/
- **Cheat Sheet:** [Markdown Guide](https://www.markdownguide.org/basic-syntax/)

---

## Additional Resources

### Git & GitHub
- [GitHub Docs](https://docs.github.com/)
- [Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)
- [GitHub Skills - Interactive Tutorials](https://github.com/skills)
- [Atlassian Git Tutorials](https://www.atlassian.com/git/tutorials)

### VS Code
- [VS Code Git Integration](https://code.visualstudio.com/docs/sourcecontrol/overview)
- [VS Code Tips and Tricks](https://code.visualstudio.com/docs/getstarted/tips-and-tricks)
- [VS Code Keyboard Shortcuts](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf)

### Markdown
- [Markdown Guide](https://www.markdownguide.org/)
- [GitHub Flavored Markdown](https://github.github.com/gfm/)
- [Awesome Markdown](https://github.com/mundimark/awesome-markdown)

### Docs-as-Code
- [Write the Docs](https://www.writethedocs.org/)
- [The Docs-as-Code Approach](https://www.writethedocs.org/guide/docs-as-code/)
- [Sphinx Documentation](https://www.sphinx-doc.org/)

---

## Troubleshooting

### General Issues

**"Git isn't installed"**
- Download from https://git-scm.com/downloads
- Follow installation instructions for your OS
- Verify: Run `git --version` in terminal

**"I can't authenticate with GitHub"**
- GitHub now requires personal access tokens or SSH keys
- [Creating a personal access token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)
- [Setting up SSH keys](https://docs.github.com/en/authentication/connecting-to-github-with-ssh)

**"VS Code isn't showing Git features"**
- Make sure Git is installed first
- Restart VS Code after installing Git
- Check: View → Source Control (should show Git options)

**"I'm stuck on an exercise"**
- Review the step-by-step instructions in each repository
- Check the troubleshooting section in each exercise
- Ask your instructor for help
- Search [GitHub Community](https://github.community/)

---

## Workshop Schedule

### Suggested 3-Hour Workshop

**Hour 1: Fundamentals (60 min)**
- Presentation: Git, GitHub, and Docs-as-Code (20 min)
- Exercise 1: Favorite Restaurants (40 min)

**Hour 2: VS Code & Conflicts (60 min)**
- Exercise 2: Style Guide Police (30 min)
- Exercise 3: Merge Conflict Simulator (30 min)

**Hour 3: Advanced Skills (60 min)**
- Exercise 4: Release Notes Compiler (30 min)
- Exercise 5: Global Find & Replace (20 min)
- Wrap-up and Q&A (10 min)

### Self-Paced Learning

Take your time with each exercise! Most students complete:
- Beginner pace: 4-5 hours total
- Comfortable pace: 3-4 hours total
- Experienced pace: 2-3 hours total

---

## Key Concepts

### Repository (Repo)
A project folder tracked by Git, containing all files and history.

### Fork
Your personal copy of someone else's repository on GitHub.

### Clone
Downloading a repository from GitHub to your computer.

### Branch
A parallel version of the repository where you can make changes safely.

### Commit
A snapshot of your changes with a descriptive message.

### Push
Uploading your local commits to GitHub.

### Pull Request (PR)
A request to merge your changes into the original repository.

### Merge
Combining changes from different branches.

### Conflict
When Git can't automatically merge changes and needs your help.

### Diff
A comparison showing what changed between two versions.

---

## After the Workshop

**Practice regularly:**
- Contribute to open-source documentation
- Create a personal documentation repository
- Use Git for your own projects

**Join the community:**
- [Write the Docs Community](https://www.writethedocs.org/slack/)
- [GitHub Community](https://github.community/)
- Local Git/GitHub meetups

**Keep learning:**
- Advanced Git topics (rebasing, cherry-picking, etc.)
- GitHub Actions for automation
- Static site generators (Jekyll, Hugo)
- Documentation platforms (ReadTheDocs, GitHub Pages)

---

## Feedback & Contributions

We welcome feedback and contributions to improve these workshops!

**Found an issue?**
- Open an issue on the relevant exercise repository
- Suggest improvements via pull request

**Want to contribute?**
- Fix typos or improve instructions
- Add new exercises or challenges
- Share your experience completing the workshops

---

## Credits

**Workshop Created By:** AMD Documentation Team

**Built With:**
- Git & GitHub
- VS Code
- Markdown
- Love for good documentation ❤️

**Special Thanks:**
- All workshop participants for their valuable feedback
- The open-source community for excellent tools
- Write the Docs community for docs-as-code inspiration

---

## Quick Start

Ready to begin? Start here:

1. **Fork** the [favorite-restaurants](https://github.com/AMD-melliott/favorite-restaurants) repository
2. **Clone** it to your computer
3. **Follow** the detailed README instructions
4. **Complete** all five exercises
5. **Celebrate** your new Git & GitHub skills! 🎉

---

**Questions?** Check the troubleshooting sections in each exercise, or ask your instructor.

**Happy learning!** 🚀