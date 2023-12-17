# Install My Personal Applications and Configurations

## Roles:

Default roles used to install are as follows.

### Shell

Defaults can be overridden with the following variables. Put a yaml file in group_vars/{all or workstation} or in the playbook in vars:.
For path variables do not include the trailing slash

Local Bin:

```yaml
local_bin: "{{ ansible_env.HOME }}/.local/bin"
```
Code path:
```yaml
code_path: "{{ ansible_env.HOME }}/Code"
```

Neovim Source:

```yaml
neovim_source_path: "{{ ansible_env.HOME }}/Code/sources/neovim"
```

### TODO:
    - Firefox:
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
