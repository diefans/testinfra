=========
Changelog
=========

1.5.4
=====

* backends: fallback to UTF-8 encoding when system encoding is ASCII.
* Service: fix is_running() on systems using Upstart

1.5.3
=====

* Sudo: restore backend command in case of exceptions

1.5.2
=====

* Honnor become_user when using the ansible backend

1.5.1
=====

* Add dependency on importlib on python 2.6


1.5.0
=====

* New kubectl backend
* Command: check_output strip carriage return and newlines (#164)
* Package: rpm improve getting version() and release()
* User: add gecos (comment) field (#155)

1.4.5
=====

* SystemInfo: detect codename from VERSION_CODENAME in /etc/os-release
  (fallback when lsb_release isn't installed).
* Package: add release property for rpm based systems.
