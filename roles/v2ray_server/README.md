# Ansible Role: v2ray server

## Description

Deploy [v2ray core](https://github.com/v2fly/v2ray-core) using install [scripts](https://github.com/v2fly/fhs-install-v2ray) by ansible.

You should have a valid v2ray config file on your **control node**, and **provide that file path in `v2ray_config_file_path` variable**. 

## Example

### Playbook

Use it in a playbook as follows:
```yaml
- hosts: all
  roles:
    - role: ryojerryyu.default.v2ray_server
      vars:
        v2ray_config_file_path: /etc/v2ray/config.json
```


## License

This project is licensed under MIT License. See [LICENSE](/LICENSE) for more details.
