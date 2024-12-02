# learn-k8


## Learning Concepts

### General
- ReplicatSet: Maintains a stable set of replica Pods running at any given time.
- Deployment: A deployment is a higher level wrapper around a replica set

### YAML

The pipe will make evevrything that follow to be part of a string litteral.

```yaml
multiline_string: |
  This is a
  multiline
  string in YAML.
```

Equivalent in JSON:

```json
{
    multiline_string: "This is a\nmultiline\nstring in YAML."
}
```

The greater sign will inteprete the next line as a single line string.

```yaml
multiline_string: >
  This is a
  multiline
  string in YAML.
```

Equivalent in JSON:

```json
{
    multiline_string: "This is a multiline string in YAML."
}
```

