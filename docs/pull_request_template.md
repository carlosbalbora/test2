# PR considerations

For any new feature in the project, modify:

- `CHANGELOG.mod`
- `mix.exs`

with the correct one new version.

Before to publish modification, run these commands:

- `mix format` , format the code
- `mix test` , run the tests
- `mix credo` , static code analysis
- `mix dialyzer` , static code analysis

Before to close an issue for the `ntrip-caster`, validate with a manual test that `ntrip-caster` is working correctly.

For running a local ntrip-caster, try to running locally

If it is possible, test it with helm, running our [albaspot project](https://github.com/alboracore/albaspot-deploy)
