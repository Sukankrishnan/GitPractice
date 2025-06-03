To avoid certain files and folders from the project, mentioning in .gitignore file will help not to add in the GitHub repository.

For example,

The project structure is 

    -Student(Folder)
    
        StudentDetails.xlsx
        
    -special.log
    
    -test.js
    
    -Input(Folder)

When you want to push only test.js and igore other files and folders, add the relevant file name/path in the .gitignore file.

  *.log
  
  Student/
  
  Input/*.xlsx


  Resource: [How to use gitignore file](https://www.youtube.com/watch?v=1Qk8jrBrp9o)
