# Gym-Git-Exercises-Solutions

# Exercise 1
1. 
D:\Programs\Gym\Gym Git Exercises Solutions> git init
Initialized empty Git repository in D:/Programs/Fec/.git/

D:\Programs\Gym\Gym Git Exercises Solutions> git remote add origin https://github.com/happydavid226/Gym-Git-Exercises-Solutions

D:\Programs\Gym\Gym Git Exercises Solutions> git branch

D:\Programs\Gym\Gym Git Exercises Solutions> git switch -c main
Switched to a new branch 'main'

D:\Programs\Gym\Gym Git Exercises Solutions> git pull origin main 
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 6 (delta 0), reused 3 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (6/6), 4.30 KiB | 91.00 KiB/s, done.
From https://github.com/happydavid226/Gym-Git-Exercises-Solutions
 * branch            main       -> FETCH_HEAD
 * [new branch]      main       -> origin/main

D:\Programs\Gym\Gym Git Exercises Solutions> 


2. 
D:\Programs\Gym\Gym Git Exercises Solutions>git branch
* main

D:\Programs\Gym\Gym Git Exercises Solutions>git branch -m master

D:\Programs\Gym\Gym Git Exercises Solutions>git branch
* master

D:\Programs\Gym\Gym Git Exercises Solutions>git branch -m main

D:\Programs\Gym\Gym Git Exercises Solutions>git branch
* main

D:\Programs\Gym\Gym Git Exercises Solutions>

3. 
D:\Programs\Gym\Gym Git Exercises Solutions>git add .

D:\Programs\Gym\Gym Git Exercises Solutions>git commit -m "initial commit"
[main d836ff7] initial commit
 1 file changed, 42 insertions(+), 1 deletion(-)

D:\Programs\Gym\Gym Git Exercises Solutions>git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 20 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 686 bytes | 686.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/happydavid226/Gym-Git-Exercises-Solutions
   0236181..d836ff7  main -> main

D:\Programs\Gym\Gym Git Exercises Solutions>

4. shown above

5. 

D:\Programs\Gym\Gym Git Exercises Solutions>git switch -c dev
Switched to a new branch 'dev'

D:\Programs\Gym\Gym Git Exercises Solutions>git switch -c test
Switched to a new branch 'test'

D:\Programs\Gym\Gym Git Exercises Solutions>git checkout dev
M       README.md
Switched to branch 'dev'

D:\Programs\Gym\Gym Git Exercises Solutions>git branch
* dev
  main
  test

D:\Programs\Gym\Gym Git Exercises Solutions>git branch -d test
Deleted branch test (was d836ff7).

D:\Programs\Gym\Gym Git Exercises Solutions>git branch
* dev
  main

D:\Programs\Gym\Gym Git Exercises Solutions>

# Exercise 2
git add home.html
git stash
git add about.html
git stash
git add team.html
git stash
git stash pop stash@{1}
git commit -m "added home and about pages"
git push
git stash pop
move team.html ../
cls
doskey /history

D:\Programs\Gym\Gym Git Exercises Solutions>


