## Usage guide
---

- Your Bridge network interface might be different than `wlp2s0`
- Make sure `id-rsa.pub` exists or rename `id-rsa.pub` to other existing public ssh key file.

### GOAL

- Setting up ssh key into virtual machine setup by vagrant.
- Setting up mDNS
- SSHing using hostname rather than setting static ip for virtual machine

```
ssh vagrant@vm-debian.local
```

**_NOTE: `vm-debian` is the hostname setup in Vagrantfile_**
