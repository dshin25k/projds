# DS Web App Project

This repository is for the web app prototype, which I will gradually
build while studying for _IBM Full-Stack JavaScript Developer
Professional Certificate_ from
_[Coursera](https://www.coursera.org/)_.

## Requirements

### Tech Stacks

-   This project will loosely tied to the certificate courses but some
    technologies may be added, removed, or replaced.

-   The following stacks will be used for this project:

    -   HTML
    -   CSS
    -   JavaScript
    -   [Bulma](https://bulma.io/)
    -   [NodeJS](https://nodejs.org/)
    -   [ExpressJS](https://expressjs.com/)
    -   [PostgreSQL](https://www.postgresql.org/)

### General

-   The basic structure will be similar to a typical blogging
    platform. In the end, the final product will be like a simple CMS.

-   All the operations will be done from the frontend. (Ex: Managing
    users & writing posts)

-   The interface language will be English but the contents may be in
    any language.

### User Management

-   There will be multiple users.

-   All the user information will be stored in the database. Each user
    will take one row of `users` table, which stores user information
    and passwords. (Encryption may be needed.)

-   `admin` user will have a privilege to add, modify, or delete a row
    of `users` table. Each user will be able to modify or delete his
    or her own row of `users` table.

-   There should be a method to ensure unique usernames.

-   When adding a user, a table named after the username will be
    created. When deleting a user, the table under that username will
    be deleted.

-   All the manipulations on `users` table will require username and
    password authentication.

### Writing & Reading Posts

-   All the posts a user writes will be stored in the database. Each
    post will take one row of `posts` table, which stores headers and
    contents.

-   `tags` column will be added to `posts` table to enable searching
    by tags. `tags` column will have array data type so that it can
    store multiple tags per post.

-   When reading a post, the content will be dynamically fetched from
    the database to be displayed on a web page. (The page will be a
    kind of fixed HTML template and only the content will be
    dynamically rendered.)

-   Reading a post will not require authentication.

-   When writing a post, not the whole page but the content will be
    stored in the database so that it can be fetched and rendered when
    needed.

-   Writing a post will require username and password to access the
    database.

### Images

-   When writing a post, images may be inserted.

-   When uploaded, an image will be renamed according to the naming
    convention of `date` followed by `letter suffix` and will be
    stored in a separate directory named after each username. (Ex:
    `/images/dshin/20241115a.jpg`)

-   There should be a method to ensure unique image names.

-   When a post is fetched from the database, its corresponding images
    will also be retrieved from the directory.

### Error Handling

-   Error handling method should be implemented in case of, for
    example, invalid inputs or missing resources.

## Notes

-   This is just the initial concept and will be modified as I
    continue studying.

-   It will be a long journey!
