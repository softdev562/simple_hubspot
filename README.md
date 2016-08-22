# SimpleHubspot

SimpleHubspot Gem is a pure light-weight implementation for Hubspot API

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'simple_hubspot'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install simple_hubspot

## Usage

### Basic Usage

```ruby
require 'simple_hubspot'
```

Setting your `hapikey`

```ruby
SimpleHubspot.configure do |config|
  config.hapikey: "YOUR API KEY"
end
```

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release` to create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

1. Fork it ( https://github.com/[my-github-username]/simple_hubspot/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
