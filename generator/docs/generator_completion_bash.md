## generator completion bash

Generate the autocompletion script for bash

### Synopsis

Generate the autocompletion script for the bash shell.

This script depends on the 'bash-completion' package.
If it is not installed already, you can install it via your OS's package manager.

To load completions in your current shell session:

	source <(generator completion bash)

To load completions for every new session, execute once:

#### Linux:

	generator completion bash > /etc/bash_completion.d/generator

#### macOS:

	generator completion bash > $(brew --prefix)/etc/bash_completion.d/generator

You will need to start a new shell for this setup to take effect.


```
generator completion bash
```

### Options

```
  -h, --help              help for bash
      --no-descriptions   disable completion descriptions
```

### Options inherited from parent commands

```
      --config string     config file (default is PROJECT/.env)
      --modifyExistCode   allow generator modify exist code (default true)
```

### SEE ALSO

* [generator completion](generator_completion.md)	 - Generate the autocompletion script for the specified shell

###### Auto generated by spf13/cobra on 24-Jun-2022