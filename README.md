A commandline interface to Haveibeenpwned
=========================================
# Dependencies
- curl
- ruby
- ruby-terminal-table
  - gem install terminal-table
    or
    apt install ruby-terminal-table
- jq

# Install
1. Symlink the hibp binary to your $PATH, e.g.
   ln -s /usr/local/share/hibp/hibp /usr/local/bin/hibp
   or
   ln -s /~/somewhere/hibp/hibp $HOME/bin/hibp
2. Optional, copy/symlink shell-completions to your completions dir

# Config
Place a config into ~/.config/hibp.env:
-----8<----------------------------------------------
API_KEY=00000000000000000000000000000000
