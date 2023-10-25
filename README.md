# Ansible Collection - ryojerryyu.default

My default ansible collection containing some useful roles, modules and plugins.

## Roles

- [nvidia_gpu_exporter](roles/nvidia_gpu_exporter/README.md)
- [v2ray server](roles/v2ray_server/README.md)

## Install

```bash
ansible-galaxy collection install ryojerryyu.default
```

Or, if you already have a `requirements.yml` file, add an item to the collections list:

```yaml
collections:
  - ryojerryyu.default
```

Then, install the collection with `ansible-galaxy collection install -r requirements.yml`.

Anyways, you can refer to [ansible docs](https://docs.ansible.com/ansible/latest/collections_guide/index.html) for more details.

## License

This project is licensed under MIT License. See [LICENSE](/LICENSE) for more details.
