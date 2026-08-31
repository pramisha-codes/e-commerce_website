# Git & GitHub Cheatsheet

## Important Rules for Our Project

1. **Do not work directly on `main`.**
2. **Create a feature branch before starting a feature.**
3. **Pull the latest `main` before creating a new branch.**
4. **Make small, meaningful commits.**
5. **Use clear commit messages.**
6. **Push your branch regularly.**
7. **Create a Pull Request when a feature is ready.**
8. **Let the other developer review the Pull Request.**
9. **Fix review comments before merging.**
10. **Keep `main` stable and working.**
11. **Do not create unnecessary branches for tiny changes.**
12. **Do not use `git push --force` unless both developers agree.**
13. **Before starting new work, make sure your local `main` is updated.**
14. **Communicate with the other developer if you are editing the same file or section.**

---

# Quick Reference

| Purpose                | Command                                |
| ---------------------- | -------------------------------------- |
| Clone project          | `git clone <url>`                      |
| Check status           | `git status`                           |
| Check branches         | `git branch`                           |
| Check all branches     | `git branch -a`                        |
| Switch branch          | `git checkout branch-name`             |
| Create branch          | `git checkout -b feature/name`         |
| Update main            | `git pull origin main`                 |
| Get remote information | `git fetch origin`                     |
| See changes            | `git diff`                             |
| Stage all files        | `git add .`                            |
| Stage one file         | `git add filename`                     |
| Commit                 | `git commit -m "message"`              |
| Push                   | `git push`                             |
| Push new branch        | `git push -u origin branch-name`       |
| View commits           | `git log --oneline`                    |
| Restore file           | `git restore filename`                 |
| Unstage file           | `git restore --staged filename`        |
| Merge branch           | `git merge branch-name`                |
| Delete local branch    | `git branch -d branch-name`            |
| Delete remote branch   | `git push origin --delete branch-name` |
| Check remote           | `git remote -v`                        |
