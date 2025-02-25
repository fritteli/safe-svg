# Changelog

All notable changes to this project will be documented in this file, per [the Keep a Changelog standard](http://keepachangelog.com/), and will adhere to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased] - TBD

## [1.9.9] - 2020-05-07
### Fixed
- Issue where 100% width is accidentally converted to 100px width (props @joehoyle).

## [1.9.8] - 2020-05-07
### Chaged
- Underlying library update.

## [1.9.7] - 2019-12-10
### Chaged
- Underlying library update.

## [1.9.6] - 2019-11-07
### Security
- Underlying library update that fixes a security issue.

## [1.9.5] - 2019-11-04
### Security
- Underlying library update that fixes some security issues.

## [1.9.4] - 2019-08-21
### Fixed
- Bug causing lots of error log output to do with `safe_svg::fix_direct_image_output()`.

## [1.9.3] - 2019-02-19
### Fixed
- Bug causing 0 height and width SVGs.

## [1.9.2] - 2019-02-14
### Fixed
- Warning about an Illegal string offset.
- Issue if something other than a WP_Post object is passed in via the `wp_get_attachment_image_attributes` filter.

## [1.9.1] - 2019-01-29
### Fixed
- Warning that was being generated by a change made in 1.9.0.

## [1.9.0] - 2019-01-03
### Changed
- If an image is the correct ratio, allow skipping of the crop popup when setting header/logo images with SVGs.

## [1.8.1] - 2018-11-22
### Changed
- Don't let errors break upload if uploading an empty file.

### Fixed
- Fix featured image display in Gutenberg. Props @hendridm :)

## [1.8.0] - 2018-11-04
### Added
- Pull SVG dimensions from the width/height or viewbox attributes of the SVG.
- role="img" attribute to SVGs.

## [1.7.1] - 2018-10-01
### Changed
- Underlying lib and added new filters for filtering allowed tags and attributes.

## [1.7.0] - 2018-10-01
### Added
- Allow devs to filter tags and attrs within WordPress.

## [1.6.1] - 2018-03-17
### Changed
- Images will now use the size chosen when inserted into the page rather than default to 2000px everytime.

## [1.6.0] - 2017-12-20
### Added
- Fairly big new feature - The library now allows `<use>` elements as long as they don't reference external files!

### Fixed
- You can now also embed safe image types within the SVG and not have them stripped (PNG, GIF, JPG).

## [1.5.3] - 2017-11-16
### Fixed
- 1.5.2 introduced an issue that can freeze the media library. This fixes that issue. Sorry!

## [1.5.2] - 2017-11-15
### Changed
- Tested with 4.9.0.

### Fixed
- Issue with SVGs when regenerating media.

## [1.5.1] - 2017-08-21
### Fixed
- PHP strict standards warning.

## [1.5.0] - 2017-06-20
### Changed
- Library update.
- role, aria- and data- attributes are now whitelisted to improve accessibility.

## [1.4.5] - 2017-06-18
### Changed
- Library update.

### Fixed
- Issues with defining the size of an SVG.

## [1.4.4] - 2017-06-07
### Fixed
- SVGs now display as featured images in the admin area.

## [1.4.3] - 2017-03-06
### Added
- WordPress 4.7.3 Compatibility.

### Changed
- Expanded SVG previews in media library.

## [1.4.2] - 2017-02-26
### Added
- Check / fix for when mb_* functions are not available.

## [1.4.1] - 2017-02-23
### Changed
- Underlying library to allow attributes/tags in all case variations.

## [1.4.0] - 2017-02-21
### Added
- Ability to preview SVG on both grid and list view in the wp-admin media area.

### Changed
- Underlying library version.

## [1.3.4] - 2017-02-20
### Fixed
- SVGZ uploads failing and not sanitising correctly.

## [1.3.3] - 2017-02-15
### Changed
- Allow SVGZ uploads.

## [1.3.2] - 2017-01-27
### Fixed
- Mime type issue in 4.7.1. Mad props to @lewiscowles.

## [1.3.1] - 2016-12-01
### Changed
- Underlying library version.

## [1.3.0] - 2016-10-10
### Changed
- Minify SVGs after cleaning so they can be loaded correctly through `file_get_contents`.

## [1.2.0] - 2016-02-27
### Added
- Support for camel case attributes such as viewBox.

## [1.1.1] - 2016-07-06
### Fixed
- Issue with empty svg elements self-closing.

## [1.1.0] - 2015-07-04
### Added
- I18n.
- da, de, en, es, fr, nl, and ru translations.

### Fixed
- Issue with filename not being pulled over on failed uploads.

## [1.0.0] - 2015-07-03
- Initial Release.

[Unreleased]: https://github.com/10up/safe-svg/compare/trunk...develop
[1.9.9]: https://github.com/10up/safe-svg/compare/1.9.8...1.9.9
[1.9.8]: https://github.com/10up/safe-svg/compare/1.9.7...1.9.8
[1.9.7]: https://github.com/10up/safe-svg/compare/1.9.6...1.9.7
[1.9.6]: https://github.com/10up/safe-svg/compare/1.9.5...1.9.6
[1.9.5]: https://github.com/10up/safe-svg/compare/1.9.4...1.9.5
[1.9.4]: https://github.com/10up/safe-svg/compare/1.9.3...1.9.4
[1.9.3]: https://github.com/10up/safe-svg/tree/1.9.3
[1.9.2]: https://plugins.trac.wordpress.org/browser/safe-svg?rev=2030675
[1.9.1]: https://plugins.trac.wordpress.org/browser/safe-svg?rev=2020831
[1.9.0]: https://github.com/10up/safe-svg/compare/1.8.1...1.9.0
[1.8.1]: https://github.com/10up/safe-svg/tree/1.8.1
[1.8.0]: https://plugins.trac.wordpress.org/browser/safe-svg?rev=1968505
[1.7.1]: https://github.com/10up/safe-svg/compare/1.7.0...1.7.1
[1.7.0]: https://github.com/10up/safe-svg/compare/1.6.1...1.7.0
[1.6.1]: https://github.com/10up/safe-svg/tree/1.6.1
[1.6.0]: https://plugins.trac.wordpress.org/browser/safe-svg?rev=1790304
[1.5.3]: https://plugins.trac.wordpress.org/browser/safe-svg?rev=1767971
[1.5.2]: https://plugins.trac.wordpress.org/browser/safe-svg?rev=1767107
[1.5.1]: https://plugins.trac.wordpress.org/browser/safe-svg?rev=1717074
[1.5.0]: https://plugins.trac.wordpress.org/browser/safe-svg?rev=1682064
[1.4.5]: https://plugins.trac.wordpress.org/browser/safe-svg?rev=1680702
[1.4.4]: https://plugins.trac.wordpress.org/browser/safe-svg?rev=1672159
[1.4.3]: https://plugins.trac.wordpress.org/browser/safe-svg?rev=1609079
[1.4.2]: https://plugins.trac.wordpress.org/browser/safe-svg?rev=1603943
[1.4.1]: https://plugins.trac.wordpress.org/browser/safe-svg?rev=1602282
[1.4.0]: https://plugins.trac.wordpress.org/browser/safe-svg?rev=1600797
[1.3.4]: https://plugins.trac.wordpress.org/browser/safe-svg?rev=1600043
[1.3.3]: https://plugins.trac.wordpress.org/browser/safe-svg?rev=1596667
[1.3.2]: https://plugins.trac.wordpress.org/browser/safe-svg/trunk?rev=1583740
[1.3.1]: https://plugins.trac.wordpress.org/browser/safe-svg?rev=1544361
[1.3.0]: https://plugins.trac.wordpress.org/browser/safe-svg?rev=1511922
[1.2.0]: https://plugins.trac.wordpress.org/browser/safe-svg?rev=1359493
[1.1.1]: https://plugins.trac.wordpress.org/browser/safe-svg/trunk?rev=1193752
[1.1.0]: https://github.com/10up/safe-svg/compare/1.0.0...1.0.1
[1.0.0]: https://github.com/10up/safe-svg/tree/1.0.0
