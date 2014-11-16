Proposals
=========

A repository and issue tracker for proposed analyzers which have not yet been developed. Proposals should be treated similarly to requests; any user is free to start the implementation if they want to see a concrete diagnostic for the proposal.

At the point when a repository is created for a proposed diagnostic, the associated issue in this repository will be closed and future work will be performed through the issue tracker for the new project.

Guidelines
----------
+ Potentially controversial analyzers and refactoring tools will be off by default.  
For example, although an analyzer for the existence of #region or var/no-var is acceptable, by default such analyzers will be off by default, and need to be turned on by the user using the ruleset file or other configuration setting.
