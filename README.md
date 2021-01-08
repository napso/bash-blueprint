# Bash-Blueprint

Inspired from the following article:  [Minimal safe Bash script template](https://betterdev.blog/minimal-safe-bash-script-template)



```#!/usr/bin/env bash```
or the best compatibility, it references /usr/bin/env, not the /bin/bash directly. 

"```#!/usr/bin/env``` searches PATH for bash, and bash is not always in /bin, particularly on non-Linux systems"

``set -Eeuo pipefail``

see: [Safer bash scripts with set -euxo pipefail](https://vaneyckt.io/posts/safer_bash_scripts_with_set_euxo_pipefail/)