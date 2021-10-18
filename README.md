# Custom Ghost Theme (Example)

This theme has been created by using [Casper](https://github.com/TryGhost/Casper) as a starting point but removing much of the original theme's code.
# First time using a Ghost theme?

Ghost uses a simple templating language called [Handlebars](http://handlebarsjs.com/) for its themes.

The official [theme API documentation](https://ghost.org/docs/themes/) explains every possible Handlebars helper and template.

Also, you read my explanation [on my blog](https://christhefreelancer.com/ghost-theme-development-guide/)

**The main files are:**

- `default.hbs` - The parent template file, which includes your global header/footer
- `index.hbs` - The main template to generate a list of posts, usually the home page
- `post.hbs` - The template used to render individual posts
- `page.hbs` - Used for individual pages
- `tag.hbs` - Used for tag archives, eg. "all posts tagged with `news`"
- `author.hbs` - Used for author archives, eg. "all posts written by Jamie"

One neat trick is that you can also create custom one-off templates by adding the slug of a page to a template file. For example:

- `tag-example-tag.hbs` - Custom template for `/tag/example-tag/` archive
- `author-christopher.hbs` - Custom template for `/author/christopher/` archive
