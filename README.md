<h1 align="center">Bot Framework</h1>

<p align="center">
<img src="https://img.shields.io/tokei/lines/github/JonZavialov/bot-framework?color=9cf" alt="Total Lines" />
<img src="https://img.shields.io/github/repo-size/JonZavialov/bot-framework?color=9cf&logo=GitHub" alt="GitHub Repo Size" />
<img src="https://img.shields.io/github/commit-activity/m/JonZavialov/bot-framework?color=9cf&logo=GitHub" alt="Commit Activity" />
</p>

<p align="center">A general framework for Discord bots using Node</p>

## ⚙️ Configuration

1. Create a discord bot
2. Add a file to the root folder named `config.json`
3. In the file, add the following. Your bot's token goes in the `token` field, and your bot's prefix goes in the `prefix` field.
```json
{
    "token": "your_token_here",
    "prefix": "your_prefix_here"
}
```
4. Add commmands in the commands directory, the format is the following:
```js
    function commandName(msg, args){
        //do command function
    }

    module.exports = commandName
```
Note: `msg` is a discord Message object, and args are passed as an array. If your command doesn't have arguements, don't include an `args` parameter.


## 👨‍💻 Developlment

This project has been completed by Jonathan.
