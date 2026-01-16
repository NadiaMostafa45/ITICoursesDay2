How to remove them locally 
git branch -d dev
git branch -d test

How to remove them remotly
git push origin --delete dev
git push origin --delete test


git stash
git checkout dev
git stash pop

to remove tag local
git tag -d v1.7
to remove tag from github 
git push origin --delete v1.7

<img width="1920" height="1080" alt="Screenshot (1725)" src="https://github.com/user-attachments/assets/32cad4ad-c2a1-4beb-9a5c-7d9c820f4045" />

