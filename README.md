# Requirements
docker, chromedriver, imagemagick, rvm

```bash
brew tap homebrew/cask && brew cask install chromedriver
brew install imagemagick
```

```
Each one script has a RUBY_VERSION variable, by default it is 2.6.2
```

# Preparations
Place ga_sandbox and galore beside
|- ga_sandbox
|- galore

# Run postgresql && redis within Docker compose
```bash
./up
```

# Configure SOLR && Run tests
```bash
./test
```

# Configure SOLR && Run it is on development mode
```bash
./solr
```


