# Chirpy Starter [![Gem Version][image-1]][1] [![GitHub license][image-2]][2]


The startup template for [**Jekyll Theme Chirpy**][3].

When installing the **Chirpy** theme through [RubyGems][4], Jekyll can only read files in the folders `_includes`, `_layout`, `_sass` and `assets`, as well as a small part of options of the `_config.yml` file from the theme's gem. (You can find the gem files by using the command `bundle info --path jekyll-theme-chirpy`). To fully use all the features of **Chirpy**, you need to copy the other critical files/directories from the theme's gem to your Jekyll site.

The critical files/directories to run or build the **Chirpy** theme are as follows:

```shell
.
├── _data
├── _plugins
├── _tabs
├── _config.yml
└──  index.html
```

So we've extracted all the **Chirpy** gem necessary content here to help you get started quickly.

## Installation

[Use this template][5] to generate a new repository, and then execute:

```
$ bundle
```

## Usage

Please see the [theme's docs][6].

## Upgrading

First, please modify the target version number of `jekyll-theme-chirpy` in the `Gemfile` (e.g., `gem "jekyll-theme-chirpy", "~> 4.0", ">= 4.0.1"`).

After that, execute the following command:

```console
$ bundle update jekyll-theme-chirpy
```

As the version upgrades, the critical files and configuration options will change. Please refer to the [Upgrade Guide][7] to keep your website files in sync with the latest version of the theme.

## License

This work is published under [MIT][8] License.

[1]:	https://rubygems.org/gems/jekyll-theme-chirpy
[2]:	https://github.com/cotes2020/chirpy-starter/blob/master/LICENSE
[3]:	https://github.com/cotes2020/jekyll-theme-chirpy/
[4]:	https://rubygems.org/gems/jekyll-theme-chirpy
[5]:	https://github.com/cotes2020/chirpy-starter/generate
[6]:	https://github.com/cotes2020/jekyll-theme-chirpy#usage
[7]:	https://github.com/cotes2020/jekyll-theme-chirpy/wiki/Upgrade-Guide
[8]:	https://github.com/cotes2020/chirpy-starter/blob/master/LICENSE

[image-1]:	https://img.shields.io/gem/v/jekyll-theme-chirpy
[image-2]:	https://img.shields.io/github/license/cotes2020/chirpy-starter.svg?color=blue