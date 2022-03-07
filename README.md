REQUIREMENTS
  Install conda by  following this guide: https://developers.google.com/earth-engine/guides/python_install-conda

replicate the environment by running the following conda command.

conda env create -f path-to-ee-shared-env.yml

Note: The first line of the ee-shared-env.yml file defines the name of the environment to be created. Conda will not overwrite an existing environment, so the name of the environment in the ee-shared-env.yml file may need to be altered. Alternatively, use conda's remove command or the --clone flag of conda's create command to manage environment names.
