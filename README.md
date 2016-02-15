# lecture-13-git-review-demo
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
  
3. Wait for Mike to make changes
4. Check to see if there have been any changes:
  
  ```
  git fetch
  ```
  
4. Integrate the changes into your (unchanged) repository using the `git pull` command:
  
  ```
  git pull origin master
  ```
