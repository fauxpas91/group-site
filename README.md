# reading-group-up-site
The Reading UK group of freeCodeCamp

  ## About this project
  This repo is for the __freecodecamp Reading group members__ who might like to introduce themselves to __Git and Github__. The idea came along when Paul Cb, a new  member, whom joined the Reading Group, 8-MAR-2017 and was keen to; in his own words, ... "get something going ... like a Reading fcc website ... and different group members could add different functionality to it". I thought this was a __great idea__ and had a notion to see if I could help that thought along a bit. His initial idea was to use a "meetup" to discuss the matter of a group project, but a meetup had not been achieved in the past although efforts had been made to get one setup. I relate my own situation with regards a meetup, in that it would have to be worth the seventy mile round trip to Reading for me to attend. So thoughts turned towards online communication using Git and Github; could a project to build a Reading Group site, with these technologies and by relatively inexperienced users be accomplished?

  ## How can you join this project?
  If you have not used Git or Github before then there is a bit of "legwork" to do. You should skip to the section of this README headed Resources watch some videos and or do some reading and rejoin here later.

  If you are somewhat familiar with Git and Github then I suggest you plough on. Here a condensed guide, but you should refer to the resources below:
   - Install Git on machine. I prefer the Unix type console, if you are using a Windows box, which you get when you install Git Bash. [see Resources - How to install Git Bash in Windows].
   - Fork this repository at [https://github.com/fcc-reading](https://github.com/fcc-reading)
   - Check your Git is installed. Do git --version which should return the version number you installed.
   - Clone it to your machine.
   - Open your cloned index.html file in your browser and if you scroll to the page called Site development roles you can choose a role for yourself to work on.
   - Put your details against your chosen role by altering the index.html.
   - This then becomes a way of notifying other members that you are currently working on that part of the site.
   - You will notice that there is a "role prefix" and you should use this prefix to make a new branch off of your master branch. For instance if you picked the role "header" and you intended to start work on the nav you could name your branch header-nav.
   - Now, I suggest you read the two references below GitHub Standard Fork & Pull Request Workflow and Development workflow with Git: Fork, Branching, Commits, and Pull Requests.
   - Notice you will need to setup the upstream remote so that you can sync your fork with the upstream repository. "Upsteam" refers to the original repo that was forked.
   - So use your role name prefix to make your branch name eg. git branch header-nav and then switch to that branch using git checkout header-nav.
   - Open up your editor from the terminal using the command editor-name followed by a space then a dot. eg. If you are using atom it would be atom . and with sublime text it would be subl .
   - You can now make your changes to a file or files in your editor.
   - Go back to your terminal and type git status to show your modifications.
   - Continue the cycle of git add, git commit, git status, git push as per the resources below.
   - After your push go back to your Github account and do a pull request.
   - The above is just an overview; follow the resources below for details of the correct work flow.
   - Good luck! If you have problems your first port of call should be that font of all knowledge ... Google. If your still stuck raise an issue on this repo. If I can't help someone else might be able to. Additionally, Reading Groups facebook page.
  ## Using Github issues
  It might be a good idea to communicate any problems, new feature requests, etc. using Github issues. Sign into your Github account and navigate to the upstream repo and click the New Issue button.

  Incidentally, if you are completely adverse to working in the terminal then the [Github Desktop](https://desktop.github.com/) is another way to go.

  ## Resources
  - [How to install Git Bash in Windows](https://www.youtube.com/watch?v=rWboGsc6CqI)
  - [freecodecamps' Git training on youtube](https://www.youtube.com/playlist?list=PLGvfHSgImk4aTlKBUPeC8Eh42LVDcSv9s)
  - [Git & GitHub Crash Course For Beginners - by Traversy Media](https://www.youtube.com/watch?v=SWYqp7iY_Tc) again on youtube.
  - [Submiting Your First Pull Request on Github](https://www.youtube.com/watch?v=YTbRzhQju4c)
  - [Github - Pull request tutorial](https://www.youtube.com/watch?v=NnBb9NTk-To)
  - [How to set up SSH keys for Git and Github](https://www.youtube.com/watch?v=Vi-WqFKYpnw)
  - [Fork A Repo](https://help.github.com/articles/fork-a-repo/)
  - [Understanding the GitHub Flow](https://guides.github.com/introduction/flow/)
  - [Syncing a fork](https://help.github.com/articles/syncing-a-fork/)
  - [Configuring a remote for a fork](https://help.github.com/articles/configuring-a-remote-for-a-fork/)
  - [GitHub Standard Fork & Pull Request Workflow](https://gist.github.com/Chaser324/ce0505fbed06b947d962)
  - [Development workflow with Git: Fork, Branching, Commits, and Pull Request](https://github.com/sevntu-checkstyle/sevntu.checkstyle/wiki/Development-workflow-with-Git:-Fork,-Branching,-Commits,-and-Pull-Request)
  - [ GitHub Desktop - Simple collaboration from your desktop](https://desktop.github.com/)
  - [Git Branch Naming Conventions](https://allenan.com/git-branch-naming-conventions/)
  - [Pro Git - an online Git book](https://git-scm.com/book/en/v2)

  ## One last question before wrapping up. What makes a great looking website?
  Take a look at this [website](http://www.florin-pop.com) what a great design and functionality. Click the About, Resume, Portfolio buttons; such a great design! At the moment have we got the skills to get near to this; probably not! However, it should be our future goal to do so. So what specifically is so appealing about it? Think about this and perhaps, if you've got a moment, post your thoughts on our facebook page or better still by using this repos issue feature.


  ## Congrats! you got to the end of this README...
  In the spirit of the [Pomodoro Technique](http://codepen.io/Andromeda31/full/oZMxdx/) ... take a break.

  Cheers! John
