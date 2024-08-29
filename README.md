# NewRepo
![image](images/pic1.jpg)
Question1_SOL:  

echo "# NewRepo" >> README.md 
git init 
git add README.md 
git commit -m "first commit" 
git branch -M main 
git remote add origin https://github.com/Manar-Abdelraheem/NewRepo.git 
git push -u origin main 

Question2_SOL: 

# Create and push the dev branch 

git checkout -b dev 

echo "This is the dev branch." > dev-file.txt 

git add dev-file.txt 

git commit -m "Add dev-file.txt on dev branch" 

git push -u origin dev 

  

# Create and push the test branch 

git checkout -b test 

echo "This is the test branch." > test-file.txt 

git add test-file.txt 

git commit -m "Add test-file.txt on test branch" 

git push -u origin test 

Question3_SOL: 

# Switch to the main branch 

git checkout main 

  

# Merge dev into main 

git merge dev 

  

# Merge test into main 

git merge test 

  

# Push the main branch to the remote repository 

git push origin main 

Question4_SOL: 

# Switch to the main branch 

git checkout main 

  

# Delete branches locally 

git branch -d dev 

git branch -d test 

  

# (Optional) Force delete branches locally 

# git branch -D dev 

# git branch -D test 


# Delete branches remotely 

git push origin --delete dev 

git push origin --delete test  

Question5_SOL: 

 

# Stash your uncommitted changes 

git stash 

# Checkout the branch you want to switch to 

git checkout <branch-name> 

# Switch back to your original branch 

git checkout <original-branch-name> 

# Apply the stashed changes 

git stash pop 



Question6_SOL: 

# Create an annotated tag with the name v1.7 

git tag -a v1.7 -m "Release version 1.7" 

 Question7_SOL: 

# Push the tag to the remote repository 

git push origin v1.7 

Question8_SOL: 

git tag: Lists all tags. 

git show-ref --tags: Lists tags with their commit hashes. 

git tag -l "pattern": Lists tags matching a specific pattern. 

git tag -n: Lists tags with their descriptions. 

 
Question9_SOL: 

# Delete the tag locally 

git tag -d v1.7 


# Delete the tag remotely 

git push origin --delete v1.7 

 

Question10_SOL: 

 git add README.md images/pic1.jpg

 git commit -m "Add logo image to README.md"
 
git push origin main

 

 
