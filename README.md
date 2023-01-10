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