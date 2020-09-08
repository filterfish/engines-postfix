# Postfix

Installs a simple postfix configuration in its own container with a minimal
configuration. This is intended to used on systems that have sensible defaults
(Debian based systems for example) and you want to minimise the number of
changes.

It has configuration for `/etc/postfix/main.cf` and `/etc/mailname`. See
`config/templates/**/*` for the required parameters.
