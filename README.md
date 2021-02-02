# Public Wiki

This is a test of a public wiki-style site.  The site consists of Markdown documents that are rendered as HTML through the lightweight [MDwiki](http://dynalon.github.io/mdwiki/#!index.md) project.  The project is no longer maintained, but I like the idea: simply add ".md" files (and other media) and the main page will load these and transform them into HTML on the fly.  The only thing that might make this cooler would be an option to edit the markdown files in the browser and save them, but this would make too many assumptions about where the wiki was running.  For now, we will just edit the markdown files locally, commit to GitLab/GitHub, and try to automate the deployment of the site to Google Cloud Storage.  In the future we might use one of those fancy new static site generators, but this should be a quick way to get some content going.

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
