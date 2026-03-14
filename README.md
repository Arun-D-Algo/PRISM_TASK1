# Git and Markdown Tutorial

This repository was created as part of the **PRISM Junior Cohort Task 1**.

In this tutorial we will learn:

* What Git is
* How to push code to GitHub
* What Markdown is
* Basic Markdown syntax

---

# 1. What is Git?

Git is a **version control system** used by developers to track changes in their code.

It allows developers to manage different versions of a project and collaborate with others without overwriting each other’s work.

With Git you can:

* Track code changes
* Go back to previous versions of your code
* Work on projects with other developers
* Maintain a complete history of your project

Git works locally on your computer and keeps a record of every change made to the project.

---

# 2. What is GitHub?

GitHub is a **cloud platform that hosts Git repositories**.

While Git manages the version history locally, GitHub allows you to store and share your repositories online.

Using GitHub you can:

* Share your code with others
* Collaborate with teams
* Manage project documentation
* Track issues and improvements

GitHub uses Git as its underlying version control system.

---

# 3. How to Push Code to GitHub

Below are the basic steps required to push code from your local machine to GitHub.

### Step 1: Initialize a Git repository

```bash
git init
```

This creates a new Git repository inside your project folder.

---

### Step 2: Add files to Git

```bash
git add .
```

This command stages all files so they are ready to be committed.

---

### Step 3: Commit the changes

```bash
git commit -m "First commit"
```

A commit records the changes you have made in the project.

---

### Step 4: Connect your local repository to GitHub

```bash
git remote add origin https://github.com/username/repository-name.git
```

This links your local project to the GitHub repository.

---

### Step 5: Push your code to GitHub

```bash
git push -u origin main
```

This uploads your project to GitHub.

After this step, your code will be available online in your GitHub repository.

---

# 4. What is Markdown?

Markdown is a **lightweight markup language used for formatting text**.

It is widely used for documentation because it is simple, readable, and easy to write.

Markdown is commonly used in:

* README files
* Project documentation
* GitHub repositories
* Technical notes

Markdown allows you to format text using simple symbols.

---

# 5. Basic Markdown Syntax

## Headings

You can create headings using the `#` symbol.

```markdown
# Heading 1
## Heading 2
### Heading 3
```

Example:

# Heading 1

## Heading 2

### Heading 3

---

## Lists

### Unordered List

```markdown
- Item 1
- Item 2
- Item 3
```

Example:

* Item 1
* Item 2
* Item 3

---

### Ordered List

```markdown
1. First
2. Second
3. Third
```

Example:

1. First
2. Second
3. Third

---

## Code

Inline code can be written using backticks.

Example:

`git status`

Code blocks can be written using three backticks.

```bash
git add .
git commit -m "commit message"
```

---

## Links

Links can be written like this:

```markdown
[GitHub](https://github.com)
```

Example:

[GitHub](https://github.com)

---

# Useful Git Commands

Some commonly used Git commands include:

```bash
git status
git log
git clone
git pull
git push
```

These commands help you manage repositories, check changes, and synchronize code with GitHub.

---

# Conclusion

Git and Markdown are essential tools for modern software development.

Git helps developers track changes and collaborate on projects, while Markdown helps create clear and readable documentation.

Learning these tools early makes it much easier to work on real-world software projects and collaborate effectively with other developers.

