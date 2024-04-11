# kubectl-namespace Plugin

The `kubectl-namespace` plugin is a simple utility designed to facilitate namespace management in Kubernetes clusters using the `kubectl` command-line tool. It provides a convenient way to switch between namespaces and view the current namespace in use.

## Installation

To use the `kubectl-namespace` plugin, follow these steps:

1. Ensure you have Python installed on your system (Python 3.x recommended).
2. Save the `kubectl-namespace` Python script to a directory in your system's PATH. You may name the script as desired.
3. Make the script executable by running `chmod +x kubectl-namespace` in the directory where the script is saved.

## Usage

### Switching to a Namespace

To switch to a specific namespace, use the following command:

```bash
kubectl namespace <namespace>
```

Replace `<namespace>` with the name of the namespace you want to switch to. The plugin will validate if the namespace exists before switching.

### Viewing the Current Namespace

To view the current namespace in use, simply run:

```bash
kubectl namespace
```

This command will print the name of the current namespace.

## Example

Switching to the `test` namespace:

```bash
kubectl namespace test
```

Viewing the current namespace:

```bash
kubectl namespace
```