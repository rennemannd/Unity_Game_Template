# untitled_project
This is some sort of game developed in unity by UF students and others who want to work on game development. For more information our discord server can be found here: https://discord.gg/FKWf8st

We are using the git flow model for branch orginization described here (this should be reviewed before any pushes!!!): https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow

The following instructions are to start work on this project. Git LFS does not need to be installed if you are using GitKraken for source control. 

1. Install Unity version 2019.1.12f1
2. Install git here: https://git-scm.com/book/en/v2/Getting-Started-Installing-Git
3. Install git lfs from here: https://github.com/git-lfs/git-lfs/releases
4. Run "git lfs install" in with git 
5. Git hooks must be enabled to use git lfs which is done in CL by (SOMEONE TEST AND PUT THAT HERE). It is done in GitKraken by going to Preferences -> General and setting the path to sh.exe found in the git install bin.
6. Clone the project from this repo, the flags for LFS are already defined in .gitattributes.
7. Open the untitled_project subfolder in Unity. 
8. To change the editor used go to edit -> prefrences -> external tools -> external script editor and set it there.


Possible Errors:
Push or Pre-Hook failed due to locking error: This can be fixed by disabling git lfs locking with "git config lfs.github.com/UserName/untitled_project.git/info/lfs.locksverify false"
