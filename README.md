# github-final-project
A hands-on project demonstrating Git and GitHub skills, including forking, branching, committing changes, merging, creating pull requests, and reverting changes.
2023 XYZ, Inc.
git add README.md
git commit -m "Fix typo: Update footer to 2023"
git push origin bug-fix-typo
git checkout main
git merge bug-fix-typo
git checkout -b bug-fix-revert
git revert <commit_hash_of_typo_fix>
git push origin bug-fix-revert
