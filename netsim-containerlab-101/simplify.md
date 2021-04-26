Make your life simpler: add **netsim-tools** to the search path, and enable auto-completion of **containerlab** shell commands:

* Add netsim-tools to PATH:

`export PATH="netsim-tools:$PATH"`{{execute}}

* Enable auto-completion of shell commands:

`source <(containerlab completion bash)`{{execute}}

Obviously you'd put these commands into your Bash profile in your development environment.
