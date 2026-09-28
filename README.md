# merge-queue-sandbox

A sandbox for testing how GitHub's merge queue treats required checks from a
GitHub App. It holds no product code, and it will be archived when the test
ends.

The `test` check fails whenever a file named `FAIL` is present, so a pull
request can be made to fail on purpose.

Measurement run 1: a pull request that passes every check.

A queue entry the merge policy blocks leaves the queue.
