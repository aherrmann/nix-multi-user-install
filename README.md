# Nix multi-user-mode Installation Script

This script will install the [Nix package manager][1] in multi-user-mode on a
host system. Right now the script has only been tested on a fresh CentOS 6.5
installation. It should, however, not be incredibly difficult to port it to
other distributions. For that purpose, have a look at the functions
`install_daemon`, `start_daemon`, and `install_user_profile`.

[1]: http://nixos.org/nix/
