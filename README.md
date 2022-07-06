- Create feature branch `git checkout -b feature-branch`
- Make changes to project
- Git add + commit + push `git add . && git commit -m 'Changes' && git push origin feature-branch`
- Git push to subtree `git subtree push --prefix=subtree-test shared feature-branch`
- Merge PR in subtree: https://github.com/bvodola/subtree-test
- Plll changes on another project `git subtree pull --prefix=subtree-test shared master`

Useful commands:
git remote add shared https://github.com/bvodola/subtree-test.git
git subtree add --prefix=subtree-test shared master
git subtree push --prefix=subtree-test shared main
git subtree pull --prefix=subtree-test shared main
