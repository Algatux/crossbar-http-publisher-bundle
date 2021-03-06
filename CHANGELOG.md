# Changes in CrossbarHttpPublisherBundle

All notable changes of the CrossbarHttpPublisherBundle are documented in this file using the 
[Keep a CHANGELOG](http://keepachangelog.com/) principles.

## [1.0.1] - 2017-01-24

### Changed
* Raised test coverage to nearly 100%
* Bump PHPUnit's minimum require-dev version to 4.6 to use Prophecy

### Fixed
* Minor style fixes
* Removed BC layer for Symfony <2.6 factory definition 

## [1.0] - 2017-01-23

### Changed
* Bump minimum required PHP version to 5.6
* Bump minimum required Symfony version to 2.7
 
## [0.2] - 2017-01-18

* Second, belated tagged release

### Changed
* Added support for Symfony 3.x
* Various internal refactoring, to avoid duplication of the private factory service 

### Fixed
* Drop support to PHP 5.3, since it wasn't possible due to Guzzle 5 minimum requirements
* Improvements to the `composer.json` package description
* Various CI improvements:
  * Enable Travis CI build matrix (PHP 5.4 up to 7.1, and lowest & .lock deps)
  * Add an integration test using a containerized Crossbar server, to test the whole functionality of the bundle
  * Enable code coverage in Travis build
  * Enable Scrutinizer inspection and code coverage collection
  * Enable Coveralls.io

## [0.1] - 2015-10-05

* First, belated tagged release; previously released as dev-master only 
