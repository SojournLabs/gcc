# gcc
Docker container for running GCC.

Getting started
===============
Run `git submodule init` to pull the files you'll need to get started.
Run `./gcc` to start the docker image. You probably want to mount a persistent directory
for this image:

    VAPR_DATA_DIR_PERSISTENT=ABSOLUTE_PATH_TO_PERSISTENT_DIRECTORY ./gcc
