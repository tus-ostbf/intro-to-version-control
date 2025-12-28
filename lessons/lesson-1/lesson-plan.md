# Lesson 1: Introduction to Version Control - Detailed Plan

## Learning Objectives

By the end of this lesson, students will be able to:

1. Explain the importance of version control in software development and beyond.
2. Install Git on their local machine (or confirm existing installation).
3. Create a local Git repository and stage changes.
4. Create meaningful commits with descriptive messages.

## Time Allocation

Total time: 90 minutes

## Materials

- Instructor slides (optional)
- Whiteboard or digital board
- Student computers with Git installed (or ability to install)
- Access to internet

## Lesson Flow

### Part 1: Motivation (15 minutes)

**Activity:** Ask students about times they have lost work because they saved over an old version, or collaborated with others and ended up with conflicting copies. Discussion leads to the need for a better system.

**Key Points:**

- What is version control?
- Why is it essential for collaboration and tracking history?
- Real-world examples: software development, academic writing, government documents.

### Part 2: Installing Git (15 minutes)

**Activity:** Step-by-step guided installation for Windows, macOS, and Linux.

- Show how to download from git-scm.com.
- Verify installation by opening a terminal and typing `git --version`.

### Part 3: Initializing a Repository (30 minutes)

**Activity:** Students create a new directory and initialize a Git repository.

- Command: `git init`
- Explanation of the hidden `.git` folder.
- Staging and committing a simple text file.

**Hands-on Steps:**

1. Create a new folder named `my-first-repo`.
2. Navigate into that folder in the terminal.
3. Run `git init`.
4. Create a file `hello.txt` with a greeting.
5. Stage the file with `git add hello.txt`.
6. Commit with `git commit -m "First commit"`.

### Part 4: Understanding Commits (20 minutes)

**Discussion:** What is a commit? Analogy: taking a snapshot of your project at a specific moment.

- Show the commit log with `git log`.
- Introduce the concept of a unique commit hash.
- Briefly mention the tree model of Git.

**Activity:** Make a second change to the same file, stage, and commit. Compare the two commits.

### Part 5: Wrap-up and Assessment (10 minutes)

**Review Questions:**

- What is the purpose of version control?
- What command creates a new Git repository?
- How do you stage changes? How do you commit them?

**Homework:** Students are asked to write a short paragraph describing a scenario where version control would have helped them in the past.

## Assessment Rubric

| Criteria | Excellent (4) | Proficient (3) | Developing (2) | Beginning (1) |
|----------|---------------|----------------|----------------|---------------|
| Understanding of purpose | Can clearly articulate why version control matters, with examples. | Understands the basic purpose of version control. | Partial understanding, may be fuzzy on details. | Little or no understanding of purpose. |
| Installation and setup | Git is installed and verified; repository is created correctly. | Git is installed; repository is created with minor errors. | Git installation incomplete; repository not correctly initialized. | Git not installed; no repository created. |
| Creating commits | Creates at least two commits with meaningful messages. | Creates one commit with a descriptive message. | Creates a commit but message is not descriptive. | No commits created. |

## Additional Resources

- Git official documentation: https://git-scm.com/doc
- Visual Git Guide: https://marklodato.github.io/visual-git-guide/
- Interactive tutorial: https://learngitbranching.js.org/