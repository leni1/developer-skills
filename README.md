# About

This repository tracks my development of Developer skills in general. The front-end developer skill track is in `front-end-developer.md` and `back-end-developer.md` contains the back-end skill track as well as DevOps as per what I've seen on job listings. The back-end section is Python-oriented as well as containing DevOps-specific content for the time being. Will add more to this as time goes on. The checklist style is borrowed from jwsham's coding university repo [here](https://github.com/jwasham/coding-interview-university) and the list as well as the order of things to learn is mostly derived from Kamran's developer roadmap [here](https://github.com/kamranahmedse/developer-roadmap)

## How to use it

Essentially, clone the repository, create a new branch called `progress` or any name that is along those lines, and then check the items you've learned by putting an `x` in the brackets like so `[x]`. The commands are as follows:

1. Fork the repo on GitHub and clone your fork, replacing `yourusername` with your GitHub username

    `git clone https://github.com/yourusername/developer-skills.git`

2. Checkout a new branch, add this repo as a remote and get any updates.

    ``` git checkout -b progress

        git remote add leni1 https://github.com/leni1/developer-skills

        git fetch all
     ```

 3. Mark all boxes with `x` once you've learned something. (As an addition, you could link to the project you've built to demonstrate your skills. Documentation counts as a project too :))

    ```
    git add .

    git commit -m "Marked x"

    git rebase leni1/master

    git push --force
    ```

## How to contribute

I'd like to add good resources to get started with the various technologies on the lists contained in the various `*.md` files. Will add them as time goes on, but feel free to open an issue suggesting a resource or a pull request and I'll be happy to review and merge.
