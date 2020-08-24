<p align="center">
<img src="" align="center" alt="logo" title="Themeboot logo" alt="Themeboot Logo" width="160">
</p>

<p align="center">
    <a href="//packagist.org/packages/zaghadon/themeboot">
        <img src="https://poser.pugx.org/zaghadon/themeboot/v" alt="Latest Stable Version" title="Latest Stable Version">
    </a>
    <a href="//packagist.org/packages/zaghadon/themeboot">
        <img src="https://poser.pugx.org/zaghadon/themeboot/downloads" alt="Total Downloads" title="Total Downloads">
    </a>
    <a href="//packagist.org/packages/zaghadon/themeboot">
        <img src="https://poser.pugx.org/zaghadon/themeboot/license" alt="License" title="License">
    </a>
    <h1 align="center">
        Themeboot CLI
    </h1>
</p>
<br>

# themeboot

[Themeboot](https://github.com/zaghadon/themeboot) is A Free and OpenSource Lightweight CLI app to bootstrap WordPress Theme Development created by @zaghadon.
This repository is the official repository for `themeboot`.

### Why themeboot

Me self no know ooh, but as e be, if you use it and you like it eh, Just send me your project link let me list it on the `Created with` section and why you enjoyed it so I can update this section too please. Thank you <3

## Getting Started

You'll need `php-cli`, [Composer](https://getcomposer.org/) and A local [WordPress](https://wordpress.org) installation to get started.

Simple Installation:
Make sure to place Composer's system-wide vendor bin directory in your $PATH so the laravel executable can be located by your system. This directory exists in different locations based on your operating system; however, some common locations include:

macOS: $HOME/.composer/vendor/bin
Windows: %USERPROFILE%\AppData\Roaming\Composer\vendor\bin
GNU / Linux Distributions: $HOME/.config/composer/vendor/bin or $HOME/.composer/vendor/bin

You could also find the composer's global installation path by running composer global about and looking up from the first line.

Run `composer global require zaghadon/themeboot` to install Themeboot Globally in your computer.
Run `themeboot` to verify successful installation.

Another Way is to clone the project directly to your computer. Change Directory to the cloned project, Install composer dependency and allow the post installation cmd script to export the Shell Script to your local environment PATH to enable global access.

Run `git clone https://github.com/zaghadon/themeboot.git`
Run `cd themeboot`
Run `composer install`

If the post install script didn't run successfully, you can manually install it globally by:
- Windows : Adding the path to `themeboot` to system PATH variable.
-Linux : Run `sudo ln -s /usr/local/bin/themeboot /path/to/themeboot` replacing path to with your themeboot installation location. This would create a symlink between your local global bin folder and themeboot executable binary.

Run `themeboot` to verify successful installation.

Simple Usage:

Change Directory to the theme Folder of your wordpress installation.
    `cd **/wp-content/themes/`
Initialize new theme development with themeboot
    `themeboot init`


## Contributing

Contributions are very welcome! You can contribute with code, documentation, filing issues...

## Credits

* WP Theme Scaffold created by @krafthaus_ is based on Underscores http://krafthaus.co.id/, (C) 2012-2016 Automattic, Inc.
Underscores is distributed under the terms of the GNU GPL v2 or later.

* [Minicli](https://github.com/zaghadon/themeboot) is an experimental dependency-free toolkit for building CLI-centric applications in PHP.
Minicli was created as [an educational experiment](https://dev.to/erikaheidi/bootstrapping-a-cli-php-application-in-vanilla-php-4ee) and a way to go dependency-free when building simple command-line applications in PHP. It can be used for microservices, personal dev tools, bots and little fun things.

## Created with Themeboot

- [Themester](https://github.com/zaghadon/themester) - a Multipurpose WordPress Theme for building beautiful dynamic websites (Under Development).
