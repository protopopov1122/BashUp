## BashUp

This repository contains simple backing up Bash scripts. The main goal is simplification of heterogenous backups.
`mkbackup` recursively searches `.mkbackup` files in the specified directory and executes them.
`mkbackuplib` contains library of functions which simplify backing up (like bundling or archiving git repositories, archiving whole directories, invoking subproject backing up scripts);
the functions are automatically exposed to `.mkbackup` scripts.

I've created these scripts to be able to make automatic backups of my projects using individual backup presets for each of them, so that only significant files are backed up.

#### Author & License
Author: Jevgenijs Protopopovs \
License: WTFPL