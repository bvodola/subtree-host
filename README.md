git remote add shared https://github.com/bvodola/subtree-test.git

git subtree add --prefix=subtree-test shared master

git subtree push --prefix=subtree-test shared main
