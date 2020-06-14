# ryersonbikes.com

[![Netlify Status](https://api.netlify.com/api/v1/badges/3d8517cb-7d47-4cbe-b1f2-0351fd24d287/deploy-status)](https://app.netlify.com/sites/ryersonbikes/deploys)

The official repo for the ryersonbikes.com website. Written in Markdown and JavaScript, the ryersonbikes repo provides the infrastructure for the creation of the website onto the web.

## Installation

1. Make sure you have the **enhanced** version of hugo, from https://gohugo.io/getting-started/installing/

2. Add the repository to your local computer using git.

> git clone https://github.com/luiszugasti/ryersonbikes.com

## New posts

1. To make edits, add a new page (example from the root folder, to make a new activity):

> hugo new activities/volunteering.md

2. Make sure to remove the 'draft' indicator, add all your new edits, and add the change.

> git add activities/volunteering.md

3. Commit it to your local staging area:

> git commit -m "meaningful commit message here"

4. Push it back to the github repo!

> git push origin master

5. Watch the Netflify status bar on the top, to make sure that your changes were published!

## New image assets

All the images to be used are located in the static -> img folder. To add files here, simply drag and drop from your explorer to the folder. Please limit the size of the images to at most 500 Kb to keep the site running light.

## Development Assets

There's quite a few entry points to editing the overall structure of the site. This section aims to show how to access these points and what to do with them in an FAQ-like format.

All entries assume a starting point at the root of the project.

### How to edit the sections

> config.toml > [menu] > [menu.main]

### How to
