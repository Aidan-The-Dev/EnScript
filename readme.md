# ![EnScript](https://i.ibb.co/CmDrt0V/image.png)
>[demo](#) | [download](https://github.com/TriSn0w/EnScript/raw/main/runCode.js)

## Welcome to EnScript!
This is a Easy-to-use Node.js superset (hence the name, "EnScript") that I made so I can test my Node skils. You can use normal Node with it aswell.

## Installation/Usage
1. Download or copy the runCode.js file
2. Make a `script.en` file that looks something like this:
   ```js
   log 'Hello World!';
   ```
 3. Navigate to your terminal or console and type the following:
   ```js
   npm install n-readlines
   ```
 <br>  
4. Go to your terminal or console and type the following:

```js
node [name-of-RunCode-File] [name-Of-En-File]
```

## The 2 rules of EnScript
To make sure there are no errors in your EnScript project, follow these 2 rules.

1. Always have `;` at the end of a line. This makes interpreting lines easier (somehow :sweat_smile:).
2. (because of a bug) No empty lines. If you wish to put a space between certain parts of code you will need to add a `;` on each empty line


## Syntax / Examples
Here is an example of console logging (the famous "Hello World!" one)
```js
log 'Hello World!';
```

as you can see, instead of `console.log()`, it got reduced to just `log `. This makes things simple, and easy to use.

Also, notice how we added the `;` symbol into there too. Keep that in mind while I keep showing examples.

Here is another example, with functions.
```js
!! This is a comment!
function test() {;
log 'Wowie!';
};
test();      
```

Now, see how there is a lot of the character `;`? It helps the interpreter know it's the end of a line, AND helps in another way too. (I may go into depth soon)

Let's do one more example. A Discord bot!

```js
!! this code has not been tested by us, but it should work!
var Discord = require('discord.js');
var client = new Discord.Client();
client.on('ready', () => {;
  log `Ready as ${client.user.username}`;
});
client.on('message', (message) => {;
  if (message.content == "ping") {;
    message.reply('Pong!')
  };
});
client.login('YOUR_TOKEN_HERE');
```
This code seems a little different than Node.js, but it really isn't that different.

## More of the README is being worked on and is coming soon!
