Creating A New Repo/Folder that Accept Changes and Sync bewtween your local computer and Github

    1.If you are working an a brand new/original project or code
        do the following


    2.On your Local Computer, 
        create a folder where you want the code and files to save. Folder Name is a Good Idea to be the Project Name 
        ie "Calculator App"

    3.On Github.com 
        Create a repo, give it the same name as the folder on your Desktop Local Computer.

    4.Once created GitHub.com will create a link that you use to sync VS Code (on your PC) with Github.com 
         ie https://github.com/your-username/<your-github-repo>

    5.On VS Code (local desktop app)
        Top Left click file > open folder, you can tell you are in the file because its show up on the explore tab on the left 

        right click the folder in VS Code and in the mini menu select "Open in Intergrated Terminal" 
        this will open VS Code CLI

        run the following commands in this order

        git status 
            check if VS Code is tracking changes, 
                    skip next 

        git init : 
            will activate code change tracking (do it only on BRAND NEWcode files once)
        git add . 
            will stage the changes to be publsihed to Github.com
        git commit -m 
            "write a publication msg, fyi this is public" this will save the save the staged stages
        git remote add origin <repo-URL>
            this will connect the local folder to the online (Github) repo
        git branch -M main
            "branch" is a another term for copy/verison "-M" means rename, so you are renaming this copy of code the "main" 
            because this is the base 
        git push -u origin main
            PUSH publishes your code to public, but it wont work unless you are actually making changes to a file 
            (.pyt .md .js etc)

    6. Now start coding
        if you done all the previous commmands correct with no error

        every time you add/change the code you should be able to save updated online to git hub

        by using the following commands it CLI
        git add . {stages your code}
        git commit -m "you must type a message"  {saves your code}
        git push {publishes your code to GitHub online}



Let Say you are now on a new computer and want to pull the code from github and continue editing and updating  

    1.On your NEW local computer,
        Open File Explore and Create a Folder where you want the code/project saved
  
    2.On VS Code 
        On the welcome tab, in the "Start" in the middle select "Clone Git Repository" 
            VS Code will asks for the link of the GitHub repo you want to download 
            ie https://github.com/your-username/<your-github-repo>
            VS Code will then prompt you to select where your want the repo stored locally. 
            (select the folder we created in step 1)
        Once Store Locally 
             you should see the file downloaded is available is the VS Code explorer tab (on the left) 
                if not you may need to just open the folder, by clicking "open folder" in VS Code

    3.Start Editing normally

        to save to Github      
    4.On VS Code Terminal (to open ternimal right click on the project file/folder and select open intergated terminal)    
            Becuase you cloned a repo, you don't need to do "git init"
        
        In Terminal use the following 
        
         git add . 
            will stage the changes to be publsihed to Github.com
         git commit -m 
            "write a publication msg, fyi this is public" this will save the save the staged stages 
         git push -u origin main
            PUSH publishes your code to public, but it wont work unless you are actually making changes 
            to a file (.pyt .md .js etc) you
            only have to do the full line the once the first time, afterwards "git push" works just fine


