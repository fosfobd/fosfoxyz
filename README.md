# fosfo.xyz
A space to talk about our favorite videogames, trending ones, upcoming releases, and anything we might be playing in our spare time.

## Installation
This site uses jekyll static content generation and runs on github pages. Ruby needs to be installed, and using Bundler is recommended.

### OSX
1. Install `homebrew`, `chruby` and `ruby-install`, and a stable ruby version:
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew install chruby ruby-install xz
ruby-install ruby 3.1.3
```
2. Install `jekyll`:
```
gem install jekyll bundler
```

## Running
Use specific jekyll version according to gemfile:
```
bundle exec jekyll serve --livereload
```

## Notes

