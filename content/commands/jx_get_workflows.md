---
date: 2019-05-10T12:00:57Z
title: "jx get workflows"
slug: jx_get_workflows
url: /commands/jx_get_workflows/
---
## jx get workflows

Display either all the available workflows or a specific workflow

### Synopsis

Display either all the workflows or a specific workflow

```
jx get workflows [flags]
```

### Examples

```
  # List all the available workflows
  jx get workflow
  
  # Display a specific workflow
  jx get workflow -n default
```

### Options

```
  -h, --help            help for workflows
  -n, --name string     The name of the workflow to display
  -o, --output string   The output format such as 'yaml'
```

### Options inherited from parent commands

```
  -b, --batch-mode                Runs in batch mode without prompting for user input (default true)
      --install-dependencies      Enables automatic dependencies installation when required
      --log-level string          Sets the logging level (panic, fatal, error, warning, info, debug) (default "info")
      --no-brew                   Disables brew package manager on MacOS when installing binary dependencies
      --skip-auth-secrets-merge   Skips merging the secrets from local files with the secrets from Kubernetes cluster
      --verbose                   Enables verbose output
```

### SEE ALSO

* [jx get](/commands/jx_get/)	 - Display one or more resources

###### Auto generated by spf13/cobra on 10-May-2019