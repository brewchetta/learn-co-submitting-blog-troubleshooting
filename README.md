# Troubleshooting Guide: Submitting Your Blog Through Learn-Co

If you're having trouble submitting your blog through the learn-co website, you aren't alone! In order to publish a blog, learn-co hosts its blogs through [github pages](https://pages.github.com/). More often than not, it's an issue with creating the repository that causes publishing to fail.

### Markdown:

Make sure your blog doesn't use any illegal characters or conventions. Blogs utilize [markdown](https://www.markdownguide.org/cheat-sheet/) and if it isn't properly formatted for markdown, it may break the publishing process.

### Github Pages:

See if you already have github pages set up. Search for one of your repositories called `username.github.io` where `username` is (you guessed it) your github username!

### If You Have A Repo:

You'll need to delete the old repo. On the repo page for `github.io`, click on settings and scroll all the way down to the bottom where you'll see a danger zone that includes an option to delete this repo. Follow those steps and then head back to learn.co and attempt to publish again. If your attempt to publish fails again, follow the steps below as though you didn't have a repo.

*If you were using github pages for anything other than your blog, that work will be deleted as well. You may be better off maintaining a blog from a different source like medium.com.*

### If You Don't Have A Repo

A repo for pages should have automatically been created when you publish your blog on learn.co but sometimes it doesn't work as intended. Since something went wrong, you'll need to create it manually. Create a new repository by clicking the "+" in the upper right corner of the page. You want to name it `username.github.io` where `username` is your github username. Once that's been done, attempt to publish your blog again.

### Why Doesn't My Blog Have Styling?

The styling template for your blog should have gotten created when it was published, but sometimes it doesn't. The easiest way to get around this is to delete your pages repo using the steps from _If You Have A Repo_ and attempt to publish from learn.co again. If you had to manually create your pages repo, you may have to reach out to an instructor for the various files to add styling to your pages.
