# bpt-select
Like xcode-select, but for bpt.

# Requirements
* Ruby >=2.6

# Gotchas
* Both `src/bpt-select` and the `install` script has a shebang for Ruby as `#!/usr/bin/ruby`. If your Ruby is installed somewhere else, modify the scripts or run via `ruby`.

# Install
From the repo's root directory run the `install` script. This will copy the `src/bpt-select` script into `~/bin`. This directory will be created if it's not present.
You should add this directory to your PATH environment variable.

# Usage
```Usage: bpt-select [option] [path_to_bpt_exe]

Available options:
   -p                   Print info about the currently set version.
   -s                   Set a new version interactively
                        (will discovery available version via spotlight search).
   -s path_to_bpt_exe   Set a specific executable (provided via next argument).
   -h, --help           Display this help.```
