# kprobe-tools
kprobe based debugging tools

## drm-info

```bash
sudo insmod drminfo.ko

# check kernel function
cat /proc/kallsyms | grep i915_request

dmesg | grep do_fork

sudo rmmod drminfo.ko
```
