# Basic Helix Example - Test code

This is the test code for the Basic Helix Example, that you can run with `npm test` after setting
the TEST_DOMAIN environment variable, like

    export TEST_DOMAIN=project-helix.page

For now, this Helix project must be deployed to that domain before running the tests.

This branch is checked out by the CircleCI config in the master branch and used to run tests against 
the https://helix-example-basic-adobe.project-helix.page/ URL where the content found in the master branch 
of this repository is published.

The tests are "hidden" in this branch to keep the master branch focused on what's actually relevant for the example.

As this basic example requires no programming, it's good to keep the master branch minimal and focused on what's
actually required to publish a Helix Pages website.
