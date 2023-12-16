# Install My Personal Applications and Configurations

## Roles:

Default roles used to install are as follows.

### Shell

Defaults can be overridden with the following variables. Put a yaml file in group_vars/{all or workstation}.
For path variables do not include the trailing slash

```yaml
local_bin: "{{ ansible_env.HOME }}/.local/bin"
```

### TODO:
    - Firefox:
        - Remove Snap
        - Replace with Deb
        - Policies for initial set up
    - Git LFS
    - Install Applications:
        - flatpack:
            - Bitwarden
            - Others...
        - External:
            - phpstorm
        - Rust:
            - Install Rustup
            - install tools
        - Configs:
            - Install Chezmoi
            - Init and Apply Chezmoi
