PDXGo-Hugo-Website
==================

[Hugo](http://hugo.spf13.com/) Static website for the PDXGo group.  To host event descriptions and link to media.

## Setup
To get started with development, get [Hugo Installed](http://hugo.spf13.com/overview/installing) to generate the html pages.  Hugo has great rebuilding functionality, editing content automatically updates the browser!

## Content
/content contains the markdown pages which will get generated into static html.  
Currently the only pages I've created is 'post', which are just event listings for August.  

For some reason 'Post' should show up on the sidebar to show them but that's borked up for some reason.*Issue*

## Theme
Currently I have modified the [hyde theme](https://github.com/spf13/hyde) and forked it to contain latest changes. If people like the theme, gutting the submodule and just adding the whole theme to the repo is probably the best solution.  

## Running/Development

Once hugo is installed in your GOPATH, simply run the following command in the repository:
> hugo server --theme=hyde --buildDrafts --watch

This will build the static site and serve it on port 1313.  
[Using hugo command](http://hugo.spf13.com/overview/usage)
