# timdev/ansible-bootstrap-debian

Very rudimentary bootstrapping of a base debian box.  Built/tested against debian 7.8 (wheezy).  Useful as a first step in a "run-once" style bootstrap playbook.

* Ensure ansible-related python things are available.
* Set hostname to inventory_hostname.
* Fix up time zone (UTC).
* Ensure all packages up-to-date, and reboot if necessary.
