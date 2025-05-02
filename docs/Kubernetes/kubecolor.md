# kubecolor
- ⁠`kubectl` output can be hard to scan quickly, especially when you have many pods or resources.
- ⁠`kubecolor` adds syntax highlighting and colors to the output, improving visibility.
- You can alias ⁠`kubectl` to ⁠`kubecolor` for colorized output by default.

Example usage:
```
kubecolor get pods
kubecolor describe svc myservice
```

Change alias for `kubectl` to use `kubecolor` instead:
```
alias k='kubecolor'
```

Completion can be easily borrowed from the `kubectl` command by adding this to your `~/.zshrc` file:
```
# Make "kubecolor" borrow the same completion logic as "kubectl"
compdef kubecolor=kubectl
```

## Installation on macOS (with Homebrew)
```
brew install kubecolor
```

## References
[kubecolor | kubecolor](https://kubecolor.github.io/)
