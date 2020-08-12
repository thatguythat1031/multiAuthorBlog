# Multi-Author Blog

A for fun blog focusing on Philosophy and politics. The repo is a fork of the [Clean Blog](https://startbootstrap.com/themes/clean-blog/) free bootstrap theme. All credit for the original code goes to the author of the original template- more info can be found at the link above. All writing and articles are our own. The site can be visited by opening a new browser tab and searching: `https://www.lunchroomprophecies.com`. I cannot currently link to the site on github as we do not yet have an SSL certificate set up. Site is hosted on Heroku.

## Current Authors

1. Seth Peters (myself)
2. 

## Local setup

This website requires that nodeJS and NPM be installed on the host. Then it can be installed by cloning the repo: ''

After installation, run `npm install` and then run `npm startLocal` which will open up a preview of the template in your default browser, watch for changes to core template files, and live reload the browser when changes are saved.

### For the authors- how to add a new article

1. Branch off of the master branch and name your branch something like "feature/{authorName}/addArticle{articleName}"
1. Create a new .html file in the articles folder in the project, under the correct category (ex. `/articles/bookReviews/<yourArtile>.html`)
2. Copy all of the HTML from one of the previously-existing .html files in the folder into your file to use as a template.
3. Add a link to your new .html file at the top of the `directory.html` file for your directory (ex. `/articles/bookReviews/directory.html`)
4. Add a link to your new .html file at the top of the `articles/masterDir.html` file.
5. Change the main content section of the `index.html` file so that your new file is linked with its description as the top article, move the previous first/top article down to the second, and so on. The previous last article should no longer be on the `index.html` page at all after this edit.
4. Add any images you want to use in your article page to the `/img` folder.
5. Edit the Page Header HTML: Choose an image from the `/img` folder to use as your header image.
6. Edit the Page Header HTML with your background image, name (author), post-heading (title), subheading, and meta (date posted).
7. Paste your article into the post content section of your .html file, with paragraph, header, and image tags where appropriate. If you need help, reference the `/articles/samplePost.html` file.
8. Once your file is finished, and the necessary edits have been made to all other files, run `npm run startLocal`. This will start the website locally on your computer.
9. Verify that your new page looks good, that links everywhere work, and that you haven't broken anything.
10. Push your changes to your github branch and make a new PR to master.
11. Once your PR is approved, the new version of the site will be automatically deployed to Heroku, and can be viewed by opening a new browser tab and searching for `https://www.lunchroomprophecies.com`.
