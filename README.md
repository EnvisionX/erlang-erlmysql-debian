# Debianization for the Erlang MySQL Driver

The repo contains so called DEBIAN directory with
scripts and configs needed to package the
[erlmysql](http://sourceforge.net/projects/erlmysql/)
library into a DEB package for the Debian Wheezy distro.

ErlMySQL is a MySQL client written in Erlang and provides
API that is very close to Connector/C library. The client
is using low level (TCP/IP socket) connection to MySQL
server and allows to exchange a data with maximum possible
speed. Multiple datasource support and connection pool are
incapsulated in the client that increases a performance in
concurrent environment.
