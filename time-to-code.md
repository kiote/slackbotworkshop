# Time to code!

## Short overview

During this step you'll be coding bot's "brain" which will be able to get the command from slack and reply with exchange rate.



## Init npm project

You should have npm installed on your machine after Installation step. So you need to open command line \(it should be still opened since the step Github project configuration\) and type:

```text
npm init
```

this command will start to ask you questions, but it is fine for now just to hit Enter to every question :\) When you reached the point with a question "Is this OK?" type "yes" and hit Enter.

After that, run 

```text
npm install
```

with this two commands we've initialised empty project, which does nothing so far.

## Create main program to run

### Create empty file

From the same command line, run

{% tabs %}
{% tab title="Windows" %}
```text
type nul >> main.js
```
{% endtab %}

{% tab title="MacOS" %}
```text
touch main.js
```
{% endtab %}
{% endtabs %}

This command will create new empty file in the same folder.

Now you need to open your code editor you've installed during the installation step and make it to open the folder, where your fresh npm project is.

For that, open code editor's menu File -&gt; open and find a folder, for me it's here \(Snadbox/slack-bot-workshop\):

![](.gitbook/assets/screenshot-2019-03-22-at-16.13.25.png)

Click on "main.js" file to start editing it in your code editor.

### Add first lines

Type this into your main.js:

```text
const express = require('express');
const app = express();
const bodyParser = require('body-parser');
```

This three lines declares that you are going to use express server and body-parser. These are both programmes written by other developers and we just going to use them.

You can find out more if you google "express nodejs" and "body-parser nodejs"

After that, add these lines to your main.js:

```text
const listener = app.listen(process.env.PORT, function () {
  console.log('Your app is listening on port ' + listener.address().port);
});
```

### Trying to run for the first time!

Now save the file and go back to command line, enter this command there:

```text
node main.js
```

this command suppose to run your program, but instead you should see this error:

```text
module.js:471
    throw err;
    ^

Error: Cannot find module 'express'
    at Function.Module._resolveFilename (module.js:469:15)
    at Function.Module._load (module.js:417:25)
    at Module.require (module.js:497:17)
    at require (internal/module.js:20:19)
    at Object.<anonymous> (/Users/kiote/Sandbox/slack-bot-workshop/main.js:5:17)
    at Module._compile (module.js:570:32)
    at Object.Module._extensions..js (module.js:579:10)
    at Module.load (module.js:487:32)
    at tryModuleLoad (module.js:446:12)
    at Function.Module._load (module.js:438:3)
```

Once again, do not be scared, we going to fix it right away!

This error says, that you declared the module "express", but you don't have it anywhere, so it's impossible to use it. To fix it, you need to install it \(in the command line\):

```text
npm install express -s
```

Try to run your 

