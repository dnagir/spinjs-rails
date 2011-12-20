# Spin.js - spinner with no CSS, Images

Provides an easy-to-use Rails 3.1 asset for [Spin.js](http://fgnass.github.com/spin.js/)

# Install

Add it to your Rails application's `Gemfile`:

```ruby
gem 'spinjs-rails'
```

Then `bundle install`.


# Usage

Require `spin`:


```javascript
// application.js

//= require spin
```

or as jQuery plugin:

```javascript
// application.js

//= require jquery.spin

// Then you can:

$(".abc").spin(); // Shows the default spinner
$(".abc").spin(false); // Hide the spinner

// Show customised spinner:
$(".abc").spin({
  lines: 12, // The number of lines to draw
  length: 7, // The length of each line
  width: 9, // The line thickness
  radius: 30, // The radius of the inner circle
  color: '#000', // #rgb or #rrggbb
  speed: 1, // Rounds per second
  trail: 60, // Afterglow percentage
  shadow: false // Whether to render a shadow
});
```


See the full usage details on the [spin.js](http://fgnass.github.com/spin.js/) site.


# License

[MIT](http://www.opensource.org/licenses/mit-license.php) by [@dnagir](https://twitter.com/#!/dnagir).

