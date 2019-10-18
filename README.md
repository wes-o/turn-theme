# turn-theme

Welcome! 

## Installation

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "turn-theme"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: turn-theme
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install turn-theme

To experiment with this code, add some sample content and run `bundle exec jekyll serve` – this directory is setup just like a Jekyll site!

## Usage

Please follow this directory structure when making a pull request:

	_layout.scss
	_component.scss
	_base.scss

	main.scss

When the pull request is reviewed, the maintainer of this project will have a much easier time with incorporation into the larger structure.


### The _sass Folder Structure:

-Abstracts: functions, mixins, and variables
-Base: animations, base, typography, and utilities
-External: based on normalize.css project 
-Components: a single scss file for each component. For example, _button.scss , _slider.scss
-Layout: header, footer, grid, navigation. Overall wireframe.
-turn-theme.scss

A free and open-source [Jekyll](https://jekyllrb.com) theme. Great for blogs and easy to customize.

[Online](https://wes-o.github.io/turn-theme/)


1. Fork and clone the [Turn Theme repo](https://github.com/wes-o/turn-theme): `git clone https://github.com/wes-o/turn-theme`
2. [Install Jekyll](https://jekyllrb.com/docs/installation/): `gem install jekyll`
3. Install the theme's dependencies: `bundle install`
4. Customize theme (see instructions below)
5. Run the Jekyll server: ` bundle exec jekyll serve`

## Customizing

Open `_config.yml`

Certain variables, _optional_ can be blank

```yml
theme:
  title: Turn Theme
  avatar:
  gravatar:
```

### Site Configuration

For a given username:

```yml
# SITE CONFIGURATION
baseurl: ""
url: "https://username.github.io"
```

Jekyll website *with* subpath:

```yml
# SITE CONFIGURATION
baseurl: "/sub-directory"
url: "https://username.github.io/"
```

## Contributing


Bug reports and pull requests are welcome on GitHub at https://github.com/[wes-o]/hello. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## Development

To set up your environment to develop this theme, run `bundle install`.

Your theme is setup just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

When your theme is released, only the files in `_layouts`, `_includes`, `_sass` and `assets` tracked with Git will be bundled.
To add a custom directory to your theme-gem, please edit the regexp in `turn-theme.gemspec` accordingly.

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

