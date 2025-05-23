## Assignment-3

**GithubLink**: https://github.com/AravindMandan/Assignment3

**Created Pull Request**

<img width="960" alt="new1" src="https://github.com/user-attachments/assets/b5019f48-af35-4a5c-a3ef-f11ed13c438e" />


**Merge Conflict occured**

<img width="960" alt="new 2" src="https://github.com/user-attachments/assets/91bc501a-7e6e-4fc4-b05d-9984ad75a45a" />

**Errors in the file**

<img width="960" alt="new 3" src="https://github.com/user-attachments/assets/84e265aa-f94b-4a27-9b76-763eba9cc972" />

**Merge Conflicts Resolved**

<img width="933" alt="new 4" src="https://github.com/user-attachments/assets/84d22a81-7480-4803-8f83-4349fb052a94" />


**Explanation of how conflicts are resolved**


Identify the Conflict: When you try to merge branches, GitHub will notify you if there are conflicts. These conflicts occur when changes in different branches overlap.

Open the Conflict Editor: You can resolve simple conflicts directly on GitHub using the conflict editor. Navigate to the pull request with the conflict and click on "Resolve conflicts" 1.

Choose Changes to Keep: In the conflict editor, you'll see the conflicting changes marked with <<<<<<<, =======, and >>>>>>>. Decide whether to keep changes from your branch, the other branch, or a combination of both1.

Edit and Save: Remove the conflict markers and make the necessary changes. Once you've resolved all conflicts, click "Mark as resolved" and then "Commit merge"


## Assignment 4
## Husky and Lintstaged
Husky is a popular tool used in software development projects to manage Git hooks. Git hooks are scripts that run automatically every time certain important actions occur in a git repository, such as committing or pushing code. Husky simplifies the management of these hooks, ensuring that code commits meet the project's standards before they are pushed to the repository. This guide explores how to set up and use Husky with npm, the Node.js package manager.
## Setting up Husky with npm
**Step 1: Install Husky**

npm install husky --save-dev

**Step 2: Enable Git hooks**

npx husky install

**Step 3: Add hook scripts**

npx husky add .husky/pre-commit "npm run lint"


