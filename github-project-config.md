# Github project configuration

## Short overview

During this step, we will create and store out bot's source code \(program!\) in the github. That is needed for several reasons: 

* you can easily access this code any time you need from different computers \(since it's going to be published in the internet\)
* you can track the changes of your code \(git does history saving for you\), so you don't need to be afraid to make any changes to your code
* you can share your code with other developers so they will be able to help you to identify a problem remotely, if needed.

## Initialise the project

1. got to github.com and login
2. Click "new" 

![](.gitbook/assets/screenshot-2019-03-22-at-11.53.47.png)

3. Choose the repository name, it doesn't really matter but would be better if you can use something self-describing, like "my-first-slack-bot"

4. Click "initialise repository with a README". It is always a good idea to have a README in your project, with a short explanation what project does and how to use it

5. Click "Add .gitignore" and type "Node" in a field which will appear. This step is needed to not add any non-necessary files, which NodeJS generates, to git.

You should see something similar to this screenshot:

![](.gitbook/assets/screenshot-2019-03-22-at-11.58.32.png)

If all set, click "Create repository"

## Clone github repository

1. Open command line
2. Switch to github.com, after clicking "Create repository", you should see something like this:

![](.gitbook/assets/screenshot-2019-03-22-at-15.53.46.png)

3. Click on "Clone or download" green button

4. Copy url starting with "git@..." by clicking on grey button from the field's right

5. Switch back to command line and enter:

```text
git clone git@github.com:coingaming/slack-bot-workshop.git
```

6. Replace git@... with your own url, which you just have copied on the step 4, and press enter

7. In command line, run 

```text
cd my-first-slack-bot
```

8. Hit enter

9. Leave command line opened, we will need it on "Time to code!" step

