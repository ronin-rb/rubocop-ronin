# rubocop-ronin

* [Website](https://ronin-rb.dev/)
* [Source](https://github.com/ronin-rb/rubocop-ronin)
* [Issues](https://github.com/ronin-rb/rubocop-ronin/issues)
* [Documentation](https://ronin-rb.dev/docs/rubocop-ronin/frames)
* [Discord](https://discord.gg/6WAb3PsVX9) |
  [Twitter](https://twitter.com/ronin_rb) |
  [Mastodon](https://infosec.exchange/@ronin_rb)

## Description

rubocop-ronin is a set of common [rubocop] rules for the [ronin-rb] project.
This is necessary because [rubocop]'s default configuration clashes with
[ronin-rb]'s coding style, or sometimes even differs from the defacto Ruby
coding style.

## Features

* Overrides [rubocop]'s default configuration to support [ronin-rb]'s coding
  style.

## Requirements

* [rubocop] ~> 1.0

## Install

Add the gem to the `Gemfile`:

```ruby
gem 'rubocop-ronin', '~> 0.1', require: false
```

Add the following lines to a `ronin-*` gem's `.rubocop.yml` file:

```yaml
inherit_gem:
  rubocop-ronin: rubocop.yml
```

## Development

1. [Fork It!](https://github.com/ronin-rb/rubocop-ronin/fork)
2. Clone It!
3. `cd rubocop-ronin/`
4. `bundle install`
5. `git checkout -b my_feature`
6. Code It!
8. `git push origin my_feature`

[rubocop]: https://rubocop.org/
[ronin-rb]: https://github.com/ronin-rb
