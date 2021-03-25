# jekyll-theme-jam

[![Gem Version](https://badge.fury.io/rb/jekyll-theme-jam.svg)](https://badge.fury.io/rb/jekyll-theme-jam)
[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/desiredpersona/jekyll-theme-jam/master/LICENSE.md)

View [theme demo](https://desiredpersona.com)


## Installation

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "jekyll-theme-jam"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: jekyll-theme-jam
```

And then execute:

```
$ bundle
```

Or install it yourself as:

```
$ gem install jekyll-theme-jam
```

This theme can also be used with [jekyll-remote-theme](https://github.com/benbalter/jekyll-remote-theme).
To do so:
  1. Add the gem to your Gemfile under Jekyll-Plugins
  ```
  # If you have any plugins, put them here!
  group :jekyll_plugins do
      # other plugins...
      gem "jekyll-remote-theme"
      # other plugins...
  end
  ```
  2. Specify the repository in the 'remote_theme' tag in `_config.yml`
    ```
    remote_theme: desiredpersona/jekyll-theme-jam
    ```

**N.B:** When using remote-theme and doing style overrides things are a little different. First, make a file `assets/css/jam.scss` (filepath from Jekyll root)

Inside the `jam.scss` file, put the following boilerplate code at the top of the file before defining any style rules
```
---
---
@import "_theme";
```
## Usage

TODO: Write usage instructions here. Describe your available layouts, includes, sass and/or assets.

## Credits

#### Creator

Desired Persona

- [https://desiredpersona.com](https://desiredpersona.com)
- [https://twitter.com/desiredpersona](https://twitter.com/desiredpersona)
- [https://github.com/desiredpersona](https://github.com/desiredpersona)

#### Thanks

- [Jekyll](http://jekyllrb.com) static site generator.
- [Tachyons](http://tachyons.io) functional css for humans.
- [BrowserStack](https://www.browserstack.com) live, web-based browser testing.

## Contributing

Bug reports and pull requests are welcome on GitHub at [https://github.com/desiredpersona/jekyll-theme-jam](https://github.com/desiredpersona/jekyll-theme-jam). This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## License

[MIT](https://github.com/desiredpersona/jekyll-theme-jam/blob/master/LICENSE.md)
