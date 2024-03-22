# personal-website
Wentao's website! Made with eleventy, starting from eleventy-base-blog.

## Updating content
To add a new publication, just duplicate one of the .md files under content/publications/ and fill in the metadata. Use absolute URLs (e.g., starting at the root "/"), not relative URLs!

If you add a new user-facing tag (e.g., a research topic), then no further action is needed. However, if you add an infrastructural tag that you don't want users to see, make sure to update the filters in content/tags.njk and in eleventy.config.js