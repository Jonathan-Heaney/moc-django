# Map of Contemporaries

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)

## Overview

### Screenshot

![](./screenshot.jpg)

### Links

- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Python/Django
- HTML/Django Templating Language
- CSS

### What I learned

- Had some trouble connecting to the RDS database when I first made migrations. It was because the default db_name is 'postgres'
- Ran into a bunch of problems adding data to the new database. Ended up using pgAdmin to connect to Amazon RDS database, and then importing the data with a CSV file
  - Also explored a pg_dump/psql tool, which didn't work in this case because of pg_dump version compatibility issues

### Continued development

### Useful resources
