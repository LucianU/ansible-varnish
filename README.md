varnish
=======
- Adds the repo key
- Adds the deb repo
- Installs `varnish`
- Installs `varnish` config

Role Variables
--------------
| Variable | Description | Default value |
|----------|-------------|---------------|
|`varnish_config`| Path to config file template | `default.vcl.j2` |
|`varnish_repo` | Deb repo | `deb https://repo.varnish-cache.org/ubuntu/trusty varnish-4.1` |
|`varnish_repo_key_url`| URL of the repo GPG key | `https://repo
.varnish-cache.org/GPG-key.txt` |

Dependencies
------------
none

License
-------
BSD
