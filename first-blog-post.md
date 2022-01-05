---
title: first blog post
content: first blog post
image: ''

---
## Creating a Static Site

**You’ll need to have Node >= 6 on your local development machine**. You can use [nvm](https://github.com/creationix/nvm#installation) (macOS/Linux) or [nvm-windows](https://github.com/coreybutler/nvm-windows#node-version-manager-nvm-for-windows) to easily switch Node versions between different projects.

To create a new app, run:

    npx create-static-site my-site --template [template]

Replace `[template]` with either `hugo` or `jekyll`.

It will create a directory called `my-site` inside the current folder.  
 Inside that directory, it will generate the initial project structure and install the transitive dependencies:

    my-site
    ├── LICENSE
    ├── node_modules
    ├── package.json
    ├── README.md
    ├── static-scripts.config.js
    ├── .browserslistrc
    ├── .eslintrc.yml
    ├── .gitignore
    ├── .postcssrc.js