---
date: 2019-05-15T16:34:42Z
title: "jx create step"
slug: jx_create_step
url: /commands/jx_create_step/
---
## jx create step

Creates a step in the Jenkins X Pipeline

### Synopsis

Creates a step in the Jenkins X Pipeline

```
jx create step [flags]
```

### Examples

```
  # Create a new step in the Jenkins X Pipeline interactively
  jx create step
  
  # Creates a step on the command line: adding a post step to the release build lifecycle
  jx create step -sh "echo hello world"
  
  # Creates a step on the command line: adding a pre step to the pullRequest promote lifecycle
  jx create step -p pullRequest -l promote -m pre "echo before promote"
```

### Options

```
  -d, --dir string         The root project directory. Defaults to the current dir
  -h, --help               help for step
  -l, --lifecycle string   The lifecycle stage to add your step. Possible values: setup, setversion, prebuild, build, postbuild, promote
  -m, --mode string        The create mode for the new step. Possible values: pre, post, replace
  -p, --pipeline string    The pipeline kind to add your step. Possible values: release, pullrequest, feature
  -c, --sh string          The command to invoke for the new step
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

* [jx create](/commands/jx_create/)	 - Create a new resource

###### Auto generated by spf13/cobra on 15-May-2019