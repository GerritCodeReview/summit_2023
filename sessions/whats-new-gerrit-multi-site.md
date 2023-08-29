# What's new in Gerrit Multi-Site

Gerrit Multi-Site plugin is reaching its 4th anniversary,
after its inception back in February 2019.

Over the years, it has gone through
[different maturity stages](https://gerrit.googlesource.com/plugins/multi-site/+/refs/heads/master/DESIGN.md#the-road-to-multi_site)
and has gone recently through major improvements, thanks also
the advances in provided by the
[pull-replication plugin](https://gerrit.googlesource.com/plugins/pull-replication/+/refs/heads/master/src/main/resources/Documentation/about.md).

Luca gives an overview of the recent advances in the
Gerrit multi-site architecutre, including:

- Reduction of the replication lag latency with synchronous
  pull-replication
- Simplification of the multi-site setup, based on pure
  Git/HTTPS connections
- Managing sites downtimes and catch-up using an event
  message broker
- Putting replicas in the Gerrit multi-site picture
- Managing multi-site migrations

GerritHub.io has also gone through all the evolution of the
Gerrit multi-site maturity stages and experienced unprecedented
reliability, heading towards a 99.999% uptime.

*[Luca Milanesio, GerritForge](../speakers.md#luca)*