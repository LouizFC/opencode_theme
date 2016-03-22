# Opencode Theme
[![RubyGems][gem_version_badge]][ruby_gems]
[![RubyGems][gem_downloads_badge]][ruby_gems]

Opencode Theme Command Line tool for developing themes in [TrayCommerce](https://github.com/tray-tecnologia).
## Dependencies

*  minimal version of ruby v 2.1.3

## Installation

Install Opencode Theme from rubygems with the command:

```bash
$ gem install opencode_theme
```

or install from source with:

```bash
$ git clone https://github.com/tray-tecnologia/opencode_theme
cd opencode_theme
bundle install
bundle exec opencode -h
```

## Usage

Run:

```bash
$ opencode configure API_KEY PASSWORD THEME_ID
```

You can see more in  `opencode -h`, and details here: [CLI Commands](http://dev.tray.com.br/hc/pt-br/articles/215996428-Comandos-da-GEM-OpenCode).

## Versioning

OpencodeTheme follows the [Semantic Versioning](http://semver.org/) standard.

## Issues

If you have problems, see [ISSUES.md](https://github.com/tray-tecnologia/opencode_theme/blob/master/CONTRIBUTING.md) and please create a [Github Issue](https://github.com/tray-tecnologia/opencode_theme/issues).

## Contributing

Please see [CONTRIBUTING.md](https://github.com/tray-tecnologia/opencode_theme/blob/master/CONTRIBUTING.md) for details.

## Release

Follow this steps to release a new version of the gem.

1. Test if everything is running ok;
2. Change version of the gem on `VERSION` constant;
3. Add the release date on the `CHANGELOG`;
4. Do a commit "vX.X.X", follow the semantic version;
5. Run `$ rake release`, this will send the gem to the rubygems;
6. Check if the gem is on the rubygems and the tags are correct on the github;

This gem was created and is maintained by [TrayCommerce](https://github.com/tray-tecnologia).
![Tray-logo](https://avatars1.githubusercontent.com/u/3370163?v=3&s=220)


[tray_commerce]: http://www.tray.com.br
[gem_version_badge]: http://img.shields.io/gem/v/opencode_theme.svg?style=flat
[gem_downloads_badge]: http://img.shields.io/gem/dt/opencode_theme.svg?style=flat
[ruby_gems]: http://rubygems.org/gems/opencode_theme
