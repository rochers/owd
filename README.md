# OWD

[![Build Status](https://travis-ci.org/rochers/owd.png?branch=master)](https://travis-ci.org/rochers/owd) [![Code Climate](https://codeclimate.com/github/rochers/owd.png)](https://codeclimate.com/github/rochers/owd)

The owd gem is a simple client for One World Direct's XML API.

  client = OWD::Client.new(:client_id => 123, :client_authorization => 'XXXXXXXXXX')
  client.api.inventory_create(:sku => 'MY-FANCY-SKU')
  client.api.order_status({ order_reference: 666 })

Install the gem with
  gem install owd

See OWD's website at http://www.owd.com