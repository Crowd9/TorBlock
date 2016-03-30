
## ABOUT

Retrieves the [Tor Project](https://www.torproject.org/)'s [list of exit nodes](https://check.torproject.org/exit-addresses) and generates a list of `deny` directives for use by Nginx's [http_access_module](http://nginx.org/en/docs/http/ngx_http_access_module.html).

## USAGE

Requires Ruby (uses standard library functions only). Developed on Ruby 2.3, works on 1.9.

```
Usage: nginx_tor_ip_blacklist.rb [options]
    -o, --output-file NAME           Output filename for nginx deny directives
    -d, --[no-]debug                 Prints debug output
    -h, --help                       Show this message
```

## LICENSE

Copyright (C) 2016 Crowd9 Pty. Ltd.

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the [GNU General Public License](LICENSE.md) along with this program.  If not, see [http://www.gnu.org/licenses/](http://www.gnu.org/licenses/).
