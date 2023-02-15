# The Git-Github lecture for MDG SoC'23

*This is a list of basic git commands you will be needing for **MDG SoC '23***
> Some pre-requisites:
> - Install [git](https://git-scm.com/downloads)
> - Sign up for [github](https://github.com/)

### 1. Configuring Git   

   - Setting your username
   ```sh
   git config --global user.name "FIRST_NAME LAST_NAME"
   ```   
   - Setting your email
   ```sh
   git config --global user.email "MY_NAME@example.com"
   ```   
   
### 2. Initializing / Cloning a Repository   
  
   - Initialize an empty git repository 
   ```sh
   git init
   ```   
   - Cloning a repository
   ```sh
   git clone https://github.com/user/this-is-just-an-example.git
   ```

### 3. Branches - Create, Switch, Delete and View

   - Create a new branch
   ```sh
   git branch new_branch
   ```   
   - Switching to a branch
   ```sh
   git checkout your_branch
   ```   
   > Or... you could use ```git checkout -b new_branch``` to create new_branch and switch to it.
   - Deleting a branch
   ```sh
   git branch --delete not_wanted_branch
   ```
   - View which branches exist
   ```sh
   git branch
   ```

### 4. Status, Add, Commit
### 5. Push to remote
### 6. Pulling from the origin
### 7. Stash, pop
### 8. Raising a PR

Here are some other useful links you might need:
- [Git-Github for Poets](https://www.youtube.com/playlist?list=PLozRqGzj97d02YjR5JVqDwN2K0cAiT7VK)
- [Official Git docs](https://git-scm.com/docs) - if reading is more your thing

*Welcome to MDG SoC'23...we'll be waiting for your first PR :heart:*