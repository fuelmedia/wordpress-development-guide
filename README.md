# Documentation

## Inline Documentation

All functions, classes, and methods should be documented inline using [phpDoc](http://phpdoc.org/) or just basic comment. Inline documentation should be used to describe the purpose of the function, class, or method, as well as the parameters it accepts and the value it returns.

# Wordpress Coding Standards

## PHP

Follow the [Official WordPress PHP Coding Standards](https://make.wordpress.org/core/handbook/best-practices/coding-standards/php/).

## JavaScript

Follow the [Official WordPress JavaScript Coding Standards](https://make.wordpress.org/core/handbook/best-practices/coding-standards/javascript/).

## HTML

Follow the [Official WordPress HTML Coding Standards](https://make.wordpress.org/core/handbook/best-practices/coding-standards/html/).

## CSS

Follow the [Official WordPress CSS Coding Standards](https://make.wordpress.org/core/handbook/best-practices/coding-standards/css/).

# Plugin / Library Usage

Always use the latest version of the plugin or library. Never use not maintained plugins or libraries. Ensure that the plugin or library is well documented and has a good community support.

# Version Control

## Git

Always use Git for version control. Use understandable commit messages. Always follow [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) for commit messages. We should understand what the commit is doing just by reading the commit message.

## Branches

Never directly commit to the `main` branch. Always create a new branch for each feature or bug fix. Use the following naming convention for branches:

- `feature/` for new features
- `bugfix/` for bug fixes
- `hotfix/` for critical bug fixes
- `release/` for release branches
- `chore/` for chores
- `docs/` for documentation

# Wordpress Core Files

Never edit the core files of Wordpress. If you need to change the core files, create a plugin or a library and use it. Also it's considered a good practice to create a child theme and use it instead of editing the core files of the theme.

# Wordpress Plugins and Libraries Core Files

Never edit the core files of Wordpress plugins and libraries. If you need to change the core files, create a plugin or a library and use it. When you need to change the core files of a plugin or a library, create a fork of the plugin or the library and use it.

# General Software Development Guideline

## Naming Conventions

- Always use 'meaningful names' for variables, functions, classes, etc.
- Always use 'camelCase' for naming JavaScript variables, functions, classes, etc.
- Always use 'snake_case' for naming PHP variables, functions, classes, etc.

## Code Formatting

- Use editorconfig plugin for non-JS/TS files.
- Use prettier plugin for format TS/Vue files.

## Code Style

- Follow 'SOLID' principles as much as possible. (https://en.wikipedia.org/wiki/SOLID)
- Don't use 'magic numbers' or 'magic strings'. Use constants/enums instead.

## Code Structure

- Avoid writing raw SQL queries. Use ORM or query builder instead.

## Library & Plugin Usage

- If there are battle-tested libraries that can do the job, use them instead of writing your own code.
- If you're using a new library, make sure to read the documentation and understand how it works.
- Don't use libraries that are not maintained or not used by the community anymore.

## Always Consult With Your Teammates

- Don't change the structure of the project without consulting with the team.
- Don't change configuration files without consulting with the team. (e.g. .env, .editorconfig, .prettierrc, etc.)
