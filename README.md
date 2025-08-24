This github repository is the main way that people in the Cult of Tato community can contribute to the website at http://cultoftato.com.

General workflow for submitting changes to Cult of Tato from the command line:
    ```git status``` see current state of the local repository
    ```git pull``` get all the latest changes from the GitHub repository
    ```git checkout -b user/feature_name``` create and switch to a new branch under your username and the feature name
Make changes to the code on the new branch, then
    ```git add feature_files``` add the edited files to the staging area so they will be committed
    ```git commit -m "message about the changes you made...coherence preferable"``` record the changes with a commit
    ```git push``` push the branch and associated changes upstream to GitHub...you should already be on the feature branch - if it is the first time need to do git push --set-upstream origin user/feature_name
Then you can go to GitHub in a web browser and open a PR from your feature branch to request approval and have the change merged
