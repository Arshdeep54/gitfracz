# ignore-them

1. Setup for this exercise

   ```
   git start ignore-them
   ```  
  
3. create a .gitignore file

   ```
   touch .gitignore
   ```  

5. Edit the .gitignore file using vim

   ```
   vim .gitignore
   ```
   and add
   ```
   *.exe
   *.o
   *.jar
   libraries/
    ```
   
7.  add the .gitignore file and commit

   ```
    git add .gitignore
    git commit -m "ignore-them "
   ```
   

Now ```git verify```   
Passed!
