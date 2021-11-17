# smol

> Forked by ptrcnull to make some customizations

A minimal, monospaced blogging theme for Hugo that respects your privacy and is easy on your bandwidth.

A real-life example can be found at https://ptrcnull.me.

smol is based on [Blank](https://github.com/Vimux/Blank) created by [Vimux](https://github.com/Vimux).


## Features

- No JavaScript
- No Google spyware or tracking of any kind
- No other external dependencies, embedded fonts or comment sections

## Installation

In your Hugo site `themes` directory, run:

```
git clone https://github.com/ptrcnull/smol
```

Next, open `config.toml` in the base of the Hugo site and ensure the theme option is set to `smol`.

```
theme = "smol"
```

Lastly, add the following lines to your `config.toml` to set site parameters and make use of all the menu entries in the header and footer sections if you need them.

```
# Parameters
[params]
    subtitle = "Your blog subtitle goes here!"
    dateFmt = "02.01.2006 15:04"

# Header
[menu]
  [[menu.main]]
        identifier = "posts"
        name = "Posts"
        url = "/posts/"
        weight = 1 

  [[menu.main]]
        identifier = "categories"
        name = "Categories"
        url = "/categories/"
        weight = 2 

  [[menu.main]]
        identifier = "tags"
        name = "Tags"
        url = "/tags/"
        weight = 3

# Footer
  [[menu.footer]]
        name = "Github"
        url = "https://github.com/example"
        weight = 1 

    [[menu.footer]]
        name = "Mastodon"
        url = "https://example.com/@user"
        weight = 2 

    [[menu.footer]]
        name = "Imprint"
        url = "/imprint"
        weight = 3 

```

For more information read the official [quick start guide](https://gohugo.io/getting-started/quick-start/) of Hugo.

## Contributing

Have you found a bug or got an idea for a new feature? Feel free to use the [issue tracker](https://github.com/colorchestra/smol/issues) to let me know. Or make directly a [pull request](https://github.com/colorchestra/smol/pulls).

## License

This theme is released under the [MIT license](https://github.com/colorchestra/smol/blob/master/LICENSE).
