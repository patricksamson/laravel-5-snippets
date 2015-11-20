# Laravel 5 Snippets for Sublime Text

[![Package Control][ico-package-control]][link-package-control]

### Installation
**With the Package Control plugin** :
The easiest way to install **Laravel 5 Snippets** is through Package Control, which can be found at [http://wbond.net/sublime_packages/package_control](http://wbond.net/sublime_packages/package_control).

```
Using Package Manager, search for "Laravel 5 Snippets"
```

**Without Git** :
Download the latest source from GitHub and copy the "Laravel 5 Sippets" folder to your Sublime Text "Packages" directory.

**With Git** :
Clone the repository in your Sublime Text "Packages" directory:

```
git clone https://github.com/Lykegenes/laravel-5-snippets.git "Laravel 5 Snippets"
```

### Configuration
Sublime Text treats the '@' character as a "character that is considered to separate words". This prevents the blade snippets included in this package from triggering until you type the whole tabTrigger parameter. To fix this, just add this line to your user preferences:

```
"word_separators": "./\\()\"'-:,.;<>~!#$%^&*|+=[]{}`~?"
```

## Credits

- [Patrick Samson][link-author]
- [All Contributors][link-contributors]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[ico-package-control]: https://packagecontrol.herokuapp.com/downloads/Laravel%205%20Snippets.svg?style=flat-square

[link-package-control]: https://packagecontrol.io/packages/Laravel%205%20Snippets
[link-author]: https://github.com/lykegenes
[link-contributors]: ../../contributors
