# Filosofia - Bacharelado 2020.1

<img src="https://i.imgur.com/pA2d7HO.gif" alt="gifmind" />


- [Tufte CSS] for the original CSS file
- [Tufte Pandoc CSS] uses Markdown in conjunction with Tufte CSS

[Tufte CSS]: https://edwardtufte.github.io/tufte-css/
[Tufte Pandoc CSS]: https://jez.io/tufte-pandoc-css/

You may ask, "What's the difference between this and `tufte-jekyll`?"

## Installation

There are two external dependencies in order to use this theme. You can install
them through your package manager (like `apt-get` or `brew`):

```
# EXAMPLE: This is for macOS. Change if you're on Linux.
# Note: you must have pandoc version 2.0 or greater
brew install pandoc
brew install jez/formulae/pandoc-sidenote
```

Next, add this line to your Jekyll site's Gemfile:

```ruby
gem "tufte-pandoc-jekyll"
```

And add these lines to your Jekyll site's `_config.yml`:

```yaml
theme: tufte-pandoc-jekyll

gems:
  - jekyll-pandoc
```
