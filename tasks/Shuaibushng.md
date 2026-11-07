# My SIWES Report!
## Topics Covered.
>1. Git, GitHub and Repository
>2. Commit Changes With Terminal Command
>3. Commit Changes Using GitHub Desktop
>4. Clun a Repositories into a Code space or VScode
>5. Marge Conflicts and Resolved it
## Weekly Activity.
### Week 1.
1. I Create GitHub Account
2. learn How to create Repository
3. And Make a Pull Request.
---
### Week 2.
* I learn How to Commit changes in GitHub project with terminal command By
Typing the Following Command;
1. `Git Status:` it allowed you to Detect an error in the project
2. `Git Add-all:` it enable to add all of your changes in the project
3. `Git Commit -m ("your message"):` This will allows you to save all the changes into your project and write a message on what contains in the file.
4. `Git Push:` its enable you to Upload All changes back to the original GitHub Project
---
### Week 3. 
* I learn how to commit changes in GitHub project with GitHub Desktop App by Clun My project with GitHub Desktop to edit the project with VScode then commit the changes and Push it back into the original project on GitHub Account all by Using with GitHub Desktop.
---
### Week 4.
* I learn Merge Conflicts and how Resolve it.
* What causes merge conflicts in GitHub is when
A merge conflict happens when Git finds changes in two branches that it cannot automatically combine.
This usually happens when two or more developers work on the same file or the same lines of code.
1. Two developers edit the same line

For example:
Developer A changes index.html to:
* (Welcome to my website)

Developer B changes the same line to:
* (Welcome to my portfolio)

When both changes are merged, Git doesn't know which version you want to keep.
This causes a merge conflict.

*How to resolve a merge conflict in GitHub

Step 1: Check the conflict
Open your project terminal and run:
git status
You may see:
both modified: index.html
This means index.html has conflicting changes.

Step 2: Open the conflicting file
Open index.html in VS Code.
You may see something like this:
* (Hello World)
* (Welcome to my website)

Step 3: Choose which code to keep
VS Code will show options:
- Accept Current Change: Keep your current branch's code.
- Accept Incoming Change: Keep the code coming from the other branch.
- Accept Both Changes: Keep both versions.
For example, you can resolve the conflict by changing the code to:
* (Welcome to my website)