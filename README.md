Experiment to see if there's a better way of managing chromedriver versions with Homebrew.

Add tap:

```
brew tap gpaciga/homebrew-chromedriver
```

Install a specific version of chromedriver, e.g.:

```
brew cask install chromedriver73
```

Should result in something like:

```
$ chromedriver --version
ChromeDriver 73.0.3683.68 (47787ec04b6e38e22703e856e101e840b65afe72)
```

Then `install`/`reinstall` as needed.

This isn't the proper way to version since `switch` doesn't work... still learning and YMMV.

Versions are cloned from <https://github.com/Homebrew/homebrew-cask/blob/master/Casks/chromedriver.rb>.

