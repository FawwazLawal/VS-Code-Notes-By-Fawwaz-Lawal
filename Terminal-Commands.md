Creating A New Repo/Folder that Accept Changes and Sync bewtween your local computer and Github

If you are working an a brand new/original project or code
    do the following


On your Local Computer, 
    create a folder where you want the code and files to save. Folder Name is a Good Idea to be the Project Name ie "Calculator App"

On Github.com 
    Create a repo, give it the same name as the folder on your Desktop Local Computer.

    Once created GitHub.com will create a link that you use to sync VS Code (on your PC) with Github.com 
         ie https://github.com/your-username/<your-github-repo>

On VS Code (local desktop app)
    Top Left click file > open folder, you can tell you are in the file because its show up on the explore tab on the left 

    right click the folder in VS Code and in the mini menu select "Open in Intergrated Terminal" 
    this will open VS Code CLI

    run the following commands 

    git init : 
        will activate code change tracking
    git add . 
        will stage the changes to be publsihed to Github.com
    git commit -m 
        "write a publication msg, fyi this is public" this will save the save the staged stages
    git remote add origin <repo-URL>
        this will connect the local folder to the online (Github) repo
    git branch -M main
        defines which verison you are editing main is the orginal 
    git push -u origin main
        PUSH publishes your code to public, but it wont work unless you are actually making changes to a file (.pyt .md .js etc)

Let Say you are now on a new computer and want to pull yhe code from github and continue editing         

