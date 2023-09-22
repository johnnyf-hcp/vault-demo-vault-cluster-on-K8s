# Vault Demo Setup in Kubernetes

This demo is intended to demonstrate the process of setting up a 3-node Vault HA cluster.
To simulate the K8s cluster, we will be using a kind cluster.

We will also be showing how to setup Vault auto-unseal with the transit engine.

You can use Visual Studio Code to run the notebook by:
- Installing "Jupyter" extension. Ref: https://www.alphr.com/vs-code-open-jupyter-notebook/
- Install the jupyter kernel for bash. Ref: https://pypi.org/project/bash_kernel/
```shell
pip install bash_kernel
python -m bash_kernel.install
```