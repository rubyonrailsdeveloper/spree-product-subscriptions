Installation
------------

Add spree_product_subscriptions to your Gemfile:

```ruby
gem 'spree_product_subscriptions', github: 'rubyonrailsdeveloper/spree-product-subscriptions'
```

Bundle your dependencies and run the installation generator:

```shell
bundle
bundle exec rails g spree_product_subscriptions:install
```

You can also seed the default data with:
```shell
bundle exec rails g spree_product_subscriptions:seed
```

