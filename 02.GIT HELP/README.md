![freeCodeCampFaro Logo](https://github.com/freeCodeCampFaro/Summer_Hackathon/raw/master/logoimgs/logo.png)

# Summer_Hackathon


### freeCodeCamp Faro
#### Hackathon to build a React-Native Game


#### Git Helper:

##### Cloning the Repository Fork

1. Fork the freeCodeCampFaro/Summer_Hackathon repository through the fork link on the top of the page. This will create a new repository on your GitHub account.

2. Go to your forked repository and get the clone link (HTTPS recommended).  
   Now on your PC, go to where you would like the repository folder to be, and open a git console. Clone the repository:  
     ```
     git clone <YOUR_CLONE_LINK> <FOLDER_NAME>
     ```
     
     NOTE: If you don't give it a folder name, it just saves to a folder with the same name as the Repo.

3. Now you have the folder with the repository. Go inside it.
   ```
   cd <FOLDER_NAME>
   ```

##### Setting the Upstream

4. We need to set the upstream for the repository, so we can update our fork when the original is updated.
   Check your current remotes:
   ```
   git remote -v
   ```
   You should see something like this:
   ```
   origin  https://github.com/<YOUR_USERNAME>/Summer_Hackathon.git (fetch)
   origin  https://github.com/<YOUR_USERNAME>/Summer_Hackathon.git (push)
   ```

5. Go to the original repository page on GitHub. Get it's clone link like you did for your repository.

6. Back on the git console, do:
   ```
   git remote add upstream <ORIGINAL_REPO_LINK>
   ```
   Note: BE CAREFUL about spaces. If you have errors, only copy the link and rewrite everything else again, including spaces! If it lets you add but then you have problems updating (see next section), do:
   ```
   git remote remove upstream
   ```
   And redo the add above.

7. You can check the remotes again (see 4.). You should name have 2 more named "upstream".

##### Updating your fork

8. Now you're ready to update your fork! Whenever new merges are made to the original repo, you will want to do this.
   We fetch from the original (our upstream now) the most recent changes we don't have.
   ```
   git fetch upstream
   ```
   
9. Make sure you have checkout out the branch you want to update.
   ```
   git checkout master
   ```
   
10. Now we want to merge the changes we fetched to our local branch (notice it's a local, not our fork yet).
    ```
    git merge upstream/master
    ```

11. If you go to your forked repository on GitHub now, you will see nothing has changed, you still have things missing from the Upstream. We need to push the changes from the upstream to our remote forked repository (our repository's origin). So you just have to do:
    ```
    git push
    ```

12. All done! Now you should have your fork equal to do original repository!

----------------------------------------------------------------------------------------------

That's all folks! And Remember: BE STRONG & CODE ON! 
Aug 2017


















