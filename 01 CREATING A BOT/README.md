## INSTALLATION

Create you account on [Replit](https://replit.com/~) and create node.js project.([click me to create project](https://replit.com/new/nodejs))<br />
Node.js 16.6.0 or newer is required for using discord.js v13 so we will upgrade our node version to 16.6.0 or above.

**STEP : 1**<br />
Delete `Package.json` and `Package-lock.json` from your project and type this command in replit shell.
```
npm init -y && npm i --save-dev node@17.0.1 && npm config set prefix=$(pwd)/node_modules/node && export PATH=$(pwd)/node_modules/node/bin:$PATH
```
**STEP : 2**<br />
Now we have execute npm start so we will create a file `.replit` and type this code in it.
```
run= "npm start"
```
**STEP : 3**<br />
Now we have to run our main file so we will add this code in script section of `Package.json`.
```
"start": "node index.js"
```

## VIDEO

If you need [video tutorial](https://youtu.be/PL4DBcyW96k) then this is the link to the [video](https://youtu.be/PL4DBcyW96k)!
<div align="center">
  <p>
    <a href="https://youtu.be/PL4DBcyW96k"><img src="https://media.discordapp.net/attachments/966943970145996800/966975451341918298/1650615303344.jpg" alt="Episode 1" /></a>
  </p>
</div>

## SUPPORT

If you don't understand something from my tutorial, you are getting errors, or you need help related to tutorial, please don't hesitate to join our official [support server](https://discord.gg/MRbJCmv4YJ).
