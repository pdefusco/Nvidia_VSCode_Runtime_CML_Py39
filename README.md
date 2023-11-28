# Nvidia VSCode Runtime CML with Python 3.9

This is a CML Runtime with VSCode, Cuda 11 and Python 3.9. You can use this runtime in your CML Workspace by adding it to the Workspace Runtime Catalog by following [these instructions](https://docs.cloudera.com/machine-learning/cloud/runtimes/topics/ml-adding-new-ml-runtimes.html).

This runtime is built by extending the CML Python 3.9-CUDA PBJ Runtime 'ml-runtime-pbj-workbench-python3.10-cuda:2023.08.2-b8'. You can find the dockerfile attached to this repository.

If you are curious to learn more about how this runtime was built please visit the article on a CUDA-VS Code Runtime with Python 3.10 at [this link](https://community.cloudera.com/t5/Community-Articles/CML-Runtime-with-Nvidia-Libs-and-VSCode-Editor/ta-p/379181). The only difference is the selection of base runtime at line 46 of this Dockerfile.
