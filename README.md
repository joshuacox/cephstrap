# cephstrap

This follows the 
[official docs](https://docs.ceph.com/en/pacific/cephadm/install/#install-cephadm)
on using cephadm.

For now these distros are supported:

 * "Debian GNU/Linux 10 (buster)"
 * "Ubuntu 18.04.6 LTS"

By default this installs cephadm from the octopus release. This can be changed by defining an environment variable:

```
export CEPH_RELEASE=nautilus
```

Then you can pipe the script directly to bash:

```
curl -L git.io/cephstrap | bash
```

Or download it first and execute it after reading through it.

```
wget git.io/cephstrap
bash ./cephstrap
```
