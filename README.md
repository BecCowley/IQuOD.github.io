## IQuOD.org

This repo contains all the assets for www.iquod.org.

## Git & GitHub Quickstart

Please open issues and pull requests with suggestions and bug reports. If you've never used git or GitHub before, see the instructions below, and please open an issue to ask for help if you're stuck.

### Making Suggestions

If you see any mistakes, have any requests or encounter any problems with iquod.org, please [click here to file an Issue](https://github.com/IQuOD/IQuOD.github.io/issues/new), and describe your suggestion there.

### Making Contributions

Updates to this website are made by pull request. Follow the steps below to set up and start contributing:

#### First-time setup

Do these steps just once, the first time you want to start contributing:

1. Click *Fork* at the top-right corner of this repo. Your fork is your own personal copy that you can change at will.

2. Install git on your computer.

3. In a terminal on your computer, type:

    ```
    git clone <URL to your fork>
    cd IQuOD.github.io/
    git remote add upstream https://github.com/IQuOD/IQuOD.github.io
    ```

    The URL to your fork will look like `https://github.com/<your github username>/IQuOD.github.io`; it's the page GitHub automatically took you to when you created your fork.

#### Every time you want to contribute

Do these steps every time you want to propose a change:

1. In a terminal on your computer, navigate to the `IQuOD.github.io/` directory, and type:

    ```
    git checkout master
    git pull upstream master
    git checkout -b proposal-1234
    ```

    This fetches everything that's new since last time, and creates a new branch called 'proposal-1234' to hold your work. You can change this name to anything you like; usually a one word label of your changes is best.

2. Make whatever changes you like.

3. If you added new files to the repository, for each of them do:

    ```
    git add <your-new-file>
    ```

4. When you're ready to submit, type:

    ```
    git commit -a -m '<commit message>'
    git push origin proposal-1234
    ```

    This sends your changes to your fork on GitHub.

5. Finally, head back to your fork on GitHub, click *New Pull Request*, and make the dropdowns presented look like this:

    ![](images/set-up-pr.png)

    the red box indicates the only thing you should need to change; make it match the branch name you created above.

6. Click *Create Pull Request*, describe the reasoning for your change in the box provided, and click *Create Pull Request* one last time. This submits your changes for peer review - a maintainer of the website will review your changes and either accept them or ask for corrections.

#### If you're stuck

Open an issue, the maintainers are always happy to help.

#### Learn More about version control

The instructions above are the minimum possible number of steps to make a contribution; if you'd like to learn more about what they mean and other things you can do with git, start with [Software Carpentry's introdcutory lesson](https://swcarpentry.github.io/git-novice/). 










