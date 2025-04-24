# lab2_task1  
# Delete branches locally & remotely  

#Delete local branches:  

#git branch -d dev  

#git branch -d test  

#Delete remote branches:
#git push origin --delete dev  

#git push origin --delete test  


# Checkout another branch without committing changes  
 
You have uncommitted changes but want to switch?  

#git stash  

#git checkout <jalal_working_branch>  

# To get the changes back:
#git stash pop  


# Create annotated tag and push it  

#git tag -a v1.7 -m "Version 1.7 release"  

#git push origin v1.7  


# List all tags  

#git tag  

# Delete tag locally and remotely  

# Delete locally:  

#git tag -d v1.7  

# Delete remotely:  

#git push origin --delete tag v1.7  


![image created by Jalal](githubReadmeImage.png)
