1: Create folder FirstVScodeProject
2: Open Foder with VScode
3: Create New File and Save as Readme.txt
4: Ctrl + Shift P： search for console window to view
5: Go to Terminal window
6: Under the same folder：type git init (git needs to be in the path, git will create .git folder)
7: In Vscode, add a new file and write one line to save
8: In terminal: git status to check
9: In terminal: git add <fileName> or git add . to all files
10: git commit
11: go to github and create a new repository
12: Copy github repo url, come back to terminal in vscode \
13: git remote add origin https://github.com/shruk/FirstVScodeProject.git (origin is the remote github)
14: git remote -v (verify?)
15: git push origin master (git push to remote)
16: git branch -a to display all branches
17. git diff master origin/master to display diff between local and remote
18: make some change and save again. you can see the left gutter with color coded sign to indicate change.
19: go to git window and under the changes file, you can double click the file to view the differences between original and the change.