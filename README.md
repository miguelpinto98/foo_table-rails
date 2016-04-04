# FooTable::Rails::V3 [![Build Status](https://secure.travis-ci.org/TwilightCoders/foo_table-rails.png)](http://travis-ci.org/TwilightCoders/foo_table-rails) [![Gem Version](https://badge.fury.io/rb/foo_table-rails.png)](http://travis-ci.org/TwilightCoders/foo_table-rails) [![Code Climate](https://codeclimate.com/github/TwilightCoders/foo_table-rails.png)](https://codeclimate.com/github/TwilightCoders/foo_table-rails) [![Dependency Status](https://gemnasium.com/TwilightCoders/foo_table-rails.svg)](https://gemnasium.com/TwilightCoders/foo_table-rails)

Wire up the [FooTable](http://fooplugins.github.io/FooTable/) [assets](https://github.com/bradvin/FooTable) for your Rails
applications. Use the newest version of FooTable.

## Getting Started

If you're using Bundler, you can add foo_table-rails to your Gemfile:

```ruby
gem 'foo_table-rails'
```

Or manually install the foo_table-rails gem:

```shell
gem install foo_table-rails
```


## FooTable::Rails for Rails >= 3.1

All of the assets from the most latest stable FooTable::Rails release are vendored
so that you can use them with the asset pipeline.  At a minimum, you will
probably want the following in your application.js and application.css/scss:

```js
//= require footable
```

```css
//= require footable.bootstrap
// or...
//= require footable.standalone
```

```scss
@import "footable.bootstrap";
// or...
@import "footable.standalone";
```

### With plugins

Additional syntax modes can be added to your application.js and application.css:

```js
//= require footable.core

// and...
//= require footable.filtering
//= require footable.paging
//= require footable.sorting
```

```css
//= require footable.core.bootstrap
// or...
//= require footable.core.standalone

// and
//= require footable.filtering
//= require footable.paging
//= require footable.sorting
```

### Contributing

Find a mistake? New version of FooTable::Rails? Submit a pull request!

---

Copyright (c) 2015 Dale Stevens, released under the MIT license
