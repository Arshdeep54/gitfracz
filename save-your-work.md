# save-your-work

1. Setup for this exercise

   ```
   git start save-your-work
   ```  
  
2. Stash the current working tree

   ```
   git stash
   ```  

3. Fix the bug and commit 

   ```
   git add bug.txt
   git commit -m " bug fix "
   ```

4. Back to previous working tree

   ```
   git stash pop
   ```

5. Add new line as asked , stage and commit

   ```
   vim bug.txt # add the Finally, finished it. text 
   git add .
   git commit -m " finished"
   ```

Now ```git verify```   
Passed! 
