# Github Training for Product Developers

0. To create a new branch and immediately switch to it or switch to existing feature branch
    ```sh
    $ git checkout -b <<Feature_Branch>>
    $ git checkout <<Feature_Branch>>
    ```

1. Always first use **git pull** before working(Editing and making changes) on a feature branch.
    ```sh
    $ git pull origin <<Feature_Branch>>
    ```
2. After you make necessary changes to the feature branch, make git status, commit, push feature branch.
    ```sh
    $ git status
    $ git add -A
    $ git commit -m "<<Message>>"
    $ git push origin "<<Feature_Branch>>""
    ```
3. After pushing changes to remote feature branch you make merge request to product maintainers to merge your feature branch to that of master branch.


