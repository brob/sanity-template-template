# Readme describing the full template

This README should talk about what this Starter does. It will be pulled into the page at [sanity.io/create](https://sanity.io/create), but also should mention how to contribute to the Starter, as well as use it.

## Building your first template?

We have a [guide for building a Starter](https://www.sanity.io/docs/creating-a-1-click-sanity-starter-project) and [documentation](https://www.sanity.io/docs/starter-templates).

* `/assets/` is where your preview images will go
* `/data/` is where a Sanity dataset export will go if you want to give default data
* `/template/` is where your site and studio will go

To work locally:

```bash
# Install the CLI
npm install -g sanity-template

# From project root, run this command to set a watcher to rebuild files to a build directory with proper template values
sanity-template watch --template-values=template-values-development.json
```

You'll want to run the site and the Studio from within the build directories.
