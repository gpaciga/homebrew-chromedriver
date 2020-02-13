# homebrew-chromedriver

Experiment to see if there's a better way of managing chromedriver versions with Homebrew.

This isn't the proper way to version since `switch` doesn't work... still learning and YMMV. But potentially useful anyway.

## Add tap

```
brew tap gpaciga/homebrew-chromedriver
```

## Install a specific version

First make sure you have the latest versions:

```
brew update
```

To install a specific version of chromedriver:

```
brew cask install chromedriver73
```

Or, if you've previously installed this version, you may need to use `reinstall` instead:

```
brew cask reinstall chromedriver73
```

Should result in something like:

```
$ chromedriver --version
ChromeDriver 73.0.3683.68 (47787ec04b6e38e22703e856e101e840b65afe72)
```

## Getting new versions

Versions are cloned from <https://github.com/Homebrew/homebrew-cask/blob/master/Casks/chromedriver.rb>.

