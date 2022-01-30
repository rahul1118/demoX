Create Repository:
    • Use GitHub to create a remote repository named demoX.
    • Use GitHub to create the first commit.
        ◦ Add README.
        ◦ Modify the text to  # DEMOX README # .
        ◦ Click Commit. Change the commit message to add README .
        
 Clone Repository:
    • Clone the remote repository to local using:
        ◦ git clone [url]
        ◦ cd demoX
Commit To Repository:
    • Create an file named fileA.txt in the projecta directory using:
        ◦ echo “Git Demo” > fileA.txt
    • Execute git status . You should see that Git notices the fileA.txt file and identifies it as untracked.
    • Add fileA.txt to the staging area using:
        ◦  git add fileA.txt
    • Execute git status again. You should see that Git adds fileA.txt under "Changes to be committed".
    • Execute git commit -m "added fileA.txt" to create a commit.
    • Execute git log --oneline . A concise version of the history is displayed.
