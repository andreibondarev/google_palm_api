# GooglePalmApi

Ruby API client for the Google PaLM APIs.

Part of the [Langchain.rb](https://github.com/andreibondarev/langchainrb) stack.

![Tests status](https://github.com/andreibondarev/google_palm_api/actions/workflows/ci.yml/badge.svg)
[![Gem Version](https://badge.fury.io/rb/google_palm_api.svg)](https://badge.fury.io/rb/google_palm_api)
[![Docs](http://img.shields.io/badge/yard-docs-blue.svg)](http://rubydoc.info/gems/google_palm_api)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/andreibondarev/google_palm_api/blob/main/LICENSE.txt)
[![](https://dcbadge.vercel.app/api/server/WDARp7J2n8?compact=true&style=flat)](https://discord.gg/WDARp7J2n8)


## Installation

Install the gem and add to the application's Gemfile by executing:

    $ bundle add google_palm_api

If bundler is not being used to manage dependencies, install the gem by executing:

    $ gem install google_palm_api

## Usage

```ruby
require 'google_palm_api'
```
```ruby
client.generate_text(prompt:)
```
```ruby
client.generate_chat_message(prompt:)
```
```ruby
client.embed(text:)
```
```ruby
client.get_model(model:)
```
```ruby
client.list_models()
```
```ruby
client.count_message_tokens(message:)
```
## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and the created tag, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/andreibondarev/google_palm_api.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
