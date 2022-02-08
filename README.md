## updated-tech-blog

# Description

I built a CMS-style blog site similar to a Wordpress site, where developers can publish their blog posts and comment on other developers’ posts also deploy it to Heroku. The app follows the MVC paradigm in its architectural structure, using Handlebars.js as the templating language, Sequelize as the ORM, and the express-session npm package for authentication.

# Links

- Deployed Heroku link: https://updated-tech-blog.herokuapp.com/

- Github Repo link: https://github.com/jj77847/updated-tech-blog

# User Story

```
AS A developer who writes about tech
I WANT a CMS-style blog site
SO THAT I can publish articles, blog posts, and my thoughts and opinions
```

# Installation

The steps and packages required to install this project are:

```
- clone repository
- npm init -y
- npm run start
```

# Tools/Technologies

- Express Server
- Express Session (User Authentication)
- Sequelize (ORM)
- Handlebars
- MySQL DB
- Heroku (deployment)

# Pages

- Homepage: All blogs from DB | Navbar with links Home, Login, Sign Up
  - View Route `/`

# User Journeys

- AS a user when I navigate to the homepage THEN I should see all blogs from DB
- AS a logged out user I should see the nav bar with 3 link Home, Login and Sign Up
- AS a user when I click on a tech blog THEN I should navigate to that individual blog page
- AS a user when I click on Login THEN I should navigate to the login page
- AS a user when I click on Sign Up THEN I should navigate to the sign-up page
- AS a user when I click on Home THEN I should navigate to the home page
- AS a user when I navigate to the homepage THEN my tech blog card should render blog title, content, and date created, created by user,
- AS a user when I navigate to the sign up page then I should see a form with a username input, password input, confirm password input and a submit button (handle client sides form errors)
- AS a user when I navigate to the login page then I should see a form with a username input, password input, and a submit button (handle client sides form errors)
