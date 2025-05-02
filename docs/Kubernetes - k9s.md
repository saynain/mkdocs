#kubernetes 
# K9S
## What is k9s?
-   A terminal-based UI tool that helps you **navigate, observe, and manage** your Kubernetes clusters interactively.
-   Simplifies viewing pods, deployments, logs, and resource details without typing long `kubectl` commands.
-   Great for quick troubleshooting and cluster monitoring.

## Basic usage
### Start k9s:
```bash
k9s
```

It will connect to your current Kubernetes context and display a dashboard of pods by default.

### Navigate resources:
-   Use arrow keys or `j`/`k` to move up/down.
-   Press `/` to search/filter resources.
-   Press `:`, then type resource name (e.g., `deploy`, `svc`, `nodes`) to switch views.
-   Press `0` to go back to the main view.

### View logs:
-   Select a pod and press `l` to view logs.
-   Use `f` to follow log output live.
-   Press `q` to exit logs view.

### Describe resources:
-   Select a resource and press `d` to see detailed info (similar to `kubectl describe`).

### Delete resources:
-   Select a resource and press `Ctrl+d` to delete it (with confirmation).

### Switch namespaces:
-   Press `:ns` and enter the namespace name to switch.
-   Or press `0` to return to all namespaces.

### Help and quit:
-   Press `?` to open help with keybindings.
-   Press `Ctrl+c` or `q` to quit k9s.

## Installation (macOS with Homebrew)
```bash
brew install k9s
```

## Resources
[K9s - Manage Your Kubernetes Clusters In Style](https://k9scli.io/)