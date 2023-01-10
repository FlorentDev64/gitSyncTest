# Test Repo
This repo is a test to see how we can handle git sync with DSS.

# Steps done so far

1. Create a repo on github
2. Add the README.md from DSS
3. Sync from DSS to github
4. Import the lib (from sync by plugin) into PyCharm
5. Modify the README.md  (Can't sync with git, as the library folder does not contain ``.git`` directory.)
6. Sync with DSS.
7. From DSS: Modify the README and Push to github.
8. Modify the README.md (in DSS, while branch has been create from github, and the file hase been modified from Pycharm)
9. Commit and push from DSS
10. New modification from DSS, and then try to push.
11. There is no synchronization between PyCharm and DSS. So every modification done in POycharm has been lost.
12. Third modification from Pycharm, then sync with DSS. After sync reload the file from DSS before doing modification.
13. If we reload the file before doing any modification, the file is updated, and then we can do modification.
8. Create a branch from GitHub.
9. Modify the README (from github), and commit
10. Some modifcations to the github branch (from github)
11. Try to merge branch from github
12. Some conflicts (expected) to resolve.
14. Modification from DSS while the branch has been merged
15. While pushing the conflict has been detected, and then resolve the conflict inside DSS, and mark as resolved, and push.

# Another Test
1. From Pycharm, clone the repo.
2. From DSS, reload page. The ne directory appears, but it is not linked to Github.
3. Update the reference, with the appropraite informations.
4. Modify the README, and push from DSS
5. The referecne from the git repo has been lost... SO in the same situation than before.