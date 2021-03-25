# My Personal Website

An implementation of my personal website which is a fork of [academicpages](https://github.com/academicpages/academicpages.github.io)
which is released under the MIT License (See LICENSE.md).

# To run locally

1. Make sure you have ruby-dev, bundler, and nodejs installed: `sudo apt install ruby-dev ruby-bundler nodejs`
2. Run `bundle clean` to clean up the directory (no need to run `--force`)
3. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.
4. Run `bundle exec jekyll liveserve` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.
