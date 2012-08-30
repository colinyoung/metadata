# Metadata

## Usage

  class User < ActiveRecord::Base
    metadata do |obj|
      puts obj.name
      is a: 'user'
      with friends: obj.friends.count
      stop
    end
    
Results in

    Joe is a user with 37 friends.

## Installation

Add this line to your application's Gemfile:

    gem 'metadata'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install metadata

## Usage

TODO: Write usage instructions here

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
