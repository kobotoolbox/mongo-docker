At one time, MongoDB 5.0 was not available as a package for Ubuntu 22.04. Maybe
that's not true anymore, but to work around the obstacle, I hacked up
https://github.com/kobotoolbox/kobo-docker/ to run MongoDB alone inside a
Docker container. All other databases (PostgreSQL and two instances of Redis)
run outside of Docker using traditional Ubuntu/Debian installation and
configuration methods.

If you're going to run your own instance of KoboToolbox, you should either use
https://github.com/kobotoolbox/kobo-helm-chart for a large instance, or
https://github.com/kobotoolbox/kobo-install for something smaller. This
repository exists for internal use only and is offered publicly with ABSOLUTELY
NO WARRANTY OR SUPPORT in the hope that it may be a useful reference.
