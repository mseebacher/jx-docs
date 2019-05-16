---
date: 2019-05-15T16:34:42Z
title: "jx delete token"
slug: jx_delete_token
url: /commands/jx_delete_token/
---
## jx delete token

Deletes one or more issue token resources

### Synopsis

Deletes one or more issue token resources

```
jx delete token [flags]
```

### Options

```
  -h, --help   help for token
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

* [jx delete](/commands/jx_delete/)	 - Deletes one or more resources
* [jx delete token addon](/commands/jx_delete_token_addon/)	 - Deletes one or more API tokens for a user on an issue addon server

###### Auto generated by spf13/cobra on 15-May-2019