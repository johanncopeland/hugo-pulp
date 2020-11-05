# Flat Valley
flat-valley is my theme for [Hugo](https://gohugo.io/) and a fork of [pulp](https://github.com/koirand/pulp) [(MIT)](https://github.com/koirand/pulp/blob/master/LICENSE.md)

## Installation
If your site is also under version control using git, the easiest way to install this theme is to add it as a submodule. If you have not created a git repo for your project yet, you need to run `git init` beforehand. Inside the folder of your Hugo site, run the following command.
```
git submodule add https://github.com/johanncopeland/flat-valley.git themes/flat
```

Alternatively, you can clone the theme into your project.
```
git clone https://github.com/johanncopeland/flat-valley.git themes/flat
```

## Configuration
Configure your config.toml with reference to exampleSite.
Put your own avatar image in /static/img/avatar.jpg of your own site, and also favicon.ico. Hugo will automatically use that images instead of the standard one. It's not necessary to alter the theme.

## Update the theme
You can update the theme by issuing the following command inside your project folder.
```
git submodule update --remote --rebase
```

If you have cloned the theme, you can run `git pull` inside the theme folder.

# Included third-party software
[Pulp](https://github.com/koirand/pulp)
[(License: MIT)](licenses/pulp-MIT.md)
