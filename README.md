# Mina::Git::Revision

This is the standard git module that comes with mina except it writes out a file called REVISION so we can match up which version is running in production.

## Installation

Add this line to your application's Gemfile:

    gem 'mina-git-revision'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install mina-git-revision

## Usage

Standard usage with the built-in module. Just include this at the top of your deploy.rb

```
require 'mina/git/revision'
```

## Contributing

1. Fork it ( https://github.com/[my-github-username]/mina-git-revision/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
