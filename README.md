grafana
=======


What is does this role do?
--------------------------

This role installs and configures a grafana instance.

Meta
----

Files Managed:
  * /var/service/grafana
  * /etc/iptables.d/grafana.rules

Defaults Provided:
  * grafana.public_bind: false

Variables Required:
  * None

Optional Variables:
  * grafana.public_bind: make the server publicly visible

Files Required:
  * None

Optional Files:
  * None

Conflicting Roles:
  * None

Depends On:
  * network
