## Welcome to Radiant

Radiant is a no-fluff, open source content management system designed for
small teams. It is similar to Textpattern or MovableType, but is a general
purpose content management system (not just a blogging engine).

[![Build Status](https://secure.travis-ci.org/radiant/radiant.png?branch=master)](http://travis-ci.org/radiant/radiant)

Radiant features:

* An elegant user interface
* The ability to arrange pages in a hierarchy
* Flexible templating with layouts, snippets, page parts, and a custom tagging
  language (Radius: http://radius.rubyforge.org)
* A simple user management/permissions system
* Support for Markdown and Textile as well as traditional HTML (it's easy to
  create other filters)
* An advanced plugin system
* Operates in two modes: dev and production depending on the URL
* A caching system which expires pages every 5 minutes
* Built using Ruby on Rails
* And much more...

## License

Radiant is released under the MIT license and is copyright (c) 2006-2009
John W. Long and Sean Cribbs. A copy of the MIT license can be found in the
LICENSE file.

## Installation

The aim is to have everything served from your Gemfile

    gem 'radiant'
    gem 'radiant-archive-extension'
    gem 'radiant-layouts-extension'

## Development

* Fork the project
* Write tests in tests/railsapp/specs
* Modify code in the root directory
* Continue hacking ...
* Send a pull request

## Support

The best place to get support is on the mailing list:

  [http://radiantcms.org/mailing-list/](http://radiantcms.org/mailing-list/)

Most of the development for Radiant happens on Github:

  [http://github.com/radiant/radiant/](http://github.com/radiant/radiant/)

The project wiki is here:

  [http://wiki.github.com/radiant/radiant/](http://wiki.github.com/radiant/radiant/)

Enjoy!

--
The Radiant Dev Team
http://radiantcms.org