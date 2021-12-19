# cephstrap

By  default this install cephadm from the octopus release. This can be changed by defining an environment variable:

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
