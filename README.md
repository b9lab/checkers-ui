# CosmJs Part For Checkers Blockchain

This project contains the elements, messages, scripts and GUI of the Checkers blockchain.

## Branches progression

The project is created with a clean list of commits in order to demonstrate the natural progression of the project. In this sense, there is no late commit that fixes an error introduced earlier. If there is a fix for an error introduced earlier, the fix should be squashed with the earlier commit that introduced the error. This may require some conflict resolution.

Having a clean list of commits makes it possible to do meaningful `compare`s.

To make it easier to link to the content at the different stages of the project's progression, a number of branches have been created at commits that have `Add branch the-branch-name` as message. Be careful with the commit message as it depends on it matching the `"Add branch [0-9a-zA-Z\-]*"` regular expression.

The script `push-branches.sh` is used to extract these commits and force push them to the appropriate branch in the repository. After having made changes, you should run this script, and also manually force push to `main`.

* [`start`](../../tree/start)
* [`generated`](../../tree/generated) [diff](../../compare/start...generated)
* [`stargate`](../../tree/stargate) [diff](../../compare/generated...stargate)
* [`signing-stargate`](../../tree/signing-stargate) [diff](../../compare/stargate...signing-stargate)

## V1 branches progression

* [`start`](../../tree/start)
* [`v1-generated`](../../tree/v1-generated) [diff](../../compare/start...v1-generated)
* [`v1-stargate`](../../tree/v1-stargate) [diff](../../compare/v1-generated...v1-stargate)
* [`v1-signing-stargate`](../../tree/v1-signing-stargate) [diff](../../compare/v1-stargate...v1-signing-stargate)
* [`v1-unwired-gui`](../../tree/v1-unwired-gui) [diff](../../compare/v1-signing-stargate...v1-unwired-gui)
* [`gui`](../../tree/v1-gui) [diff](../../compare/v1-unwired-gui...v1-gui)
* [`v1-server-indexing`](../../tree/v1-server-indexing) [diff](../../compare/v1-gui...v1-server-indexing)
