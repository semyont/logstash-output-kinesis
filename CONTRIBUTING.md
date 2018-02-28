## TL;DR

Raising an issue is great, raising a PR is better, raising a PR with tests is *bestest*.

## Developing

You'll need [Git LFS](https://git-lfs.github.com/) to properly clone this repo.

Ensure you have JRuby 9.1.x installed. [rvm](https://rvm.io/) is your friend :)

```sh
rvm use --install .
gem install bundler && bundle install
bundle exec rake
```

### Running tests

```
rake
```

### Updating KPL

Change the dependency version in `logstash-output-kinesis.gemspec`, and then build with `bundle install`. No need to check in the jars!
