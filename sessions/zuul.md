# Zuul: Project Gating for Gerrit

Zuul is a project gating system, which is like a CI/CD system that is
primarily focused on ensuring multiple changes are well-tested with
each other before being merged.

Zuul was originally written for Gerrit, and as such, has a special
relationship with it.  Zuul takes advantage of Gerrit topics to
support circular dependencies between changes.  It may be the only CI
system that can do something reasonable with Gerrit submodule
subscriptions.  And it recently added its eighth method of interfacing
with Gerrit.

In addition to all this love for Gerrit, Zuul also seamless integrates
with other code review systems allowing teams to use its cross-project
dependency features to test changes in Gerrit and GitHub/Gitlab/etc
together.

This presentation will provide an overview of Zuul, how it integrates
with Gerrit, and recent updates to support new features in Gerrit.

*[James Blair, Acme Gating](../speakers.md#corvus)*
