CHANGELOG
=========

1.2.0
-----

2016 - TBD

This is a backwards incompatible release.

  * Drop Ruby 1.8.7 support
  * Move to voxpupuli namespace
  * Significant code quality improvements

Thanks to Joseph Yaworski for his work on this release.

1.1.3
-----

2014-09-02

This is a backwards compatible bugfix release.

  * Invoke super in self.initvars to initialize `@defaults`

Thanks to Igor Galić for his work on this release.

1.1.2
-----

2013-07-04

This is a backwards compatible bugfix release.

  * Update permissions of built modules to be a+rX.

1.1.1
-----

2012-12-30

This is a backwards compatible bugfix release.

  * (filemapper-#4) Add resource failure when in error state

Thanks to Reid Vandewiele for his contribution for this release.

1.1.0
-----

2012-12-07

This is a backwards compatible feature release.

  * Add Apache 2.0 LICENSE
  * Add Gemfile
  * (filemapper-#3) Add `unlink_empty_files` attribute
  * (maint) spec cleanup for readability
  * (filemapper-#2) Add pre and post flush hook support

1.0.2
-----

This is a backwards compatible maintenance release.

  * Update metadata to reference forge username
  * Ensure implementing classes return a string from format_file

1.0.1
-----

This is a backwards compatible maintenance release.

  * Remove call `#symbolize` method; said method was removed in Puppet 3.0.0
  * Fail fast if an including class returns bad data from Provider.parse_file
  * Don't try to fall back to `@resource.should` value for properties
