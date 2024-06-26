# install_yq

Role to install and manage [yq](https://github.com/mikefarah/yq).

## Role Variables

```yaml
install_yq_version: "v4.42.1" # Version to install
```

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: wittdennis.install_yq, install_yq_version: "v4.42.1" }

## License

MIT
