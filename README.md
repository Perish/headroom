# Headroom

[headroom.js](http://wicky.nillia.ms/headroom.js/) 和 [animate.css](http://daneden.github.io/animate.css/) 

## Installation

添加下面代码到 Gemfile:

```ruby
gem 'headroom'
```

执行:

    $ bundle

或者是执行:

    $ gem install headroom

## Usage

在application.js中引用:

```
//= require headroom
```

在application.css中引用:

```
//= require animate
```

或者

在application.coffee中引用:

```
#=require animate
```

在application.scss中引用:

```
#=require headroom
```



## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release` to create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

1. Fork it ( https://github.com/[my-github-username]/headroom/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
