Chat Relater Changelog
======================


Version 0.3
-----------

(released on 09-Aug-2015)

- Introduced compatibility with Python 3.3 and 3.4.
- Ported command line argument handling from 'optparse' to 'argparse'.
- Switched from YAML to JSON as the intermediate format produced by the
  analyzer.
- Remove potential status symbols from nicknames.
- Improved nickname recognition.
- Moved scripts out of the package.


Version 0.2
-----------

(released on 27-Jul-2015)

- Dropped support for Python versions below 2.7.
- Switched DOT library from 'pydot' to 'graphviz'.
- Don't require `ez_setup` anymore.
- Moved package docstring into stand-alone README file.
- Moved requirement specifications from setup script into pip-style text
  files.
- Created configuration file for tox.
- Various small refactorings and cleanup.


Version 0.1
-----------

(released on 05-Jul-2007)

- Initial release.
