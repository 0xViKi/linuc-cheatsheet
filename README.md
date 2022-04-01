# Linux Command Cheatsheet

#### Shred Files Recursively:
  shred all files in sub-directories
  
  ```find path/to/dir -type f exec shred -uvz {} \;```
