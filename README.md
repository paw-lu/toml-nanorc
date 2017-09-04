# toml-nanorc
nanorc highlighting for TOML (https://github.com/toml-lang/toml)

# Installation
1. Copy `toml.nanorc` to `/usr/share/nano/`
2. Open `/etc/nanorc`
3. If you can't find `include "/usr/share/nano/*.nanorc"`, add the following.
    # TOML
    include "/usr/share/nano/toml.nanorc"
4. Enjoy.

# Features
* Key / table name highlighting
* Numbers / strings / string blocks highlighting
* Basic checks
  * Keyless values
  * Trailing whitespace
  * Invalid table names
