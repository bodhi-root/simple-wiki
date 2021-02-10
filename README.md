# Simple Wiki

https://bodhi-root.github.io/simple-wiki/

This is a test of a public wiki-style site.  The site consists of Markdown documents that are rendered as HTML through the lightweight [MDwiki](http://dynalon.github.io/mdwiki/#!index.md) project.  The project is no longer maintained, but I like the idea: simply add ".md" files (and other media) and the main page will load these and transform them into HTML on the fly.  The only thing that might make this cooler would be an option to edit the markdown files in the browser and save them, but this would make too many assumptions about where the wiki was running.  For now, we will just edit the markdown files locally, commit to GitHub, and create a GitHub Pages website.  In the future we might use one of those fancy new static site generators, but this should be a quick way to get some content going.

## Local Test Server

A simple node express server was created to serve static content
from the 'www' folder for testing.  This was done following these
instructions:

* https://blog.kevinchisholm.com/javascript/node-js/express-static-web-server-in-five-minutes/

You can start the server by running:

```
npm start
```

This allows you to view your site before committing it to git or pushing it to production.

## New Wiki

I ended up not using this template for my wiki and instead opted to go with the Gatsby template below:

https://www.gatsbyjs.com/starters/hasura/gatsby-gitbook-starter/

The resulting project is available at:

https://github.com/bodhi-root/public-wiki
