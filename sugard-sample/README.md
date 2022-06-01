This is a sample usage of ``sugard-openbsd``: all the heavy lifting
is performed by the ``imports`` file, which will load all the hooks
and scripts in the ``ready/`` directory. The import is enabled by
the main ``pre-hook``.

The file ``tls.names`` should describe the domain name for which we
want to aquire TLS certificates.

Finally, the file ``httpd.tests`` provide a few HTTP tests example
that can be performed by ``hook-post-setup-httpd``.
