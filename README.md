# Welcome to Drow!

Welcome to your new Drow site! Drow is a small, simple, and opinionated static
site generator. This means it should be extremely easy to use, but may not
offer or plan to offer all the features you'd get from other generators.

Drow works via the `drow` command line tool. If you're seeing this, you've
already generated your new Drow site via the `drow setup` command.

The other commands are:

- `drow build`: This builds your Drow site once, putting the results into
  the build directory.
- `drow deploy`: This deploys your Drow site to GitHub Pages based on the
  configuration in your `Drow.toml` file.
- `drow page`: This creates a new Drow page, contained in your `pages/`
  folder.
- `drow post`: This crates a new Drow post, contained in your `posts/`
  folder.
- `drow admin`: This runs both a local live-reloading version of your Drow
  site, and an admin page for editing your configuration, modifying or
  adding posts, and modifying or adding pages.

All configuration for your Drow site is contained in your `Drow.toml` file.
Only a few variables are treated specially, namely `pages_repo` (which should
be the location of the GitHub Pages repository you plan to deploy to) and
`pages_user` (the name of the user for that GitHub Pages repo). All other
variables are simply variables to be passed on to your site templates.

