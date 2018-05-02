# Runroom's Sonata User Bundle fork

This fork is an extension of Sonata User Bundle 4.x branch, which is only compatible with :

* PHP `^7.1`
* Symfony `^2.8`, `^3.2` and `^4.0`

It's purpose is to restore the bundle's compatibility with the following PHP versions:

* PHP `^5.6` and `^7.0`

To use it, simply replace `"sonata-project/user-bundle": "^4.1"` by `"runroom/user-bundle": "4.x-dev"` in your `composer.json` file and run `composer update`.

# Sonata User Bundle

Symfony SonataUserBundle

[![Latest Stable Version](https://poser.pugx.org/runroom/user-bundle/v/stable)](https://packagist.org/packages/runroom/user-bundle)
[![Latest Unstable Version](https://poser.pugx.org/runroom/user-bundle/v/unstable)](https://packagist.org/packages/runroom/user-bundle)
[![License](https://poser.pugx.org/runroom/user-bundle/license)](https://packagist.org/packages/runroom/user-bundle)

[![Total Downloads](https://poser.pugx.org/runroom/user-bundle/downloads)](https://packagist.org/packages/runroom/user-bundle)
[![Monthly Downloads](https://poser.pugx.org/runroom/user-bundle/d/monthly)](https://packagist.org/packages/runroom/user-bundle)
[![Daily Downloads](https://poser.pugx.org/runroom/user-bundle/d/daily)](https://packagist.org/packages/runroom/user-bundle)

Branch | Travis | Coveralls |
------ | ------ | --------- |
4.x   | [![Build Status][travis_stable_badge]][travis_stable_link]     | [![Coverage Status][coveralls_stable_badge]][coveralls_stable_link]     |

## Documentation

Check out the documentation on the [official website](https://sonata-project.org/bundles/user).

## Support

For general support and questions, please use [StackOverflow](http://stackoverflow.com/questions/tagged/sonata).

If you think you found a bug or you have a feature idea to propose, feel free to open an issue
**after looking** at the [contributing guide](CONTRIBUTING.md).

## License

This package is available under the [MIT license](LICENSE).

[travis_stable_badge]: https://travis-ci.org/Runroom/SonataUserBundle.svg?branch=4.x
[travis_stable_link]: https://travis-ci.org/Runroom/SonataUserBundle

[coveralls_stable_badge]: https://coveralls.io/repos/github/Runroom/SonataUserBundle/badge.svg?branch=4.x
[coveralls_stable_link]: https://coveralls.io/github/Runroom/SonataUserBundle?branch=4.x
