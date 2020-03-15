PDX Go Website
==================

[Hugo](http://hugo.spf13.com/) Static website for the PDX Go group - intended to host event descriptions and links to media.

## Setup
To get started with development, get [Hugo Installed](http://hugo.spf13.com/overview/installing) to generate the html pages.  Hugo has great rebuilding functionality, editing content automatically updates the browser!

## Content
/content contains the markdown pages which will get generated into static html. Currently the only files being linked to are in the /meetups folder and the about page. 

## Theme
We're using a fork of the [hugo-goa](https://github.com/arschles/hugo-goa) theme. 

## Running/Development

Once hugo is installed in your GOPATH, simply run the following command in the repository:
> hugo server

This will build the static site and serve it on port 1313.  
