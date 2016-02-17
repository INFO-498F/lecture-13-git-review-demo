# Git review demo
This is a really quick demo to show how to check for and then pull down changes from a remote repository. To follow along:

1. Clone this repository (yes, _**this**_ repository):
  
  ``` 
  git clone https://github.com/INFO-498F/lecture-13-git-review-demo.git 
  ```
  
2. Confirm the location of your remote
  
  ```
  # Verbose check of the remote
  git remote -v
  ```
  
3. Mike made some changes
4. Check to see if there have been any changes:
  
  ```
  git fetch
  ```
  
4. Integrate the changes into your (unchanged) repository using the `git pull` command:
  
  ```
  # Check status 
  git status
  
  # Pull in changes
  git pull origin master
  ```
5.  Confirm that you can see the changes in your (local) log
  
  ```
  git log --oneline
  ```
