# FSA-11
Welcome to The Hunt app.This is a gaming app similiar to Treasure Hunt.

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/dabde95955984dd08493709c421c7da6)](https://app.codacy.com/gh/denisecase/web-app-2020-fall?utm_source=github.com&utm_medium=referral&utm_content=denisecase/web-app-2020-fall&utm_campaign=Badge_Grade)
![GitHub repo size](https://img.shields.io/github/repo-size/denisecase/web-app-2020-fall?style=flat)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)

## User stories
- As a player, I want to touch/click the first color to request a valid (treasure) location.
- As a player, I want to hear confirmation that a location has been selected (so I can I can begin searching). 
- As a player, I want to touch/click the second color:  If I am outside the treasure location, I want to hear information to help me find the treasure location (clue? how far away? what direction to walk?)
- As a player, I want to touch/click the second color: If I am inside the treasure location, I want to hear and see confirmation that I have earned this treasure.
- As a player, after confirmation that I have earned a location: I want the game to ask me if I would like to select another location. If I select yes, we reset and begin again. 

## Stack
- Platform: Node (v15.0.1)
- Web Framework: Express
- View engine: EJS
- DB: NoSQL
- ORM: Sequelize 
- Web App Host: Heroku
- Data host: PostgreSQL
- Coding standards: Prettier/ESlint

## CI/CD
-Auto-deploying from our main repo.

## Team Members:

<table>
  <tr>
   <td align="center"><a href="https://github.com/KHARIKA17"><img src="https://avatars.githubusercontent.com/u/60010885?s=460&u=24c5428d5a37b37a3efd752d271740b402177734&v=4" width="100px;" alt=""/><br /><sub><b>Harika Kulkarni</b></sub></a><br /></td>
  
  <td align="center"><a href="https://github.com/GUNDUPOOJA"><img src="https://avatars.githubusercontent.com/u/60015515?s=460&u=a691ffb3d3f0d5b6668835340aa29ca8599d7667&v=4" width="100px;" alt=""/><br /><sub><b>Pooja Gundu</b></sub></a><br /></td>
</tr>
</table>

## Prerequisites

- Node.js (comes with npm)
- Git
- TortoiseGit
- VS Code

## Prerequisites for Publishing

- [Heroku CLI - to publish](https://devcenter.heroku.com/articles/getting-started-with-nodejs#set-up)
- [Heroku login](https://id.heroku.com/login)
- [PostgreSQL local install](https://www.enterprisedb.com/downloads/postgres-postgresql-downloads)
## How to Contribute

### Step 1 - Get fresh code.

1. Pull fresh code. (Fork & clone if this is the first time.)
1. Run npm install
1. Run npm run start
1. Verify everything runs.

### Step 2 - Make your contributions.

As you test your code, format it with Prettier and
lint (clean it up) with ESLint.
See scripts in package.json.

1. Immediately, make your local edits.
1. Verify the app still runs & standarize your code (see commands below)

```PowerShell
npm install
npm run start

npm run prettier
npm run lint
npm run lint-fix
```
## Start Options

Start the app by running npm run start.
Until error handling is complete, a clean shutdown is better.

```PowerShell
npm run start
```

View the application locally at <http://localhost:3025/>

## Sequelize commands

```PowerShell
npx sequelize-cli db:migrate
```

## PostgreSQL commands (for Production Database)

```PowerShell
Start-Process 'C:\Program Files\PostgreSQL\13\scripts\runpsql.bat'
psql "${DATABASE_URL}"

```



