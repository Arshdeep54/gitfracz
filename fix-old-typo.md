# fix-old-typo

1. Setup for this exercise

   ```
   git start fix-old-typo
   ```  
  
3. Rebase interactively to chnage commit details of the old commit , change pick option to edit in last 2 commits 

   ```
   git rebase -i
   ```  

5. Edit and stage the file 

   ```
   vim file .txt 
   git add file.txt
   ```
6. Commit the change with ```--amend``` to edit the message also

   ```
   git commit --amend
   ```
7. Back to the last commit with

   ```
   git rebase --continue
   ```

8. Fix the merge conflict , stage and commit

   ```
   vim file.txt
   git add .
   git commit -m " conflict "
   ```

Now ```git verify```   
Passed! 
    
