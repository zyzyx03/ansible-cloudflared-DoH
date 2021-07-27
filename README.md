# [Cloudflared DNS over HTTPS](#Cloudflared)

## [Example Playbook](#example-playbook)

This example is taken from `molecule/resources/converge.yml` and is tested on each push, pull request and release.
```yaml
---
- name: Converge
  hosts: all
  tasks:
    - name: "Include ansible-cloudflared-doh"
      include_role:
        name: "ansible-cloudflared-doh"
```

