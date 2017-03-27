# reading-group-site
The Reading UK group of freeCodeCamp

##### _You should read this README carefully, and completely, before joining the project_.
###### I have tried to write this guide with the newcomer to the use of the terminal, Git and Github in mind, but please remember, I am also a freeCodeCamp student that is trying to get to grips with it myself. I have used Git as a single user, but have never used it in collaboration with other programmers in conjunction with Github. I believe it will be an interesting beginning for all Reading members and regardless of how much you end up participating, you are more than likely to know more about Git, Github and the working of the terminal than if you hadn't participate at all.

So, you can see that I am fairly new to Git myself and what I have picked up has been by watching youtube videos or reading articles on the web. So, if you have any problems with your Git commands or the workings of Github then your first port of call should be that universal font of knowledge "Google"!

## So why learn Git and why should I learn it now?
Twelve projects into freeCodeCamp and I should be pleased, but I would have been much more pleased if I had setup each project as a Github repo; a history of how I built them would have been nice to have. I think I "missed a trick"!

Have you seen that statement "try to pair program"? Did you ever manage it? Was you told how to achieve it? Or, did the thought just pass you by? Well, we know that freeCodeCamp advocates it all the time, but I can never remember reading how I should go about it in practice? I hope, this project will tick the pair programming box for you.

Git and Github; they are the tools of much software collaboration in many companies and in open source projects around the world; and the interest in Git has gone off the scale; [visit this site for some pretty graphs of usage.](https://rhodecode.com/insights/version-control-systems-2016) Just take a quick peek and you will see how Git has increased in popularity in comparison to other version control systems. It seems people that need to use a vcs are migrating to Git!

## About this project
This repo is for the __freeCodeCamp Reading group members__ who might like to introduce themselves to __Git and Github__ in a safe environment. The idea came along when Paul Cb, a new  member, whom joined the Reading Group, 8-MAR-2017 and was keen to; in his own words, ... "get something going ... like a Reading fcc website ... and different group members could add different functionality to it". I thought this was a __great idea__ and had a notion to see if I could help that thought along a bit. His initial idea was to use a "meetup" to discuss the matter of a group project, but a meetup had not been achieved in the past although efforts had been made to get one setup. I relate my own situation with regards a meetup, in that it would have to be worth the sixty mile round trip to Reading for me to attend. So thoughts turned towards online communication using Git and Github; could a project to build a Reading Group site, with these technologies and by relatively inexperienced users be accomplished? An interesting question ... and we will find out in due course.

And for those Reading members who expressed a desire for a meetup you should really be asking yourself ... "how can I help to make a meetup happen?".

## How can you join this project?
If you have not used Git or Github before then there is a bit of "legwork" to do. You should skip to the section of this README headed Resources watch some videos and or do some reading and rejoin here later.

If you are somewhat familiar with Git and Github then I suggest you plough on. Here is a condensed guide, with some instructions particular to this project, but you should refer to the resources and should follow them in preference to my musings below when detail is important __and detail is always important:__
 - Install Git on your machine. I prefer a Unix type console, if you are using a Windows box, then you can set this up when you install Git Bash. [see Resources - How to install Git Bash in Windows].
 - Fork this repository at ([https://github.com/fcc-reading](https://github.com/fcc-reading)). For details see the resources - Fork A Repo.
 - Check your Git is installed. In your terminal do command git --version which should return the version number you installed.
 - Clone your copy of the repo that you have just forked to your machine in a directory of your choice.
 - Open your cloned index.html file that you now have on your machine in your browser and if you scroll to the page called Site development roles you can choose a role for yourself to work on.
 - Put your details against your chosen role by altering the index.html file on that page.
 - This then becomes a way of notifying other members that you are currently working on that part of the site and it's aim is to reduce merge conflicts to a minimum. A merge conflict occurs, for instance, when two or more coders change the same line of code and a merge is attempted.
 - When your done with a role, after a few days or weeks, please take your detail down so that others can continue.
 - Initially, I wouldn't be too fussy about what is accepted to go into the master branch, but as the project progresses I should ask the submitter ... "do you really think this improves the site?".
 - But why such a crappy site to begin with? Well, that's intentional and I hope it will inspire people to improve it.
 - Moving on, you will notice that there is a "role prefix" and you should use this prefix to make __a new branch off of your master branch.__ For instance if you picked the role "header" and you intended to start work on the nav you could name your branch header-nav.
 - Once the site is completely developed, the Site development roles page can then be stripped out or possibly morphed to a Members Profile page if the finished site is published to the great www. How it can be hosted, at zero cost, I have no idea at this stage.
 - Now, I suggest you read the reference below __GitHub Standard Fork & Pull Request Workflow__ and take note of the content and work through the steps carefully.
 - Notice you will need to setup the upstream remote so that you can sync your fork with the upstream repository. "Upsteam" refers to the original repo that was forked. This is going to allow you to receive changes to "upstream" that other members have had merged.
 - So use your role name prefix to make your branch name eg. git branch header-nav and then switch to that branch using git checkout header-nav. __You should not make changes on your master branch.__ Branching is important; it allows you to isolate your work from the master branch. Your master branch should remain equal to the upstream master. This is the currently deployable branch.
 - Open up your editor from the terminal using the command editor-name followed by a space then a dot. eg. If you are using atom it would be atom . and with sublime text it would be subl . NB: The dot means load all files/directories in the current directory.
 - You can now make your changes to a file or files in your editor.
 - Go back to your terminal and type git status to show your modifications.
 - Continue the cycle of git add, git commit, git status, git push, __but again follow the resources below. Particularly the one entitled GitHub Standard Fork & Pull Request Workflow. In that document  he states "Unfortunately, it's quite easy to make mistakes ...", so I can only say FOLLOW THE STEPS CAREFULLY.__
 - How often should you commit? When you say to your self ... "at this point things are working well. I want to be able to come back to this point if something goes wrong in the future." Commits are a snapshot of the repo at any point in time. The Git command git add puts new or modified files into a "staging area" and these are the modifications to the repo that will go into the next commit.
 - After your push go back to your Github account and do a pull request. You are asking upstream to consider your changes and merge into the master branch.
 - The above is just an overview; follow the resources for details of the correct work flow.
 - Good luck! If you have any problems remember ... your first port of call should be Google. If your still stuck raise an issue on this repo. If I can't help someone else might be able to. Additionally, communicate via Reading Groups facebook page or you will find that [Stackoverflow](http://stackoverflow.com/) has more than 83,000 questions tagged git and more than 22,000 tagged Github.

## Using Github issues
It might be a good idea to communicate any problems, new feature requests, etc. using Github issues. Sign into your Github account and navigate to this repo and click __issues__ then __New Issue__ button.

Incidentally, if you are completely adverse to working in the terminal then the [Github Desktop](https://desktop.github.com/) is another way to go, but you don't get the complete benefit of using the terminal commands which is a transferrable skill to other Git web-based version control repositories.

## About this mock site
I wanted to keep it simple and to give enough to give a base to build upon. The only part of the site I would like you to leave "as is" is the Site development page and it's css. As I previously mentioned, this is a sort of register; and when you fill it in you don't have to link to a photo of yourself if that doesn't appeal to you, or give your full name. Incidentally, the styling of this page is achieved using css Flexbox as I did not, at this stage, want to include something like Bootstrap for layout. Although we could include it later.

Whoever takes on the About page feel free to modify it as you please, but I was thinking, how best to say something about freeCodeCamp and the Reading group, you may have better ideas.

## Have I missed something out
I wanted to keep this README as brief as possible without losing meaning. So, if you think that something needs changing or expanded upon then please raise an issue and explain as clearly as you can what it is.

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
- [GitHub Desktop - Simple collaboration from your desktop](https://desktop.github.com/)
- [Git Branch Naming Conventions](https://allenan.com/git-branch-naming-conventions/)
- [Pro Git - an online Git book](https://git-scm.com/book/en/v2)

## One last question before wrapping up. What makes a great looking website?
Take a look at this [website](http://www.florin-pop.com) what a great design and functionality. Click the About, Resume, Portfolio buttons; such a great design! At the moment have we got the skills to get near to this; possibly not! However, it should be our future goal to do so. So what specifically is so appealing about it? Think about this and perhaps, if you've got a moment, post your thoughts on our facebook page or better still by using this repos issues feature.

## Last call
This repo has taken me considerable time to put together. This README, has gone through many revisions and has taken the bulk of the time. You wouldn't think it would you! But, I've cut things out because nobody really wants to read a long README anyway. It seems that I am far happier writing code than writing a README! Now it's time to get back to my freeCodeCamp projects, the joys of React.js bekons! But, I know one thing for sure I will be moving forwards with Git and Github.

## Congrats! you got to the end of this README...
In the spirit of the [Pomodoro Technique](http://codepen.io/Andromeda31/full/oZMxdx/) ... take a break.

I just hope Reading freeCodeCampers can recognize an opportunity when they see one. I've done the inception phase. I leave the testing through to deployment to the group. Have fun!

Cheers! John S

March 2017.
