# sample-buildkite-plugin

A demo for a buildkite plugin.

Example:

```
steps:
  - command: ls
    env:
      BUILDKITE_PLUGINS_ALWAYS_CLONE_FRESH: "true"
    plugins:
      - lukefaccin/sample:
          pattern: '*.md'
```
