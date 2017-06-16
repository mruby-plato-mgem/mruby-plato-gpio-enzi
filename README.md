# mruby-plato-gpio-enzi   [![Build Status](https://travis-ci.org/mruby-plato/mruby-plato-gpio-enzi.svg?branch=master)](https://travis-ci.org/mruby-plato/mruby-plato-gpio-enzi)
Plato::GPIO class (General Purpose Input/Output library) for enzi board
## install by mrbgems
- add conf.gem line to `build_config.rb`

```ruby
MRuby::Build.new do |conf|

  # ... (snip) ...

  conf.gem :git => 'https://github.com/mruby-plato/mruby-plato-gpio'
  conf.gem :git => 'https://github.com/mruby-plato/mruby-plato-gpio-enzi'
end
```

## example
```ruby
io = Plato::GPIO.new(Plato::GPIO::D8)
io.high
```

## License
under the MIT License:
- see LICENSE file
