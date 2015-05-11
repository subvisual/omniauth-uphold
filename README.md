# Omniauth Bitreserve

This gem contains the [Bitreserve](https://bitreserve.org/) strategy for OmniAuth

## Using this strategy

Add this line to your application's Gemfile:

```ruby
gem 'omniauth-bitreserve'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install omniauth-bitreserve

Now you must tell OmniAuth about this provider, For a Rails app, your `config/initializers/omniauth.rb` file should look like this:

```ruby
Rails.application.config.middleware.use OmniAuth::Builder do
  provider :bitreserve, 'API_KEY', 'API_SECRET'
end
```

## Contributing

1. Fork it ( https://github.com/[my-github-username]/omniauth-Bitreserve/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request