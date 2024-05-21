# Odin Recipes 🍗

## Table of Contents

- [Introduction](#introduction)
- [Objective](#objective)
- [Key Notes](#key-notes)
- [Reflection](#reflection)

## Introduction {#introduction}

We've learned a few basic HTML tags and elements, now it's time to build something. This should be a fun, ugly, project. "Make a recipe page containing 3 of you favorite recipes!" or "Make an HTML document that can link to other HTML documents that contain images, lists, etc." Honestly, I know a couple CSS styling techniques from the Myspace days but I don't think the point is to make it look good. It's to practice implementing basic HTML tags: `<h1>, <h2>, <img>, <ol>, <ul>, etc`.

## Objective 🎯 {#objective}

Simply put, this should test to see if I can build an HTML page that can:

    1. Be viewed in a browser
    2. Display text as an <h1> heading
    3. Display links that can also redirect to other pages in the directory as <a> elements

Those pages other pages will be structured similarly and should be:

    1. Able to be viewed in a browser
    2. Display the name of the recipe in an <h1> heading
    3. Display an image of the recipe stored somewhere in the project directory
    4. Show a list of ingredients as an unordered list <ul>
    5. Show steps to make this recipe as an ordered list <ol>
    6. Link back to the homepage

## Key Notes ✏️ {#key-notes}

I still don't fully understand the `rel` attribute or what is important about it but it doesn't seem to matter so far. I'll add the attribute to links in the project just because it seems like best practice. Let's just default to the example: `rel="noopener noreferer"`. Also, unclear as to when I should open a link in a new tab `target="_blank"`. I assume it's dealers choice but their is probably a rule of thumb to follow.

I went an alternative route about getting this on GitHub. I initialized the repo locally on branch main `git init -b main` and then pushed that to GitHub:

`git remote add origin`
`git push origin main`

Took a little Googling but it was simple enough. In my research, I came across the [GitHub CLI](https://cli.github.com/). I wonder if its worth spending time using this tool. According to Reddit, a lot of people are just using the desktop GUI.

## Reflection 🤔 {#reflection}

This was pretty straight forward. I'm using Visual Studio Code and there are a lot of shortcuts and auto-completes which saved me a ton of typing. Where I feel like I spent a lot of time typing was the terminal. I am making it a point that if I want to access my repos, I have to get there from the terminal. Also, I spent a lot of time staging and committing in GIT. I spent a little time looking at other people's commit messages on [theodinproject repo](https://github.com/TheOdinProject/theodinproject) and it seems like it runs gamut. Some are far more verbose than others.

I also took an interest in markdown. I know that README.md files are documentation, but mine are going to be a journal for these projects. I wouldn't suggest anyone copying this repo. :joy:

It's pretty cool that you can deploy a simple webpage on Github. Deployed mine [here](https://alvarez0daniel.github.io/odin-recipes/).
