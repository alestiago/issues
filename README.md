## References

Repository: [very_good_coverage](https://github.com/invertase/dart_custom_lint)

Issue: [Allow custom coverage on empty coverage file](https://github.com/VeryGoodOpenSource/very_good_coverage/issues/167)

This shows how to resolve the above issue and avoid the workflow from crashing, see [this modified workflow](.github/workflows/main.yaml) which skips the coverage workflow from executing whenever the lcov is empty or not found.

This [pull request](https://github.com/alestiago/issues/pull/2) shows how the suggested workflow works as intended.
