---
layout: default
title: An introduction to GitHub Pages
---

# An introduction to GitHub Pages

GitHub Pages is a feature of GitHub that allows you to create and host a website for your project, your portfolio, your blog, or anything else you want to share with the world. GitHub Pages is free, easy to use, and supports custom domains and themes. In this article, we will learn the basics of GitHub Pages and how to get started with your own site.

## What is GitHub Pages?

GitHub Pages is a static site hosting service that takes files from a repository on GitHub and publishes them as a website. You can use any static site generator, such as Jekyll, Hugo, or Eleventy, to create your site, or you can simply write HTML, CSS, and JavaScript files. GitHub Pages also supports Markdown, a lightweight markup language that lets you write formatted text using plain text syntax.

GitHub Pages offers two types of sites: user or organization sites and project sites. A user or organization site is a site that is associated with your GitHub username or organization name. It has a URL like username.github.io or organization.github.io, where username or organization is your GitHub username or organization name. A project site is a site that is associated with a specific repository on GitHub. It has a URL like username.github.io/repository or organization.github.io/repository, where username or organization is your GitHub username or organization name, and repository is the name of the repository.

You can have one user or organization site per GitHub account, and unlimited project sites per repository. You can also use a custom domain name for your GitHub Pages site, such as example.com or blog.example.com, by configuring a CNAME record with your DNS provider.

## How to create a GitHub Pages site?

To create a GitHub Pages site, you need to have a GitHub account and a repository for your site. If you don't have a GitHub account, you can sign up for free at [github.com](https://docs.github.com/pages/quickstart). If you don't have a repository for your site, you can create one by following the steps in "[Creating a repository for your site](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)".

Once you have a repository for your site, you need to decide which publishing source you want to use. A publishing source is the branch and folder where your site files are stored in your repository. GitHub Pages will look for an index.html, index.md, or README.md file as the entry file for your site. You can choose one of the following publishing sources:

- The main branch
- The main branch and the /docs folder
- The gh-pages branch

You can configure your publishing source in the settings of your repository, under the "Pages" section. For more information, see "[Configuring a publishing source for your GitHub Pages site](https://docs.github.com/en/pages)".

After you configure your publishing source, you can add, edit, or delete your site files using any of the following methods:

- Using the web interface of GitHub
- Using the GitHub Desktop app
- Using the command line and Git

You can also use a theme for your site, which is a pre-made design and layout that you can apply to your site. GitHub Pages supports several themes that you can choose from the settings of your repository, under the "Pages" section. For more information, see "[Adding a theme to your GitHub Pages site with the theme chooser](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Tools_and_setup/Using_Github_pages)".

When you make changes to your site files, GitHub Pages will automatically build and deploy your site within a few minutes. You can then visit your site at the URL of your publishing source. For example, if your publishing source is the main branch of a user or organization site, your site URL will be username.github.io or organization.github.io.

## Next steps

Congratulations, you have created your first GitHub Pages site! You can now explore the various features and options that GitHub Pages offers, such as:

- Adding content to your site using Markdown, HTML, CSS, and JavaScript
- Using a static site generator to create your site
- Customizing your site's appearance and functionality with themes, plugins, and custom code
- Securing your site with HTTPS and enforcing HTTPS redirects
- Using submodules to include other repositories in your site
- Using custom workflows with GitHub Actions to build and deploy your site
- Deleting or unpublishing your site

For more information and resources, you can visit the [GitHub Pages documentation](https://docs.github.com/en/pages) or the [GitHub Pages Help Community](https://github.com/orgs/community/discussions/categories/pages).
