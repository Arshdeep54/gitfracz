# ignore-them

1. Setup for this exercise

   ```git start ignore-them```  
  
2. create a .gitignore file

   ```touch .gitignore```  

3. Edit the .gitignore file using vim

   ```vim .gitignore```
   and add
   ```
   *.exe
   *.o
   *.jar
   libraries/
    ```
   
4.  add the .gitignore file and commit

   ```
    git add .gitignore
    git commit -m "ignore-them "
   ```
   

Now ```git verify```   
Passed!
