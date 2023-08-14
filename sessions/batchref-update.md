# Processing multiple ref updates as a one event - pull-replication use case

In this talk, we would like to discuss new stream event called `batch-ref-updated`
which represents a single batch ref update operation.

We will introduce the new stream event, discuss what are the benefits of using
it and how to configure Gerrit to produce new events.
After the introduction we would like to show a working example of the
`batch-ref-update` event in pull-replication.

*[Christoforos Miliotis, GerritForge Inc.](../speakers.md#cmiliotis)*
*[Marcin Czech, GerritForge Inc.](../speakers.md#mczech)*
