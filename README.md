# fosfo.xyz

## Installation
This site uses jekyll static content generation and runs on github pages. Ruby needs to be installed, and using bundler is recommended.

### OSX
1. install homebrew, chruby and ruby install, and a stable ruby version
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew install chruby ruby-install xz
ruby-install ruby 3.1.3
```
2. install jekyll
```
gem install jekyll bundler
```

## Running
use specific jekyll version according to gemfile
```
bundle exec jekyll serve --livereload
```

## Notes

