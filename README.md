# Proposals

A repository and issue tracker for proposed analyzers which have not yet been developed. Proposals should be treated similarly to requests; any user is free to start the implementation if they want to see a concrete diagnostic for the proposal.

At the point when a repository is created for a proposed diagnostic, the associated issue in this repository will be closed and future work will be performed through the issue tracker for the new project.

## What can I propose here?

This issue tracker is used for several types of proposals.

* **Diagnostic**: Code which performs a source or binary analysis to identify potential problems and/or "items of interest" to a developer.
* **Code Fix**: Code which suggests an automatic alteration to the source or binary in response to the output of a Diagnostic.
* **Refactoring**: Code which performs on-demand alteration to the source or binary in response to a direct request from the developer, which may or may not be prompted by the output of a Diagnostic.

## Why `DotNetAnalyzers`?

The name **Analyzers** stems from the name of the node in **Solution Explorer** where all of the items described above appear when they are installed through NuGet. In addition, the name of the command in Visual Studio to add new ones to the project is **Add Analyzer...**.

## My analyzer is hosted elsewhere

While this organization was formed to allow maximum flexibility for users to develop analyzers, we understand that in some situations it might not make sense to place an analyzer repository here. If you would like to improve exposure to your analyzer without creating (or moving) your main repository to the DotNetAnalyzers organization, please review issue #6 for some ideas about how to proceed.

## Guidelines

In general, contributors are free to establish their own guidelines for their own repositories. During community code reviews, users may suggest changes to your code and/or guidelines when they feel the current practice may cause problems down the road, or could make it difficult to incorporate your analyzer alongside analyzers from other developers. The policy for determining what, if any, action is taken in response to these issues is likely to vary by repository.

For additional details about guidelines for a specific repository within the DotNetAnalyzers organization, please see the readme (or other documentation) associated with that repository.
