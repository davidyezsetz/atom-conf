#atom conf
Sync atom config files and packages

##installation
 - `git clone `
 - `apm install --packages-file my_atom_packages.txt`
 - backup config files `mv  .backup/`
 - symlink config files

##create a package list
 - `apm list --installed --bare | grep '^[^@]\+' -o > my_atom_packages.txt`
