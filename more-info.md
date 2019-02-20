# Installation

## If you're attending a workshop <a id="if-youre-attending-a-workshop"></a>

Follow the instructions here, as best you can. Then at the main workshop, when you get to an installation step in the main tutorial, if you were not able to get that piece installed you can get help from your coach.

## Installation

In this tutorial you will be building a slack bot. In order to do that, as you go through the tutorial you'll be instructed on how to install various software on your computer and set up some online accounts as they are needed. This page gathers all of the installation and sign-up instructions in one place.

Some installation steps might be different for different operating systems \(we cover MacOS and Windows here\). In that case you should see thing like that:

{% tabs %}
{% tab title="MacOS" %}
Instructions applicable only to MacOS
{% endtab %}

{% tab title="Windows" %}
Instructions applicable only to Windows
{% endtab %}
{% endtabs %}

Just click on the tab with your system's name and you should be fine!

## Brief intro to the command line <a id="brief-intro-to-the-command-line"></a>

Many of the steps below reference the "console", "terminal", "command window", or "command line" -- these all mean the same thing: a window on your computer where you can enter commands. When you get to the main tutorial, you'll learn more about the command line. For now, the main thing you need to know is how to open a command window and what it looks like:  


{% tabs %}
{% tab title="MacOS" %}
Go to Applications → Utilities → Terminal.
{% endtab %}

{% tab title="Windows" %}
Depending on your version of Windows and your keyboard, one of the following should open a command window \(you may have to experiment a bit, but you don't have to try all of these suggestions\):

* Go to the Start menu or screen, and enter "Command Prompt" in the search field.
* Go to Start menu → Windows System → Command Prompt.
* Go to Start menu → All Programs → Accessories → Command Prompt.
* Go to the Start screen, hover your mouse in the lower-left corner of the screen, and click the down arrow that appears \(on a touch screen, instead flick up from the bottom of the screen\). The Apps page should open. Click on Command Prompt in the Windows System section.
* Hold the special Windows key on your keyboard and press the "X" key. Choose "Command Prompt" from the pop-up menu.
* Hold the Windows key and press the "R" key to get a "Run" window. Type "cmd" in the box, and click the OK key.

![](.gitbook/assets/windows-plus-r.png)

Later in this tutorial, you will need to have two command windows open at the same time. However, on some versions of Windows, if you already have one command window open and you try to open a second one using the same method, it will instead point you to the command window you already have open. Try it now on your computer and see what happens! If you only get one command window, try one of the other methods in the list above. At least one of them should result in a new command window being opened.
{% endtab %}
{% endtabs %}

## Install NodeJS

Node.js lets developers use JavaScript for [server-side scripting](https://en.wikipedia.org/wiki/Server-side_scripting)—running scripts server-side to produce [dynamic web page](https://en.wikipedia.org/wiki/Dynamic_web_page) content before the page is sent to the user's web browser.

If previous sentence made no sense for you, please start with [this page](https://tutorial.djangogirls.org/en/how_the_internet_works/) :D

{% tabs %}
{% tab title="MacOS" %}
1. Download nodeJS distributive [here](https://nodejs.org/dist/v10.15.1/node-v10.15.1.pkg)
2. Open the command line \(if you have no clue, read [this](https://kiote1.gitbook.io/slackbotworkshop/~/drafts/-LZ9oZ1zsvxmvkO4i5nG/primary/more-info#brief-intro-to-the-command-line) again\)
3. In the command line type:

```text
node -v
```

4. Hit "Enter"

5. You should see this response:

```text
v10.15.1
```

Something like that:

```text
➜ node -v
v10.15.1
```
{% endtab %}

{% tab title="Windows" %}
1. Download nodeJS distributive [here](https://nodejs.org/dist/v10.15.1/node-v10.15.1-x64.msi)
2. Open the command line \(if you have no clue, read [this](https://kiote1.gitbook.io/slackbotworkshop/~/drafts/-LZ9oZ1zsvxmvkO4i5nG/primary/more-info#brief-intro-to-the-command-line) again\)
3. In the command line type:

```text
node -v
```

4. Hit "Enter"

5. You should see this response:

```text
v10.15.1
```
{% endtab %}
{% endtabs %}

## Install a code editor <a id="install-a-code-editor"></a>

There are a lot of different editors and it largely boils down to personal preference. Most programmers use complex but extremely powerful IDEs \(Integrated Development Environments\), such as VSCode. As a beginner, however, that's probably less suitable; our recommendations are equally powerful, but a lot simpler.

### Atom

Atom is popular editor. It's free, open-source and available for Windows, OS X and Linux. 

[Download it here](https://atom.io/)  

