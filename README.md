PostGis Puppet module
=====================

Usage
-----

```puppet
Exec {
  path => '/usr/bin:/usr/sbin/:/bin:/sbin:/usr/local/bin:/usr/local/sbin',
}
include ::postgis
```

This will install the postgis package, create a `template\_postgis` template
database with geometry_columns and geometry_columns tables and grant some
privileges to PUBLIC role.

This module is provided by [Camptocamp](http://www.camptocamp.com/)

## Contributing

Please report bugs and feature request using [GitHub issue
tracker](https://github.com/camptocamp/puppet-postgis/issues).

For pull requests, it is very much appreciated to check your Puppet manifest
with [puppet-lint](http://puppet-lint.com/) to follow
the recommended Puppet style guidelines from the
[Puppet Labs style guide](http://docs.puppetlabs.com/guides/style_guide.html).

## License

Copyright (c) 2013 <mailto:puppet@camptocamp.com> All rights reserved.

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.
    
    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.
    
    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.
