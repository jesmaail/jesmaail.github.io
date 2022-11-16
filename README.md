# Personal page
Making use of both the [Modern Resume Theme by @sproogen](https://github.com/sproogen/modern-resume-theme) and [Gradfolio Theme by @jitinnair1](https://github.com/jitinnair1/gradfolio).

Both have been hacked together to make my own Franken-Theme. 
- Some overriding of page layout done with `-override.html` files in this repo as the source
is being provided as a remote theme.
- Add Navbar so more than just the single page.
- Merge the projects view from both and get info from `.md` files under `/projects`.


## Running Locally
I'm using VSCode devcontainer for the Ruby/Jekyll environment as I'm a Ruby noob.

### Once in the devcontainer:
1. `bundle install` to install Jekyll and required plugins as a prerequisite
1. `bundle exec jekyll serve --incremental --trace` to run the project.
    - `--incremental` reflects changes live
    - `--trace` gives some extra debugging niceness
1. `bundle exec jekyll clean` to clear down generated files

1. And if necessary, [check here for more commands](https://jekyllrb.com/docs/usage/)

## TODO
- Font fix for projects page
- Finalise about me page
- Finalise projects that will be listed
- CV page?
- Publish