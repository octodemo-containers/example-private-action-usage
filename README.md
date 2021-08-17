# example-private-action-usage

This repository showcases an example of using a GitHub Application owned by this organization `octodemo-containers` and selectively provided access (of read only repository contents) on the selected private repository [`octodemo-containers/private-action`](https://github.com/octodemo-containers/private-action) which is private within the `octodemo-containers` organization.

This approach allows you to utilize a private or internal access scoped action that you cannot or do not wish to publically publish to the GitHub Marketplace. It also shows how you can provide GitHub Applications to get a temporary limited access (at least if set up in that way) token to access the action and incorporate it inside a GitHub Actions workflow.

Ultimately this will become unnecessary as there is a Github Roadmap item; [Actions: Use actions from internal repositories](https://github.com/github/roadmap/issues/74) that will be providing an ability to do this in a much more stremalined and controlled way.

Consult the workflow file [.github/workflows/use_private_action.yml](.github/workflows/use_private_action.yml) for more aspects and an eaxmple workflow on how to achieve using a private or internal action in a workflow.
