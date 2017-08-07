![freeCodeCampFaro Logo](https://github.com/freeCodeCampFaro/Summer_Hackathon/raw/master/logoimgs/logo.png)

# Summer_Hackathon


### freeCodeCamp Faro
#### Hackathon to build a React-Native Game


#### 01. INTRO

Hi Peeps! 

Summer is here and cool stuff pops out of the box! It's time to drink some beers and improve our friendship and cohesion as a group! It's also time to improve our skills and go furthermore! This is the perfect opportunity to be TOGETHER and to have some geek fun developping an App and working over a GitHub Repo. Read below to get the idea and remember BSCO! - Be Strong & Code On!

---------------------------------------------------------------------------------------------

#### 02. THE IDEA

FCC Students are in different stages of learning how to program. That's the perfect opportunity to gather skills and develop an App / Game from Scratch and publish it to the world in the Apple and Google Stores. This will be an ASYNC event. You'll have meetings called the B+F (Beer + Fun) to discuss face-to-face the main goals and structures of the App. Then you'll have to estabilish a compromise and work at home to improve and develop the solutions generally defined in the B+F Meetings. Each participant is welcome to take part in each component of the app development independently of his/her own stage in the fcc certification. Everyone is welcome and invited to do something / contribute.

You can think of this as a side project that can raise our motivation and confidence as beginners. You can also learn to use some important tools such as GitHub. Consider yourself,since now, invited to fork this repo and propose some changes doing PR(See Note 1 below).

----------------------------------------------------------------------------------------------

### 03. THE GAME

The main objective would be to create a Game, available on computer browser and mobile devices. We should use React Native since it's cross-compatible with IOS and Android environments. It would be a standard quizz game for programmers. Each question would appear to the user with four different answers: A,B,C,D. All the main definitions and structure of the App should be freely discussed and designed in face-to-face meetings/btainstorms.

To accomplish this objective the FCC Faro Group would have two types of efforts:

1. Participate in the face-to-face mettings;
2. Participate alone or in groups at home working and doing PR to this GitHub repo;

----------------------------------------------------------------------------------------------

### 04. HACKATHON LINE-UP


**Day 01** _(11/08/2017 - 21h00 - Faro - Seu Café)_

1. B+F (Beer + Fun) Meeting to define the user story of the game;

2. Work at home to improve the main user story defined before;

**Day 08**

3. B+F to define the main functionality of the APP (UI/UX) based on the User Story Defs;

4. UI/UX Tournament (Definition of the Mockups and Functionality of the App)

Peeps will have time to prepare their best design/mockups of the app.

**Day 22**

5. B+F to elect the winner of the UI/UX Tournament

6. Work at home to improve the winning UI/UX mockup.

**Day 36** 

7. B+F to define Front-End and Back-End requirements

8. Work at home to develop the FE and BE parts.

**Day 50**

9. B+F to discuss and fine tune the FE and BE parts.

**Day 64**

10. B+F for discuss/prepare the App to be published in Apple and Google Stores

11. Work at home to accomplish with the preps.

**Day 78**

12. B+F Party to celebrate and do the App launch and discuss the event to future improvement.

----------------------------------------------------------------------------------------------

### 05. THE MENTORSHIP & ORGANIZATION

Get in touch with us ate the GeekSessions FAO Slack (#freecodecamp)

Mentors:
1. André Jonas (@jonas)
2. Miguel Coquet (@coquet)
3. Nelson Neves (@nneves)

Remote Mentors: 
1. Filipe Dias (@nosleepfilipe)

Organization: 
1. Eduardo Vedes (@evedes)
2. Alexandre Palma (@alxjspalma)
3. Patrícia Ribeiro (@pribeiro)
----------------------------------------------------------------------------------------------

### 06. SPONSORSHIP

WTF we need: 

1. Offices or Places to do the B+F Meetings;
2. Fresh beer;
3. Projector;
4. It would be nice if we could pay dinner to the mentors.

----------------------------------------------------------------------------------------------

### 07. NOTES

NOTE 01:

- You will need a GIT HUB account so if you don't have one create it! RSA! (Read Search Ask);
- You need to fork the freeCodeCampFaro/Summer_Hackathon Repo;
- You clone it to your machine and edit some changes;
- You push the changes from your origin to master branch of your Fork in your GH account;
- You do a Pull Request (PR) on GH Forked Repo and wait for comments / approval / rejection.

----------------------------------------------------------------------------------------------

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
   Note: BE CAREFUL about spaces. If you have errors, only copy the link and rewrite everything else again, including spaces!

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


















