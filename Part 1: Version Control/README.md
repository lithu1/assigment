## 1.SSH Authentication Done 
<img width="1364" height="766" alt="image" src="https://github.com/user-attachments/assets/9c9ae324-8805-4864-9c4c-28565b998acb" />
## 2.
###  Difference between Git Fetch and Git Pull

#### Git Fetch
- It only downloads the changes from the remote repository.  
- It will not update or modify your working branch.  
- Mainly used when you want to review the changes before merging them.  

#### Git Pull
- It actually downloads and merges the changes into your current branch.  
- Useful when you are ready to update your branch with the latest changes from the remote repository.  

### Git Merge Conflict

A merge conflict arises when two or more people try to change the same line of code in a file.  

I can solve it by:  
1. Opening the file.  
2. Removing the conflict markers
3. Deciding which line of code should remain (or by combining both lines).  
4. Committing the changes.  
5. Finally, the merge conflict is cleared.

##3.
### Simulating a Merge Conflict and Resolving It

1. I created a `main` branch in the repo and added a file named `file.txt`.  
2. Then I made two branches named `feature-A` and `feature-B`.  
3. I edited `file.txt` in `feature-A` and added `"from feature A"`. Then I raised a PR and merged it into the `main` branch without any conflict.
     <img width="1590" height="1105" alt="image" src="https://github.com/user-attachments/assets/7f936cdb-aa09-46a3-97a8-1d35886bb6aa" />
4. Next, I edited `file.txt` in `feature-B` and added `"from feature B"`. When I raised a PR and tried to merge it into the `main` branch, I found a merge conflict.
     <img width="1593" height="1109" alt="image" src="https://github.com/user-attachments/assets/12c210a7-e662-4aed-a6e9-46978b2145ea" />

5. I resolved the conflict by combining the changes in `file.txt`, and then merged `feature-B` into `main` successfully without any conflict.
  <img width="1593" height="1107" alt="image" src="https://github.com/user-attachments/assets/d62898d4-aca8-433b-b266-49029be118c3" />
  <img width="1595" height="1107" alt="image" src="https://github.com/user-attachments/assets/f52fcc79-90ed-4f6d-bb24-aa1cff54d0df" />



