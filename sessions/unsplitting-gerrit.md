# Unsplitting Gerrit

Gerrit's natural focus on scalability relies on being able to run clusters with
multiple nodes and reliably serving traffic from each node.
Observability over how the nodes are in sync, when they start to drift apart
and being able to quickly investigate and fix issues when they arise becomes
critical to the correct operation of the cluster.

In this talk I'll go over the main hurdles, what problems we have found and
what solution we have put in place solutions to ensure Gerrit Admins are
always on top of the installation.

*[Daniele Sassoli, GerritForge](../speakers.md#dsassoli)*
