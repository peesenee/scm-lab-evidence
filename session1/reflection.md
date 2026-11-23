Part 5 Reflection
Q1. Why is a commit history useful when maintaining software? Give one concrete maintenance situation (for example finding when a bug appeared) and refer to your own commits.

- A commit history helps developers track changes and identify when errors were introduced. For example, if a bug occurs, I can check previous commits to identify which changes may have caused it. My commits, such as "Add README for SCM evidence repository", help me track changes made to my project.

Q2. Explain the difference between Git and GitHub, using your two repositories (the exercise repository and scm-lab-evidence) as examples.

- Git is a version control tool used to track and manage changes locally on my computer. GitHub is an online platform used to host repositories and support collaboration. I used Git to manage my scm-lab-evidence repository and GitHub to store and access it online.

Q3. In the GitHub Skills exercise you worked on a branch and used a pull request instead of changing main directly. What risk does this reduce?

- Using a separate branch reduces the risk of introducing errors directly into the main branch. A pull request allows changes to be reviewed before merging. This helps prevent unfinished or incorrect changes from affecting the main project.

Q4. State which of your commands changed only your computer and which changed GitHub.

- Commands such as git init, git add, git commit, git status, and git merge changed my local repository. The git push command uploaded my commits to GitHub, while git clone downloaded a repository from GitHub. The git pull command downloaded and integrated changes from GitHub into my local repository.