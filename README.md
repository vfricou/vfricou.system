# README

# Disclaimer

This repository contain my own work about some applications able to be deployed with Ansible.  
This collection was use in my own managed environment.

Review code before usage.

**Use at your own risks.**


# How to use

Create or add in your existing `requirements.yml` file this collection :

```yaml
---
collections:
  - name: "vfricou.system"
    source: "https://github.com/vfricou/vfricou.system.git"
    version: "<latest_tag>"
```

> You can use `master` as defined version to pull latest collection version.
> Master branch wasn’t release, and wouldn’t be considered as production grade branch.
