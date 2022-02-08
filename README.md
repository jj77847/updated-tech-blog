## updated-tech-blog

## Description

I built a CMS-style blog site similar to a Wordpress site, where developers can publish their blog posts and comment on other developers’ posts also deploy it to Heroku. The app follows the MVC paradigm in its architectural structure, using Handlebars.js as the templating language, Sequelize as the ORM, and the express-session npm package for authentication.

# Links

- Deployed Heroku link: https://updated-tech-blog.herokuapp.com/

- Github Repo link: https://github.com/jj77847/updated-tech-blog

## User Story

```
AS A developer who writes about tech
I WANT a CMS-style blog site
SO THAT I can publish articles, blog posts, and my thoughts and opinions
```

## Installation

The steps and packages required to install this project are:

```
- clone repository
- npm init -y
- npm run start
```

## Tools/Technologies

- Express Server
- Express Session (User Authentication)
- Sequelize (ORM)
- Handlebars
- MySQL DB
- Heroku (deployment)

## Pages

- Homepage: All blogs from DB | Navbar with links Home, Login, Sign Up
  - View Route `/`
