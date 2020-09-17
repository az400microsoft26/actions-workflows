# Shared Workflow Templates for the Actions Demo Organization

This repository contains [shared GitHub Actions workflow templates](https://docs.github.com/en/actions/learn-github-actions/sharing-workflows-with-your-organization) for [the **actionsdemo** organization](https://github.com/actionsdemo/)

These [workflow templates](workflow-templates) are useful as starter worfklows for common CICD tasks in the organization, related to building, testing, and releasing software.

The currently available workflow templates are

* `gradle-java` - a build, check, test, and publish workflow which uses gradle to build a Java application using the GitHub Actions [`setup-java`](https://github.com/actions/setup-java) action and publishes a Maven snapshot JAR to the [GitHub Package Registry](https://docs.github.com/en/packages/publishing-and-managing-packages/about-github-packages)

* `gradle-release` - a workflow for manually publishing the current version of the code as a Maven package in the GitHub Package Registry with a version and description provided as inputs.
