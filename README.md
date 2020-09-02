# Git-Learning
Git learnings

Imp points to remember:


- [ ] Git allows multi tasking in a very easy way possible. It makes sure that all people working on a similar file work productively
- [ ] All changes submitted by one person is readily available to others, however in case of conflicts, human intervention maybe needed
- [ ] Today we mostly use Version Control systems (VCS) and Distributed Version Control (DVC) which allows us to effectively makes changes on local system and then merge changes
- [ ] Downside of DVC is that it’s dependent on server, if the server fails, it’s not possible to fetch or push changes.
- [ ] Git (is DVC) came out in April 2005, its very fast, efficient with large projects and branching is exceptional
- [ ] Git maintains a snapshots of all check ins done on a particular file and since every file has a unique SHA1 ID, its easy to manage
- [ ] ONLY those files which have been changed are identified in the system, if user opens a file but doesn’t make any changes, it won’t show up on GIT
- [ ] Git doesn’t need to connect with a central repo all the time, once a version of code is fetched, changes can be done completely locally
- [ ] ONLY time you need to connect with the server is to exchange commits with others to fetch/push new changes
- [ ] Its flexible and adaptable and protects you with Data loss when you encounter connection issues
- [ ] Git can transfer data using 4 network protocols : Local access, SSH, Git protocol and HTTP
- [ ] Git main tools : add, status, diff, push, pull, reset, RM, log, tag
- [ ] Git rm will remove all the files from your working directory, but if you wanna delete just the staged files use git rm -cached
- [ ] Git log will gives you what changes you made. Git log -p will show diff introduced in each commit, we can also limit the commit by using option 2 for last 2 commits (e.g. git log -p 2)
- [ ] You can add tags for every commit with optional -a tag. There are two types of tag : lightweight (just a pointer) and annotated (full git object in DB)
- [ ] Annotated tags are recommended and they are shown in alphabetical order
- [ ] Branching and Merging, branching is an expensive feature for larger projects. Git is very fast as far as branching and merging is concerned
