# Irb::Theme::Dracula

irb theme for [dracula color scheme](https://draculatheme.com/)

## Installation

Install the gem and add to the application's Gemfile by executing:

    $ bundle add irb-theme-dracula

If bundler is not being used to manage dependencies, install the gem by executing:

    $ gem install irb-theme-dracula

## Usage
Following write your irbrc file:

```ruby ~/.irbrc
require "irb/theme/dracula/light" # if your console is dark
# require "irb/theme/dracula/dark" # if your console is light
```

## Development

After checking out the repo, run `bin/setup` to install dependencies. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and the created tag, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/irb-theme-dracula.
