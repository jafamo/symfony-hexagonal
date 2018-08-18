The Infrastructure Layer
========================

The main purpose of the infrastructure layer is organize code related, not to the
domain or actions that can be performed in it, but to deal with external services
that your domain uses. These can be databases, in memory key store, message queues,
http controllers, cli commands, email or filesystem. These are things that your
domain should not know and not care about, since infrastructure is an implementation
detail in general.