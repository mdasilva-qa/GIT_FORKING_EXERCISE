# GIT_FORKING_EXERCISE

Your task is to fork this remote repository, thus creating a copy on your GitHub. You will then configure the `upstream` remote repository for your forked repository, allowing it to pull changes from the `upstream` remote.

## Steps

1. Fork this repository using the `Fork` button

![image](https://user-images.githubusercontent.com/67016030/115005139-797a9f00-9e9f-11eb-8747-05d5090a6ae4.png)

2. Once you have been redirected to your account's version of the repository, clone your repository to your local machine

3. Change into the directory of the project you cloned

4. Run `git remote -v` to confirm that your `fetch` and `push` `origin` remotes point to your forked repository

5. Copy the Git URL for this repository, not your copy. Then add it as a new remote called `upstream` using `git remote add upstream [URL]`

6. Confirm with `git remote -v`

7. To pull changes from the remote repository, first:

    1. Run `git fetch upstream` to fetch any changes, this does not download the files
    2. Merge the changes from the `upstream/main` repository branch to the local `origin/main` repository branch. (merge conflicts may have to be resolved) using `git merge upstream/main`
    3. Push any changes to your remote repository using `git push`
