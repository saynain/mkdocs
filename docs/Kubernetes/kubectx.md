# kubectx
- When you work with multiple clusters or different user contexts, switching between them using plain `⁠kubectl config use-context` can be tedious.
- `kubectx` simplifies this with a short command and tab completion.
- It also comes with ⁠kubens to switch Kubernetes namespaces quickly.

Example usage:
```
kubectx               # lists available contexts
kubectx my-cluster    # switch to 'my-cluster' context
kubens my-namespace   # switch to 'my-namespace' in current context
```

## Installation on macOS (with Homebrew)
```
brew install kubectx
```

## References
[ahmetb/kubectx: Faster way to switch between clusters and namespaces in kubectl](https://github.com/ahmetb/kubectx/)
