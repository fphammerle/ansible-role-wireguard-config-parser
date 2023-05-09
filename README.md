# Ansible Role: WireGuard Configuration File Parser

## Required Input Variables

```yaml
wireguard_config_path: /etc/wireguard/wgnet0.conf
```

## Output Variables / Return Values

```
wireguard_config_interface # dict[str, str]
wireguard_config_peers # list[dict[str, str]]
```
