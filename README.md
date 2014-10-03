ecsig.com
=========

This site uses [Jekyll][jekyll] to build a static set of pages. Using it to
add new pages and posts is fairly straightforward, but what follows is
a quick start.

##Workflow
A general overview:

- If you've got push rights on the repo, clone it and create a new
  branch for your work. If not, fork it and do the same.
- Create/change any content as you see fit
- Push to your branch on Github, and submit a pull request
- Someone with push rights on the repo reviews the request, starts
  a conversation about changes if necessary, and eventually pulls
- A Github web hook will take care of getting the changes reflected on the website

If you have questions about any of these steps, don't be afraid to ask!

###Create a new post
There are two steps:

- Create a new file in `_posts` with the format `<date>-<post title>.markdown`
- Write the post

After that's done, you can generate your changes and serve them locally to
check them out: `jekyll serve`. This starts a server on port 4000 by default.
You can use `jekyll serve -w` to continually watch for changes as you code.

###Create a new page
The steps for creating a new page are similar to a new post. Create a new folder
to match what you want to see, e.g. `/about/` for the URL `ecsig.com/about/`, and
create an `index.html` file in that folder. Look at existing pages for examples.

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll.

##Source
Source for the site can be found [here][ecsig-gh].

[ecsig-gh]: https://github.com/ECSIG/ecsig.com
[jekyll]:    http://jekyllrb.com

