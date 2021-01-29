# Intro to Jekyll: Tutorial by Heidi
## Why Jekyll?
Jekyll has some great advantages over WordPress. It is especially useful for websites that are information driven and must be static.

**Pros**
1. served up blazing fast
2. source controlled by default
3. highly stable
4. less complex than competitors
5. easy to understand structure since it is just a directory of files served up
6. collection of themes is built in for seamless launch in seconds
7. templates, templates, templates! 
8. can do everything and edit all files directly in GitHub
9. can use online editor with live preview and direct GitHub import/export

**Cons**
1. no GUI
2. less support and documentation
3. fewer themes
4. extensions are run at build time rather at time of request
5. harder for a client to understand
6. slight learning curve
7. public sites only on free GitHub accounts, so not good for private data unless you are a Pro or higher member

## Let's do this!
1. Create a new repository on GitHub
2. Go to 'Settings'
3. Scroll to the _GitHub Pages_ section, select a theme from the dropdown and press **Select Theme**.
4. Edit the index.md file and commit
5. Open your new site in a browser: username.github.io/repo-name

## Add a new flavor
1. Pick a more interesting theme [here](https://jekyllthemes.io/github-pages-themes)
2. Let's try this with _[the Millenial theme](https://github.com/LeNPaul/Millennial)_
3. Fork the theme
4. Change the repository name if you wish
5. check that the site is live _(it should be live immediately)_
6. navigate to [__data/settings.yml](https://github.com/HeidiRichburg/MillennialTemplate/blob/gh-pages/_data/settings.yml)
7. update per the Readme.md
8. navigate to [__posts folder](https://github.com/HeidiRichburg/MillennialTemplate/tree/gh-pages/_posts)

## Add a new [post](https://jekyllrb.com/docs/posts/)
1. click _Add New_
2. name the file with the following format **YYYY-MM-DD-FILE-NAME.md**
3. add content to the file
4. add [_front matter_](https://jekyllrb.com/docs/front-matter/) to the file
4. commit changes
5. check it out live!

## What's next....
1. play around with [_layouts_](https://jekyllrb.com/docs/layouts/)
2. learn [_Liquid_](https://jekyllrb.com/docs/liquid/)
3. add a new [_page_](https://jekyllrb.com/docs/pages/) maybe _'About Me'_
4. learn about [_collections_](https://jekyllrb.com/docs/collections/) and maybe add a collection of your favorite cities
5. learn about [_variables_](https://jekyllrb.com/docs/variables/)
6. examine the [_config.yml page](https://github.com/HeidiRichburg/MillennialTemplate/blob/gh-pages/_config.yml) to see how _[site configuration](https://jekyllrb.com/docs/configuration/)_ is done (title, etc)



## Resources
- [simple tutorial to get up and running with Jekyll on GitHub pages](https://pages.github.com/)
- [long version of tutorial for Jekyll on GitHub pages](https://docs.github.com/en/github/working-with-github-pages/setting-up-a-github-pages-site-with-jekyll)
- [pick a non-standard theme](https://jekyllthemes.io/github-pages-themes)
- [master markdown](https://guides.github.com/features/mastering-markdown/)
- [online editor with real-time preview](https://dillinger.io/)
- [develop with Jekyll locally](https://jekyllrb.com/docs/)
- [configure a custom domain](https://docs.github.com/en/github/working-with-github-pages/configuring-a-custom-domain-for-your-github-pages-site)

## Below is all the stuff that was included with the theme....
## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/HeidiRichburg/studious-potato/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/HeidiRichburg/studious-potato/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
