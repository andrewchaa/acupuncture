# Acupuncture

A Jekyll based static website.

### To install the latest ruby on Mac

[set up documentation](https://www.moncefbelyamani.com/how-to-install-xcode-homebrew-git-rvm-ruby-on-mac/?utm_source=stackoverflow&utm_campaign=51126403)

```
brew doctor
brew install chruby ruby-install
ruby-install ruby-3.1.0
echo "source /usr/local/share/chruby/chruby.sh" >> ~/.zshrc
echo "source /usr/local/share/chruby/auto.sh" >> ~/.zshrc
echo "chruby ruby-3.1.0" >> ~/.zshrc
```

### To run the website locally

```
gem install bundler jekyll
bundle install
bundle exec jekyll serve
```

### To build the site

```
bundle exec jekyll build
```
