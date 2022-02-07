

```
git clone git@github.com:tarmstrong/rubygems
git fetch origin tavish/bundler-v2.2.30:tavish/bundler-v2.2.30
git checkout tavish/bundler-v2.2.30

cd bundler
gem build bundler.gemspec
gem install bundler-2.2.30.gem
```

after getting logs:

```
gem uninstall bundler
gem install bundler -v 2.2.30
```
