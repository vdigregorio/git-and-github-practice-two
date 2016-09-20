# Git and GitHub Intro Lab
_adapted from Jay Nappy's [git-github-lab](https://github.com/GA-WDI/curriculum/tree/master/resources/01-workflow/git-github-lab)_

## Introduction

> ***Note:*** _This can be a pair programming activity or done independently._

Let's apply what we've learned from class to share and update each other's code.  With a partner, you're going going to alternate between who 'drives' and who 'navigates' while following the requirements under "Exercise" below. The goal will be to create a project, have a partner fork, clone, and edit the project, submit the changes as a pull request, and then have the changes merged.  

Be sure to look at the previous lesson for notes and helpful hints.

## Exercise

Partners will be referred to as partner1 and partner2.

### Part 1

**With partner1 driving:**

- create a folder called `git-and-github-practice`
- 'cd git-and-github-practice'
- within that folder create the following files `index.html` and `style.css`.
- copy and paste the code from the [starter-code](starter-code) from the `index.html` and `style.css` into the files you just created
- Initiate a git repository
- Commit your changes with the message "initial commit"
- Create a GitHub repository, set your remotes, and push to GitHub


**With partner2 driving, from their computer:**

- Get the link to your partner's GitHub repository and fork and clone it
- in your cloned repository, create a file called `normalize.css`.
  * copy the css from [here](https://necolas.github.io/normalize.css/4.1.1/normalize.css) and paste it into your newly created `normalize.css` file.
- commit your changes and submit a pull request back to partner1


**With partner1 driving:**

- merge the pull request from the GitHub interface



### Part 2

**With partner2 driving**:

- create a different folder, outside of the first project, called `git-and-github-practice-two`
-  within that folder create the following files `index.html`, `style.css`, and `normalize.css`
-  copy and paste the code from the merged pull request files (of your partner’s `git-and-github-practice` project) from each of the appropriate files to the new files in `git-and-github-practice-two`
- Initiate a git repository
- Commit your changes
- Create a new repository *on Github* called `git-and-github-practice-two`, set your remotes, and push your code up to github
> Note: Partner2 should now have the solution from Part 1 locally

**With partner1 driving:**

- get the link to your partner's new GitHub repository - fork and clone it
- open the project and change the `style.css`, so that both the header and testimonial's `background-color` is changed from `#131e27` to `#e95346`
- commit your changes, push to github, and submit a pull request back to partner2


**With partner2 driving:**

- merge the pull request from the GitHub interface

## Additional Resources

- [Git documentation](https://git-scm.com/documentation)
- [Forking on github](https://help.github.com/articles/fork-a-repo/)
- [Syncing a fork](https://help.github.com/articles/syncing-a-fork/)
