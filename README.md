# DS Web App Project

This repository is for the web app prototype, which I will gradually
build while studying for _IBM Full-Stack JavaScript Developer
Professional Certificate from [Coursera](https://www.coursera.org/)_.

## Requirements

### Tech Stacks

-   Initially, this project will use only the technologies covered in
    the certificate course:

    -   HTML
    -   CSS
    -   JavaScript
    -   [ReactJS](https://react.dev/)
    -   [NodeJS](https://nodejs.org/)
    -   [ExpressJS](https://expressjs.com/)
    -   [MongoDB](https://www.mongodb.com/)

-   Later, however, certain components may be changed:

    -   ReactJS will be removed to ensure a fully _vanilla_ frontend.
    -   [Bulma](https://bulma.io/) will be used for styling.
    -   MongoDB will be replaced with [SQLite](https://sqlite.org/) or
        [PostgreSQL](https://www.postgresql.org/)

### Structure

-   The basic structure will be similar to a typical blogging
    platform.

-   The final product will be like a simple CMS.

### User Management

-   There will be multiple users.

-   Users will be added from the backend. (There will be no frontend
    UI for user registration.)

-   All the user information will be stored in the database.

### Writing & Reading

-   All the posts will be stored in the database table under each
    username.

-   When reading a post, the contents will be dynamically fetched from
    the database to be displayed on a web page. (The page will be a
    fixed HTML template and only the contents will be dynamically
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
    each username & post. (Ex: `/images/username/postname/01.jpg`)

-   When a post is fetched from the database, its corresponding images
    will also be retrieved from the directory.

## Notes

-   This is just the initial concept and will be modified as I
    continue studying.

-   It will be a long journey!
