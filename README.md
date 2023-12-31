# LeanSeo

Welcome to your new gem! In this directory, you'll find the files you need to be able to package up your Ruby library into a gem. Put your Ruby code in the file `lib/lean_seo`. To experiment with that code, run `bin/console` for an interactive prompt.

TODO: Delete this and the text above, and describe your gem

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'lean_seo'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install lean_seo


## Customizing SEO Optimization Configuration

To configure the SEO Optimization Gem for your application, open the initializer file located at `config/initializers/leanseo.rb`. This file contains default configuration settings that you can modify to suit your needs.

For example, you can set your desired canonical URL structure, default URL, default site title, and schema data. Here's how you can customize the initializer:

```ruby
SeoOptimizationGem.configure do |config|
  # Set the canonical URL structure
  config.canonical_url_structure = '/custom-structure/:path'

  # Define a different default URL
  config.default_url = '/custom-default-url/'

  # Specify your site's title
  config.default_site_title = 'My Custom Site Title'

  # Configure schema data as needed
  config.schema_data = { ... }
end


## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake test` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/cporrast/lean_seo.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
