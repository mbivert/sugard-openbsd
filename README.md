# Introduction
Generic OpenBSD setup scripts and base/template configuration
files for use with [sugar(1)][gh-mb-sugar-1].

They all rely on the behavior and functions from  the default
[sugar.lib][gh-mb-sugar-lib], such as ``samurai()`` or ``mksshlink()``,
so make sure, to import those, e.g. with ``sugar.imports``.

See this [blog post][tales-sugar] for more. For the SSL/TLS setup,
see [this blog post][tales-le-obsd].  For the email/[Gmail][gmail] setup,
see [this blog post][tales-mail-obsd].

The ``sugard.sample/`` directory provides a ``sugard/`` example for a basic
OpenBSD box, that inherits from essentially all of the features supported by
``sugard-openbsd``


[gh-mb-sugar-1]:         https://github.com/mbivert/sugar/tree/master/sugar.1
[gh-mb-sugar-lib]:       https://github.com/mbivert/sugar/tree/master/sugar.lib
[gh-mb-osugar-lib-obsd]: https://github.com/mbivert/sugard-openbsd/tree/master/sugar.lib.OpenBSD

[tales-sugar]:       https://tales.mbivert.com/on-sugar/
[tales-le-obsd]:     https://tales.mbivert.com/on-letsencrypt-on-openbsd/
[tales-mail-obsd]:   https://tales.mbivert.com/on-openbsd-sendmail-and-gmail/

[gmail]:                 https://gmail.com/
