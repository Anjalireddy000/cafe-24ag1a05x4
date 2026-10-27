\# Git Practical Exam Answers



\*\*GitHub Username:\*\* Anjalireddy000



\*\*Repository:\*\* https://github.com/Anjalireddy000/cafe-24ag1a05x4



\*\*Roll Number:\*\* 24ag1a05x4

Q1: Individual Git Operations



1.1 Repository and Initial Commits



Created the cafe-24ag1a05x4 repository.



Created README.md with the first line Campus Cafe Menu - 24ag1a05x4.



Created and updated the menu using separate commits.



1.2 Git Diff and Restore



git diff displays changes that have not been staged.



git restore <file> discards unstaged changes to a file.



git diff --staged displays changes staged for the next commit.



1.3 Revert and Reset



git revert <commit> creates a new commit that reverses an earlier commit.



git reset --soft <commit> moves HEAD while keeping changes staged.



git reset --hard <commit> resets the working tree and staging area, discarding tracked changes.



Revert is generally safer for shared history because it preserves existing commits.



1.4 Branching and Merging



A branch allows changes to be developed separately.



Merging integrates changes from another branch.



git log --oneline --graph --all displays commit history in a compact graph.



Q2: Team Git and GitHub



2.1 Remote Repository



Created a GitHub repository and pushed the local main branch.



Cloned the repository into a separate folder for Sam.



2.2 Git Identity



Configured Git identity for the Sam clone using the required teammate name and email.



Created a commit with the message Sam: add samosa.



2.3 Fetch and Pull



git fetch downloads remote updates without merging them into the current branch.



git pull fetches remote changes and integrates them into the current branch.



2.4 Divergence and Synchronization



Compared local and remote branch histories.



Merged the required changes and pushed the updated branch to GitHub.



2.5 Tracking Branch



Created the feature/loyalty branch.



A tracking branch connects a local branch to its corresponding remote branch.



\## Q3: Pull Request and Review



\### 3.1 Protect Main

\- Configured branch protection to require changes through a pull request.

\- Direct push to `main` was rejected.

\- Error observed: `GH013: Repository rule violations found for refs/heads/main`.

\- The error indicated that changes must be made through a pull request.



\### 3.2 Feature Branch and Pull Request

\- Branch: `feature/dessert-menu`

\- Pull request title: `Add brownie to desserts`

\- Added `Brownie 45` to `desserts.txt`.



\### 3.3 Review and Update

\- Review comment: `Sam: is 45 the right price?`

\- Reply: `Alex: changing to 50.`

\- Updated the dessert price to `Brownie 50`.

\- Commit message: `Update brownie price to 50`.



\### 3.4 Merge

\- Pull request: https://github.com/Anjalireddy000/cafe-24ag1a05x4/pull/2

\- Record the final merge and branch deletion status after verifying them on GitHub.



\## Q4: Merge Conflict and Cherry-Pick



\### 4.1 Coffee Price Changes

\- Alex branch: `feature/coffee-price`

\- Alex's change: `Coffee 35`

\- Sam branch: `feature/coffee-offer`

\- Sam's change: `Coffee 40`

\- Sam's commit message: `Sam: coffee 40`



\### 4.2 Merge Conflict

\- Record the exact conflict message shown by GitHub when opening Alex's pull request.



\### 4.3 Conflict Resolution

\- Required final coffee price: `Coffee 38`

\- Preserve `Tea 25` and `Juice 40`.

\- Remove all conflict markers before committing the resolution.



\### 4.4 Merge Alex's Changes

\- Verify that the merged `main` branch contains `Coffee 38`.



\### 4.5 Cherry-Pick

\- Experimental commit: `Add ice experiment`

\- Tax commit: `Add tax note`

\- Cherry-pick only the tax-note commit onto `fix/tax-note`.

\- Verify that `ice.txt` is not present on `main`.



\*\*Note:\*\* Complete the remaining answers after performing and verifying the corresponding exam tasks.

