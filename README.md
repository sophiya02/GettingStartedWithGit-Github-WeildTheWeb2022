[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![Pull Request Merged](https://img.shields.io/github/issues-pr-closed/sophiay02/GettingStartedWithGit-Github-WeildTheWeb2022)](https://github.com/sophiya02/GettingStartedWithGit-Github-WeildTheWeb2022/pulls)

# First Contribution

- Thinking about doing an open source contribution?
- Don't know where to start or how to do?
- Looking for a simple repository to help you to get started?

Then look no further, we have created this repository to help you to get started.

## Step-by-Step Guide for beginners for getting started with Open-Source

### This project is part of Weild the Web 2022, by CES, MMMUT Gorakhpur
[![Weild the Web](assets/copy-to-clipboard.png)](https://wtwces.netlify.app/)

### 1. The first thing you need is Git installed on your system, if it is not installed then download it as per your OS and install it.

- ## Git Setup
<ul>
<li><a href="https://git-scm.com/downloads">Download Git</a> as per your OS.</li>
<li>Git installation<a href="https://www.youtube.com/watch?v=2j7fD92g-gE"> Video</a> for Windows User</li>
<li>Git installation<a href="https://www.youtube.com/watch?v=ZM3I16Z-lxI"> Video</a> for Mac User</li>
<li>Git installation<a href="https://www.youtube.com/watch?v=PLQQ3tJwBJg"> Video</a> for Linux User</li>

<li>Install Git</li>
<li>Open the Git Bash ( Right Click )</li>
<li>Run the Commands</li>

`$ git config --global user.name "Your Name"`

`$ git config --global user.email youremail@example.com`

`$ git config --list`

<li>You should be able to see your entered name and email under <mark>user.name</mark> & <mark>user.email</mark></li>

</ul><br>
<hr>

### 2. Now you just have to setup the project from GitHub to your local system.

- ## Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

- ## Clone the repository

<img align="right" width="300" src="assets/clone.png" alt="clone this repository" />

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the clone button and then click the _copy to clipboard_ icon.

Open a terminal and run the following git command:

```
git clone "URL you just copied"
```

<img align="right" width="300" src="assets/copy-to-clipboard.png" alt="copy URL to clipboard" />

For example:

```
git clone https://github.com/this-is-you/first-contributions.git
```

where `this-is-you` is your GitHub username. Here you're copying the contents of the first-contributions repository in GitHub to your computer.
<hr>

### 3. Create a new branch(It is always advisable to create new branch for any changes).

- ## Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd first-contributions
```

Now create a branch using the `git checkout` command:

```
git checkout -b <add-your-new-branch-name>
```

For example:

```
git checkout -b add-muhammad
```

(The name of the branch does not need to have the word _add_ in it, but it's a reasonable thing to include because the purpose of this branch is to add your name to a list.)
<hr>

### 4. Make necessary changes and commit those changes

Now open `contributions.yml` file from `_data` directory in a text editor, add your name with emoji of your country flag, github_account and profile picture URL (avatar) to it. Don't add it at the beginning or end of the file. Put it anywhere in between. Now, save the file.

<img align="right" width="450" src="assets/git-status.png" alt="git status" />

If you go to the project directory and execute the command `git status`, you'll see there are changes.

Add those changes to the branch you just created using the `git add` command:

```
git add _data/contributions.yml
```

Now commit those changes using the `git commit` command:

```
git commit -m "Add <your-name> to Contributors list"
```

replace `<your-name>` with your name.
<hr>

### 5. Push changes to GitHub

Push your changes using the command `git push`:

```
git push origin <add-your-branch-name>
```

replace `<add-your-branch-name>` with the name of the branch you created earlier.

<hr>

### 6. Submit your changes for review

Now if you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

<img style="float: right;" src="assets/compare-and-pull.png" alt="create a pull request" />

Now submit the pull request.

<img style="float: right;" src="assets/submit-pull-request.png" alt="submit pull request" />

Soon, I'll be merging all your pull requests into the master branch of this project. You will get a notification email once the changes have been merged.

<hr>

## Contributors

Thank you to all the contributors who help in making this project better :raised_hands:

<a href="https://github.com/sophiya02/GettingStartedWithGit-Github-WeildTheWeb2022/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=sophiya02/GettingStartedWithGit-Github-WeildTheWeb2022" />
</a>

<br>

## Weild the Web 2022:
# First time Contributors 
-   ### **A** <br>
-   ### **B** <br>
-   ### **C** <br>
-   ### **D** <br>
-   ### **E** <br>
-   ### **F** <br>
-   ### **G** <br>
-   ### **H** <br>
-   ### **I** <br>
-   ### **J** <br>
-   ### **K** <br>
-   ### **L** <br>
-   ### **M** <br>
-   ### **N** <br>
-   ### **O** <br>
-   ### **P** <br>
-   ### **Q** <br>
-   ### **R** <br>
-   ### **S** <br>
    -   [Sophiya Singh](https://github.com/sophiya02)
-   ### **T** <br>
-   ### **U** <br>
-   ### **V** <br>
-   ### **W** <br>
-   ### **X** <br>
-   ### **Y** <br>
-   ### **Z** <br>

