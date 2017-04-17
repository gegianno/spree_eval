SpreeEval
================

Rails example project that implements Spree store, and a Spree extension that adds a report view for all the products that in a range of dates ran out of stock.

## Installation

1. Install the gems using Bundler:
  ```ruby
  bundle install
  ```

2. Install Spree:
  ```ruby
  bundle exec rails g spree:install
  ```

3. Install the Spree extension:
  ```ruby
  bundle exec rails g spree_stock_report:install
  ```

4. Restart your server

  If your server was running, restart it so that it can find the assets properly.


Copyright (c) 2017 Giorgio, released under the New BSD License
