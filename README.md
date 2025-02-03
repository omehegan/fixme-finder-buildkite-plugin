# Fixme Finder Buildkite Plugin

This plugin searches your source code and flags any lines which include 'FIXME.'

## Example

Add the following to your `pipeline.yml`:

```yml
steps:
  - command: ls
    plugins:
      - omehegan/fixme-finder#v1.0.0
```

## Configuration

No configuration required.

## Developing

To run the tests:

```shell
docker-compose run --rm tests
```

## Contributing

1. Fork the repo
2. Make the changes
3. Run the tests
4. Commit and push your changes
5. Send a pull request
