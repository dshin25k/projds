# DS Web App Project

This repository is for the web app prototype, which I will gradually
build while studying for _IBM Full-Stack JavaScript Developer
Professional Certificate_ from
_[Coursera](https://www.coursera.org/)_.

## Requirements

### Tech Stacks

-   This project will loosely follow the certificate program but some
    technologies may be added, removed, or replaced.

-   The following stacks will be used for this project:

    -   HTML
    -   CSS
    -   JavaScript
    -   [Bulma](https://bulma.io/)
    -   [NodeJS](https://nodejs.org/)
    -   [ExpressJS](https://expressjs.com/)
    -   [SQLite](https://sqlite.org/) or
        [PostgreSQL](https://www.postgresql.org/)

### Structure

-   The basic structure will be similar to a typical blogging
    platform.

-   In the end, the final product will be like a simple CMS.

### User Management

-   There will be multiple users.

-   Users will be added from the backend. (There will be no frontend
    UI for user registration.)

-   All the user information will be stored in the database.

### Writing & Reading

-   All the posts will be stored in the database table under each
    username.

-   When reading a post, the content will be dynamically fetched from
    the database to be displayed on a web page. (The page will be a
    fixed HTML template and only the content will be dynamically
    rendered.)

-   Reading a post will not require authentication.

-   Writing a post will be done from the frontend and the content will
    be sent to the database. (There will be a frontend UI for writing
    a post.)

-   Writing a post will require username and password to access the
    database.

### Images

-   When writing a post, images may be inserted.

-   All the images will be stored in separate directories named after
    each username & postname. (Ex: `/images/username/postname/01.jpg`)

-   When a post is fetched from the database, its corresponding images
    will also be retrieved from the directory.

## Notes

-   This is just the initial concept and will be modified as I
    continue studying.

-   It will be a long journey!
