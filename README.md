# GitHub-Contribution-Bot

Manipulate your GitHub contribution Graph

# GitHub Contribution Bot

[![](https://img.shields.io/github/license/utsanjan/Github-Contribution-Bot?logoColor=red&style=plastic)](https://github.com/utsanjan/Github-Contribution-Bot/blob/main/LICENSE)‎ ‎
[![](https://img.shields.io/github/languages/count/utsanjan/Github-Contribution-Bot?style=plastic)](https://github.com/utsanjan/Github-Contribution-Bot/search?l=shell)‎ ‎
[![](https://img.shields.io/github/languages/top/utsanjan/Github-Contribution-Bot?color=light%20green&style=plastic)](https://github.com/utsanjan/Github-Contribution-Bot)‎ ‎ `<br>`

**Does your GitHub Graph looks like a noob with a few number of Commits and Push? Do you want to have your contribution graph with lots of commit like pro, then this project is at your rescue. Manipulate your GitHub Contribution graph just like above.**`<br>`

## 📝 Introduction

The project uses [Moment](https://www.npmjs.com/package/moment), a JavaScript date library for parsing, validating, manipulating, and formatting dates. It allows you to make a commit on past date done by subtracting the years from given date and make commits over a period of regular days. Also you can do alot with this code.

## 🛠️ Installation

Clone and fork the repository to make the changes in your local system.

```git-bash
git clone https://github.com/Mohit-005/GitHub-Contribution-Bot
cd Github-Contribution-Bot
```

Now this command creates a directory named node_modules and installs all the required packages in it.

```javascript
npm install
```

Finally, run the project to see what the moment package does.

```javascript
node index.js
```

Voilà!!
You can see the commit date in terminal.

## 💻 Commits

```javascript
subtract(year, "y");
```

year here represents the year to start the commits. Greater the value of year, more dense the graph along main axis. Example - subtract(2,'y')

```javascript
add(days, "d");
```

Difference of commits between timestamps. Less the value of days, more dense the contributon graph will be. Example - add(4,'d')