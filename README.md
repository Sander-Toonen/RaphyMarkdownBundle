# RaphyMarkdownBundle

[![SensioLabsInsight](https://insight.sensiolabs.com/projects/b675534d-9c5c-490a-aefa-492a48ca4e16/mini.png)](https://insight.sensiolabs.com/projects/b675534d-9c5c-490a-aefa-492a48ca4e16)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/Raphy/RaphyMarkdownBundle/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/Raphy/RaphyMarkdownBundle/?branch=master)
[![Build Status](https://img.shields.io/travis/Raphy/RaphyMarkdownBundle.svg)](https://travis-ci.org/Raphy/RaphyMarkdownBundle)
[![Code Coverage](https://scrutinizer-ci.com/g/Raphy/RaphyMarkdownBundle/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/Raphy/RaphyMarkdownBundle/?branch=master)
[![Total Downloads](https://poser.pugx.org/raphy/markdown-bundle/downloads)](https://packagist.org/packages/raphy/markdown-bundle)
[![Latest Stable Version](https://poser.pugx.org/raphy/markdown-bundle/v/stable)](https://packagist.org/packages/raphy/markdown-bundle)
[![License](https://poser.pugx.org/raphy/markdown-bundle/license)](https://packagist.org/packages/raphy/markdown-bundle)

Provides a fully-featured Markdown bundle

# Requirements

The bundle supports:
- PHP ^5.6 | ^7.0
- Symfony ^2.8 | ^3.0 | ^4.0

## Documentation

To have an idea of how the bundle works, see the [Basic usage](Resources/doc/basic-usage.md) documentation page.
See the `doc` directory for more detailed documentation or just start with [main documentation page](Resources/doc/index.md).

## Features

- [X] **Parser modularity** Allow to use any Markdown parser library (by default use [Parsedown](https://github.com/erusev/parsedown))
- [x] **Twig filter** Provides the Twig filter `markdown`
- [x] **Editor** Use a textarea in a form as Markdown editor using [SimpleMDE](https://github.com/NextStepWebs/simplemde-markdown-editor)
- [x] **Multi parser** Add multiple parser and use a specific parser when wanted

## License

See the [LICENSE](LICENSE) file for details.
