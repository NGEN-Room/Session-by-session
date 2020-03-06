# Morning Session: Digital Marketing

Will link video once found


# Afternoon Session: Coding - Bringing it together

presentation: https://www.canva.com/design/DAD1RtezvCE/rDnyjsiLmAKgwoIxWEBfUw/view?utm_content=DAD1RtezvCE&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink

## Mindset - Problem Solving
- Techniques and methods
  - Pseudocode
  - The rubber ducky method
  - Reading error messages Console.logging
  - Googling
  - Trying something
  - Asking your peers for help
  - Asking coaches for help
  - Improving your process with reflection




## Different Stages while coding
- Working or Development
  - What you are working on in your local enviroment ( on the PCS that you cloned the REPO )

- Staging your code
  - in your command line you would save your changes by typing `git add .` please remember that the fullstop stands for everything within that repository

- Commiting your code
  - to commit your code means to give your saved code ( which is currently sitting in your git enviroment ) a `message` or a `Name` so that that once you push the chagnes to Github you can revist this commit, read the commit and understand what was changed in this commit. 


## Git Basics
### `Git Clone <url-of-repo>` / Clone
To clone your repo is to bring down your work or code from Github and clone it onto your local machine so you can do more mahi on it.
*git clone https://github.com/NGEN-Room/this-is-an-example.git*


### `Git Branch <name-of-branch>` / Branch
Branching is to take the current branch ( usually master branch ) and create a copy of that so you can work off of it. The benfits of this is you can create an exact copy of the master branch and work on it. This prevents you from making changes to the master branch which might be your finished product.
*`git branch <name>`*


### `Git Push` / Push
To push a repo means that you have done the following process
```
1. added changes of code to the git envrioment
2. commited those changes
3. ready to push code
```
The act of pushing is to push your saved work up to the github repo. IF you are pushing on a branch THAT branch will be pushed up example: if i am in branch: Te-Pihas-new-changes
then that branch will appear online.

### Merge
The act of merging is to grab the branch you created and pushed its new work onto github. And merge or combine those new changes into the master branch. This allows us to work on seperate branches for seperate issues and be able to slowly add them to the master branch and not have bugs (after testing and what not).
An example
```
Im currently building a landing site for NGEN Room. At the moment its a very static page with not alot of content. only paragraphs of words. 
- Im wanting to create a Image image carousel
- I will then branch the master branch and call it image-carousel
- in this brnach i will only work on the coding for the image-carousle (not touching any other coding even if there is spelling mistakes)
- after i complete this branch with a fully functional, tested image carousel
- i will create a pull request ( which is where im requestiong someone to pull in my work into the main branch )
- someone else will go through my code changes and verfiy that it works.
- that same person will also then merge the branch into master branch. 
- COMPLETE
```