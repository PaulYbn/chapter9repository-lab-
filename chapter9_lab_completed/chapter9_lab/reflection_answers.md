# Reflection Answers

1. **Why is version control better than keeping many copied files with different names?**

   Version control systems like Git store the complete history of a project efficiently. Instead of manually creating numerous copies of files with names like `final_v2` or `final_v3`, Git tracks changes at the content level, enabling you to view, revert, and collaborate on specific changes without cluttering your filesystem. It prevents confusion and errors that occur when multiple versions float around without clear lineage.

2. **Why is `git status` often called a radar, compass, or checkpoint command?**

   `git status` gives real‑time feedback about the state of your repository — which files are untracked, which are modified, which are staged, and what branch you are on. It guides your next actions, much like a radar or compass helping navigate, so you always know where you stand before making commits or switching branches.

3. **What is the purpose of the staging area?**

   The staging area (also called the index) allows you to assemble exactly which changes will go into the next commit. You can stage some modified files and leave others unstaged, crafting a coherent snapshot with a meaningful message. This intermediate step between working directory and repository history provides fine‑grained control over commits.

4. **What is the difference between an untracked file and a modified file?**

   An untracked file is one that exists in your working directory but has never been added to Git, so Git is unaware of it. A modified file, on the other hand, has been tracked (committed) previously and then changed in the working directory. Git knows about it and will show it as modified, ready to be staged and committed again.

5. **Why does Git need your name and email before committing?**

   Each commit in Git includes metadata about who created it. Git uses your name and email to associate changes with their author, enabling accountability and collaboration. When working with others or pushing to remote repositories, this information identifies authorship and helps track contributions over time.
