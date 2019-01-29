# Symfony CMF Block Bundle

[![Latest Stable Version](https://poser.pugx.org/symfony-cmf/block-bundle/v/stable)](https://packagist.org/packages/symfony-cmf/block-bundle)
[![Latest Unstable Version](https://poser.pugx.org/symfony-cmf/block-bundle/v/unstable)](https://packagist.org/packages/symfony-cmf/block-bundle)
[![License](https://poser.pugx.org/symfony-cmf/block-bundle/license)](https://packagist.org/packages/symfony-cmf/block-bundle)

[![Total Downloads](https://poser.pugx.org/symfony-cmf/block-bundle/downloads)](https://packagist.org/packages/symfony-cmf/block-bundle)
[![Monthly Downloads](https://poser.pugx.org/symfony-cmf/block-bundle/d/monthly)](https://packagist.org/packages/symfony-cmf/block-bundle)
[![Daily Downloads](https://poser.pugx.org/symfony-cmf/block-bundle/d/daily)](https://packagist.org/packages/symfony-cmf/block-bundle)

Branch | Travis | Coveralls | Scrutinizer |
------ | ------ | --------- | ----------- |
3.0-dev   | [![Build Status][travis_stable_badge]][travis_stable_link]     | [![Coverage Status][coveralls_stable_badge]][coveralls_stable_link]     | [![Scrutinizer Status][scrutinizer_stable_badge]][scrutinizer_stable_link] |
3.0-dev | [![Build Status][travis_unstable_badge]][travis_unstable_link] | [![Coverage Status][coveralls_unstable_badge]][coveralls_unstable_link] | [![Scrutinizer Status][scrutinizer_unstable_badge]][scrutinizer_unstable_link] |


This package is part of the [Symfony Content Management Framework (CMF)](https://cmf.symfony.com/) and licensed
under the [MIT License](LICENSE).

The BlockBundle provides integration with
[SonataBlockBundle](https://github.com/sonata-project/SonataBlockBundle).
It is used to manage fragments of content, so-called blocks, that are persisted
in a database and can be incorporated into any page layout. The BlockBundle also
provides a few commonly used standard blocks, including the ability to edit them.


## Requirements

* PHP 7.2 / 7.3
* Symfony 3.4 / 4.0 / 4.1 / 4.2
* See also the `require` section of [composer.json](composer.json)

## Documentation

For the install guide and reference, see:

* [symfony-cmf/block-bundle Documentation](https://symfony.com/doc/master/cmf/bundles/block/index.html)

See also:

* [All Symfony CMF documentation](https://symfony.com/doc/master/cmf/index.html) - complete Symfony CMF reference
* [Symfony CMF Website](https://cmf.symfony.com/) - introduction, live demo, support and community links

## Support

For general support and questions, please use [StackOverflow](https://stackoverflow.com/questions/tagged/symfony-cmf).

## Contributing

Pull requests are welcome. Please see our
[CONTRIBUTING](https://github.com/symfony-cmf/blob/master/CONTRIBUTING.md)
guide.

Unit and/or functional tests exist for this package. See the
[Testing documentation](https://symfony.com/doc/master/cmf/components/testing.html)
for a guide to running the tests.

Thanks to
[everyone who has contributed](contributors) already.

## License

This package is available under the [MIT license](src/Resources/meta/LICENSE).

[travis_stable_badge]: https://travis-ci.org/symfony-cmf/block-bundle.svg?branch=3.0-dev
[travis_stable_link]: https://travis-ci.org/symfony-cmf/block-bundle
[travis_unstable_badge]: https://travis-ci.org/symfony-cmf/block-bundle.svg?branch=3.0-dev
[travis_unstable_link]: https://travis-ci.org/symfony-cmf/block-bundle

[coveralls_stable_badge]: https://coveralls.io/repos/github/symfony-cmf/block-bundle/badge.svg?branch=3.0-dev
[coveralls_stable_link]: https://coveralls.io/github/symfony-cmf/block-bundle?branch=3.0-dev
[coveralls_unstable_badge]: https://coveralls.io/repos/github/symfony-cmf/block-bundle/badge.svg?branch=3.0-dev
[coveralls_unstable_link]: https://coveralls.io/github/symfony-cmf/block-bundle?branch=3.0-dev

[scrutinizer_stable_badge]: https://scrutinizer-ci.com/g/symfony-cmf/block-bundle/badges/quality-score.png?b=3.0-dev
[scrutinizer_stable_link]: https://scrutinizer-ci.com/g/symfony-cmf/block-bundle/?branch=3.0-dev
[scrutinizer_unstable_badge]: https://scrutinizer-ci.com/g/symfony-cmf/block-bundle/badges/quality-score.png?b=3.0-dev
[scrutinizer_unstable_link]: https://scrutinizer-ci.com/g/symfony-cmf/block-bundle/?branch=3.0-dev
